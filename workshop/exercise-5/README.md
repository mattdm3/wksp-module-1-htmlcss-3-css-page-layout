# 1.2 - CSS: Page Layout - Workshop

## Exercise 5

Create an `index.html` file and a `style.css` file that reproduces the following:

![exercise-5 goal](../../assets/ex-5-goal.png)

This is a full screen background image with text in the center

### Reference

Your HTML should have the following structure:

```html
<!DOCTYPE html>
<html>

<head>
    <link href="style.css" rel="stylesheet" />
    <link href="https://fonts.googleapis.com/css?family=Poppins&display=swap" rel="stylesheet">
</head>

<body>
    ...
</body>

</html>
```

- Set the body margin to 0
- Give the `<body>` a `0` margin.
- Use the Poppins font
- Use the provided image in the imgs folder

To style your main `<div>` with a background image, you will need to use:

```css
background-image: url('imgs/bg.jpg'); /* you need to specify the path to the file */
background-size; /* Use this to have the image cover the full space */
background-position /* Use this to center the background image */
```

### Properties Needed

```
margin
font-family
display
align-items
justify-content
min-height
background-image
background-size
background-position
color
```
