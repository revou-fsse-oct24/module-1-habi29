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
    
    <header>
        <nav>
             <ul>
                <li><a href="#index.html">Home</a></li>
                <li><a href="#About-us">About</a></li>
                <li><a href="#Fasilitas">Fasilitas</a></li>
                <li><a href="#Boking">Boking</a></li>
            </ul>
        </nav>
    </header>

    <main>
        <section>
            <div>
                <h1>Welcome To Daima Moosa Glamping Park</h1>
                <p>We offer accommodation in the Solok district area with beautiful views.</p>
                <img src="https://www.kabarsumbar.com/wp-content/uploads/2022/07/354032472.jpg" width="500" height="350" />
            </div>
        </section>
             
        <section class="About-us" id="About-us">
            <h2>About</h2>
            <p>provides comfortable and safe accommodation at affordable prices, has excellent facilities</p>
        </section>

        <section class="Fasilitas" id="Fasilitas">
            <h2>Fasilitas</h2>
            <p>some of the facilities available at Daima Moosa Glamping Park </p>
            <iframe src="https://www.youtube.com/embed/F2OPT1wS7E8" width="500" height="350" ></iframe>

        </section>

        <Section class="Boking" id="Boking">
            <h2>Boking</h2>
        </Section>

    <form action="/action_page.php" target="_blank" method="get">
        
            <label for="fname">nama lengkap:</label><br>
            <input type="text" id="fname" name="fname"><br>
            <label for="number">NIK:</label><br>
            <input type="number" id="number" name="number"><br/>
            <label for="number">nomor telpon:</label><br>
            <input type="number" id="number" name="number"><br/>
        

    <p>Room:</p>
        
            <input type="radio" id="Superior" name="Room" value="Superior">
            <label for="room">Superior</label><br>
            <input type="radio" id="Vila 2 Badroom" name="Room" value="Vila 2 Badroom">
            <label for="room">Vila 2 Badroom</label><br>
        

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
</form>
</main>
    <footer>
        <p>&#169: 2024 Habi Permana Putra </p>
    </footer>
</body>
```

> index.css
```
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
```