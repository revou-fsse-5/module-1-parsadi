[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/_rEaNyCz)
# NAVBAR
sticky
```html
    <header>
        <img src="flagpack--mx.png" alt="Mexican" class="logo">
        <ul>
            <li><a href="#">Home</a></li>
            <li><a href="#">About</a></li>
            <li><a href="#">Menu</a></li>
            <li><a href="#">Contact</a></li>
        </ul>
    </header>
```

Media query 
```css
 .hamburger {
        display: block;

    }

    .hamburger.active .bar:nth-child(2) {
        opacity: 0;
    }

    .hamburger.active .bar:nth-child(1) {
        transform: translateY(8px) rotate(45deg);
    }

    .hamburger.active .bar:nth-child(3) {
        transform: translateY(-8px) rotate(-45deg);
    }

    .nav-menu {
        position: fixed;
        left: -1000%;
        top: 70px;
        gap: 0;
        flex-direction: column;
        background-color: black;
        width: 100%;
        text-align: center;
        transition: 0.3s;


    }

    .nav-item {
        margin: 16px 0;
    }

    .nav-menu .active {
        left: 0;
    }

```

# MENU CONTENT
this is the content
```html
<h1>Our Menu</h1>
        <div class="flex-container container">
            <div class="menu-container">
                <img src="burito_carne_asada.jpeg" alt="Burito Carne Asada">
                <h3>Burito Carne Asada</h3>
                <h5>Burito filled with Mexican authentuic grilled meat</h5>
            </div>
            <div class="menu-container">
                <img src="burito_pollo_chille.jpg" alt="Burito Pollo con Chille">
                <h3>Burito Pollo con Chille</h3>
                <h5>Burito filled with spicy chicken</h5>
            </div>
            <div class="menu-container">
                <img src="burger.jpg" alt="Burger">
                <h3>Burger</h3>
                <h5>Special burger by our restaurant that will crave your gut</h5>
            </div>
        </div>
```

Media quey for Content 
```css
 .grid-container {
        display: grid;
        grid-template-rows: 1fr 1fr 1fr;
        grid-template-columns: 1fr;
        width: 100%;
        margin-left: 0;
        margin-right: 0;
        padding-left: 0;
        padding-right: 0;

    }
```

# ABOUT US
```html
    <div class="aboutUs container">
            <h1>About Us</h1>
            <h3>Lorem ipsum dolor sit amet consectetur adipisicing elit. Exercitationem, atque! Porro magnam odio
                similique officia, architecto nulla minima reprehenderit incidunt adipisci, labore cupiditate!
                Voluptate, ratione?
            </h3>
        </div>
```

# HOW TO REACH US
```html
    <div class="container">
            <h3>Contact Us</h3>
            <form action="">
                <div class="contactUs">
                    <input type="text" id="fname" name="fname" placeholder="Your Name">
                    <input type="text" id="email" name="email" placeholder="Your email">
                </div>
                <textarea name="" id="" cols="30" rows="10">Your Message</textarea>
                <input type="submit">

            </form>
        </div>
```
Pictures inside the content :

![Burito Carne Asada](burito_carne_asada.jpeg)
![Burito Pollo con Chille](burito_pollo_chille.jpg)
![Burger](burger.jpg )

<p> https://revou-fsse-5.github.io/module-1-parsadi/ </p>