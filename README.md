# Getting-started-template

## Content
- [CSS boilerplate](#css)
- [HTML boilerplate](#html)

## CSS

```css
/*=============== VARIABLES CSS ===============*/
:root{
    --header-height: 3.5rem; /* 56px */
    
    /*===== colors =====*/
    --first-color: ;
    --first-color-alt: ;
    --first-color-light: ;
    --first-color-lighten: ;
    --title-color: ;
    --text-color: ;
    --text-color-light: ;
    --body-color: ;
    --container-color: #FFF;

    /*===== font & typography =====*/
    --body-font: 'Poppins', sans-serif;
    --big-font-size: 2rem;
    --h1-font-size: 1.5rem;
    --h2-font-size: 1.25rem;
    --h3-font-size: 1rem;
    --normal-font-size: .938rem;
    --small-font-size: .813rem;
    --smaller-font-size: .75rem;
    
    /*===== font weight =====*/
    --font-medium: 500;
    --font-semi-bold: 600;

    /*===== margin bottom =====*/
     --mb-0-5: .5rem;
     --mb-0-75: .75rem;
     --mb-1: 1rem;
     --mb-1-5: 1.5rem;
     --mb-2: 2rem;
     --mb-2-5: 2.5rem;
    
    /*===== z index =====*/
    --z-tooltip: 10;
    --z-fixed: 100;
}

/* responsive typography */
@media screen and (min-width: 968px){
    :root{
        --big-font-size: 3.5rem;
        --h1-font-size: 2.25rem;
        --h2-font-size: 1.5rem;
        --h3-font-size: 1.25rem;
        --normal-font-size: 1rem;
        --small-font-size: .875rem;
        --smaller-font-size: .813rem;
    }
}

/*=============== BASE ===============*/
*{
    box-sizing: border-box;
    padding: 0;
    margin: 0;
}

html{
    scroll-behavior: smooth;
}

body,
button,
input,
textarea{
    font-family: var(--body-font);
    font-size: var(--normal-font-size);
}

body{
    margin: var(--header-height) 0 0 0;
    background-color: var(--body-color);
    color: var(--text-color)
}

button{
    cursor: pointer;
    border: none;
    outline: none;
}

h1,h2,h3{
    color: var(--title-color);
    font-weight: var(--font-semi-bold);
}

ul{
    list-style: none;
}

a{
    text-decoration: none;
}

img{
    max-width: 100%;
    height: auto;
}


/*=============== THEME ===============*/


/*=============== REUSABLE CSS CLASSES ===============*/
.section{
    padding: 5.5rem 0 1rem;
}

.section__title,
.section__title__center{
    font-size: var(--h2-font-size);
    margin-bottom: var(--mb-2);
    line-height: 140%;
}

.section__title__center{
    text-align: center;
}

.container{
    max-width: 968px;
    margin-left: var(--mb-1-5);
    margin-right: var(--mb-1-5);
}

.grid{
    display: grid;
}

.main{
    overflow: hidden; /*for animation*/
}

/*=============== HEADER ===============*/





/*===============  ===============*/
/*=====  =====*/
```

<p align="right"><a href="#content">⬆ Back to Index</a></p>

## HTML

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <!-- FAVICON -->
    <link rel="shortcut icon" href="assets/img/favicon.png" type="image/x-icon">

    <!-- GOOGLE FONTS -->
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;500;600;700&display=swap" rel="stylesheet">

    <!-- REMIX ICONS -->
    <link href="https://cdn.jsdelivr.net/npm/remixicon@2.5.0/fonts/remixicon.css" rel="stylesheet">

    <!-- CSS -->
    <link rel="stylesheet" href="assets/css/style.css">

    <title>Getting Started</title>
</head>
<body>
    <!-- HEADER -->
    <header class="header" id="header">
    </header>

    <main class="main">
        <!-- HOME -->
    </main>

    <!-- FOOTER -->
    <footer class="footer section">
    </footer>

    <!-- SCROLL UP -->

    <!-- SCROLL REVEAL -->

    <!-- MAIN JS -->
    <script src="assets/js/main.js"></script>

</body>
</html>
```

**[⬆ Back to Index](#content)**


