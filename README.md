<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Lethabo Design Portfolio</title>
    <style>
      body {
        margin: 0;
        font-family: "Poppins", sans-serif;
        background: #f8f9fa;
        color: #000000;
        scroll-behavior: smooth;
      }

      a {
        color: #ff4081;
        text-decoration: none;
      }

      a:hover {
        text-decoration: underline;
      }

      header {
        position: relative;
        color: #fef2ff;
        text-align: center;
        padding: 100px 20px 50px;
        overflow: hidden;
      }

      /* Video background */
      header video {
        position: absolute;
        top: 0;
        left: 0;
        width: 100%;
        height: 100%;
        object-fit: cover;
        z-index: -1;
      }

      /* Glow animation */
      @keyframes glow {
        0% {
          text-shadow: 0 0 10px #ff4081, 0 0 20px #ff4081, 0 0 30px #ff4081,
            0 0 40px #d5006c, 0 0 50px #d5006c;
        }
        50% {
          text-shadow: 0 0 20px #ff4081, 0 0 30px #ff4081, 0 0 40px #ff4081,
            0 0 50px #d5006c, 0 0 60px #d5006c;
        }
        100% {
          text-shadow: 0 0 10px #ff4081, 0 0 20px #ff4081, 0 0 30px #ff4081,
            0 0 40px #d5006c, 0 0 50px #d5006c;
        }
      }

      header h1 {
        font-size: 3.5rem;
        font-weight: 800;
        text-transform: uppercase;
        margin: 0;
        letter-spacing: 3px;
        animation: glow 2s infinite ease-in-out;
      }

      header p {
        font-size: 1.2rem;
        font-family: "Georgia", "Times New Roman", serif;
        color: #ff02af;
        text-align: center;
        max-width: 600px;
        margin: 20px auto;
        line-height: 1.8;
      }

      header p em {
        font-style: italic;
        color: #9a9098;
        font-weight: bold;
      }

      .header-image {
        margin: 30px auto;
        display: flex;
        justify-content: center;
        align-items: center;
        position: relative;
        height: 300px;
        width: 300px;
        border-radius: 100%;
        border: 5px solid #ff04d1;
        overflow: hidden;
      }

      .header-image img {
        width: 100%;
        height: auto;
        object-fit: cover;
      }

      .resume-button {
        position: absolute;
        top: 20px;
        right: 20px;
        background-color: #0c0b0c;
        color: white;
        padding: 12px 30px;
        font-size: 1.2rem;
        font-weight: bold;
        text-transform: uppercase;
        border-radius: 50px;
        text-align: center;
        box-shadow: 0 4px 10px rgba(74, 29, 29, 0.3);
        transition: all 0.3s ease;
      }

      .resume-button:hover {
        background-color: #d5006c;
        box-shadow: 0 6px 15px rgba(0, 0, 0, 0.4);
      }

      section {
        padding: 60px 20px;
        text-align: center;
      }

      section h2 {
        font-size: 2.5rem;
        margin-bottom: 20px;
        font-weight: bold;
        text-transform: uppercase;
        color: #000000;
      }

      section p {
        max-width: 700px;
        margin: 0 auto;
        font-size: 1.2rem;
        line-height: 1.6;
        color: #121212;
      }

      .work-images {
        display: flex;
        justify-content: center;
        gap: 20px;
        flex-wrap: wrap;
        margin-top: 30px;
      }

      .work-images img {
        width: 300px;
        height: 200px;
        object-fit: cover;
        border-radius: 10px;
        box-shadow: 0 4px 10px rgba(0, 0, 0, 0.3);
        transition: transform 0.3s;
      }

      .work-images img:hover {
        transform: scale(1.05);
      }

      footer {
        background: #1a1a1a;
        color: #d4d4d4;
        text-align: center;
        padding: 20px;
        font-size: 0.9rem;
      }

      .socials {
        margin-top: 20px;
        display: flex;
        justify-content: center;
        gap: 20px;
      }

      .socials a {
        font-size: 1.2rem;
        color: #027ffc;
      }

      @media (max-width: 768px) {
        header h1 {
          font-size: 2.5rem;
        }

        header p {
          font-size: 1.2rem;
        }

        .work-images img {
          width: 90%;
          height: auto;
        }
      }

      form {
        display: grid;
        gap: 15px;
        text-align: left;
        max-width: 600px;
        margin: 0 auto;
      }

      label {
        font-weight: bold;
      }

      input,
      textarea {
        padding: 10px;
        font-size: 1rem;
        border: 1px solid #ddd;
        border-radius: 5px;
        width: 100%;
      }

      button {
        background-color: #ff4081;
        color: white;
        padding: 12px 20px;
        border: none;
        border-radius: 5px;
        cursor: pointer;
        font-size: 1.1rem;
        transition: background-color 0.3s ease;
      }

      button:hover {
        background-color: #d5006c;
      }
    </style>
  </head>

  <body>
    <header>
      <video autoplay muted loop>
        <source src="project55.mp4" type="video/mp4" />
        Your browser does not support the video tag.
      </video>
      <h1>Hello, I am Lethabo!</h1>
      <p>
        Design is more than what meets the eye; it's the silent language of
        emotion, intention, and vision. Through each line and every colour, I
        craft meaning that speaks louder than words. <br />
        <em>Hire me!</em>
      </p>
      <div class="header-image">
        <img src="lethabos.jpg" alt="Lethabo Semenya" />
      </div>
      <a href="Lethabo Semenya Cv.pdf" class="resume-button" download
        >Download Resume</a
      >
    </header>

    <section id="about">
      <h2>About Me</h2>
      <p>
        I am a highly motivated and versatile graphic designer with 3 years of
        experience in freelance design and project management, specializing in
        the construction industry. Additionally, I possess a strong skill set in
        digital marketing, allowing me to create visually engaging content that
        drives brand awareness and audience engagement. With a proven ability to
        manage projects from concept to completion, I deliver impactful designs
        that align with client goals. I am now seeking opportunities to apply my
        creative expertise, technical proficiency, and marketing knowledge to
        help drive the success of a dynamic organization.
      </p>
    </section>

    <section id="projects">
      <h2>Recent Projects</h2>
      <p>
        Below are some of the works I am particularly proud of. Check them out!
      </p>
      <div class="work-images">
        <img src="work2.png" alt="Project 1" />
        <img src="image3.jpg" alt="Project 2" />
        <img src="image4.jpg" alt="Project 3" />
        <br />
        <img src="work1.png" alt="Project 1" />
        <img src="project1.png" alt="Project 2" />
        <img src="project2.png" alt="Project 3" />
      </div>
    </section>

    <section id="contact">
      <h2>Contact Me</h2>
      <p>
        If you're interested in discussing a project or simply wish to connect,
        <br />
        please feel free to fill out the form below.
      </p>
      <form
        action="mailto:lethabosemenya@gmail.com"
        method="post"
        enctype="text/plain"
      >
        <label for="name">Your Name</label>
        <input type="text" id="name" name="name" required />

        <label for="email">Your Email</label>
        <input type="email" id="email" name="email" required />

        <label for="message">Your Message</label>
        <textarea id="message" name="message" rows="5" required></textarea>

        <button type="submit">Send Message</button>
      </form>
    </section>

    <footer>
      <p>&copy; 2024 Lethabo Design Studio. All Rights Reserved.</p>
      <div class="socials">
        <a href="https://www.instagram.com/lethabo_semenya/">Instagram</a>
        <a href="www.linkedin.com/in/lethabo-semenya-80aa81282">LinkedIn</a>
        <a href="https://x.com/Thabo84602222">Twitter</a>
      </div>
    </footer>
  </body>
</html>
