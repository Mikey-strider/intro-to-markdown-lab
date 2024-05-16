![Two red arrows facing away from eachother with a forward slash in the middle separting them, on a white-ish background](https://images.unsplash.com/photo-1621839673705-6617adf9e890?q=80&w=1932&auto=format&fit=crop&ixlib=rb-4.0.3&ixid=M3wxMjA3fDB8MHxwaG90by1wYWdlfHx8fGVufDB8fHx8fA%3D%3D)

# Creating a basic HTML file:

When creating a basic HTML file, you will need to add some basic information to it.

HTML is the skeleton of any web based appilication, and it needs to be set up properly in order for your app to work correctly.

Luckily it is a fairly straight forward process with only a few commands needed.

1. When you first open your HTMl file you will find that it is completely blank. Luckily for you Emmet snippets is built directly into vscode. So, all you have to do is press the exclamation point **!** button and then hit tab and it will build the entire HTML beginning bones for you. It should look like this:

```HTML
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Document</title>
</head>
<body>
  
</body>
</html>
```

2. Once you have that done, you will need to attach your *Javascript* and *CSS* files to it. You will need to place these in the ***head*** tag.
It will look like this:

For **CSS:**
`<link rel="stylesheet" href="./css/style.css">`

For **Javascript:**
  `<script defer src="./js/app.js"></script>`

  This is what your file should look like once complete:

  ```HTML
  <!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <link rel="stylesheet" href="./css/style.css">
  <script defer src="./js/app.js"></script>
  <title>Document</title>
</head>
<body>
  
</body>
</html>
```

Once you have added your files to the HTMLK file you will be ready to go!
If you have any other question or want to read more visit the MDN docs.[MDN docs.](https://developer.mozilla.org/en-US/docs/Web/HTML)