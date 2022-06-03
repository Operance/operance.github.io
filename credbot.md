<div class = "navbar">
  <a href = "/"> Home </a>
  <a href = "/about"> About Me </a>
  <a href = "/projects"> Projects </a>
</div>


<h2><strong>Cred Bot</strong></h2>
<p> 
  The Cred Bot is an ongoing project that is a "fun" type bot along with some useful features. I am invested in making this bot unique, one that is different from many of the popular Discord bots that you could add to your server. 
</p>
 <p>
   <strong>Language:</strong> Python 
  <br>
   <strong>Features:</strong>
  <ul>
    <li>Give and take "cred" from members of the server (limited to 50 cred per day).</li>
  <li>"Cash in" cred for rewards such as muting, deafening or kicking another member of the server.</li>
  <li>Text alerts on voice channel join for enabled members.</li>
  <li>Custom admin text alerts to enabled members.</li>
  <li>Request a temporary email and recieve emails through Cred Bot </li>
  <li>"Wake up" calls to members phones at a member-specified time. Also good for finding a lost phone! </li>
   </ul>
  </p>
   <br>
   <p>
   <strong>Current Goals/Roadmap:</strong>
   <ul>
  <li>Migrate the bot to Azure or Google Cloud hosting.</li>
  <li>After migration, swap from Replit DB to MongoDB </li>
  <li>Research the potential of a discord phone with discord.js</li>
  <li>General Cleanup</li>
   </ul>
   </p>
   
   <div class="accordion">
     <div class="accordion-header">
        <div class="accordion-title">Snippets of code with explanations</div>
        <span class="accordion-icon">◀</span>
      </div>
      <div class="accordion-content">
        <ul>
          <li><a href="https://i.imgur.com/2Upd0Eq.png">Give Cred</a></li>
          <li><a href="https://i.imgur.com/wiZjboM.png">Rewards</a></li>
          <li><a href="https://i.imgur.com/rMoUJUo.png">Text Alerts</a></li>
          <li><a href="https://i.imgur.com/FsgC44d.png">Temporary Email</a></li>
          <li>Calls (Snippets coming soon!)</li>
        </ul>
      </div>
    </div>
   <div class="accordion">
     <div class="accordion-header">
        <div class="accordion-title">Video Demonstrations</div>
        <span class="accordion-icon">◀</span>
      </div>
      <div class="accordion-content">
        <ul>
          <li><a href="https://youtu.be/tUliYlRtDt4">Give Cred</a></li>
          <li><a href="https://youtu.be/9JL36dAr3Zc">Rewards</a></li>
          <li><a href="https://youtu.be/bETXtH8jMWs">Text Alerts</a></li>
          <li><a href="https://youtu.be/yliNWhPObvA">Temporary Email</a></li>
          <li>Calls (Video coming soon!)</li>
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

  

