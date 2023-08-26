# floorfy downloader

## What it does

floorfy-dl downloads cubemap skybox 360 and equirectangular panos photos of floorfy houses virtual tours 

## Dependencies

php, php-curl, curl  

This code can run over Linux and Windows  

## Usage

    $ php ./floorfy-dl.php <floorfy url>  

e.g: If the url is https://floorfy.com/tour/417174 you have to run the script this way:  

    $ php ./floorfy-dl.php https://floorfy.com/tour/417174  

It will download all the skybox and equirectangular images.

## Viewers

Web Browser: Chrome and Firefox: Pannellum (webgl based), self hosted virtual tour, equirectangular and cubemap skybox: https://github.com/mpetroff/pannellum  
Pannellum configuration can be done with this script https://github.com/fdd4s/floorfy-dl-virtual-tour-web-viewer  

Android: (only equirectangular) Ricoh Theta App https://play.google.com/store/apps/details?id=com.theta360&hl=en&gl=US  

PC: Linux/Mac/Windows Panini and opening as Cube Faces or Equirectangular: https://github.com/lazarus-pkgs/panini  

## Equirectangular

Floorfy stores panos in Skybox and Equirectangular format, but the skybox version of floorfy has higher quality, to keep high quality in equirectangular, skybox can be converted to equirectangular with this tool:

https://github.com/fdd4s/skybox2equirectangular  

Equirectangular can be viewed in players like Ricoh Theta for Android https://play.google.com/store/apps/details?id=com.theta360&hl=en&gl=US  

## Credits

Created by fdd4s  
Send feedback and questions to fc1471789@gmail.com  
All files are public domain https://unlicense.org/  
