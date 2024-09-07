<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
    <link rel="stylesheet" href="style.css">
    <title>GhsotAce Saint</title>
</head>
<body>
    <nav>
        <div class="nav-container">
            <div class="logo" data-aos="zoom-in" data-aos-duration="1500">
                Ghost <span>Ace</span>
            </div>
            <div class="links">
                <div class="link" data-aos="fade-up" data-aos-duration="1500" data-aos-delay="300"><a href="Gamer.html">Home</a></div>
                <div class="link" data-aos="fade-up" data-aos-duration="1500" data-aos-delay="400"><a href="videos.html">Videos</a></div>
                <div class="link" data-aos="fade-up" data-aos-duration="1500" data-aos-delay="500"><a href="Comment.html">Comments</a></div>
        </div>
        <i class="fa-solid fa-bars hamburg" onclick="hamburg()"></i>
    </div>
        <div class="dropdown">
            <div class="links">
                <a href="Gamer.html">Home</a>
                <a href="videos.html">Videos</a>
                <a href="Comment.html">Comments</a>
                <i class="fa-solid fa-xmark cancel" onclick="cancel()"></i>
            </div>
        </div>
    </nav>
    <section>
        <div class="main-container">
            <div class="image" data-aos="zoom-out" data-aos-duration="3000">
                <img src="C:\Users\LENOVO\Pictures\Fondo Ghost Legendario.jpg" alt="">
            </div>
            <div class="content">
                <h1 data-aos="fade-left" data-aos-duration="1500" data-aos-delay="700">Soon To Become</h1>
                <div class="typewriter" data-aos="fade-right" data-aos-duration="1500" data-aos-delay="900"><span class="typewriter-text"></span><label for="">|</label></div>
                <p data-aos="flip-down" data-aos-duration="1500" data-aos-delay="1100">Hellow i'm GhostAce an dedicated gamer who plays 
                    every day with the goal of becoming a well-known name in the gaming world. With a passion for competitive play and 
                    a drive to succeed, I strives to improve skills, build a fanbase, and achieve gaming fame.
                    Understanding that success in gaming isn't just about play, I currently studying Information Technology (IT) to gain
                    more knowledge in areas like video editing, programming, Game Creator and content creator. This expertise will help 
                    create engaging content, build custom mods, and navigate the technical side of gaming to stand out in the industry.                   
                    I'm determined to combine gaming talent with tech skills to rise to the top and become a recognized figure in the 
                    gaming community.</p>
                <div class="social-links">
                    <a href="https://www.facebook.com/me/" data-aos="fade-up" data-aos-duration="1500" data-aos-delay="1400"><i class="fa-brands fa-facebook"></i></a>
                    <a href="https://www.tiktok.com/@3ghostace3?is_from_webapp=1&sender_device=pc" data-aos="fade-up" data-aos-duration="1500" data-aos-delay="1500"><i class="fa-brands fa-tiktok"></i></a>
                    <a href="http://www.youtube.com/@Ghost-Ace35" data-aos="fade-up" data-aos-duration="1500" data-aos-delay="1600"><i class="fa-brands fa-youtube"></i></a>
                </div>
            </div>
        </div>
        <footer>&copy;GhostAce Saint</footer>
    </section>
    <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
    <script>
      AOS.init({offset:0});
    </script>
    <script src="script.js"></script>
</body>
</html>

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.5.1/css/all.min.css">
    <link rel="stylesheet" href="https://unpkg.com/aos@next/dist/aos.css" />
    <link rel="stylesheet" href="style.css">
    <title>GhsotAce Saint</title>
    <style>
      .video-grid {
        display: grid;
        grid-template-columns: repeat(3, 1fr);
        gap: 10px;
        overflow-y: auto;
        max-height: 600px;
        padding: 10px;
      }
      .video-grid-item {
        background-color: #f7f7f7;
        padding: 5px;
        border: 1px solid #ddd;
        border-radius: 10px;
        cursor: pointer;
      } 
      .video-grid-item:hover {
        background-color: #eee;
      }
    </style>
</head>
<body>
    <nav>
      <div class="nav-container">
        <div class="logo" data-aos="zoom-in" data-aos-duration="1500">
            Ghost <span>Ace</span>
        </div>
        <div class="links">
            <div class="link" data-aos="fade-up" data-aos-duration="1500" data-aos-delay="300"><a href="Gamer.html">Home</a></div>
            <div class="link" data-aos="fade-up" data-aos-duration="1500" data-aos-delay="400"><a href="Videos.html">Videos</a></div>
            <div class="link" data-aos="fade-up" data-aos-duration="1500" data-aos-delay="500"><a href="Comment.html">Comments</a></div>
    </div>
    <i class="fa-solid fa-bars hamburg" onclick="hamburg()"></i>
</div>
    <div class="dropdown">
        <div class="links">
            <a href="Gamer.html">Home</a>
            <a href="Videos.html">Videos</a>
            <a href="Comment.html">Comments</a>
            <i class="fa-solid fa-xmark cancel" onclick="cancel()"></i>
        </div>
    </div>
    </nav>
    <section class="video-grid">
      <div class="video-grid-item" data-aos="fade-up" data-aos-duration="1500" data-aos-delay="100">
        <video width="100%" height="100%" controls>
          <source src="Gameplay0.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>
      <div class="video-grid-item" data-aos="fade-up" data-aos-duration="1500" data-aos-delay="200">
        <video width="100%" height="100%" controls>
          <source src="Gameplay 1.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>
      <div class="video-grid-item" data-aos="fade-up" data-aos-duration="1500" data-aos-delay="200">
        <video width="100%" height="100%" controls>
          <source src="Gameplay2.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>
      <div class="video-grid-item" data-aos="fade-up" data-aos-duration="1500" data-aos-delay="200">
        <video width="100%" height="100%" controls>
          <source src="Gameplay3.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>
      <div class="video-grid-item" data-aos="fade-up" data-aos-duration="1500" data-aos-delay="1000">
        <video width="100%" height="100%" controls>
          <source src="Gameplay4.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>
      <div class="video-grid-item" data-aos="fade-up" data-aos-duration="1500" data-aos-delay="1100">
        <video width="100%" height="100%" controls>
          <source src="Gameplay5.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>
      <div class="video-grid-item" data-aos="fade-up" data-aos-duration="1500" data-aos-delay="200">
        <video width="100%" height="100%" controls>
          <source src="Gameplay6.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>
      <div class="video-grid-item" data-aos="fade-up" data-aos-duration="1500" data-aos-delay="200">
        <video width="100%" height="100%" controls>
          <source src="Gameplay7.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>
      <div class="video-grid-item" data-aos="fade-up" data-aos-duration="1500" data-aos-delay="200">
        <video width="100%" height="100%" controls>
          <source src="Gamplay8.mp4" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>
    </section>
    <footer>&copy;GhostAce Saint</footer>
    <script src="https://unpkg.com/aos@next/dist/aos.js"></script>
    <script>
      AOS.init({offset:0});
    </script>
    <script src="videos.js"></script>
</body>
</html>
