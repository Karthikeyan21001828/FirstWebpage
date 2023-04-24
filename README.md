# FirstWebpage
## HTML:
```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <title>baker</title>
    <link rel="stylesheet" href="style.css" />
    <link rel="icon" href="./img/icon.png" type="image/x-icon" />
  </head>

  <body>
    <div class="container">
      <div class="menu">
        <div class="menuitemselected"><a href="#home">Home</a></div>
        <div class="menuitem"><a href="#pages">Pages</a></div>
        <div class="menuitem"><a href="#portfolio">Portfolio</a></div>
        <h2 class="menuitem"><b><i class="color">Baker</i></b></h2>
        <div class="menuitem"><a href="#blog">Blog</a></div>
        <div class="menuitem"><a href="#shop">Shop</a></div>
        <div class="menuitem"><a href="#elements">Elements</a></div>
        <h2 class="color">QUI GOUTE</h2>
        <h1 class="color">TRES BON</h1>
      </div> 
      <div class="containerbody">
        <div class="items">
        <div class="imagecinnamon">
        </div>
        <div class="text">
            <h1>CINNAMON ROLLS</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus imperdiet, nulla et dictum interdum, nisi lorem egestas vitae scel<span id="dots">...</span></p>
            <button>read more</button>
        </div>
    </div>
    <div class="items">
        <div class="text">
            <h1>STRAWBERY DONUT</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit. Phasellus imperdiet, nulla et dictum interdum, nisi lorem egestas vitae scel<span id="dots">...</span></p>
            <button>read more</button>
        </div>
        <div class="imagedonut">
            <img src="donut.jpg" alt="">
        </div>
    </div>
    <div class="items">
        <div class="imagepoppy">
        </div>
        <div class="text">
            <h1>POPPY CROISSANT</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</br>Phasellus imperdiet, nulla et dictum interdum, nisi lorem</br> egestas vitae scel</p>
            <button>read more</button>
        </div>
      </div>

      <div class="items">
        <div class="text">
            <h1>BLUEBERRY MUFFIN</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</br>Phasellus imperdiet, nulla et dictum interdum, nisi lorem</br> egestas vitae scel</p>
            <button>read more</button>
        </div>
        <div class="imagemuffin">
        </div>
      </div>
      </div>
      <div class="footer">
        <p class="menuitem">Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
        <button class="menuitem">Purchase Now</button>
      </div>
    </body>
</html>
```

## CSS:
```css
.container {
    width: 1080px;
    height: 265px;
    margin-left: auto;
    margin-right: auto;
    border-width: 1px 1px 1px 1px;
    border-style: solid;
  }
  .containerbody {
    width: 1080px;
    height: 1460px;
    margin-left: auto;
    margin-right: auto;
    border-width: 1px 1px 1px 1px;
    border-style: solid;
  }
  
  .menu {
    display: block;
    width: 100%;
    height: 250px;
    font-size: larger;
    background-color: pink;
    text-align: center;
    padding-top: 15px;
    margin: 0px 0px 0px 0px;
    border-width: 1px;
  }
  
  .menuitem {
    display: inline-block;
    margin-left: 10px;
    margin-right: 10px;
  }
  .menuitemselected {
    display: inline-block;
    margin-left: 10px;
    margin-right: 10px;
    color: #16d1ae;
  }
  .menuitem a
  {
    color: black;
    border-left: 2px;
  }
  .menuitemselected a
  {
    color: black;
    border-left: 2px;
  }
  .color
  {
    color:aliceblue
  }
  .items 
  {
    display: block;
    width: 100%;
    height: 350px;
    font-size: larger;
    background-color: white;
    padding-top: 15px;
    margin: 0px 0px 0px 0px;
    border-width: 1px;
  }
  .itemstext
  {
    display: inline-block;
    margin-left: 10px;
    margin-right: 10px;
  }
  .imagecinnamon
  {
    display: block;
    width: 50%;
    height: 350px;
    font-size: medium;
    background-color: white;
    margin: 0px 0px 0px 0px;
    background-image: url("cinnamon.jpg");
    background-size: 520 365;
    background-repeat: no-repeat;
    float: left;
  }
  .imagedonut
  {
    display: block;
    width: 20%;
    height: 150px;
    font-size: medium;
    background-color: white;
    float: left;
  }
  .imagepoppy
  {
    display: block;
    width: 50%;
    height: 350px;
    font-size: medium;
    background-color: white;
    margin: 0px 0px 0px 0px;
    background-image: url("poppy.jpg");
    background-size: 520 365;
    background-repeat: no-repeat;
    float: left;
  }
  .imagemuffin
  {
    display: block;
    width: 50%;
    height: 350px;
    font-size: medium;
    background-color: white;
    margin: 0px 0px 0px 0px;
    background-image: url("muffin.jpg");
    background-size: 520 365;
    background-repeat: no-repeat;
    float: left;
  }
  .text
  {
    float: left;
    width: 50%;
    height: 350px;
  }
  .footer
  {
    background-color: pink;
    text-align: center;
  }
  .footer p
  {
    color: white;
  }
```
## OUTPUT:

![image](https://user-images.githubusercontent.com/93427303/233939446-ee625c02-9407-4e01-a2aa-e97c886fe336.png)

