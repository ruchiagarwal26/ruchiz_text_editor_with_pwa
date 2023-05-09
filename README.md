# 19 Progressive Web Applications (PWA): Text Editor

## Deployed App heroku link : https://thawing-wildwood-60203.herokuapp.com/

## Github repo link : https://github.com/ruchiagarwal26/ruchiz_text_editor_with_pwa

## Overview :
This is a Text editor that has functionality to be used online and offline. The notes are saved in IndexDB and can be retrieved when required. 
Adding to it, the app can be installed and an icon will be created on your desktop.

* this app is built on Express and PWA functionalities. Without the use of any backend databases like DynamoDB or MySQl, intead IndexDB
* 
* this app has client - server folder structure:

![image](https://user-images.githubusercontent.com/115508901/236969455-68216496-73a2-4478-ba58-c69f942fbc40.png)

* Upon running the npm start, the build happens and the server starts :

![image](https://user-images.githubusercontent.com/115508901/236969411-257d1279-399c-4ace-8135-b10020b23d8a.png)

* IndexDB is created in the server :

![image](https://user-images.githubusercontent.com/115508901/236969679-59f43ab9-df9e-4ff1-befb-14dcf50da9b6.png)


* The notes can be added and retrieved with/without internet

* The app is hosted on heroku App

![image](https://user-images.githubusercontent.com/115508901/236969939-0518d9ef-2c25-4095-96f2-69c22387398d.png)

* Upon clicking install, th app got downloaded on my machine with its icon on my desktop:

![image](https://user-images.githubusercontent.com/115508901/236970231-0b682be2-8433-4950-a400-ab01529e258b.png)










## Mock-Up

The following animation demonstrates the application functionality:

![Demonstration of the finished Module 19 Challenge being used in the browser and then installed.](./Assets/00-demo.gif)

The following image shows the application's `manifest.json` file:

![Demonstration of the finished Module 19 Challenge with a manifest file in the browser.](./Assets/01-manifest.png)

The following image shows the application's registered service worker:

![Demonstration of the finished Module 19 Challenge with a registered service worker in the browser.](./Assets/02-service-worker.png)

The following image shows the application's IndexedDB storage:

![Demonstration of the finished Module 19 Challenge with a IndexedDB storage named 'jate' in the browser.](./Assets/03-idb-storage.png)


