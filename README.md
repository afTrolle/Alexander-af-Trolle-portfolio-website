# Simple portfolio website
Single page website using bootstrap 4. With the purpose of being a simple portfolio or cv page.

The web page can be located [here](https://alexander.af.trolle.dev/ "Alexander af trolle")

If you want just replace the text about me and change the links in the html that is fine but on your own disccretion. 


## Structure
This website is hosted using firebase hosting and the configuration files for it are included in this repository.
If you are using a different hosting solution you can ignore all files except the **public** folder. 


```
public -> 
    src ->  
        js -> 
            (Javascript files)
        css ->
            (Cascading Style Sheets)
        images ->
            (Images and Icons)
    index.html (Single web-page)
```
### Notice (When using Firebase hosting)
There aren't any enforcement of how to organize the files except one that all urls gets redirected to the main site, expect if it starts with **/src** 
Then it links to the src folder, these rules are set in the [firebase.json](../firebase.json) file.

Example
```
https://website/src/[file or path]/images/alex.jpg, Works
https://website/[file or path]/images/alex.jpg, Not working (would redirect to main site)
```


## Credits

Awesome Libraries used in this project!

* [Material Design for Bootstrap](https://github.com/FezVrasta/bootstrap-material-design) - open source toolkit for developing with HTML, CSS, and JS

* [Feather](https://github.com/feathericons/feather)  - collection of simply beautiful open source icons

* [ScrollReveal](https://github.com/scrollreveal/scrollreveal) - library for easily animating elements as they enter/leave the viewport.
