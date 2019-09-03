# Boilerplate Image-Gallery 

A template image gallery 🖼

## Make a Copy

Either Clone this repo or Copy and paste the contents of this repository.

## Usage

This is made for Image Gallerys of a default image quantity of four. If you have more images that you need in your gallery please add another `div` with the `image` class to the `container` div.
```javascript
<div class="container">
    <div class="image">
      <img src="YOUR IMAGE URL"
       style="width:100%">
    </div>
</div>
```
You may also need to adjust the styling of the images based of the quantity of images. We
suggest using the `column` class to do any modifications to the preview images row.
```CSS
  .column {
    float: left;
    width: 10%;
  }
```
