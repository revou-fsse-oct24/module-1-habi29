# Welcome To Daima Moosa Glamping Park

This is one of the accommodations in the Solok district area.

## Table of contents

- [Technologies Used](#technologies-used)
- [Setup](#setup)
- [Code](#Code)

## Technologies Used

- HTML5

## Setup

1. Clone the repository:
```
https://github.com/revou-fsse-oct24/module-1-habi29.git
```

2. Open The 'index.html' file your browser
```
open index.html
```
3. Assets Folder
```
<img src="https://www.kabarsumbar.com/wp-content/uploads/2022/07/354032472.jpg">
<iframe src="https://www.youtube.com/embed/F2OPT1wS7E8"></iframe>
```

## Code 

the program I use
> index.html
```
<body>
    <section class="home">
         <header>
            <nav>
                <div class="nav-content">
                    <div class="logo">
                        <img src="https://www.shutterstock.com/shutterstock/photos/1501463624/display_1500/stock-vector-villa-icon-vector-illustration-creative-sign-from-buildings-icons-collection-filled-flat-villa-1501463624.jpg" alt="logo" class="logo" width="50px">
                </div>
                    <ul>
                        <li><a href="#index.html">Home</a></li>
                        <li><a href="#About-us">About</a></li>
                        <li><a href="#Type Room">Type Room</a></li>
                        <li><a href="#Boking">Boking</a></li>
                    </ul>
                </div>
            </nav>
        </header>
    </section>

    <main>
        <section>
            <div class="content">
                <h2><br>Welcome To Daima Moosa Glamping Park</br></h2>
                <p>We offer accommodation in the Solok district area with beautiful views.</p>
                <img src="https://www.kabarsumbar.com/wp-content/uploads/2022/07/354032472.jpg" width="350" height="200" />
            </div>
        </section>
             
        <section>        
            <div class="About-us" id="About-us">
            <h3>About</h3>
            <p>Relaxing and peaceful stay at Daima Moosa Glamping Park, located in Lubuk Selasih. Enjoy a delicious dinner and enjoy the beautiful nature of tea plantations while staying in our luxury glamping park-themed inn. This eco-friendly glamping park allows leisure travelers and family vacations to enjoy their stay.</p>
        </section>

        
        <section class="Type Room" id="Type Room">
            <h3>Type Room</h3>
            
            <div class="container">
                <div class="card">
                    <div class="imgBx">
                        <a href="#">   
                            <p>Glamping</p>
                            <img src="https://daimahotel.com/images/hotel/204MNY09443-2.jpg" width="300" height="150" alt="Type Room">
                        </a>
                    </div>
                </div>
            
                <div class="card">
                    <div class="imgBx">
                        <a href="#">   
                            <p>Villa Glamping Deluxe</p>
                            <img src="https://daimahotel.com/images/hotel/694MNY09468.jpg" width="300" height="150" alt="Type Room ">
                        </a>
                    </div>
                </div>

                <div class="card">
                    <div class="imgBx">
                        <a href="#">   
                            <p>Villa Glamping Superior</p>
                            <img src="https://daimahotel.com/images/hotel/649MNY09447.jpg" width="300" height="150" alt="Type Room">
                        </a>
                    </div>
                </div>
            </div>
            
        </section>

        <Section class="Boking" id="Boking">
            <h3>Boking</h3>
        
    <form action="/action_page.php" target="_blank" method="get">
        
            <label for="fname">nama lengkap:</label><br>
            <input type="text" id="fname" name="fname"><br>
            <label for="number">NIK:</label><br>
            <input type="number" id="number" name="number"><br/>
            <label for="number">nomor telpon:</label><br>
            <input type="number" id="number" name="number"><br/>
        
    <p>Room:</p>
        
            <input type="radio" id="Glamping" name="Room" value="Glamping">
            <label for="room">Glamping</label><br>
            <input type="radio" id="Villa Glamping Deluxe" name="Room" value="Villa Glamping Deluxe">
            <label for="room">Villa Glamping Deluxe</label><br>
            <input type="radio" id="Villa Glamping Superior" name="Room" value="Villa Glamping Superior">
            <label for="room">Villa Glamping Superior</label><br>           

    <p>Extra</p>
        
            <input type="checkbox" id="vehicle1" name="vehicle1" value="Sigle Bed">
            <label for="vehicle1"> Sigle Bed</label><br>
            <input type="checkbox" id="vehicle2" name="vehicle2" value="Extra Bed">
            <label for="vehicle2"> Extra Bed</label><br>
            <input type="checkbox" id="vehicle3" name="vehicle3" value="Other">
            <label for="vehicle3"> Other</label><textarea id="w3review" name="w3review" rows="1" cols="20"></textarea><br>

        
        <p><label for="w3review">Messages:</label></p>
        <textarea id="w3review" name="w3review" rows="4" cols="50"></textarea>
        <br>
        <input type="Submit" value="Submit">

    </Section>
    </form>
</main>
    <footer>
        <p>&#169: 2024 Habi Permana Putra </p>
    </footer>
</body>

```

> index.css
```
body{
    background-color:whitesmoke;
}
nav{
    position: fixed;
    top: 0;
    left: 0;
    width: 100%;
    padding: 3px;
    background: rgba(0,0,0,0.3);
}

.nav-content{
    display: flex;
    height: 90%;
    min-width: 120px;
    margin: auto;
    align-items: center;
    justify-content: space-between;
}

.logo{
    font-size: 20px;
    font-weight: 50;
}

.nav-content ul {
    display: flex;
    align-items: center;
}

.nav-content ul li {
    list-style: none;
    margin: 0 10px;
}

.nav-content ul li a {
    font-size: 18px;
    font-weight: 500px;
    color: white;
    padding: 10px 4px;
}

.nav-content ul li a:hover {
    color: #4070f4;
}

.content{
    padding: 20px;
}

.container{
    position: relative;
    width: 1100px;
    display: flex;
    justify-content: space-between;
    align-items: center;
    flex-wrap: wrap;
    padding: 1rem;
    margin-top: 1rem; 
}

.container card{
    width: 300px;
    position: relative;
    height: 400px;
    background: black;
    margin: 30px 10px;
    padding: 20px 15px;
    display: flex;
    flex-direction: column;
    box-shadow: 0.5px 10px #e6e6e6;
    transition: 0.3s ease-in-out;
    margin-top: 5%;   
}

.container .card .imgBx{
    max-width: 100%;
    border-radius: 10px;
}

.imgBx:hover img{
    transform: scale(1.1);
}

@media only screen and (max-width: 736px) and 
(orientation: portrait) {
    
    header{
        display: none;
    }

    .container{
        position: relative;
        width: 110px;
        display: flex;
        justify-content: space-between;
        align-items: center;
        flex-wrap: wrap;
        padding: 1rem;
        margin-top: 1rem; 
    }
        
}
```

link akses https://revou-fsse-oct24.github.io/module-1-habi29/