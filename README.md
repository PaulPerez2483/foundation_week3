Foundation week 3

Foundation 6.4.3
Webpack 4.11.1

How to start : 

1. Install node_modules with : 
    > npm i
2. Open frontpage at http://yourlocalserver/
3. Run webpack watch : 
    > npm run proxy 

It will allow you to code without refreshing manualy thanks to browser sync. 
   Don't forget to change proxy.dev.json with your local url and change the port if more than one person are working on the project. 

5. Run webpack watch : 
    > npm run dev 

Will watch all your scss and js files and compile them.

6. Run webpack build : 
    > npm run build 

Build will do the same as dev but it will minify your JS and CSS file.
    
7. src/_settings.scss     
    It will allow you to change inital foundation parameters such as background colors, max-widh size, number of columns
    
8. src/ice/_xy-grid.scss
    is an upgrade of foundation xy-grid. It allow you to have different numbers of columns in regards to different screen size.
    So, we usualy work with this configuration :
    
    Smartphone : 4 columns
    Tablette : 8 columns
    PC : 12 columns
