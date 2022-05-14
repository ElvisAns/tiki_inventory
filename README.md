# Tiki Inventory
Original DogFood for TIKICMS Groupware https://tiki.org/
This project consists of setting up an item inventory system based on tiki trackers by the help of the UID technologies such as QR Code, BarCode and RFID. Having a space that allows the administrator to manage in a peaceful way, the inventory of books in a library; for example, by attaching a QR Code or any other unique identifier to an item.

[check this project on tiki dev](https://tiki.org/tiki_inventory_project) for full details

#structure

The project contain two separate folders:
- The Web app folder is for tiki instance and it is the one to be deployed on web server and it will serve as the backend for our PWA
- The PWA contains an Vue PWA made on top of the Ionic Framework [ionicframework.com/docs/vue/pwa](https://ionicframework.com/docs/vue/pwa)

#Notes 
To update the tiki web with the current version make sure to run 

```
git pull https://gitlab.com/tikiwiki/tiki.git master
```

being in the web app folder!

Thank you!
