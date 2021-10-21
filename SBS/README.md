# Picture/Demo
![ezgif com-video-to-gif](https://user-images.githubusercontent.com/78399841/136374733-efdab185-5244-4f6e-b500-9b30d6485e3b.gif)

![ezgif com-video-to-gif-2](https://user-images.githubusercontent.com/78399841/136374789-7d83ebf0-080e-439c-a8cf-d71074d97679.gif)
# Introduction

`Skating is a static demo page that deals with skating related activities.`

## Technology
* HTML5
* CSS3 
* SCSS
* Bootstrap5
 
# Links
 ```
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/4.7.0/css/font-awesome.min.css">
    <link rel="stylesheet" href="./assets/bootstrap-5.0.2-dist/css/bootstrap.min.css">
    <script src="./assets/bootstrap-5.0.2-dist/js/bootstrap.min.js"></script>
    <link rel="stylesheet" href="./assets/css/style.css">
```
# Structure
  ``` 
- SBS/
    - assets/ 
      - Bootstrap-5.0.2-dist/
          - css/
          - js/
      - css/
          - style.css
          - style.map.css
      - fonts/
          - Roboto/  
      - images/
      - scss/
         - _mediaquery.scss
         - _mixins.scss
         - _variables.scss
         - _style.scss 
   
    - index.html
    - README.txt
```
## index.html
```This file contains css,bootstrap,fontstyles links. Html elements & bootstrap classes.```

 ## style.scss
```This file contains all scss styles ,import styles from _variables.scss , _mixins.scss & _mediaquery.scss.```
## _variables.scss 
``` This file contain variables for colors. If you want to change the color of text, background-color of elements ,change color values in _variables.scss file.```  
## _mixins.scss
``This file contain mixins and placeholders .
To change the text-color & background  color of card pass the (background-color,color) respectively to card-style mixin. ``
##  _mediaquery.scss
``This file contain all media queries on different breakpoints.``

# Editing
- index.html file may be edited with any HTML editor but .scss file can't compile without Sass compiler. If you do not know where to get one, you may consider trying **Microsoft Visual Studio Code**. It can be downloaded at [https://code.visualstudio.com](https://code.visualstudio.com/)
 and it's free.

- To put your own logo you should replace logo.png (it is located in SBS>assets>images>sbs-logo.png) with your own .png file.

Alternatively, we can help you making changes to its layout, changing the color scheme or logo, adding content as per your requirements, etc.
As with all our services, we will work on the design until you are completely satisfied. Email us to request a quote for customization services.  
to get our services.Click on [gsoft consulting](https://gsoftconsulting.com/)
# Important Notice

Pull requests are welcome. For changes, please open an issue first to discuss what you would like to change. [Global Software Consulting](https://gsoftconsulting.com/) provides paid support services as need basis at high level of availability. If you are unable to find sufficient tutorial at regarding your issue please use the following email [info@gsoftconsulting.com](mailto:info@gsoftconsulting.com)  to submit a request to our technical support team. We will provide you with our assistance at low cost prices ASAP 
## License
[MIT](https://choosealicense.com/licenses/mit/)
