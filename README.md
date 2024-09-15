<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Tech2etc Ecommerce Tutorial</title>
    <link rel="stylesheet" href="https://cdn.jsdelivr.net/npm/@fortawesome/fontawesome-free@6.4.2/css/fontawesome.min.css"/>
    <link rel="stylesheet" href="style.css">
    <style>
 body {
    margin: 0;
    padding: 0;
    font-family: 'Ubuntu', sans-serif;
    color: black;    
}
.ubuntu-font {
    font-family: 'Ubuntu', sans-serif;
    color: black;
    padding-left: 25px;
    font-size: 30px;
}
.mega, .dropdown-item, .aditional-item {
    font-size: 20px;
    color: rgb(182, 186, 190);
    padding-left: 10px;
    padding-top: 50px;
}
.icon {
    margin-left: 10px;
}
.shirts, .dresses, .Jeans, .dropdown-item, .aditional-item {
    padding-left: 20px;
    font-size: 25px;
    padding-top: 15px;
    padding-bottom: 10px;
    padding-right: 0;
    margin: 0;
    display: block;
    text-align: left;
}
.dropdown {
    display: none;
    margin-left: 60px;
    margin-top: 10px;
   
}

.dropdown-item {
    font-size: 25px;
    cursor: pointer;
    padding-left: 10px;
}
.dropdown-item:hover {
    background-color: rgb(182, 186, 190);
    color: black;
}
.shirts:hover, .dresses:hover, .Jeans:hover, .aditional-item:hover {
    background-color: rgb(182, 186, 190);
    color: black;
}
.aditional {
    padding-left: 10px;
    margin-left: 5px;
    margin-top: 10px;
}
.aditional.show {
    display: block; /
}
.container {
    display: flex;
    flex-wrap: wrap; 
    padding: 20px;
    margin-left: 10px;
    height: 100vh; 
    overflow-y: auto;
}
.final {
    font-size: 20px;
    color: black;
    padding-left: 0px;
    padding-top: 50px;
    padding-right: 130px;
}
.text-content {
    padding-right: 20px; 
    padding-left: 50px;
}
.scroll-container {
    height: 70%;
    overflow-y: auto; 
    padding-right: 15px; 
}

.scroll-container::-webkit-scrollbar {
    width: 8px; 
}

.scroll-container::-webkit-scrollbar-thumb {
    background-color: darkgrey; 
    border-radius: 4px;
}

.scroll-container::-webkit-scrollbar-track {
    background-color: #f1f1f1; 
}
.dropdown-item:first-child {
    background-color: rgb(222, 229, 236);
    color: black; 
}
.head {
    display: flex;
    font-size: 30px;
}
.heading{
    padding-left: 0px;
    color: rgb(94, 99, 104);
}
#hero {
    background-image: url('https://www.w3schools.com/w3images/jeans.jpg');
    height: 500px;
    width: 800px;
    background-size: cover;
    background-position: top 25% right 0px;
    padding: 40px;
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    justify-content: flex-start;
}
#hero .shop {
    background-color: black;
    color: white;
    border: 0;
    padding: 15px 30px;
    cursor: pointer;
    font-weight: 600;
    font-size: 20px;
}
#hero .collection {
    font-size: 40px;
    color: white;
    margin-top: 0;
}
.new {
    color: white;
    font-size: 55px;
    margin-bottom: 10px;
}
#hero .shop:hover {
    background-color: rgb(182, 186, 190);
    color: black;
}
.container-image{
    display: flex;
    justify-content: space-between;
    height:50px;
    width:70px;
    flex: 1;
    max-width: 500px; /* Set a max-width for image section */
    padding-right: 40px;
    padding-left: 20px;
}
.container-section{
    display: flex;
}#product1{
    text-align: center;
}
.para{
    text-align: start;
    font-size: 20px;
    color: #767e7a;
}
#product1 .pro{
    width:3px;
    min-width: 200px;
    /*padding:10px 4px;
    border:1px solid#cce7d0;*/
    border-radius: 0px;
    cursor: pointer;
    box-shadow: 20px 20px 30px rgba(0, 0, 0, 0.02);
    /margin:15px 0px;/
    transition: 0.2s ease;
    position:relative;
    padding-top: 0px;
}
#product1.pro:hover{
    box-shadow: 20px 20px 30px rgba(0, 0, 0, 0.06);
}
#product1.pro img{
    width:100%;
    /border-radius: 20px;/
}
#product1.pro .des{
    text-align: start;
    padding: 10px 0;
}
#product1.pro .des span{
    color:#606063;
    font-size: 12px;
}
#product1.pro .des .adi .p{
    padding-top: 17px;
    color:#1a1a1a;
    font-size: 14px;
}
#product1.pro .des i{
    font-size: 12px;
    color:rgb(243, 181, 25);
}
#product1.pro .des .p{
    font-size: 15px;
    padding-top: 0px;
    font-weight: 700;
    color:#088178;
}
.des{
    text-align: start;
    padding-left: 15px;
    color:black;
}
.adi{
    color:#3d413f;
    font-size: 17px;
}
#product1 .pro-container{
    display:flex;
    justify-content: space-between;
    
    flex-wrap: wrap;
    margin-top:0px;
    margin-left: 0px;
    margin-right: 0px;
}
.overlay-box {
    position: absolute;
    top: 0px; /* Adjust this to move the box vertically */
    left: 13px; /* Adjust this to move the box horizontally */
    background-color: black;
    color: white;
    padding-top: 5px;
    font-size: 17px;
    z-index: 10; 
    height: 10px;
    width:45px;
    padding-left: 0px;
    padding-right: 10px;
    padding-bottom: 15px;
    text-align: center;
}

.pro-two{
    position: relative; 
    display: inline-block; 
}
.pro-seven{
    position: relative; 
    display: inline-block; 
}
.buyer{
  position: relative;
  display: inline-block;
}
.buyer img {
  width: 100%;
  height: auto;
}
.buy-now-box {
  position: absolute;
  bottom: 30px; 
  right: 15px;   
  padding-left: 20px;
   padding-right: 30px;
    padding-top: 10px;
     padding-bottom: 10px;
     margin-bottom: 50px;
     margin-top: 50px;
  background-color: black; 
  color: white;
  font-size: 14px;
  border-radius: 5px;
  opacity: 0; 
  transition: opacity 0.3s ease; 
}

.buyer:hover .buy-now-box {
  opacity: 1; 
}
.buy-now-box:hover {
  background-color: rgb(182, 186, 190); 
  color: black;            
}

.newsletter h4{
    font-size: 30px;
    color: #fff;
    margin-left: 15px;
}
.newsletter p{
    font-size: 20px;
    font-weight: 600;
    color: white;
    margin-left: 15px;
}
.newsletter {
    display: flex;
    justify-content: space-between;
    align-items: start;
    background-color: black;
    padding: 10px 10px;
    color: white;
    text-align: left;
}
.normal {
    background-color: rgb(219, 27, 27);
    color: rgb(247, 238, 238);
    border: 0;
    padding: 10px 17px;
    cursor: pointer;
    font-weight: 500;
    font-size: 18px;
    margin-top: 20px;
    margin-left: 15px;
    margin-bottom: 30px;
}
.mail{
    margin-left: 15px;
    padding-top: 10px;
    padding-bottom: 10px;
    font-size: 15px;
    padding-left: 15px;
    width:800px;  
}
.newsletter .normal:hover {
    background-color: rgb(182, 186, 190);
    color: black;
}
#finish {
    display: flex;
    justify-content: space-between;
    align-items: start;
    background-color: rgb(247, 238, 238);
    padding: 10px 10px;
    color: black;
    text-align: left;
}
.contact{
    margin-top: 40px;
    margin-left: 70px;
    font-size: 25px;
}
.question{
    font-size: 15px;
    margin-left: 45px;
}
.Name, .Email, .Subject, .Message{
    width:250px;
    margin-left: 40px;
    padding: 10px 10px;
    margin-bottom: 10px;
}
.send {
    background-color: black;
    color: rgb(247, 238, 238);
    border: 0;
    padding: 10px 10px;
    cursor: pointer;
    font-weight: 500;
    font-size: 15px;
    margin-top: 10px;
    margin-left: 40px;
    margin-bottom: 10px;
    width:275px;
}
#finish .send:hover {
    background-color: rgb(182, 186, 190);
    color: black;
}
.about{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    margin-bottom: 20px;
    color: #080808;
    font-size: 20px;
    margin-right: 50px;
    margin-left: 50px;
    margin-top: 20px;
    text-align: center;
}
.store{
    display: flex;
    flex-direction: column;
    align-items: flex-start;
    margin-bottom: 20px;
    color: #080808;
    font-size: 20px;
    margin-right: 200px;
    margin-left: 10px;
    margin-top: 20px;
}
.about a{
    color:#0f0e0f;
    margin-top: 10px;
    margin-bottom: 3px;
    font-size: 15px;
    text-align: center;
}
.store a{
    color:#0f0e0f;
    margin-top: 10px;
    margin-bottom: 1px;
    font-size: 15px;
    text-align: center;
}
.follow{
    margin-left: -15px;
    margin-top: 20px;
    margin-right: 10px;
}
.power .conclusion{
    display: flex;
    justify-content: space-between;
    align-items: center;
    background-color: black;
    padding-left: 350px;
    padding-top: 30px;
    padding-bottom: 30px;
    padding-right: 420px;
    text-align: left;
    width:900px;

}
.conclusion{
    background-color: #080808;
    color:white;
    font-size: 15px;
}
.power button a:hover{
    color: #74716c;
}
body {
    height: 100vh; /* Full viewport height */
    overflow-y: scroll; /* Vertical scrollbar */
    overflow-x: hidden; /* Prevent horizontal scrollbar */
    margin: 0;
    padding: 0;
}
.conclusion a{
    color:white;
}
    </style>
</head>

<body>
    <div class="container-section">
        <section class="container">
            <div class="scroll-container">
                <div class="text-content">
                    <p><span class="ubuntu-font">L O G O</span></p>
                    <div class="mega" id="banner">
                        <h3 button class="shirts"><b>Shirts</b></h3>
                        <h3 button class="dresses">Dresses</h3>
                        <h3 button class="Jeans" style="color:black;">Jeans
                            <img class="icon" style="height: 15px;width:15px;" src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAAAHlBMVEX///8AAABhYWFZWVleXl5bW1uZmZlWVlZSUlKHh4c7NRlEAAACq0lEQVR4nO3Za47jIBBFYc/E6XTvf8MjVEITx3kYTFGPPt8KfMUh/MiyAAAAAAAAAAAAAAAAAAAAAAAAYOPr9jez29eyfP/J7Luc4mr9FYpWCTXvxLXexYv1lyi5/P+5uVp/i4rr/S9qxlDXZSPfKV6XB9nu4uVxYLZQ1/3AXBOfDswU6pNEc018OTBLqC8SFRkejd0zkS3UN4nmOMUPJxj/Lr69gxlC/Zho9IkHB8YN9VCikSc2DIwZ6uFEo05sHBgv1KZERayn/8BDvxcp1OZEo51i1wkWUe5ixx2sYoTamWiciacGRgj1RKIxJp4e6D3Uk4kKz49G9zOx5TfUAYkKr6c46AQLn3dxyB2sPIY6LFGvEwcP9Bfq0EQ9TlQY6CvU4Yl6m6g00E+oKokKH0//wId+z0OoaokK+1AVE/UxUX2gdajKidpPnDLQMtQJidpOnDbQKtRJiQqLp1/1od+bH+rERMXsU5x8gsXcuzj1DlYzQ52e6OyJRgPnhWqS6MyJhgPnhGqWqNB/NAyeiS3tUE0TFbqnaH6CheZdNL6DlV6oDhIVWhPdDNQK1Umi4qYw8GY9amt8qI4SFaMnuhs4+i66uoPVyKffxUO/Ny5Uh4mKUafo9ASLMXfR5R2sRoTqNlFxfqLzgedDdZ2oODcxwMBzobpPVPQ/Go6fia3eUEMkKvpOMcwJFj13McgdrNpDDZSoaJ0YbmBrqMESFS0TQw5sCTVgouLooxHqmdg6FmrQRMWRUwx8gsXnuxj2DlafQg2dqHg/McHA9/9pOPtvotfruxj+DlavQk2RqHg+MdHA56GmSVTsn/7gD/3eY6ipEhXX3CdY3N/FZHewWjMnKtbsA2uoSRMVl+wDS6iJExU/1h8AAAAAAAAAAAAAAAAAAAAAAADw2/0D1Ro1Y8h9PUkAAAAASUVORK5CYII=">
                        </h3>
                    </div>
                    <div class="dropdown">
                        <ul class="dropdown-item" href="#">
                            <img class="icon1" style="height: 15px;width:15px;" src="https://cdn-icons-png.freepik.com/512/120/120909.png">
                            Skinny
                        </ul>
                        <ul class="dropdown-item" href="#">Relaxed</ul>
                        <ul class="dropdown-item" href="#">Bootcut</ul>
                        <ul class="dropdown-item" href="#">Straight</ul>
                    </div> 
                    <div class="aditional">
                        <ul class="aditional-item" href="#">Jackets</ul>
                        <ul class="aditional-item" href="#">Gymwear</ul>
                        <ul class="aditional-item" href="#">Blazers</ul>
                        <ul class="aditional-item" href="#">Shoes</ul>
                    </div>
                    <div class="final">
                        <ul class="final-item" href="#">Contact</ul>
                        <ul class="final-item" href="#">Newsletter</ul>
                        <ul class="final-item" href="#">Subscribe</ul>
                    </div>
                </div>
            </div>
        </section>
        <section class="first-part">
            <section class="container-image">
                <div class="image-content">
                    <div class="head">
                        <ul class="heading">Jeans</ul>
                        <img class="shoping" style="height:20px;width:20px;padding-left: 720px;padding-top:35px;" src="https://cdn-icons-png.flaticon.com/512/25/25619.png">
                        <img class="search" style="height: 20px;width:20px;padding-top: 35px;padding-left: 15px;" src="https://w7.pngwing.com/pngs/608/913/png-transparent-computer-icons-google-search-symbol-mobile-search-search-for-miscellaneous-logo-mobile-phones-thumbnail.png">
                    </div>
                    <div id="hero">
                        <h1 class="new">New arrivals</h1>
                        <p class="collection">COLLECTION 2016</p>
                        <button class="shop">SHOP NOW</button>
                    </div>
                    <section id="product1" class="section-p1">
                        <p class="para">8 items</p>
                        <div class="pro-container">
                            <div class="pro">
                                <div class="pro-one">
                                    <img style="height:200px;width:170px;border-radius: 0px;"src="https://www.w3schools.com/w3images/jeans1.jpg" alt="">
                                    <div class="des">
                                        <span class="adi">Ripped Skinny Jeans</span>
                                        <p class="p">$24.99</p>
                                    </div>
                                </div>
                            </div>
                            <div class="pro">
                                <div class="pro-two">
                                    <div class="overlay-box">New</div>
                                        <div class="buyer">
                                            <img style="height:200px;width:170px;border-radius: 0px;"src="https://www.w3schools.com/w3images/jeans2.jpg" alt="">
                                            <div class="buy-now-box">
                                                <span>Buy Now &#128722;</span> <!-- Unicode for shopping cart -->
                                            </div>
                                        </div>
                                    <div class="des">
                                        <span class="adi"style="padding-right:30px">Mega Ripped Jeans</span>
                                        <p class="p">$19.99</p>
                                    </div>
                                </div>
                            </div>
                            <div class="pro">
                                <div class="pro-three">
                                    <img style="height:200px;width:170px;border-radius: 0px;"src="https://www.w3schools.com/w3images/jeans3.jpg" alt="">
                                    <div class="des">
                                        <span class="adi">Washed Skinny Jeans</span>
                                        <p class="p">$20.50</p>
                                    </div>
                                </div>
                            </div>
                            <div class="pro">
                                <div class="pro-four">
                                    <img style="height:200px;width:170px;border-radius: 0px;"src="https://www.w3schools.com/w3images/jeans4.jpg" alt="">
                                    <div class="des">
                                        <span class="adi">Vintage Skinny Jeans</span>
                                        <p class="p">$14.99</p>
                                    </div>
                                </div>
                            </div>
                            <div class="pro">
                                <div class="pro-five">
                                    <img style="height:200px;width:170px;border-radius: 0px;"src="https://www.w3schools.com/w3images/jeans2.jpg" alt="">
                                    <div class="des">
                                        <span class="adi">Mega Ripped Jeans</span>
                                        <p class="p">$19.99</p>
                                    </div>
                                </div>
                            </div>
                            <div class="pro">
                                <div class="pro-six">
                                    <img style="height:200px;width:170px;border-radius: 0px;"src="https://www.w3schools.com/w3images/jeans3.jpg" alt="">
                                    <div class="des">
                                        <span class="adi">Washed Skinny Jeans</span>
                                        <p class="p">$20.50</p>
                                    </div>
                                </div>
                            </div>
                            <div class="pro">
                                <div class="pro-seven">
                                    <div class="overlay-box">Sale</div>
                                        <div class="buyer">
                                            <img style="height:200px;width:170px;border-radius: 0px;"src="https://www.w3schools.com/w3images/jeans4.jpg" alt="">
                                            <div class="buy-now-box">
                                                <span>Buy Now &#128722;</span> <!-- Unicode for shopping cart -->
                                            </div>
                                        </div>
                                    <div class="des">
                                        <span class="adi"style="padding-right:20px">Vintage Skinny Jeans</span>
                                        <p class="p">$14.99</p>
                                    </div>
                                </div>
                            </div>
                            <div class="pro">
                                <div class="pro-eight">
                                    <img style="height:200px;width:170px;border-radius: 0px;"src="https://www.w3schools.com/w3images/jeans1.jpg" alt="">
                                    <div class="des">
                                        <span class="adi">Ripped Skinny Jeans</span>
                                        <p class="p">$24.99</p>
                                    </div>
                                </div>
                            </div>
                        </div>
                    <section class="newsletter">
                        <div class="newstext">
                            <h4>Subscribe</h4>
                            <p>To get special offers and VIP treatment:</p>
                            <input type="text" class="mail"placeholder="Enter e-mail"></br>
                            <button class="normal">subscribe</button>
                        </div>
                    </section>
                    </section> 
                    <section id="finish">
                        <section class="contact-us">
                            <ul class="contact">Contact</ul>
                            <ul class="question">Questions? Go ahead.</ul>
                            <div class="details">
                                <input type="text" class="Name"placeholder="Name"></br>
                                <input type="text" class="Email"placeholder="Email"></br>
                                <input type="text" class="Subject"placeholder="Subject"></br>
                                <input type="text" class="Message"placeholder="Message"></br>
                                <button class="send" onclick="validateForm()">Send</button>
                            </div>
                        </section>
                        <section class="about">
                            <h4>About</h4>
                            <a href="#">About us</a>
                            <a href="#">We're hiring</a>
                            <a href="#">Support</a>
                            <a href="#">Find store</a>
                            <a href="#">Shipment</a>
                            <a href="#">Payment</a>
                            <a href="#">Gift card</a>
                            <a href="#">Return</a>
                            <a href="#">Help</a>
                        </section>
                        <section class="store">
                            <h4>Store</h4>
                            <a> Company Name</a>
                            <a> 0044123123</a>
                            <a>ex@mail.com</a>
                            <h4>We accept</h4>
                            <a style="margin-top:-10px;">Amex</a>
                            <a> Credit Card</a>
                            <div class="follow">
                                <div class="icon">
                                    <img style="height:20px;width: 20px;padding-top: 10px;"src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAAAclBMVEX///8AAADx8fGxsbH39/e+vr6KioopKSkoKCj7+/vg4OBAQECNjY0JCQkNDQ1aWlpfX19LS0tGRkbp6enQ0NCDg4OhoaEjIyPb29urq6vm5uaamprDw8MwMDBubm4dHR02NjaVlZVUVFR3d3dmZmYVFRV4y9GXAAAC9klEQVR4nO3dC3LaMBRGYTAmwUB4Q3iEJqFk/1tshnZSaKfgK1+k3+45C2D0zYAsGyFarbQVeb+7GU6mg/3rqP3V00WjU7P3IvFY7WWL3bfXdvl689QjNtVfTUe3UZcdUw+6fPPVm1V3Kks98JItxkG8z15SD71MRWcW6mu3u6lHX6LuY7ivDsL+tIpPX5gvq/nkhet9VaC4cFXZpy3MJw5AZWE28AAKC+fPLkBdYd/Hpyt0A6oKs17ThT6TjLDw6AfUFO4cgZLCtSdQUhh2L18jYeW7CXWh73tUUXhouvDFGagn9J1mBIUdb6Cc0G89Kip0/xTKCYOfbNdFuPUHigkfGi90v1SoCb0XbHrC98YLHZ9daArvMZNqCf1XbGpC51vfX61Ts85yeoz/R3lq1ll3Aa5Sq85a3AM4TK06L3yieR4cjsuHvxtu+qlRF4VNNOPOQumTdrWQO6el0kx5s4Bldy32O31VmC8WH9vUY7ZlX7MprVbKZL51mqQesTWzsF4fwlbABT/1gM1Zhd9TD9icVbhLPWBzXaOwbjOpfVmqteQsk1VYlx3qv0OIUD+ECPVDiFA/hAj1Q4hQP4QI9UOIUD+EdRDm2ZXyjVG4vfZqP4t8OM38+GE0VO4t6ncbfj97tXSIKKxwOkmV4m2JmqcBtqfRhHf4IUWp9tFmG+u3g171om2YQogQ4f8rfESIECFChAgRIkSIECFChAgRIkSIECFChAgRIkSIsHbC5u9UyBIJI24Zqvh/OKFt4gnT7PoaxwN+vk89D8sv1yj6MVhF/u8K6+7L+bVXOxWbd6sm7KC9HkKE+iFEqB9ChPohRKgfQoT6IUSoH0KE+iFEqB9ChPohRKgfQoT6IUSoH0KE+iFEqB9ChPohRKgfQoT6IUSoH0KE+iFEqB9ChPohRKgfQoT6IUSoH0KE+iFEqB9ChPohRKgfQoT6IUSoX/OF1nN46ydc24Cz1OMNaGASRj+a1CHTKbVRD5d1K1vuy/GeZnc+HvgHllpO87YiSVIAAAAASUVORK5CYII="/>
                                    <img style="height:20px;width: 20px;padding-top: 10px;"src="https://cdn-icons-png.flaticon.com/512/87/87390.png"/>
                                    <img style="height:22px;width: 22px;padding-top: 10px;"src="https://media.istockphoto.com/id/1167482178/vector/bell-icon-notification-bell-icon-vector.jpg?s=612x612&w=is&k=20&c=8XxeQq62CzJFO5zeXjZQ60YS7Ipct5BGCY3HekhxdAU="/>
                                    <img style="height:20px;width: 20px;padding-top: 10px;"src="https://www.zarla.com/images/zarla-p-1x1-2400x2400-20211124-gpwxt6df6qgtc6dfmy6h.png?crop=1:1,smart&width=250&dpr=2"/>
                                    <img style="height:20px;width: 20px;padding-top: 10px;"src="https://logowik.com/content/uploads/images/761_twitter.jpg"/>
                                    <img style="height:20px;width: 20px;padding-top: 10px;"src="data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAOEAAADhCAMAAAAJbSJIAAAAgVBMVEUAAAD////u7u7t7e309PT39/f7+/s0NDT19fU4ODjx8fEpKSkoKCgsLCzNzc3U1NSMjIyFhYU9PT3d3d2Xl5fR0dG/v7/FxcXj4+NjY2Ofn59cXFxQUFBISEiwsLBzc3OpqakODg5ubm59fX24uLiIiIgTExNYWFgcHBxDQ0MhISEGPjwiAAAIyklEQVR4nO1dbXfiLBA1BGjEGttqNdrW2upu99n//wMfgZh3spIhBjD3w55Zz2zO3E1gBriZTAIOGqIzsLCFiYQprFCYWJjUPWc0GRlaGPTI8O4YUo4o5GDcJMJE4mckbMJNJszIQeeJ+FNyZrkZEI6CSXNT/kyrHjY4Y4aIvL+Cvfh1Urir7GwxzE6/3qfTB46pwENuN5vWOH8cD0lh1DUxZDTeTtzG9rWNIU5c58fxFioZ0s3X0NGZwUZMrpdxiDkYB10PHZkx7GnGiuX5EG+GjssgNiIfhqWMzxJPHlGJMKjVNNSHSSbHe40hi4eOyTA2ZYYkxH7dwsnkh4/DYtXGho7IOJZI1Kz0kg9PQwdkHDtczvi/hg7IOLZRmeH70AEZx5SUGU6HDsg4ZqV7iDxk+EiYWDum+ZA8DB2QccwDuQvgM8NSTTMydBD3wDAdh97OpbPLXOptPnzE3mf8kaHzyBim60P/GJ7HoVwfpjv+PmYLPFZtjmNk6D541SYYynML6h/DGU3PLbzNh2PV5j7uiKHPVZtkKPU0HmaLWaqe8Tofep/x/a9p/GcYFZV7HjLMZhr/swUw4//+3i/CJEmWp6cXowGCYaam+XvickjCNWTnyy0/DQcJghGGuyhVcvBLcGFnYtFwNsDwKyZSj5wzDOib+VA7IhuH3VfAS3oRx+XqP0asoZitgDvnwwX/hw0S8t89RNsF2S5GV4bHQMHQFvkYuKYJVQxtEa5AGX4GSoaW6FTLDPV39dfyDQD5ooNkeHmXgfQSsDbmFeWebraIZNFXeB9FvObBX3TAP71ErIvsZKZbPnwRL2egej48m9Gxn5A1Acz4by0M8a6fkDUBZLhtY3joJWJdABn+2H8Py6snbbXJPBIMUcT1HNIU2g6+rCaWjEOgci9RZ4vAjtIUqtzbU2XGtycfgmqaH3VNY4lkHFyXLpUMLdnyATN8V43Dg/lgOwGu3NuRprkUL3sIthMMKPdOpJ4Pg+SP+Vi7wcRu4vkuVhkujAfaGUb22rZyuskY0pXpMAEwdAb8zN+d5ls+OArQyponlMPYGfDXcXdar/er41+T4RnAqNxzH/dwfjgydB2jcs99jMq9IfDwdlztDofV8/ebgUFjG8P58ylB6ZEyJgQl8eo/2BXBVds+5lhyLIS5EHYcVzYxhMtr3Tkp+n0uGGZZmxy+qOar6nAHOYsEK/cWgeg7Jfu+iL5THOflVFLxE4fEtOaM83PGz+S8WG1oboUwWXd/XMHKvYVqnyYs+8V8B6Ch51jWiGMaE6ZqUMYAmyJg5Z4phkexCdLSgo11HI/gmsYQw738n25tMvdsN8NNK8P1NW30SKeDELBy71XV7K4y02xYc2c8wXAfXNVGrxNFsHIvFv8+3YkS3NK7UNmMWlwSQNV5OZms+F/knB5mpx6Nzh0ogqu2OJ8gSqdrrLJh+iqCRnXnxeQbp/Pl5aHMW//VrqwvmQPXNAYYUnQ9w0B7l2t4hq9xlvOuYai9E9sfw0ookmHY7IyyznhFho3O2s8pWLn3SnK5XkG5h0nlHm6iqkejySpm3SNpjkMJsHLv2ny45hV1a6fY/JbJm6py1txQByv3dBiaaZyrebZ8s5rGHEPNkegiQ73pFKrcuzCsnwFXZoQ1L1GwyjmQnfEQK5Qwaue5JkMjVVtNuVet2uIg68rcJPOTVVsSn06bhOCAtjljrUUGULl3fcaP+c9qARViJL6Mr69j0urMtJSrN6tp/sEw2pTGx5G2OVeGuBMMSbWb4R/W9t+hI7C+WdXWxhDhukDsC2M1Q52BCFTupQwblHvVe7ihmUfNOWrKcD9EceVzHtGRW0GVe+psUcuHygSA941XPqlTi45YB9xzD57xq3f7gi/Vlfkjp8Nw8JqGqBr7bjxhqLqF6bsczQw1wjTFsPs4VFcov6lqHOqIc8HKPfBcSj+U116w5rkUEY3lBVi5B86HLcu9A1OUeDqvctxsN1HJEKuvvcIqhhopf/iqrWXf5TvygmFL9n5vUK52ZzjU+rBtxf4fUSwmdVaIYOUedI3f9qmCF2W2eLo+QLByD5rx/8mwMePrMRy2phkZusWwaRv7BgyByj3ouUXUwnAaKA45qMYnHMDKPfDZU0s+nKryoWa2kPmw74zfckKqz9DKmmZk2D9DYNUm4+DooMVQM2y6sn7VJhkOqqdR4CVQfJZSJ1vcTLnXrolSMTSTD2+T8QdkaIWubWRo4in1f6bxP1v0nfElQ59rmpGhgwwrkS/lOKw732z11PcKOB58Bdx3PowH38W4BUO/a5qR4Y0Y9rirHw++qw+s2v55MrPscDIzNXoy03fGl/mwIeN3yYd2ZPxrGbpb01QYKgWV7jKsRK5keNs97x7VJkuF2oS+tjCkKrWJzj28lXJvMVy2uJFyb2FHxh8Z3jNDB8Zh33NpMvhc2nc+DO3Ihx0Yyl0McY0AF8zqLoZ40AiuO7cwfAmarqy7iwFleHziWHE8PRXtikDyKfcoO7cIKf+uGq98hsYLF7Z1bzGPu/juGky5Zz3GnnvuY2ToPsaee+5j7LnnPu6Ioc9Vm2TYVU9jPcav5bqPe6hp/Gc4fi3XdYxVm/sYGboPA1/LtRzwr+XaDrByz3rcQ01zXwy93tX3uWqDKfesh/8Zf2ToPsDKPevxCFXuWY+qck/deMtVTMs1DbbjO8wmsS0zZIehAzKOQ5kh0u14bj/CS9Um51ISqNo0uooPzMrKvaBFKugk9hiVM74tX0Q3hReKagy1Gi1bDy5NrjIMtLplW44DP7MonQHzhVTQ3NbXRRxEOVNS7kmavtzFg/wIX0m5J/bdcBDqtAS3FS+LqPDVBVRmeB6MP0MHCMTHnjLUxjAIlrvtdPY455g9zmYlc1Yx5wVzcOfH+XR7CEVLdwXD9K0IhCMSyc/zFATotKpFp7lplTNDOcOicq/2fn90tqL819TkPxdMC53rnQoK+dDEV5ksdC4xRErva7+sZaHzyNDKoEeGJef/Aeak5DnuHFFJAAAAAElFTkSuQmCC"/>
                                </div>
                            </div>
                        </section>
                    </section>
                    <section class="power">
                        <div class="power-by">
                            <button class="conclusion">Powered by<a href="#">w3.css</a></button>
                        </div> 
                    </section>    
                </div>
            </section>
        </section>
    </div>
    <script>
      document.querySelector('.Jeans').addEventListener('click', function() {
            const dropdown = document.querySelector('.dropdown');
            dropdown.style.display = dropdown.style.display === 'block' ? 'none' : 'block';
        });         
        function validateForm() {
            var name = document.querySelector('.Name');
            var email = document.querySelector('.Email');
            var subject = document.querySelector('.Subject');
            var message = document.querySelector('.Message');
        
            if (name.value === "") {
                alert("Please fill in your Name.");
                name.focus(); // Cursor moves to the name input
                return false;
            }       
            if (email.value === "") {
                alert("Please fill in your Email.");
                email.focus();
                return false;
            }       
            if (subject.value === " ") {
                alert("Please fill in the Subject.");
                subject.focus();
                return false;
            }       
            if (message.value === "") {
                alert("Please fill in the Message.");
                message.focus();
                return false;
            }
            alert("Form submitted successfully!");
        }


    </script> 
       
   
</body>
</html>
