<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.2/css/all.min.css" integrity="sha512-SnH5WK+bZxgPHs44uWIX+LLJAJ9/2PkPKZ5QiAj6Ta86w+fsb2TkcmfRyVX3pBnMFcV7oQPJkl9QevSCWr3W6A==" crossorigin="anonymous" referrerpolicy="no-referrer" />
<link rel="stylesheet" href="portfolio.css">

<body>
    <header class="bg-grey">
        <nav class="navbar">
            <div class="logo">Portfolio</div>
            <ul class="navlist" id="navlist">
                <li>
                    <a href="#" class="active navlinks">Home</a>
                </li>
                <li>
                    <a href="#" class="navlinks">Intro</a>
                </li>
                <li>
                    <a href="#" class="navlinks">Services</a>
                </li>
                <li>
                    <a href="#" class="navlinks">portfolio</a>
                </li>
                <li>
                    <a href="#" class="primary-btn">Hire me</a>
                </li>
            </ul>
            <div class="hamburger" id="hamburger">
                <i class="fa-solid fa-bars"></i>
            </div>

        </nav>
    </header>
    <main>
        

        <!-- ----Hero SECTION------- -->

        <section class="hero-section bg-white">
            <div class="container">
                <div class="row-container">
                    <div class="content">
                        <h3>Hello!</h3>
                        <h1>I'm Acxa Mary Reji</h1>
                        <h2>UI/UX designer</h2>
                        <p>I am a UI/UX Designer and a BCA graduate with expertise in front-end development. Beyond coding, I excel in communication, project management, and problem-solving. My adaptability and proactive approach ensure I effectively contribute to dynamic environments and continuously deliver high-quality results.</p>
                        <div class="action">
                        <a href="ACXA.RESUME.pdf" class="primary-btn" download="">Download CV</a>
                        <a href="#" class="primary-btn" data-type="inverted-btn">Contact me</a>
                        </div>
                    </div>
                    <div class="image-container">
                        <img src="assets/uffffo45.png" alt="profile">
                    </div>
                </div>
            </div>
        </section>
        <br>
        

        <!-- --------SERVICES----- -->
         
        <section>
            <div class="container">
                <div class="column-container">
                   <div class="content">
                    <h3>Services</h3>
                    <h1>What I Offer</h1>
                  </div>
                 <div class="grid-card-container">
                    <div class="card">
                        <i class="fa-solid fa-lightbulb fill-white" data-type="card-icons"></i>
                        <h4>UI/UX designer. </h4>
                        <p class="para">skilled UI/UX designer, can design and develop pages according to the needed requirements </p>
                    </div>
                  </div>
                 <div class="grid-card-container">
                     <div class="card">
                        <i class="fa-solid fa-file fill-white" data-type="card-icons"></i>
                        <h4>Front End Developer. </h4>
                        <p class="para">skilled front end developer, develops web pages according to the needed requirements.</p>
                    </div>
                </div>
              </div>
            </div>
        </section>
        <br>
        <br>
        

        <!-- ------PORTFOLIO------ -->
        <section class=" secton bg-white">
            <div class="container">
                <div class="column-container">
                    <div class="content">
                        <h3>My portfolio</h3>
                        <h1>Recent work</h1>
                    </div>
                    <div class="grid-card-container">
                        <div class="portfolio-card">
                            <a href="facebook.html" class="primary-btn demo">view project</a>
                        </div>
                        <div class="portfolio-card">
                            <a href="netflix.html" class="primary-btn demo ">view project</a>
                        </div>

                        

                    </div>
                </div>
            </div>

        </section>
        <br>
        <br>
        <br>
        


        <!-- ---------CONTACT US-------- -->

        <section class="section bg-white">
            <div class="container">
                <div class="column-container">
                    <div class="content">
                       <h3>Contact Us</h3>
                       <h1>Get In Touch</h1>
                    </div>
                    <form action="#" class="form">
                        <input type="text" placeholder="username" required>
                        <input type="text" placeholder="phone number" required>
                        <input type="email" placeholder="email address" required>
                        <textarea placeholder="message" rows="6" required></textarea>
                        <input type="submit" value="send message" class="primary-btn">

                    </form>
                </div>
            </div>

        </section>
    </main>

    <!-- ------footer------ -->
     <footer class="footer-section bg-black">
        <div class="container">
            <p class="para fill-white">Copyright &copy;2024 All rights reserved by Acxa </p>
        </div>
     </footer>

    
</body>
</html>
