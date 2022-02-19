<!DOCTYPE html>
<html>
<head>
<style>
* {
  box-sizing: border-box;
}

body {
  font-family: Arial;
  padding: 10px;
  background: #f1f1f1;
}

/* Header/Blog Title */
.header {
  padding: 30px;
  text-align: top left;
  background: white;
}

.header h1 {
  font-size: 50px;

}

/* Style the top navigation bar */
.topnav {
  overflow: hidden;
  background-color: #333;
}

/* Style the topnav links */
.topnav a {
  float: left;
  display: block;
  color: #f2f2f2;
  text-align: center;
  padding: 14px 16px;
  text-decoration: none;
}

/* Change color on hover */
.topnav a:hover {
  background-color: #ddd;
  color: black;
}

/* Create two unequal columns that floats next to each other */
/* Left column */
.leftcolumn {   
  float: left;
  width: 75%;
}

/* Right column */
.rightcolumn {
  float: left;
  width: 25%;
  background-color: #f1f1f1;
  padding-left: 20px;
}

/*image */
.fakeimg {
  width: 100%;
  padding: 20px;
}

.fakeimg a:link, a:visited {
  background-color: #333;
  color: white;
  padding: 15px 70px;
  text-align: center;
  text-decoration: none;
  display: inline-block;

}

a:hover, a:active {
  background-color: #ddd;
}

.fakeimg1 {
  background-image: url("chatbot2.png");
  width: 55%;
  padding: 20px;
    background-repeat: no-repeat;
background-size: 100% 100%;
}

.fakeimg2 {
  background-image: url("chat-bot1.jpg");
  width: 55%;
  padding: 20px;
    background-repeat: no-repeat;
background-size: 100% 100%;
}

.fakeimg3 {
  background-image: url("covidbot.jpg");
  width: 55%;
  padding: 20px;
    background-repeat: no-repeat;
background-size: 100% 100%;
}
/* Add a card effect for articles */
.card {
  background-color: white;
  padding: 20px;
  margin-top: 20px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Footer */
.footer {
  padding: 20px;
  background-color: #333;
  margin-top: 20px;
}

/* Responsive layout - when the screen is less than 800px wide, make the two columns stack on top of each other instead of next to each other */
@media screen and (max-width: 800px) {
  .leftcolumn, .rightcolumn {   
    width: 100%;
    padding: 0;
  }
}

/* Responsive layout - when the screen is less than 400px wide, make the navigation links stack on top of each other instead of next to each other */
@media screen and (max-width: 400px) {
  .topnav a {
    float: none;
    width: 100%;
  }
}
</style>
</head>
<body>

<div class="header">
  </p>
  <div class="fakeimg3" style="height:400px; width:1425px; opacity: o.5;"><h1>My Covid<br>Chatbot</h1>
  </div>

</div>

<div class="topnav">
  <a href="https://www.who.int/" target="_blank">WHO</a>
  <a href="https://www.cdc.gov/" target="_blank">CDC</a>
  <a href="https://www.mohfw.gov.in/" target="_blank">MOHFW</a>
  <a href="https://www.cowin.gov.in/" target="_blank" style="float:right">COWIN</a>
</div>

<div class="row">
  <div class="leftcolumn">
    <div class="card">
      <h2>Chatbot In Healthcare-Industry</h2>
      <div class="fakeimg1" style="height:500px; width:1030px;"></div>
      <p>During the novel coronavirus (COVID-19) pandemic, institutions like the Centers for Disease Control and Prevention (CDC) and the World Health Organization (WHO) have begun utilizing chatbots to share information, suggest behavior, and offer emotional support. The CDC has named theirs “Clara”. Chatbots are software programs that talk with people through voice or text in their natural language. Some well-known examples include “Alexa” from Amazon, “Siri” from Apple, and “Cortana” from Microsoft. They often come pre-installed on smartphones or home-based smart speakers. In recent years, chatbot use for health-related purposes has increased considerably, from supporting clinicians with clinical interviews and diagnosis to aiding consumers in self-managing chronic conditions. While promising, the use of chatbots may pose safety risks.</p>
    </div>

    <div class="card">
      <h2>Chatbots in the fight against the COVID-19 pandemic</h2>
      <div class="fakeimg2" style="height:500px; width:1030px;"></div>
      <p>Chatbots have been a great help – especially healthcare in this critical time – to help spread information about the coronavirus, and also assist with customer queries.The chatbot offers a wide range of information about the pandemic in a conversational and easy-to-understand manner. The information includes symptoms, how infection is transmitted, preventive measures, health and travel advisories, and official government helplines for further assistance.chatbots also help us to prevent misinformation, aid in symptom detection, engender infection-limiting behaviors, and lessen the mental health burden of pandemic response. In a pandemic, no group of people remains unaffected for long. </p>
    </div>
  </div>

  <div class="rightcolumn">
    <div class="card">
     <section id="section4">
      <h3>About Me</h3>
        <p>My name is <b>Prashant Shinde</b> and this is my internship project.In this project i have created covid chat-bot using microsoft azure.This chat-bot can help us to prevent misinformation, aid in symptom detection, engender infection-limiting behaviors, and lessen the mental health burden of pandemic response.</p>
      </section>
    </div>

    <div class="card">
      <section id="section3">
      <h3>Popular Post</h3>
      <div class="fakeimg"><a href="https://www.nature.com/articles/s41746-020-0280-0" target="_blank">Click To See Post.</a></div>
      <div class="fakeimg"><a href="https://www.ncbi.nlm.nih.gov/pmc/articles/PMC7879453/" target="_blank">Click To See Post.</a></div>
      <div class="fakeimg"><a href="https://catalyst.nejm.org/doi/full/10.1056/CAT.20.0230" target="_blank">Click To See Post.</a></div>
    </section>
    </div>

    <div class="card">
     <div class="Follow"> 
      <section id="section2">
      <h3>Follow Me</h3>
      <center>
       <a href="https://github.com/prashant867/Covid-HealthCare-ChatBot" target="_blank">
        <img src="github.jpg"  style="width:90px;height:80px;  "></a>
      </center>
      </section>
     </div>
    </div>
    
    <div class="card">
      <section id="section1">
     <iframe src='https://webchat.botframework.com/embed/covidhealthcarechatbot-bot?s=_YSoARvl4ME.gngJOs9pFkNj0hncxW29uUUZN5gR-pJ-YGpOkQrGW4U'  style='height: 500px; width: 300px;'></iframe>
      <p><span style='font-size:50px;'>&#9757;</span>
Ask about covid-19.</p>
    </div>
      </section>
  </div>
</div>

<div class="footer">
<footer>
<section>
<a href="#section1" style="padding: 15px 70px;">Chat with bot</a>
<a href="#section2" style="padding: 15px 70px;">Follow Me</a>
<a href="#section3" style="padding: 15px 70px;">Popular Posts</a>
<a href="#section4" style="padding: 15px 70px;">About Me</a>
<a href="maileto:prashantshinde12575@gmail.com" style="float:right; ">Contact Me <br>prashantshinde12575@gmail.com</a>

</section>
</footer>
</div>

</body>
</html>
 
