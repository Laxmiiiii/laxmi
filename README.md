<!DOCTYPE html>
<html lang="en">

<head>
    <title>Portfolio Website</title>
    <!--<link rel="stylesheet" href="portfolio.css" />
   <link
        href="https://fonts.googleapis.com/css2?family=Lato:wght@300&family=Mulish:wght@300;400;600;700;800&display=swap"
        rel="stylesheet" />
   <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.1.1/css/all.min.css"
        integrity="sha512-KfkfwYDsLkIlwQp6LFnl8zNdLGxu9YAA1QvwINks4PhcElQSvqcyVLLD9aMhXd13uQjoXtEKNosOWaZqXgel0g=="
        crossorigin="anonymous" referrerpolicy="no-referrer" />
  .navbar {
    position: fixed;
    top: 0%;
    background-color: #fff;
    width: 100%;
    box-shadow: 0px 0px 8px rgba(201, 61, 61, 0.06);
  }
  ul {
    list-style-type: none;
    font-family: "Lato", sans-serif;
    font-weight: 600;
    margin-top: 0%;
  }
  li {
    float: left;
  }
  li a {
    display: block;
    padding: 25px;
    background-color: #fff;
    text-decoration: none;
    color: black;
  }
  
  /* banner section */
  .container {
    width: 100%;
    margin: 2% 0%;
    padding: 6% 0%;
  }
  .banner {
    display: grid;
    grid-template-columns: repeat(2, 50%);
    background-color: #dcdfb7;
  }
  
  .banner .image  {
    width: 100%;
  }
  
  .banner .content {
    font-family: "Lato", sans-serif;
    padding: 20% 0%;
  }
  
  .banner .content .title {
    font-size: 50px;
  }
  .banner .content .title span {
    font-weight: 800;
  }
  
  .banner .content .desc {
    font-size: 26px;
  }
  
  .banner .content .btn {
    background-color: #6b8363;
    color: #fff;
    font-size: 16px;
    font-weight: 700;
    padding: 2% 5%;
    border-radius: 30px;
    border: none;
    cursor: pointer;
    font-family: "Lato", sans-serif;
  }
  .banner .content button:hover{
      background-color: rgb(182, 61, 17)
  }
  
  /* about me section */
  .about {
    display: grid;
    grid-template-columns: repeat(2, 50%);
  }
  
  .about .image img {
    width: 80%;
    margin-top: 10%;
  }
  
  .about .content {
    font-family: "Lato", sans-serif;
    padding: 20% 13%;
  }
  
  .about .content .title {
    font-size: 28px;
    font-weight: 700;
  }
  
  .about .content .desc {
    font-size: 19px;
  }

  /* skills */

  .skills .content{
    font-family: "Lato" , sans-serif;
    background-color: #dcdfb7;
    padding:2% 10%;
  }

  .skills .content .title{
    font-size:28px;
    text-align: center;
    font-weight: 800;
  }
.skills .grid-container{
  display: grid;
  grid-template-columns: repeat(4, 25%);
  grid-gap: 10px 20px;
  margin-right: 4%;
}
.skills .grid-container .grid-item{
  border: 1px solid #fff;
  background:#fff;
  border-bottom: 5px solid #6b8363;
  padding: 7% 6% ;
  border-radius: 10px;

}
.fa-brands{
  margin-right: 8%;
  font-size: 19px;
  color:#6b8363
}

/* contact section */
.contact {
  display: grid;
  grid-template-columns: repeat(2, 50%);
}
.contact .image img {
  width: 80%;
}

.contact .content {
  font-family: "Lato", sans-serif;
  padding: 10% 13%;
}

.contact .content .title {
  font-size: 28px;
  font-weight: 700;
  margin: 0%;
}

.contact .content .form {
  padding: 2% 0%;
}

.contact .content .form .field {
  padding: 2% 0%;
}

.contact .content .form .title {
  font-size: 16px;
}
.contact .content .form .input {
  font-size: 16px;
  font-family: "Lato", sans-serif;
  width: 55%;
  padding: 2% 2%;
  border: 1px solid #ddd;
  border-radius: 8px;
  margin-top: 2%;
}

.contact .content .btn {
  background-color: #6b8363;
  color: #fff;
  font-family: "Lato";
  font-size: 16px;
  font-weight: 700;
  padding: 2% 10%;
  margin-top: 3%;
  border-radius: 30px;
  border: none;
  cursor: pointer;
}
.contact .content .btn:hover{
  background-color: orangered
}

/* footer section */
.footer {
  width: 100%;
  background-color: rgb(34, 30, 30);
  font-size: 50px;
  font-family: "Lato", sans-serif;
  text-align: center;
  color: #fff;
  padding: 2% 0;
}

.footer .footer-title h2 {
  font-weight: 600;
  color: #fff;
  font-size: 30px;
}

.footer .social-sites .footer-icons a {
  text-decoration: none !important;
  background-color: transparent !important;
  color: #fff;
  padding: 10px 12px;
  margin-right: 30px;
}

.footer .social-sites .footer-icons a:hover {
  color: #fff;
}

.footer .footer-icons a .fab {
  font-weight: 600;
  font-size: 20px;
}

.footer .social-sites p {
  font-size: 15px;
  padding: 35px 0px;
  color: #fff;
}-->
</head>

<body>
    <div class="main-container">
        <!-- navbar section -->
        <div class="navbar">
            <ul>
                <li>
                    <a href="#home">Home</a>
                </li>
                <li>
                    <a href="#about">About Me</a>
                </li>
                <li>
                    <a href="#skills">Skills</a>
                </li>
                <li>
                    <a href="#contact">Contact</a>
                </li>
            </ul>
        </div>
        <!-- banner section -->
        <div class="container banner">
            <div class="image">
                <img src="https://github.com/Laxmiiiii/Test/blob/main/banner.png?raw=true" alt="banner-img" />
            </div>
            <div class="content">
                <p class="title">Hey! I'm <span>Laxmi</span></p>
                <p class="desc">I am a Software Developer at MNC.</p>
                <button class="btn" href="#about">About Me</button>
            </div>
        </div>
        <!-- about section -->
        <div class="container about" id="about">
            <div class="content">
                <p class="title">About Me</span></p>
                <p class="desc">
                    Lorem ipsum dolor, sit amet consectetur adipisicing elit. Libero assumenda
                     odio impedit id nesciunt nihil. Quos culpa quo quas voluptas.Ipsum
                     is simply dummy text of the printing and typesetting
                    industry. Lorem Ipsum has been the industry's standard dummy text
                    ever since the 1500s, when an unknown printer took a galley of type
                    and scrambled it to make a type specimen book. It has survived not
                    only five centuries, but also the leap into electronic typesetting,
                    remaining essentially unchanged. It was popularised in the 1960s
                    with the release of Letraset sheets containing Lorem Ipsum passages,
                    and more recently with desktop publishing software like Aldus
                    PageMaker including versions of Lorem Ipsum.
                </p>
            </div>
            <div class="image">
                <img src="https://github.com/Laxmiiiii/Test/blob/main/me.png?raw=true" alt="about-img" />
            </div>
        </div>
        <!-- skills section -->
        <div class="container skills" id="skills">
            <div class="content">
                <p class="title">Skills</span></p>
                <div class="grid-container">
                    <div class="grid-item"><i class="fa-brands fa-html5"></i>HTML</div>
                    <div class="grid-item"><i class="fa-brands fa-css3"></i>CSS</div>
                    <div class="grid-item"><i class="fa-brands fa-bootstrap"></i>Bootstrap</div>
                    <div class="grid-item"><i class="fa-brands fa-js"></i>Javascript</div>
                </div>
            </div>
        </div>

        <!-- contact section -->
        <div class="container contact" id="contact">
            <div class="image">
                <img src="https://github.com/Laxmiiiii/Test/blob/main/my%20work.png?raw=true" alt="my work-img"/>
            </div>
            <div class="content">
                <p class="title">Get in touch with me here!</p>
                <form action="/action_page.php" class="form">
                    <div class="field">
                        <label for="email" class="title">Your email id:</label><br />
                        <input type="text" id="email" name="email" value="k.laxmisetty111@gmail.com" class="input" />
                    </div>
                    <div class="field">
                        <label for="lname" class="title">Message for Me:</label><br />
                        <input type="text" id="msg" name="msg" value="Hi! Hello Mis" class="input" />
                    </div>

                    <input type="submit" value="Submit" class="btn" />
                </form>
            </div>
        </div>
        <div class="footer" id="footer">
            <div class="footer-title">
                <h2>K Laxmi</h2>
                <div class="social-sites">
                    <div class="footer-icons">
                        <a href="#" class="ico">
                            <i class="fab fa-instagram"></i>
                        </a>
                        <a href="#" class="ico">
                            <i class="fab fa-linkedin-in"></i>
                        </a>
                        <a href="#" class="ico">
                            <i class="fab fa-github"></i>
                        </a>
                        <p>© <span id="year"></span>
                            <script>
                                var d = new Date();
                                var n = d.getFullYear();
                                document.getElementById("year").innerHTML = n;
                            </script>
                            copyright all right reserved /-
                        </p>
                    </div>
                </div>
            </div>
        </div>



</body>

</html>
