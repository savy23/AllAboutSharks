<head>
    <link href="styles.css" rel="stylesheet">
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AllAboutSharks</title>
    <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/css/bootstrap.min.css" rel="stylesheet" integrity="sha384-GLhlTQ8iRABdZLl6O3oVMWSktQOp6b7In1Zl3/Jr59b6EGGoI1aFkw7cmDA6j6gD" crossorigin="anonymous">
</head>
<body class = "flex-container">
    <nav class="navbar navbar-dark bg-dark fixed-top">
        <div class="container-fluid">
          <a class="navbar-brand"  id = "shark-title">All About Sharks</a>
          <button class="navbar-toggler" type="button" data-bs-toggle="offcanvas" data-bs-target="#offcanvasDarkNavbar" aria-controls="offcanvasDarkNavbar">
            <span class="navbar-toggler-icon"></span>
          </button>
          <div class="offcanvas offcanvas-end text-bg-dark" tabindex="-1" id="offcanvasDarkNavbar" aria-labelledby="offcanvasDarkNavbarLabel">
            <div class="offcanvas-header">
              <h5 class="offcanvas-title" id="offcanvasDarkNavbarLabel">Menu</h5>
              <button type="button" class="btn-close btn-close-white" data-bs-dismiss="offcanvas" aria-label="Close"></button>
            </div>
            <div class="offcanvas-body">
              <ul class="navbar-nav justify-content-end flex-grow-1 pe-3">
                <li class="nav-item">
                  <a class="nav-link active" aria-current="page" href="file:///C:/Users/savan/OneDrive/Desktop/Code/shark-website/assets/index.html">Home</a>
                <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                      Protecting You & Sharks
                    </a>
                    <ul class="dropdown-menu dropdown-menu-dark">
                      <li><a class="dropdown-item" href="https://shark-research.com/blog/conservation/how-to-save-sharks/" target="_blank" >How To Save Sharks</a></li>
                      <li><a class="dropdown-item" href="https://www.australiangeographic.com.au/blogs/shark-blog/2018/11/with-water-we-have-sharks-8-shark-safety-tips/" target="_blank">Water Safety</a></li>
                    </ul>
                  </li>
                  <li class="nav-item dropdown">
                    <a class="nav-link dropdown-toggle" href="#" role="button" data-bs-toggle="dropdown" aria-expanded="false">
                      Information
                    </a>
                    <ul class="dropdown-menu dropdown-menu-dark">
                      <div class="nav">
                        <li><a href="#flex-col-b">Prehistoric Background</a></li>
                        <li><a href="#flex-col-c">Effects on Shark Populations</a></li>
                        <li><a href="#danger">Top 3 Most Dangerous Sharks</a></li>
                      </div>
                    </ul>
                  </li>
              </ul>
            </div>
          </div>
        </div>
      </nav>
 
<main class = "flex-col-2">
    <section class="flex-col-a">
        <div id="carouselExampleCaptions" class="carousel slide">
            <div class="carousel-indicators">
                  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="0" class="active" aria-current="true" aria-label="Slide 1"></button>
                  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="1" aria-label="Slide 2"></button>
                  <button type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide-to="2" aria-label="Slide 3"></button>
                </div>
                <div class="carousel-inner">
                  <div class="carousel-item active">
                    <img src="./images/Tiger-Shark.jpg" class="cover-1">
                    <div class="carousel-caption d-none d-md-block">
                      <h5>Tiger Shark</h5>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <img src="./images/black-tip-reef.jpg" class="cover-2">
                    <div class="carousel-caption d-none d-md-block">
                      <h5>Blacktip Reef Sharks</h5>
                    </div>
                  </div>
                  <div class="carousel-item">
                    <img src="./images/Blue-Shark.jpg" class="cover-3">
                    <div class="carousel-caption d-none d-md-block">
                      <h5>Blue Shark</h5>
                    </div>
                  </div>
                </div>
                <button class="carousel-control-prev" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="prev">
                  <span class="carousel-control-prev-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Previous</span>
                </button>
                <button class="carousel-control-next" type="button" data-bs-target="#carouselExampleCaptions" data-bs-slide="next">
                  <span class="carousel-control-next-icon" aria-hidden="true"></span>
                  <span class="visually-hidden">Next</span>
                </button>
              </div>
        </div>
      </section>
    <section id="flex-col-b">
      <h1>Prehistoric Background</h1>
        <p>
          Sharks are the apex predators of the ocean and have ruled the oceans for over 400 million years. 
          Sharks are from the period of time known as the Paleozoic Era (541-251 million years ago). 
          The first sharks were crazy weird looking, almost like something you would see in a comic book.
          These images are only an estimate of what they really looked like because, we don't have skeletal 
          fossils of sharks like we do of T-Rexes. Instead of skeletons, sharks are made primarily of cartilage. 
          Here is a picture of a shark, and a fossil from a more famous prehistoric shark, the Helicoprion.
    </p>
    <img src="./images/Helicoprion_Fossil.jpg" width="400" height="400">
    <img src="./images/Helicoprion_Drawing.jpg" width="665" height="400">
    </section>
<section id="flex-col-c">
  <h1>Effects on Shark Populations</h1>
    <p>It is no doubt that the health of the ocean is a concern right now especially regarding climate change 
      and the effects it causes. But another problem happening relating closer to sharks is overfishing. 
      Overfishing has caused nearly a 70% decline in sharks and rays since 1970. It is estimated that every year,
      100 million sharks are killed. Most of the sharks being killed are being illegally taken. 
      Among the uses of sharks, shark fins are one of the most used parts of the sharks. 
      Often fishermen will cut off the shark's dorsal fin and throw them back in the water. 
 
      </p>
</section>

<div id="danger">  
<h1>Top 3 Most Dangerous Sharks</h1>
</div>

<div class="section1">
  <div class="text">
    <img src="./images/Great-White.jpg"/>
    <p>
       The great white shark takes 1st place when it comes to dangerous sharks. 
       These sharks can get massive. The largest great white shark ever recorded, named Deep Blue, 
       is 20 feet long and about 4,400 pounds! Average sharks are anywhere from 11-16 feet long and 1,500-2,400
       pounds. Great whites are easy to identify because of their white bellies and gray backs. 
       These sharks occupy water with temperatures around 54-75 degrees fahrenheit, which allows them 
       to be almost anywhere. Great whites primarily prey on seals, sea lions, and sea mammals along those lines. 
       One spooky fact about these beasts is that they can reach up to 35 miles per hour while swimming!

    </div>
  </p>
</div>

<div class="section2">
  <div class="text">
    <img src="./images/Tiger-Shark2.jpg">
    <p>
      The tiger shark takes 2nd place in this competition. These sharks are one of a kind with 
      their tiger-like stripes on their bodies. Shockingly, the largest tiger shark ever recorded was 
      bigger than the largest great at 24.6 feet, but only 1,780 pounds! Depending on the sex of the shark, 
      tigers can be anywhere from 11-14 feet long and 850-1,400 pounds. Almost as long as great whites! 
      Although tigers and whites can be the same length, they definitely don’t weigh the same. Tigers are more 
      diverse in their food options, they feed on crabs, shellfish, squid, bony fish, rays, birds, and even 
      small sharks! Tigers prefer warmer waters, 74 degrees fahrenheit or warmer. 
      In fact, the shark that bit off Bethany Hamilton's arm was a tiger shark!


    </div>
  </p>
</div>
<div class="section3">
  <div class="text">
    <img src="./images/Bull-Shark2.jpg">
    <p>
      Coming in at 3rd place is the bull shark. This shark can be harder to identify because it doesn’t 
      have any super noticeable characteristics, but there is one. Bull sharks have a more bulky build, 
      especially in the head. They are not as sleek looking as other sharks. These are the smallest of these
       three sharks growing to around 7-11 feet and 200-500 pounds. Bull sharks prefer water to be above 79 
       degrees fahrenheit but can tolerate colder water. With a more narrow meal palette these sharks like 
       to eat turtles, birds, fish, marine mammals like small dolphins, and sometimes other bull sharks. 
       These sharks are one of the few sharks that can actually survive in freshwater. Bulls have been spotted as 
       far inland as the Missouri and Mississippi rivers!


    </div>
  </p>
</div>

</main>
<script src="https://cdn.jsdelivr.net/npm/bootstrap@5.3.0-alpha1/dist/js/bootstrap.bundle.min.js" integrity="sha384-w76AqPfDkMBDXo30jS1Sgez6pr3x5MlQ1ZAGC+nuZB+EYdgRZgiwxhTBTkF7CXvN" crossorigin="anonymous"></script>
</body>
<footer>

</footer>
</html>
styles.css

.Top{
    font-size: xxx-large;
}
section {
    border: 20px rgb(209, 209, 225);
    padding: 50px;
    margin: 75px;
    border-radius: 25px;
    background: rgb(192, 192, 212);
    padding: 20px;
  }
  body{
    background-color: gray;
  }
  h1 {text-align: right;}


  #shark-title{
    font-family: Impact, Haettenschweiler, 'Arial Narrow Bold', sans-serif
  }
  #shark-title{
    font-size: x-large;
  }
  .cover-1{
    object-fit: cover;
    width: 1100px;
    margin: 5px;
    height: 600px;
  }
.cover-2{
  object-fit: cover;
  width: 1100px;
  margin: 5px;
  height: 600px;
}
.cover-3{
  object-fit: cover;
  width: 1075px;
  margin: 9px;
  height: 600px;
}
#flex-col-b h1{
text-align: left;
font-size: x-large;
font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
}
#flex-col-b p{
    font-family:'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}

#flex-col-c h1{
  text-align: left;
  font-size: x-large;
  font-family:'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif
}
#flex-col-c p{
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
}
#danger h1{
text-align: center;
font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;
font-size: xx-large;
}
.section1{
  display:flex;
  padding:40px;
  width: 95%;
  margin-bottom:auto;
}
.section1 img{
  width: 200px;
  height: 200px;
  float: left;
  overflow: hidden;
  object-fit: cover;
  border-radius: 50%;
  shape-outside: circle();
}
.section1 p{
  margin-top: 15px;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  text-align: justify;
  line-height: 1.5em;
  font-size: large;
}
.section2{
  display:flex;
  padding:40px;
  width: 95%;
  margin-bottom:auto;
}
.section2 img{
width: 200px;
height: 200px;
float: left;
overflow: hidden;
object-fit: cover;
border-radius: 50%;
shape-outside: circle();
}
.section2 p{
  margin-top: 15px;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  text-align: justify;
  line-height: 1.5em;
  font-size: large;
}
.section3{
  display:flex;
  padding:40px;
  width: 95%;
  margin-bottom:auto;
}
.section3 img{
width: 200px;
height: 200px;
float: left;
overflow: hidden;
object-fit: cover;
border-radius: 50%;
shape-outside: circle();
}
.section3 p{
  margin-top: 15px;
  font-family: 'Gill Sans', 'Gill Sans MT', Calibri, 'Trebuchet MS', sans-serif;
  text-align: justify;
  line-height: 1.5em;
  font-size: large;
}
