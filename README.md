# Tiki Inventory
Original DogFood for TIKICMS Groupware https://tiki.org/


This project consists of setting up an item inventory system based on tiki trackers by the help of the UID technologies such as QR Code, BarCode and RFID. Having a space that allows the administrator to manage in a peaceful way, the inventory of books in a library; for example, by attaching a QR Code or any other unique identifier to an item.

[check this project on tiki dev](https://tiki.org/tiki_inventory_project) for full details

#structure

The project contain two separate folders:
- The Web app folder is for tiki instance and it is the one to be deployed on web server and it will serve as the backend for our PWA
- The PWA contains an Vue PWA made on top of the Ionic Framework [ionicframework.com/docs/vue/pwa](https://ionicframework.com/docs/vue/pwa)

#Notes 

The webapp folder is a mirror from https://gitlab.com/tikiwiki/tiki and it is a submodule to enable tracking, explore https://git-scm.com/book/en/v2/Git-Tools-Submodules for more informations and how to make change.

- ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+) `REMEMBER, BEING INSIDE THE WEBAPP FOLDER YOU CAN RUN ALL GIT COMMAND TO PULL CHANGES FROM TIKI CMS ORIGINAL REPO SO FOR STAYING SAFE MAKE ALL THE CHANGES BEING OUTSIDE MASTER  Eg. Tiki_inventory branch THEN EACH TIME YOU WANT TO PULL MAIN TIKI CHANGES JUST MERGE MASTER WITH YOUR CURRENT BRANCH!!!! THEN COMMIT CHANGES BEING IN THE MAIN FOLDER NOT IN THE WEBAPP FOLDER.`


Thank you!
