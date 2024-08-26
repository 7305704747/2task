<html>
<title>PORTFOLIO</title>
<style>
body
{


}
 


.head
{   background-color:AntiqueWhite;
    margin:10px;
    padding:5px 8px;
    border:1px;
   display: flex;

}
.hero {
     
       
    display: flex;

    justify-content: space-between;

    font-family:"Lucida Console","Courier New",monospace;
    font-style:italic;
    background-color:Bisque;
    color:Black;
    margin:12px;
    border:10px;
    padding:10px 20px 30px 40px;
    width:100%;
    border-radius:5px;
  }

  
  .b {
      
     width: 50%;
  height: 150px;
    
       background-color: smoke;
  
    border: 1px solid #000;
 
    background-color:CadetBlue;
     color:Black;
    margin:15px; 
    border-radius:20px; 
     font-family:"Lucida Console","Courier New",monospace;
    font-style:italic; 
   flex-display:inline;  
}

 .container {
      display: flex;

                   
      justify-content: space-around;
    border-radius:10px;
     
  
    margin:10px;     }

  
  .box1 {
      

   //width:100px ;

      height: 50px;
    
  background-color: Lavender;
  justify-content: space-around;
     
  margin:10px;
        
  
    border: 1px solid #000;

border-radius:1px;
flex-display:inline;  }
.box {
      

   width: 50%;
      height: 100px;
    
  background-color: Lavender;
  justify-content: space-around;
     
 margin:10px; 
padding:10px;
  
    border: 1px solid #000;

border-radius:1px;
flex-display:inline-block;  }

</style>
<body style="background-color:LightGray">
<div class="head">
<h4>AKSHAYA SHRI</h4>
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp&nbsp
<nav>
<a href="#about">About</a> |
<a href="#skills">Skills</a> |
<a href="#myworks">Myworks</a> |
<a href="#contact">Contact</a>
</nav>
</div>
 

<div class="hero">
<div class="b">
<center>
<h1 style="font-size:50px"><strong>AKSHAYA SHRI</strong></h1>
</center>
</div>

<section id=about>
<div class="b">
<h4>Hi! I'm Akshaya shri,a student at Queen Mary's College(A) pursuing a degree in Computer Application.
I have keen interest in Web development and am currently focusing on Full-Stack Development.
Through my coursework and hands-on project,I've developed skills in Front-end Development and
I'm passionate about Web development.</h4>
</div>

</div>
</section>
<br>
<section id=skils>
<div>
<div class="container">
    
<div class="box"><b>skills</b><br>
web devolopment:HTML,CSS,JS<br>
Database management:Mysql<br>
Server side programming:PHP</div>
    
<div class="box"><b>hobbies</b><br>
Cooking<br>
Gardening<br>
Web designing</div>

<div class="box"><b>Volunteer Experience</b><br>
NSS volunteer,<br>
Queen Mary's College,<br>
August-2022-Present
</div>
 
</section>
</div>

<br>
<section id=myworks>
<div>
<h3>My Works</h3>
<br> <h4>my project is aim to address gardening Excellence.Growkit Provisions providing the gardening setups with the customers Exceptions </h4><br>
&nbsp&nbsp&nbsp&nbsp&nbsp<img src="sc.png" width="600px"      height="250px">
&nbsp&nbsp&nbsp&nbsp&nbsp<img src="sc1.jpg" width="600px"      height="250px">

 </div>

</section> 
<div class="box1"><b>Declaration</b><br>
I have declare that the above information given by me is true to best of my Knowledge.</div>

</div>

<section id=contact>
<footer>
  

<style>
contact-form {
    font-family: Arial, sans-serif;

    background-color: #36454f;
  
     margin: 0;

    padding: 0;
 
   display: flex;
   
   flex-direction: column;
    
  min-height: 50vh;

}



footer {
    background-color:#36454f;
    color: #fff;

    padding: 20px;
 
    text-align: center;
}


.contact-form 
  {
    background-color: #fff;
    
     color: #000;
  
     padding: 20px;

    border-radius: 8px;
  
  box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
  
  max-width: 800px;
 
   margin: 0 auto;

}


.contact-form h2 
{
    margin-top: 0;
    
color: #333;
}


.contact-form p {
    color: #555;
}


.contact-form form 
{
    display: flex;

    flex-direction: column;
}


.contact-form label
 {
    text-align: left;
    margin-top: 10px;

}


.contact-form input,
.contact-form textarea
 {
    padding: 10px;
   
 margin-top: 5px;
    
margin-bottom: 10px;
    
border: 1px solid #ccc;

    border-radius: 4px;
 
   width: 100%;
}


.contact-form button {
    
padding: 10px;
    margin-top: 10px;

    border: none;
   
 border-radius: 4px;
 
   background-color: #333;
 
   color: #fff;

    cursor: pointer;
    
width: 100%;
}


.contact-form button[type="button"] 
{
    background-color: #666;
}



.contact-form button:hover 
{
    background-color: #555;
}
</style>
      <div class="contact-form">
            <h2>Reach Out!</h2>
            
<form id="contactForm">
                
<label for="name">Name</label>

                
<input type="text" id="name" name="name"  required>

  
              <label for="email">Email Address</label>
                
<input type="email" id="email" name="email"  required>

 
               <label for="message">Message</label>
               
 <textarea id="message" name="message" placeholder="What is the issue?" required></textarea>


                <button type="submit">Submit</button>
                            </form>
           
         </div>
    

    <script>
document.getElementById('contactForm').addEventListener('submit', function(event) 
{
    event.preventDefault(); 
    const name = document.getElementById('name').value;
    
    const email = document.getElementById('email').value;
   
     const message = document.getElementById('message').value;

    
   
     //alert("Thank you, Your message has been received.");
 
  if (name&&email&&message) 
{
 
          alert('Thank you, Your message has been received.');
               
       
 document.getElementById('contactForm').reset();  } 
       else {
        alert('Please fill in all fields.');
  
  }
       
    
});</script></footer></section>

<body>
</html>
