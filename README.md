<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Landing Page</title>
    <link rel="stylesheet" href="style.css">
    <link href="https://cdn.jsdelivr.net/npm/remixicon@4.2.0/fonts/remixicon.css" rel="stylesheet" />
</head>
<style>
* {
    margin: 0;
    padding: 0;
    font-family: 'Trebuchet MS', 'Lucida Sans Unicode', 'Lucida Grande', 'Lucida Sans', Arial, sans-serif;
    box-sizing: border-box;
}

body {
    width: 100%;
    height: 100%;
}

#main {
    width: 100%;
    min-height: 100vh;
}

.top {
    width: 100%;
    min-height: 60vh;
    background-image: url(https://i.pinimg.com/736x/be/f4/84/bef484c1c2679790df69058bcd570d53.jpg);
    background-position :center;
    background-size: center;
}
.top.overlay{
    position: relative;
    width: 100%;
    min-height: inherit;
    background-color: rgb(0, 0, 0,0.295);
}
.text{
    display: flex;
    justify-content: space-between;
    align-items: center;
    position: absolute;
    width: 100%;
    padding: 0 10vh;
    color: rgba(11, 10, 10, 0.845);
    bottom: 5%;
}
.text h1{
    font-weight: 600;
    font-size: 4vw;
}
.text.image{
    background-image:url(https://images.app.goo.gl/UUSi7nPy3tNwa4yx7);
    background-size: cover;
    background-position: center;
    height: 300px;
    width: 220px;
}
.rtext{
    display: flex;
    width: 25%;
    align-items: center;
    justify-content: space-between;
}
.rtext p{
    font-size: 12px;
}
.bottom{
    display: flex;
    width: 100%;
    min-height: 40vh;
}
.b1{
  width: 30%;
  min-height: inherit;
  background-image:url(https://upload.wikimedia.org/wikipedia/commons/4/40/Sunflower_sky_backdrop.jpg);
  background-size: cover;
  background-position: center;
}
.b1 h1{
    text-align: center;
    padding: 30px;
}
.b1 p{
    color: white;
    text-align: center;
    padding: 15px;
}
.b2{
  width: 30%;
  min-height: inherit;
  display: flex;
  flex-direction: column;
}
.b2 up{
    width: 100%;
    min-height: 20vh;
    background-image: url(https://www.istockphoto.com/photo/laptop-with-sunflower-background-sitting-in-field-of-grass-gm157423911-8810466?utm_campaign=srp_photos_top&utm_content=https%3A%2F%2Funsplash.com%2Fs%2Fphotos%2Fsun-flower-url-link&utm_medium=affiliate&utm_source=unsplash&utm_term=sun+flower+url+link%3A%3A%3A);
    background-size: cover;
    background-position: center;
}
.b2.up h1{
    text-align: center;
    padding: 30px; 
}
.b2.up p{
    color: white;
    text-align: center;
    padding: 15px;
}
.b2.down{
    width: 100%;
    min-height: 20vh;
    background-image: url(https://images.herzindagi.info/image/2023/Oct/best-laptops-2.jpg);
    background-size: cover;
    background-position: center;
}
.b2.down.overlay{
    position: relative;
    width: 100%;
    min-height: 20vh;
    background-color: rgba(255, 255, 255, 0.425);
}
.b3{
  width: 40%;
  min-height: inherit;
  background-image: url(https://www.ucda.com/files/3117/);
  background-size: cover;
  background-position: center;
}
.b3 .overlay{
    justify-content: right;
    position: relative;
    margin-left: 50%;
    width: 50%;
    height: 100%;
    padding: 4vw 3vh;
}
.b3.overlay p{
    padding: 1.2vh;
}
@media(max-width:700px){
    .rtext{
        flex-direction: column;
    }
    .b3.overlay{
        width: 200%;
        margin-left: initial;
    }
}
@media(max-width:500px){
    .text{
        flex-direction: column;
        align-items: flex-start;
    }
    .text h1{
        font-size: 5vh;
    }
    .text.image{
        height: 200px;
        width: 140px;
        margin-top: 20px;
    }
    .rtext{
        flex-direction: column;
        align-items: flex-start;
    }
    .rtext p{
        margin-top: 10px;
    }
    .icons{
        margin-top: 10px;
    }
    .bottom{
        flex-direction: column;
        align-items: flex-start;
    }
    .b1{
        width: 100%;
        min-height: 30vh;
    }
    .b2{
        width: 100%;
    }
    .b2.up{
        min-height: 30vh;
    }
    .b3{
        width: 100%;
        min-height: 30vh;
        background-position: left;
    }
}

</style>




<body>
    <div id="main">
        <div class="top">
            <div class="overlay">
                <div class="text">
                    <h1>Images</h1>
                    <div class="Images"></div>
                    <div class="rtext">
                        <p>Mesmerizing</p>
                        <p>Astonishing</p>
                    </div>
                    <div class="icons">
                        <i class="ri-twitter-fill"></i>
                        <i class="ri-instagram-fill"></i>
                        <i class="ri-facebook-fill"></i>
                    </div>
                </div>
            </div>
        </div>
        <div class="bottom">
            <div class="b1">
                <h1>Popular</h1>
                <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aspernatur corrupti, quidem quam voluptas
                    tempore incidunt.</p>
            </div>
            <div class="b2">
                <div class="up">
                    <h1>Latest</h1>
                    <p>Lorem ipsum dolor sit amet consectetur adipisicing elit. Aperiam, minima exercitationem.</p>
                </div>
                <div class="down">
                    <div class="overlay"></div>
                    <h1>More...</h1>
                </div>
            </div>
            <div class="b3">
                <div class="overlay">
                    <p>Privacy Policies</p>
                    <p>Terms and Conditions</p>
                    <p>Contact Us</p>
                    <p>About Us</p>
                </div>
            </div>
        </div>
    </div>
</body>


</html>
