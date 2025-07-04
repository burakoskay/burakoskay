<style>
  /* Global Body Styles (MySpace Background) */
  body {
    background: url('https://i.imgur.com/your-myspace-background.gif') repeat; /* Replace with your desired background image URL */
    background-color: #000000; /* Fallback if image doesn't load */
    font-family: Arial, sans-serif;
    color: #333; /* Default text color */
    margin: 0;
    padding: 20px; /* Some padding around the entire content */
  }

  /* Main Container (like the central content area) */
  .myspace-container {
    width: 800px; /* Typical old web page width */
    margin: 20px auto; /* Center the container */
    background-color: #ffffff; /* White background for the main content */
    border: 1px solid #cccccc;
    box-shadow: 5px 5px 15px rgba(0,0,0,0.5); /* Subtle shadow for depth */
    padding: 20px;
    border-radius: 8px; /* Slightly rounded corners */
  }

  /* Section Headers (e.g., "About Me", "My Interests") */
  .myspace-section-header {
    background: linear-gradient(to right, #0066cc, #66ccff); /* Blue gradient header */
    color: white;
    padding: 8px 15px;
    margin-bottom: 15px;
    border-radius: 5px;
    font-size: 1.5em;
    text-shadow: 1px 1px 2px rgba(0,0,0,0.3);
    border: 1px solid #005bb5;
  }

  /* Content Boxes within sections */
  .myspace-content-box {
    background-color: #f0f8ff; /* Light blue background for content */
    border: 1px solid #aaddff;
    padding: 15px;
    margin-bottom: 20px;
    border-radius: 5px;
    line-height: 1.6;
  }

  /* Profile Picture/Top Area */
  .myspace-profile-top {
    display: flex;
    align-items: center;
    margin-bottom: 20px;
  }

  .myspace-profile-pic {
    width: 150px;
    height: 150px;
    border: 3px solid #ff00ff; /* Bright border for profile pic */
    border-radius: 50%; /* Make it round */
    margin-right: 20px;
    object-fit: cover; /* Ensure image covers the area */
  }

  .myspace-profile-name {
    font-size: 2.5em;
    color: #cc00cc; /* Purple name */
    font-weight: bold;
    text-shadow: 2px 2px 3px rgba(0,0,0,0.2);
  }

  /* Top Friends Section */
  .myspace-friends-grid {
    display: grid;
    grid-template-columns: repeat(auto-fill, minmax(100px, 1fr)); /* Responsive grid */
    gap: 15px;
    justify-content: center;
    text-align: center;
  }

  .myspace-friend {
    border: 1px solid #ffcc00; /* Yellow border for friends */
    padding: 5px;
    background-color: #fffacd; /* Light yellow background */
    border-radius: 5px;
  }

  .myspace-friend img {
    width: 80px;
    height: 80px;
    border-radius: 50%;
    object-fit: cover;
    margin-bottom: 5px;
  }

  .myspace-friend-name {
    font-size: 0.9em;
    font-weight: bold;
    color: #663300;
  }

  /* Music Player placeholder */
  .myspace-music-player {
    background: linear-gradient(to right, #ff6600, #ffcc00); /* Orange/Yellow gradient */
    padding: 10px 15px;
    border-radius: 5px;
    text-align: center;
    color: white;
    font-weight: bold;
    margin-bottom: 20px;
    border: 1px solid #cc5500;
    box-shadow: 2px 2px 5px rgba(0,0,0,0.3);
  }

  /* Visitor Counter Placeholder */
  .myspace-counter {
    text-align: center;
    font-size: 1.2em;
    color: #666;
    margin-top: 20px;
    font-style: italic;
  }

  /* Links */
  a {
    color: #0000ff; /* Classic blue link */
    text-decoration: underline;
  }

  a:hover {
    color: #ff00ff; /* Pink hover color */
  }

</style>

<div class="myspace-container">

  <div class="myspace-profile-top">
    <img src="https://avatars.githubusercontent.com/u/YOUR_GITHUB_ID?v=4" alt="Your Profile Picture" class="myspace-profile-pic"> <span class="myspace-profile-name">Burak Oskay</span>
  </div>

  <div class="myspace-music-player">
    Now Playing: &nbsp; Encuentro de Sombras by Agustin Pereyra Lucena
    <br>
    <a href="https://www.youtube.com/watch?v=DpKSbe6Z8H0" target="_blank" style="color:white; text-decoration: none;">▶️ Click to Listen (Rickroll Warning!)</a>
  </div>

  ---

  <div class="myspace-section-header">
    About Me
  </div>
  <div class="myspace-content-box">
    <p>Hey there! Welcome to my profile. I'm just a coder living in the digital world, enjoying long walks through repositories and debating tabs vs. spaces. My spirit animal is a JavaScript console error, and my favorite pastime is debugging.</p>
    <p>I'm super passionate about building cool stuff and learning new technologies. Hit me up if you want to collaborate or just talk about the good old days of Flash animations!</p>
  </div>

  ---

  <div class="myspace-section-header">
    Who
