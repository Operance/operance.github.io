<div class = "navbar">
  <a href = "/"> Home </a>
  <a href = "/about"> About Me </a>
  <a href = "/projects"> Projects </a>
</div>
   
   <h2 id="skills">Projects</h2>

   <div class="accordion">
     <div class="accordion-header">
        <div class="accordion-title">Projects</div>
        <span class="accordion-icon">◀</span>
      </div>
      <div class="accordion-content">
        <ul>
          <li><a href="/credbot">Discord Bot (Cred Bot)(Python)(In Progress)</a></li>
          <li><a href="/game">Unity Game (Browser Game)(C#)(In Progress)</a></li>
          <li><a href="/calculator.html">Basic Web Calculator (JavaScript)</a></li>
          <li><a href="https://operance-react-js-calculator.netlify.app/">React JS Basic Web Calculator (JavaScript)</a></li>
          <li><a href="https://replit.com/@operance/Playing-around-with-C#main.cpp">Basic CM/MM to Inches Converter (C++)</a></li>
          <li><a href="https://github.com/Operance/NPL/tree/master/Project%20NPL/Assets/Scripts">Former Unity Game Project (JavaScript)</a></li>
          <li>Packet Manipulation Tool using Scapy (Python)(In-Progress)</li>
          <li><a href="/mvc_project">Star Citizen Ship Database MVC Core App (C#)(In-Progress)</a></li>
          <li>ETH TX Hash to CSV tool(Python)(In-Progress)</li>
        </ul>
      </div>
    </div>
    
<style>
 .navbar{
  overflow: hidden;
  position: absolute;
  width: 100%;
  height: 6%;
  top: 0px;
  left: 0px;
  box-shadow: 0px 0px 8px 2px #000000;
  background-color: #155799;
  background-image: linear-gradient(120deg, #155799, #159957);
 }
  
.navbar a {
  float: left;
  font-size: 16px;
  color: #ffffff;
  text-decoration: none;
  text-align: center;
  padding: 16px 20px;
 }
 
 .navbar a:hover{
  background-color: #0c97b0;
  height: 100%;
  }
  .accordion {
  border: 2px solid #dce6f0;
  border-radius: 10px;
  margin: 5px 0;
}
.accordion-header {
  display: flex;
  padding: 16px;
  cursor: pointer;
  border-radius: 10px;
  background-color: #f3f6fa;
}
.accordion-title {
  flex: 1;
}
.accordion-icon {
  width: 16px;
  font-family: arial;
}
.accordion-content {
  padding: 16px;
  border-radius: 10px;
}
.accordion-content {
  display: none;
}
.accordion-header:hover {
  background-color: rgba(0, 0, 0, 0.1);
}
</style>
   
<script>

  const accordionHeaders = document.getElementsByClassName('accordion-header');
  const accordionContents = document.getElementsByClassName('accordion-content');
  const accordionIcons = document.getElementsByClassName('accordion-icon');


  for (let i = 0; i < accordionHeaders.length; i++) {
    accordionHeaders[i].addEventListener('click', () => {
      accordionContents[i].style.display = accordionContents[i].style.display == 'block' ? 'none' : 'block';
      accordionIcons[i].innerHTML = accordionContents[i].style.display == 'block' ? '▼' : '◀';
    });
  }
  
</script>
