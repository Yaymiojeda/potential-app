# potential-app

about

{% extends 'base.html'%}

    {% block content %}
    <1>This is my content</1>
    {% endblock %}
    
    
    
    
    
   home
   
   {% extends 'base.html' %}

{% block content %}
    
b>HOME PAGE!<!DOCTYPE html>
    <html>
        <head>
            <title> Health-ish - Food and life style </title>
             <meta charset="utf-8">
             <meta name="viewport" content="width=device-width, initial-scale=1.0">
   
             <link rel="stylesheet" href="healthish.css"></link>
         </head>
    
    
    
    <!--- hero image-->
    
    <div class="hero-image">
      <div class="hero-text">
        <p><h1  style="font-size:50px" id="tittle">Welcome<b class="ish">Bienvenido</b></h1></p>
    
    
      </div>
    </div>
    
    
    
        <p><h1 id="tittle"> Health<b class="ish">-ish!</b></h1></p>
    
    
    <body>
    
        <h2 class="Nourish">Nourish your soul and body</h2>
    
     <img  id="picture" src="https://media.istockphoto.com/vectors/cute-happy-smiling-banana-and-avocado-vector-id968072700?k=6&m=968072700&s=170667a&w=0&h=2-OBQTgE_reb3FfRt5T-ADTMvRUBV-PzM6gaJXznFoI=" alt="avocado and banana cartoons">
    
    <div id="tab1" class="tabcontent">
      <h3>Recipes</h3>
    
    </div>
    
    <div id="tab2" class="tabcontent">
      <h3>Living</h3>
      <p>Text here</p>
    </div>
    
    <div id="tab3" class="tabcontent">
      <h3>Community</h3>
      <p>Text here</p>
    </div>
    
    <!-- left column start -->
    
      <div class="row">
      <div class="column">
        <div id="P1">  <h3 id="tittle"> Welcome to y First Blog <b class="ish"> Who am I?<b></h3>
    
        <div class="p1color"> <p><b>Hi there,<b/> I am glad you found your way to my first post. Let me introduce myself as the regular girl that would seat next to you on the train, or most realistically, the one standing next to you. I am not a fitness guru or plan to be, and I certainly have no culinary skills or two-digit number hours of YouTube cooking. So we have something in common. I am an everyday person. Before you think that improving your lifestyle is too hard, let me just say that it is possible. I work around 35-40 hours a week while studying full-time and still squish some time to have a Health-ish lifestyle. Even if that means refusing a free donut and getting a banana. In this blog you will learn how finding better alternatives became part of who I am and why I approached a health-ish lifestyle. Next time, I will go deeper on how I went from living with my parents in a small Venezuelan town to leaving everything behind and moving to New York City.. </p>
    
        <p>I am glad you are still here. Getting to this point of my life wasn’t a smooth path. Even enjoying the process of learning about healthier food choices or how to cook wasn’t always on my “to do list”. And if you are here, I hope we can discover together what health-ish! really means. In this precise moment of my life, I would define it as whatever you are content with providing your body as a better alternative of what the market offers you. I hope you aren’t here just because you are my professor grading my site or my aunt trying to get any clue about my romantic life, but you are here to learn how to make some "hella good" pancakes. </p>
    
        <p>Now that we all know what health-ish means, let me also say that this is my safe virtual space where I can be open and brutally honest. It is easy to look at others and compare the way they eat, look, and even live their lives. I wish someone had told me this when I first moved to New York City and was only 19 years old. In the last years - even a couple of months- I experienced multiple body changes. I discovered the importance of taking care of myself from within first. In the beginning, it was a challenge for me to stay away from sweets and candies, as I came from a country with extreme food scarcity. I just couldn’t help myself! It took me some time to enjoy preparing my own meals and creating a delicious version of what I could eat for triple the amount of saturated fats and unnecessary calories. Any habit takes time. I just recently started eating Greek yogurt again because I was somehow reluctant to eat it as my very first in America was at a frozen yogurt store. I was making pennies and to save up some money I would sample the froyo (frozen yogurt as some hipsters may call say) to the point that samples would become my meal. If I had to go to school, I would buy a coffee and a bagel or some pastry for $2. However, this eating pattern was paid with my health, stamina, and self-esteem. I gained weight and no longer fitted on my clothes. I didn’t have enough energy to walk up the stairs on the train station, and most important: I was not content.</p> 
    
        <p>You should feel content, nourished, and grateful you have so many food choices and a creative mind -or internet- to create delicious meals. I hope we can create a community where being ourselves is the only way to be.</p></div>
    
      <div id="p2">
    
      <p> Insert cliché phrase: Let's be health-ish together! </p>
    </div>
    
    
    
    <!-- Email form -->
    <h3 id="email">Let's get in touch!</h3>
    
    <div class="emailform">
      <form action="MAILTO:yaymiojed@gmail.com" method="post" enctype="text/plain" /action_page.php">  <!--I could'nt to learn how to use php --> 
        <label id="name" for="fname">First Name</label>
        <input type="text" id="fname" name="firstname" placeholder="Your name..">
    
        <label id="lastname" for="lname">Last Name</label>
        <input type="text" id="lname" name="lastname" placeholder="Your last name..">
    
        <label id="country" for="country">Country</label>
        <select id="country" name="country">
        <option value="Argentina">Argentina</option>
          <option value="australia">Australia</option>
          <option value="canada">Canada</option>    
          <option value="Colombia">Colombia</option>
          <option value="Chile">Chile</option>
          <option value="Peru">Peru</option>
           <option value="usa">USA</option>
          <option value="Venezuela">Venezuela</option>
          <option value="Other">Other</option>
        </select>
    
        <label id="subject" for="subject">What is on your mind?</label>
        <textarea id="subject" name="subject" placeholder="Write something.." style="height:200px"></textarea>
    
        <input type="submit" value="Send">
      </form>
    </div>
    
    
      </div>
    </div>
    
    <!-- Right paragraph starts here -->
    
    
      <div class="column">
     <div>
       <p> 
    
      <a id="IG" href=https://www.instagram.com/yaymiv/ target="_blank">
      <img src="http://pluspng.com/img-png/instagram-png-instagram-logo-2-png-8-de-abril-de-2017-927-kb-3500-3393-3500.png" alt="instagram Logo" target:"_blank" style="width:42px;height:42px;border:0"> 
    
    
    
    
    
       <a href=https://twitter.com/Yaymiojeda target="_blank">
      <img id="twitter" src="https://logos-download.com/wp-content/uploads/2016/02/Twitter_Logo_new-700x569.png" alt="instagram Logo" style="width:42px;height:42px;border:0" ></a> 
    
      <a href=mailto:yaymiojed@gmail.com target="_blank">
      <img id="gmail" src="https://upload.wikimedia.org/wikipedia/commons/4/4e/Gmail_Icon.png" style="width:42px;height:42px;border:0" ></a>
    
    
      </p> 
    
    <div id="parrafo2">
        <img id="picture2" src="https://github.com/Yaymiojeda/Yaymiojeda.github.io/blob/master/Yaymi%20central%20park.jpg?raw=true" alt=" Oops! You are having trouble downloading the picture of Yaymi in Central Park">
    
    
        <p id="recipe1"> Talking about food... I received text message from a friend asking what banana bread recipe she should make and my gut response is to direct her to google, until I realized that Googling "best banana bread recipe" will still yield over 4 million loaves claiming to be just that. I will not call my banana bread "the best" as there are too many recipes already claiming that title. I will call it the health-ishest. This is one of the easiest, quickiest, and mess-free recipes you will find. Remember to share it with people you appreciate and make it your own.
    
        </p>
    <h3 class="version"> Banana Cake Health-ish Version!</h3>
    
    <h4 class="version">10 servings, 256 calories each.</h4>
    
    <h4> <a href="https://www.instagram.com/p/B2E1YQJBBKrOQqp8AM7LNXKh0Bf3HCVhHrY7900/" target="_blank"> You can also visit the original post  </a></h4>
    
    
     <img id="image_banana_bread" src="https://github.com/Yaymiojeda/Yaymiojeda.github.io/blob/master/Bananabread.JPG?raw=true"  alt="Banana bread image"> 
    
    <div class="pink"> Macros </div>
    
    <ul>
    <li>Carbs 19.8 g</li>
    <li>Fats 15.60 g</li>
    <li>Protein 12.70 g</li>
    
    </ul> 
    
    <p> <b class="pink">Ingredients<b> </b> </p>
    
    <ul>
    
    <li> cup almond flour</li>
    <li>1 cup oat flour</li>
    <li>3 bananas </li>
    <li>2 cups of egg whites</li>
    <li>1 scoop of vanilla whey protein </li>
    <li> 1/2 cup walnuts </li>
    <li>3 tbsp peanut butter</li>
    <li>1 tsp Salt *2 tbsp of vanilla </li>
    <li>lots of cinnamon (about 2 tbsp )</li>
    <li>1 tsp baking powder</li>
    <li>1 tsp baking soda</li>
    <li> 2.5 tbsp of love (skip this ingredient if this recipe will be shared with an ex)</li>
    
    </ul>
    
    <p class="pink"> Preparation</p>
    <p> <font color="black"> First mix all the dry ingredients and then add 1/2 cup of water to the mix. Let the mix sit for about 10 minutes and bake the cake for 35 minutes at 380 degrees </font></p>
    
    </p>
      </div>
       </div>
        </div>
    
      <div class="column">
    
        <p id="thankyou"> Thank you for visiting!</p>
      </div>
    </div>
    
    </body>

    {% endblock %}
    </html>
    
    
    base
    
    <html>
<head>

<link rel="stylesheet" href={{ url_for('static', filename='healthish.css')}} />
</head>


<nav class="navbar navbar-expand-lg navbar-light bg-light">
    <a class="navbar-brand" href="#">Navbar</a>
    <button class="navbar-toggler" type="button" data-toggle="collapse" data-target="#navbarNav" aria-controls="navbarNav" aria-expanded="false" aria-label="Toggle navigation">
      <span class="navbar-toggler-icon"></span>
    </button>
    <div class="collapse navbar-collapse" id="navbarNav">
      <ul class="navbar-nav">
        <li class="nav-item active">
        <a class="nav-link" href="/">Home <span class="sr-only">(current)</span></a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/about">Recipeeeees</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="/base">base</a>
        </li>
        <li class="nav-item">
            <a class="nav-link" href="/community">Community</a>
          </li>
      </ul>
    </div>
  </nav>
<body>
    {% block content %}
    {% endblock %}
    <p>this is from another file</p>
    <script src="https://code.jquery.com/jquery-3.5.1.slim.min.js" integrity="sha384-DfXdz2htPH0lsSSs5nCTpuj/zy4C+OGpamoFVy38MVBnE+IbbVYUew+OrCXaRkfj" crossorigin="anonymous"></script>
    <script src="https://cdn.jsdelivr.net/npm/bootstrap@4.5.3/dist/js/bootstrap.bundle.min.js" integrity="sha384-ho+j7jyWK8fNQe+A12Hb8AhRq26LrZ/JpcUGGOn+Y7RsweNrtN/tE3MoK7ZeZDyx" crossorigin="anonymous"></script>
    


</body>
</html>

healthish.css

emailform {
    border-radius: 5px;
    background-color: #f2f2f2;
    padding: 20px;
  }
  
  #name { color: #ff00ff;
          font-family: 'Bree Serif', serif;
  }
  #lastname { color: #ff00ff;
          font-family: 'Bree Serif', serif;
  }
  #subject { color: #ff00ff;
          font-family: 'Bree Serif', serif;
  }
  #country { color: #ff00ff;
          font-family: 'Bree Serif', serif;
  }
  
  
  #recipe1 {
    color: black;
    font-family: 'Titillium Web';
    text-align: justify;
  }
  
  #image_banana_bread {
  float: center;
  margin-left: auto;
    margin-right: auto;
          border: 1px solid #ddd;
          border-radius: 4px;
          padding: 5px;
    width: 100%;
  
  }
  
  li { color: black }
  
  .pink { color: #fc036b;
           }
  
  .version {
    color: black;
    font-family: 'Titillium Web';
    text-align: center;
  }
  
  #thankyou {color: black;
    font-family: 'Titillium Web';
    text-align: right;}
  
  
    /* Hero image*/
  
  body, html {
    height: 100%;
    margin: 0;
    font-family: Arial, Helvetica, sans-serif;
  }
  .hero-image {
    background-image: linear-gradient(rgba(0, 0, 0, 0.5), rgba(0, 0, 0, 0.5)), url(https://github.com/Yaymiojeda/Yaymiojeda.github.io/blob/master/spinachpeanutbutterpancakes.jpg?raw=true);
  height: 50%;
    background-position: center;
    background-repeat: no-repeat;
    background-size: cover;
    position: relative;}
  
  .hero-text {
    text-align: center;
    position: absolute;
    top: 50%;
    left: 50%;
    transform: translate(-50%, -50%);
    color: white;
  }
  


