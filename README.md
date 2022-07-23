#	3D scene and ligthing in HTML&CSS

![AmbientLightCSS Preview](https://github.com/Sahapat/AmbientLightCSS/blob/master/screenshots/AmbientLightPreview.gif)

##	How to run
This project is using SCSS(The preprocessor of CSS). It need to be complie before using in HTML.
First make sure you are already install dependencie packages for running complier script. If the packages is not installed run
```
npm install
```
Then run
```
npm run build
```
For development mode
```
npm run build:watch 
```

The SCSS files will complie into CSS which already import in the HTML.

For open the HTTP server to view the page, site available at `localhost:8000`
```
npm run serve
```

##	Concept 
The concept behind this project is CSS 3D transform. I created a span element to be a representation of the side of 3D Box.

![Concept](https://github.com/Sahapat/AmbientLightCSS/blob/master/screenshots/Concept.PNG)

The light effect is a combination between gradient color of vertical side of the box and blur border of bottom side of the box.

![Lighting Vertical Side](https://github.com/Sahapat/AmbientLightCSS/blob/master/screenshots/Lighting2.PNG)

![Lighting Bottom Side](https://github.com/Sahapat/AmbientLightCSS/blob/master/screenshots/Lighting.PNG)

![Lighting Full](https://github.com/Sahapat/AmbientLightCSS/blob/master/screenshots/screenshot-1.jpg)

The span element will be the children of cube element, so we can apply transform animation to the cube element to make it.

![Animation](https://github.com/Sahapat/AmbientLightCSS/blob/master/screenshots/AmbientLightPreview.gif)
