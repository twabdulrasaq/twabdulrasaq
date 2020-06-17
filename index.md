
<style>


@media only screen and (min-width: 320px){
  *{
    box-sizing : border-box;
  }
  #header{
    position: fixed;
    top: 0;
    height: 100px;
    display: flex;
    width: 100%;
  
  
  
  }
.form{
  font-size: 24px;
  border: 5px solid lightgrey;
  padding: 20px 100px 100px 180px;
  border-radius: 30px;
  width: 60%;
  float: left;
}
  #bo{
    margin-top: 40px;
  }
input{
  padding: 8px 20px;
  margin: 20px;
}
img{
  box-shadow: 10px 10px 10px;
  padding-right: 20px;
}
#main{
  backgroung-color: grey;
}
#what{
  font-size: 24px;
  border: 5px solid black;
  padding: 30px;
  border-radius: 15px;
  width: 70%;
  float: right;
}
#learn{
  font-size: 24px;
  border: 5px solid black;
  padding: 30px;
  border-radius: 15px;
  width: 70%;
  float: left;
}
#nav-bar{
  
  
}
ul{
  list-style-type: none;
  margin-right: 10px;
  display: flex;
}
li{
  display: inline;
  padding: 12px 30px;
  top: 0;
  font-size: 20px;
  background-color: lightgrey;
  border-radius: 5px;
  box-shadow: 10px 10px 10px black;
}
a{
  text-decoration: none;
}
#header{
  background-color: rgb(93,151,74);
  border-radius: 5px;
}
#what,#learn,#about,#vid{
  margin-bottom: 30px;
  margin-top: 30px;
}
#about{
  font-size: 24px;
  border: 5px solid black;
  padding: 30px;
  border-radius: 15px;
  width: 70%;
  float: right;
}
#vid{
  font-size: 24px;
  border: 10px outset grey;
  padding: 30px;
  border-radius: 15px;
  width: 60%;
  float: right;
  margin-right: 25%;
  margin-top: 150px;
}
  
}

</style>



<body>
  <div id="header">
    
    <img src="https://www.tech-tech.co.za/wp-content/uploads/2019/11/01014-ttech-logo-landscape-72dpi-Copy.png" id="header-img">
    
    
    <nav id="nav-bar">
      <ul>
        <li><a class="nav-link" href="#what"> What we do</a></li>
        <li><a class="nav-link" href="#learn">Learn from us</a></li>
        <li><a class="nav-link" href="#about">About</a></li>
      </ul>
    </nav>
    
    </div>
  
  <div id="bod">
  
  <div id="vid">
        <h2>The latest Samsung Galaxy Note20</h2>
        <iframe src="https://www.youtube.com/watch?v=9ydVMhGgL00" controls id="video"></iframe>
      </div>
  
  
    <div id="what">
      <h2 id="what2">What we do</h2>
    <p>
      We offer you the infos on technologies, what, why and for what a particular object is all about. <br>
      <br>
      We assist in making a decision on which to buy in technology by giving you the chance to communicate with us through email. <br>
      <br>
      In this page we show you on which latest technology will make world better, by giving you some photos of it and also a video of it(on how it works, how to operate and more).
    </p>
  </div>
  
  
    <div id="learn">
      <h2 id="learn2">Learn from Us</h2>
    <p>
      Everyone can learn from us by simply following our page. We try all our best to make sure that anyone that come to this page leave with something tangible, by providing them with what they want.
      <br>
      And we also assist in learning by simply require you to send email to us to provide you with a particular topic.
    </p>
  </div>
  
  
    <div id="about">
      <h2>About</h2>
    <p>
      This site is only to civilize people on what is going on especially in the life of technology.
    </p>
    </div>
  
    
  
  <div class="form">
    <h2>Contact Us</h2>
    <form id="form" action="https://www.freecodecamp.com/email-submit">
      <input
        name="email"
        id="email"
        type="email"
        placeholder="Enter your email address"
        required
      />
      <input id="submit" type="submit" value="Get Started" class="btn" />
    </form>
  </div>
  </div>
</body>
