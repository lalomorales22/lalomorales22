<!-- 
  Dark Theme Profile Page with White Borders
  ------------------------------------------
  Tip: This example uses inline styles to ensure GitHub renders it properly.
  You can tweak spacing, font sizes, or colors as needed.
-->

<div style="
  display: flex; 
  flex-direction: column; 
  background-color: #000; 
  color: #fff; 
  min-height: 100vh; 
  font-family: Arial, sans-serif;
">

  <!-- Hero Section -->
  <div style="
    width: 100%; 
    border: 2px solid #fff; 
    box-sizing: border-box; 
    margin-bottom: 10px;
  ">
    <img 
      src="https://laloadrianmorales.com/wp-content/uploads/2024/01/AIpenguins2-768x768.jpeg" 
      alt="Lalo's Hero" 
      style="
        display: block; 
        width: 100%; 
        height: auto; 
        max-height: 350px; 
        object-fit: cover;
      "
    />
  </div>

  <!-- Top-Level Nav Links -->
  <div style="
    display: flex; 
    justify-content: center; 
    align-items: center; 
    gap: 15px; 
    padding: 10px; 
    border: 2px solid #fff; 
    margin: 0 0 10px 0; 
    box-sizing: border-box;
  ">
    <a href="https://github.com/lalomorales22" style="color: #fff; text-decoration: none;">GitHub</a>
    <a href="https://twitter.com/lalopenguin" style="color: #fff; text-decoration: none;">Twitter</a>
    <a href="https://www.linkedin.com/in/lalo-morales-331474208/" style="color: #fff; text-decoration: none;">LinkedIn</a>
    <a href="https://www.laloadrianmorales.com" style="color: #fff; text-decoration: none;">Website</a>
    <a href="https://www.youtube.com/@thelalomorales" style="color: #fff; text-decoration: none;">YouTube</a>
    <a href="https://www.twitch.tv/laloadrianmorales" style="color: #fff; text-decoration: none;">Twitch</a>
    <a href="https://www.instagram.com/laloadrianmorales/" style="color: #fff; text-decoration: none;">Instagram</a>
    <a href="https://www.reddit.com/user/laloadrianmorales/" style="color: #fff; text-decoration: none;">Reddit</a>
    <a href="https://www.yelp.com/biz/penguin-dreams-chula-vista" style="color: #fff; text-decoration: none;">Yelp</a>
    <a href="https://www.discord.com/users/laloadrianmorales" style="color: #fff; text-decoration: none;">Discord</a>
  </div>

  <!-- Content Grid (3 columns, 2 rows) -->
  <div style="
    display: grid; 
    grid-template-columns: repeat(3, 1fr); 
    gap: 10px; 
    flex-grow: 1;
    box-sizing: border-box; 
    padding: 10px;
  ">
    <!-- About Me -->
    <div style="
      border: 2px solid #fff; 
      padding: 10px; 
      box-sizing: border-box;
    ">
      <h2 style="margin-top: 0;">About Me</h2>
      <ul>
        <li>Name: <strong>Lalo</strong></li>
        <li>Location: San Diego</li>
        <li>Profession: Software Developer &amp; Data Engineer</li>
        <li>Interests: AI, code, digital marketing, networking</li>
        <li>Personal: 2.6 years sober, father, husband</li>
      </ul>
    </div>

    <!-- Projects -->
    <div style="
      border: 2px solid #fff; 
      padding: 10px; 
      box-sizing: border-box;
    ">
      <h2 style="margin-top: 0;">Projects</h2>
      <ul>
        <li><strong>WGGY Project:</strong> <a href="http://whatgodgaveyou.com" style="color: #fff;">whatgodgaveyou.com</a></li>
        <li><strong>that's_my_bit:</strong> file structure &amp; experiments</li>
        <li><strong>Connecting the Dots:</strong> exploring language models &amp; universal patterns</li>
        <li><strong>Comedian's Joke App:</strong> AI-based transcription &amp; summarization</li>
      </ul>
    </div>

    <!-- Skills -->
    <div style="
      border: 2px solid #fff; 
      padding: 10px; 
      box-sizing: border-box;
    ">
      <h2 style="margin-top: 0;">Skills</h2>
      <ul>
        <li>Languages: HTML, JS, CSS, Python, R, Ruby</li>
        <li>Frameworks: Django, React</li>
        <li>Data Tools: Sheets, App Sheets, Looker Studio</li>
        <li>Tech: AI, NLP, LLMs, Networking</li>
      </ul>
    </div>

    <!-- Goals -->
    <div style="
      border: 2px solid #fff; 
      padding: 10px; 
      box-sizing: border-box;
    ">
      <h2 style="margin-top: 0;">Goals</h2>
      <ul>
        <li>Master data &amp; AI at all levels</li>
        <li>Acquire typing certificate</li>
        <li>Improve open source AI &amp; API skills</li>
        <li>Land a high-level AI position</li>
      </ul>
    </div>

    <!-- Contact -->
    <div style="
      border: 2px solid #fff; 
      padding: 10px; 
      box-sizing: border-box;
    ">
      <h2 style="margin-top: 0;">Contact</h2>
      <p>Email: <a href="mailto:laloadrianmorales@gmail.com" style="color: #fff;">laloadrianmorales@gmail.com</a></p>
      <p>LinkedIn: <a href="https://www.linkedin.com/in/lalo-morales-331474208/" style="color: #fff;">Lalo Morales</a></p>
      <p>Twitter: <a href="https://twitter.com/lalopenguin" style="color: #fff;">@lalopenguin</a></p>
      <p>Website: <a href="https://www.laloadrianmorales.com" style="color: #fff;">laloadrianmorales.com</a></p>
    </div>

    <!-- License -->
    <div style="
      border: 2px solid #fff; 
      padding: 10px; 
      box-sizing: border-box;
    ">
      <h2 style="margin-top: 0;">License</h2>
      <p>All repositories under MIT License unless specified otherwise.</p>
      <p>
        See <code>LICENSE</code> files for details.
      </p>
    </div>
  </div>

  <!-- Footer / Closing -->
  <div style="
    text-align: center; 
    padding: 10px; 
    margin-top: 10px; 
    border-top: 2px solid #fff;
  ">
    <p style="margin: 5px 0;">Thanks for stopping by!</p>
    <p style="margin: 5px 0;">Feel free to explore and reach out.</p>
  </div>

</div>
