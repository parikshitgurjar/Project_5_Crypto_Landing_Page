# Project 5 : Crypto Landing Page

- Click here for live demo of the Project on [ NETLIFY ](https://parikshitproject5.netlify.app/ "Parikshit Project 5")

<br/>

###  This Project is build using HTML & CSS 

***
<br/>


<br/>

>Knowledge gained :

<br/>

###  Things i learn in this Project.

>How to Code a Full Page Background Image

Making a background image fully stretch out to cover the entire browser viewport is a common task in web design:

1. Cover Viewport with Image : <br/>
    ```
      html {
            min-height: 100%;
            }
    ```

2. background-size: cover ;  
    - cover tells the browser to make sure the image always covers the entire container, in this case html. The browser will cover the container even if it has to stretch the image or cut a little bit off the edges. 
  
    <br/>
3. Fine Tune an Image Position and Avoid Tiling :
    - The browser can also choose to display your background image as tiles depending on its size. To prevent this from happening, use no-repeat:
    ```
      background-repeat: no-repeat;
    ```
4. To keep things pretty, we will keep our image a  always centered:
<b>This will center the image both horizontally and vertically at all times.</b>

   - full code:
    ```
      html {
            min-height: 100%;
            background-image: url(image.jpg);
            background-size: cover;
            background-repeat: no-repeat;
            background-position: center center;
           }
    ```



***

### Time Taken To Complete This Project : 2 days

***

<b> Note: </b>  This Project is Not Responisive to all the devices. The Responsiveness will be covered in coming Projects.

<br>

>The project is a part of the learning from  [ Sir Hitesh Choudhary's ](https://github.com/hiteshchoudhary) course on FULL STACK JAVASCRIPT WEB DEVELOPER. The idea credit is his. I have understood the concepts and learned them by building this on my own with a bare minimum reference of source code (only when my efforts couldn't clear the roadblock). The way of execution is modified as per my viewpoint whenever is necessary.









