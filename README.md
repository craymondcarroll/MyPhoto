## MyPhoto - Journey into Bootstarp ##

**Create an index.html**

**Download bootstrap, Jquery, and Popper.js**
- npm init
- npm install bootstrap 
- npm install jquery
- npm install popper.js 

**Add the following to the index.html**

```markdown

<!DOCTYPE html>
<html lang="en">
   <head>
      <meta charset="utf-8">
      <meta name="viewport" content="width=device-width, initial-
      scale=1, shrink-to-fit=no">
      <meta http-equiv="x-ua-compatible" content="ie=edge">
      <title>MyPhoto</title>
      <link rel="stylesheet" 
       href="node_modules/bootstrap/dist/css/bootstrap.min.css">
   </head>
   <body>
      <div class="alert alert-success">
         Hello World!
      </div>
      <script src="node_modules/jquery/dist/jquery.min.js"></script>
      <script src="node_modules/popper.js/dist/umd/popper.min.js"> 
      </script>
      <script src="node_modules/bootstrap/dist/js/bootstrap.min.js">
      </script>
   </body>
</html>

```


 #### Building the Layout ####
 
 First, we will split the page into **five sections:** **Welcome, Services, Gallery, About, and Contact Us, along with a footer placeholder**. We will use the grid system to create distinct sections on the page. We will add content to these sections using the Bootstrap components jumbotron, tabs, carousel, and cards.
 

- Exanple of an area

```markdown
<div class="container-fluid bg-primary">
    <div class="row">
        <h3>Welcome</h3>
    </div>
</div>

```
