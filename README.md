<html>
<head>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
  <header>
    <nav>
      <ul>
        <li><a href="#home">Home</a></li>
        <li><a href="#about">About</a></li>
        <li><a href="#projects">Projects</a></li>
        <li><a href="#contact">Contact</a></li>
      </ul>
    </nav>
  </header>

  <section id="home">
    <h1>Welcome to My Portfolio</h1>
    <p>Hi, I'm Arihant Jain, an engineering student.
        I am persuing my B.Tech. from Vidya College Of Engineering.
    </p>
  </section>

  <section id="about">
    <h2>About Me</h2>
    <p>I'm a passionate developer with experience in </p>
    <ul id="language">
        <li>C Programming</li>
        <li>C++ Programming</li>
        <li>HTML</li>
        <li>CSS</li>
        <li>JavaScript</li>
    </ul>
  </section>

  <section id="projects">
    <h2>My Projects</h2>
    <div class="project">
      <h3>Project 1 (QUIZ.CPP)</h3>
      <p>A quiz game based on C++ language with user interaction that leads to <br>
        increace in their knowledge. They get scored according to how fast they<br>
        answer the questions. They can even add or delete the questions as per <br>
        their likings.</p>
    </div>
    <div class="project">
      <h3>Project 2 (Temperature Converter)</h3>
      <p>A temperature converter website that can convet the temperatures amongst<br>
         the Celsius, Farenhite and Kelvin at the same time.</p>
    </div>
  </section>

  <section id="contact">
    <h2>Contact Me</h2>
    <form>
      <label for="name">Name:</label>
      <input type="text" id="name" name="name" required>
      <label for="email">Email:</label>
      <input type="email" id="email" name="email" required>
      <label for="message">Message:</label>
      <textarea id="message" name="message" required></textarea>
      <button type="submit">Send</button>
    </form>
  </section>

  <footer>
    <h4>&copy; 2023 Arihant Jain</h4>
  </footer>
</body>
</html>
