# transitioning-nav
A transitioning sticky navigation allows you to display two different navigations based on where the viewer is on the page. This article gives you the code to add a sticky transitioning navigation to your website which you can customize to meet your needs.

## Tutorial

For detailed instructions, view Solodev's [Adding a Transitioning Nav Using CSS](https://www.solodev.com/blog/web-design/navigation/adding-a-transitioning-nav-using-css.stml) article.

## Demo

Check out a working example on [JSFiddle](https://jsfiddle.net/solodev/qj9py1cw/).

## HTML
The transitioning sticky nav contains the following basic HTML markup.

```
<nav class="navbar navbar-default navbar-fixed-top">
      <div class="container">
        <div class="navbar-header">
          <a class="navbar-brand" href="#">
             <img src="https://www.solodev.com/assets/side-nav/logo.png" alt="Logo Solodev">
          </a>
        </div>
        <div id="navbar" class="navbar-collapse collapse navbar-right">
          <ul class="nav navbar-nav">
            <li><a href="#">Home</a></li>
            <li><a href="#about">About</a></li>
            <li><a href="#contact">Contact</a></li>
            <li class="dropdown">
              <a href="#" class="dropdown-toggle" data-toggle="dropdown" role="button" aria-haspopup="true" aria-expanded="false">Dropdown <span class="caret"></span></a>
              <ul class="dropdown-menu">
                <li><a href="#">Action</a></li>
                <li><a href="#">Another action</a></li>
                <li><a href="#">Something else here</a></li>
                <li role="separator" class="divider"></li>
                <li class="dropdown-header">Nav header</li>
                <li><a href="#">Separated link</a></li>
                <li><a href="#">One more separated link</a></li>
              </ul>
            </li>
          </ul>      
        </div><!--/.nav-collapse -->
        <button type="button" class="navbar-toggle collapsed" data-toggle="collapse" data-target="#navbar" aria-expanded="false" aria-controls="navbar">
            <span class="sr-only">Toggle navigation</span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
            <span class="icon-bar"></span>
          </button>
      </div>
    </nav>
</header>

<div style="display: block; margin: 0 auto; text-align: center;">
<img src="https://www.solodev.com/assets/hero/large-image.jpg">
</div>

```

## CSS

All necessary CSS is in trans-nav.css

## External Includes

```
<link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/css/bootstrap.min.css">
<link rel="stylesheet" href="trans-nav.css">

<script src="https://ajax.googleapis.com/ajax/libs/jquery/1.12.4/jquery.min.js"></script>
<script src="https://maxcdn.bootstrapcdn.com/bootstrap/3.3.7/js/bootstrap.min.js"></script>
```
