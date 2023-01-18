1- I am curious about this project because I am interested in creating websites. It feels like this is the only thing I'm good at, so I want to make use of it (or try to, at least).

2- So far, I have learned how to use Bootstrap 5, I have improved on my Javascript coding and learned more about HTML and CSS. With boostrap, I learned how to create working buttons, pop-ups, linking between different websites and making profile tables.

3- Some problems I've faced were the code not working due to misspelling, not putting semi colon at the end of every piece of code while using CSS, bootstrap code messing the HTML code.

4- The next steps I need to take are at least I should design my website with some text and make it about something, because I haven't even decided what to write yet.

5- The code is mine because I decorated the design myself with CSS, used various bootstrap functions, and HTML. I have included different popovers, a profile card, hyperlinks and buttons.

6-Using data-bs, I made popovers and by using basic CSS commands I decorated the webapp, while making sure these all work with Javascript and HTML.

7- I learned how to use Bootstrap 5, JavaScript and I have improved on HTML and CSS. With these, I have learned how to create buttons, popovers, adding hyperlinks, web design, profile cards, tables, adding links on tables, many new commands I can use in the future.

CODE 1

<!DOCTYPE html>
<html lang="en">
<head>
    
    <script type="text/javascript" src="script.js"></script>  
 
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>
    
<div class="container mt-3">
  <h3>My Project</h3>
  
  <button type="button" class="btn btn-primary" data-bs-toggle="popover" title="Webapp" data-bs-content="I tried to create a fully functional webapp for my programming project and this is how it turned out.">
    Webapp Project
  </button>
</div>

<script>
var popoverTriggerList = [].slice.call(document.querySelectorAll('[data-bs-toggle="popover"]'))
var popoverList = popoverTriggerList.map(function (popoverTriggerEl) {
  return new bootstrap.Popover(popoverTriggerEl)
})
</script>

</body>
</html>


<head>
  <title>Can's Webapp</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    
 

    
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Sriracha&display=swap');

    body {
      margin: 0;
      box-sizing: border-box;
    }

    
    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #f5f5f5;
    }

    .header .logo {
      font-size: 25px;
      font-family: 'Sriracha', cursive;
      color: #000;
      text-decoration: none;
      margin-left: 30px;
    }

    .nav-items {
      display: flex;
      justify-content: space-around;
      align-items: center;
      background-color: #f5f5f5;
      margin-right: 20px;
    }

    .nav-items a {
      text-decoration: none;
      color: #000;
      padding: 35px 20px;
    }

   
    .intro {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      width: 100%;
      height: 520px;
      background: linear-gradient(to bottom, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.5) 100%), url("https://th.bing.com/th/id/R.899a27ffced69e2acad576095c6706a7?rik=jFQHxQ5EHcJu4A&pid=ImgRaw&r=0&sres=1&sresct=1");
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
    }

    .intro h1 {
      font-family: sans-serif;
      font-size: 60px;
      color: #fff;
      font-weight: bold;
      text-transform: uppercase;
      margin: 0;
    }

    .intro p {
      font-size: 20px;
      color: #d1d1d1;
      text-transform: uppercase;
      margin: 20px 0;
    }

    .intro button {
      background-color: #5edaf0;
      color: #000;
      padding: 10px 25px;
      border: none;
      border-radius: 5px;
      font-size: 20px;
      font-weight: bold;
      cursor: pointer;
      box-shadow: 0px 0px 20px rgba(255, 255, 255, 0.4)
    }

    .achievements {
      display: flex;
      justify-content: space-around;
      align-items: center;
      padding: 40px 80px;
    }

    .achievements .work {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 0 40px;
    }

    .achievements .work i {
      width: fit-content;
      font-size: 50px;
      color: #333333;
      border-radius: 50%;
      border: 2px solid #333333;
      padding: 12px;
    }

    .achievements .work .work-heading {
      font-size: 20px;
      color: #333333;
      text-transform: uppercase;
      margin: 10px 0;
    }

    .achievements .work .work-text {
      font-size: 15px;
      color: #585858;
      margin: 10px 0;
    }

    .about-me {
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 40px 80px;
      border-top: 2px solid #eeeeee;
    }

    .about-me img {
      width: 500px;
      max-width: 100%;
      height: auto;
      border-radius: 10px;
    }

    .about-me-text h2 {
      font-size: 30px;
      color: #333333;
      text-transform: uppercase;
      margin: 0;
    }

    .about-me-text p {
      font-size: 15px;
      color: #585858;
      margin: 10px 0;
    }

    
    .footer {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #302f49;
      padding: 40px 80px;
    }

    .footer .copy {
      color: #fff;
    }

      
  </style>
</head>

<body>
  <header class="header">
    
    <nav class="nav-items">
     
    </nav>
  </header>
  <main>
    <div class="intro">
      <h1>Can's Webapp</h1>
      <p>Hi</p>
        <button onclick="document.location='file:///C:/Users/132-ckumustekin/Desktop/my%20page/indexx.html'">Links</button>
        
        
    </div>
    <div class="achievements">
      <div class="work">
        <i class="fas fa-skiing"></i>
        <p class="work-heading">Hobbies</p>
          <p class="work-text">I like playing ping pong, basketball and soccer. I also love playing video games and reading.</p>
      </div>
      <div class="work">
        <i class="fas fa-eraser"></i>
        <p class="work-heading">Skills</p>
        <p class="work-text">I am good at pre-calculus and chemistry.</p>
      </div>
      <div class="work">
        <i class="fas fa-atom"></i>
        <p class="work-heading">Food</p>
          <p class="work-text"> I love sushi.</p>
      </div>
    </div>
      
  
          
    <div class="about-me">
      <div class="about-me-text">
        <h2>About Me</h2>
        <p>My name is Can, I am 16 years old and a student at Riverside Secondary. </p>
      </div>
      <img src="https://th.bing.com/th/id/R.36a221ec18dde3604340ecf7df1a6685?rik=yZJGA9%2f43S6fGw&riu=http%3a%2f%2fmyriverside.sd43.bc.ca%2ffiles%2f2013%2f10%2fRiversidelogo-13f1jxv.png&ehk=ciEuRIq41xgg0SMvjitu%2b8kh%2foOLRR43rfWKxt3pdnA%3d&risl=&pid=ImgRaw&r=0&sres=1&sresct=1" alt="me">
    </div>
  </main>

  CODE 2
  
  <!DOCTYPE html>
<html lang="en">
<head>
    
    <script type="text/javascript" src="script.js"></script>  
 
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <link href="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/css/bootstrap.min.css" rel="stylesheet">
  <script src="https://cdn.jsdelivr.net/npm/bootstrap@5.2.3/dist/js/bootstrap.bundle.min.js"></script>
</head>
<body>

<div class="container mt-3">
 
</div>



</body>
</html>


<head>
  <title>Links</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.3/css/all.min.css">
    
    <button onclick="document.location='file:///C:/Users/132-ckumustekin/Desktop/my%20page/index.html'">Home</button>
    
 

    
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Sriracha&display=swap');

    body {
      margin: 0;
      box-sizing: border-box;
    }

    
    .header {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #f5f5f5;
    }

    .header .logo {
      font-size: 25px;
      font-family: 'Sriracha', cursive;
      color: #000;
      text-decoration: none;
      margin-left: 30px;
    }

    .nav-items {
      display: flex;
      justify-content: space-around;
      align-items: center;
      background-color: #f5f5f5;
      margin-right: 20px;
    }

    .nav-items a {
      text-decoration: none;
      color: #000;
      padding: 35px 20px;
    }

   
    .intro {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      width: 100%;
      height: 520px;
      background: linear-gradient(to bottom, rgba(0, 0, 0, 0.5) 0%, rgba(0, 0, 0, 0.5) 100%), url("https://th.bing.com/th/id/OIP.xJHPnD2i-lI9uIDvZ2ov5wHaE7?pid=ImgDet&rs=1");
      background-size: cover;
      background-position: center;
      background-repeat: no-repeat;
    }

    .intro h1 {
      font-family: sans-serif;
      font-size: 60px;
      color: #fff;
      font-weight: bold;
      text-transform: uppercase;
      margin: 0;
    }

    .intro p {
      font-size: 20px;
      color: #d1d1d1;
      text-transform: uppercase;
      margin: 20px 0;
    }

    .intro button {
      background-color: #5edaf0;
      color: #000;
      padding: 10px 25px;
      border: none;
      border-radius: 5px;
      font-size: 20px;
      font-weight: bold;
      cursor: pointer;
      box-shadow: 0px 0px 20px rgba(255, 255, 255, 0.4)
    }

    .achievements {
      display: flex;
      justify-content: space-around;
      align-items: center;
      padding: 40px 80px;
    }

    .achievements .work {
      display: flex;
      flex-direction: column;
      justify-content: center;
      align-items: center;
      padding: 0 40px;
    }

    .achievements .work i {
      width: fit-content;
      font-size: 50px;
      color: #333333;
      border-radius: 50%;
      border: 2px solid #333333;
      padding: 12px;
    }

    .achievements .work .work-heading {
      font-size: 20px;
      color: #333333;
      text-transform: uppercase;
      margin: 10px 0;
    }

    .achievements .work .work-text {
      font-size: 15px;
      color: #585858;
      margin: 10px 0;
    }

    .about-me {
      display: flex;
      justify-content: center;
      align-items: center;
      padding: 40px 80px;
      border-top: 2px solid #eeeeee;
    }

    .about-me img {
      width: 500px;
      max-width: 100%;
      height: auto;
      border-radius: 10px;
    }

    .about-me-text h2 {
      font-size: 30px;
      color: #333333;
      text-transform: uppercase;
      margin: 0;
    }

    .about-me-text p {
      font-size: 15px;
      color: #585858;
      margin: 10px 0;
    }

    
    .footer {
      display: flex;
      justify-content: space-between;
      align-items: center;
      background-color: #302f49;
      margin: 40px 80px;
    }

    .footer .copy {
      color: #fff;
    }
      
    .card-body1 {
        margin-right: 500px:
      }

      
  </style>
</head>

<body>
  <header class="header">
    
    <nav class="nav-items">
     
    </nav>
  </header>
  <main>
    <div class="intro">
      
        <div class="container mt-3">


  </div>
  <br>
            
            <div class="container mt-3">


  <div id="accordion">
    <div class="card">
      <div class="card-header">
        <a class="btn" data-bs-toggle="collapse" href="#collapseOne">
          Instagram
        </a>
      </div>
      <div id="collapseOne" class="collapse show" data-bs-parent="#accordion">
        <div class="card-body">
          <a href="https://www.instagram.com/invites/contact/?i=1mbi3uskpkhkq&utm_content=1zikbqs">Instagram</a>
        </div>
      </div>
    </div>
    <div class="card">
      <div class="card-header">
        <a class="collapsed btn" data-bs-toggle="collapse" href="#collapseTwo">
        Discord
      </a>
      </div>
      <div id="collapseTwo" class="collapse" data-bs-parent="#accordion">
        <div class="card-body">
          misou #0001
        </div>
      </div>
    </div>
    <div class="card">
      <div class="card-header">
        <a class="collapsed btn" data-bs-toggle="collapse" href="#collapseThree">
          Reddit
        </a>
      </div>
      <div id="collapseThree" class="collapse" data-bs-parent="#accordion">
        <div class="card-body">
          <a href="https://www.reddit.com/user/WaffleLover354">Reddit</a>
        </div>
      </div>
    </div>
  </div>
</div>
  
