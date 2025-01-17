<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Anindita Ghosh - Personal Webpage</title>
    <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/5.15.4/css/all.min.css">
    <style>
        /* Example media query for mobile devices */
@media (max-width: 600px) {
    .resume-content {
        font-size: 14px; /* Adjust font size for readability */
        padding: 10px; /* Adjust padding for better spacing */
        width: 100%; /* Ensure content takes full width */
    }
}
.resume-content {
    font-size: 16px;
    line-height: 1.5;
    padding: 20px;
    margin: 0 auto;
}

@media (max-width: 600px) {
    .resume-content {
        font-size: 14px;
        padding: 10px;
    }
}
.resume-container {
    display: flex;
    flex-direction: column;
    align-items: center;
    padding: 20px;
}

.resume-section {
    width: 100%;
    max-width: 600px;
    margin-bottom: 20px;
}

        body, html {
            margin: 0;
            padding: 0;
            font-family: 'Times New Roman', sans-serif;
            scroll-behavior: smooth;
            background-color: #cccccc;
            top: 50%;
            bottom: 50%;
        }
        .container {
            text-align: center;
            color: rgb(17, 16, 16);
            background-image: linear-gradient(to bottom, rgba(91, 68, 58, 0.8), rgba(66, 66, 80, 0.8)), url('ani.jpg');
            background-position: center;
            height: 150vh;
            display: flex;
            align-items:  justify;
            justify-content: center;
            position: relative;
            flex-direction: column;
            text-shadow: 2px 2px 4px rgba(87, 78, 78, 0.6);
        }
        .title-container {
            position: relative;
        }

        .typed-cursor {
            display: inline-block;
            font-weight: 100;
            font-size: 40px;
            color: #000000;
            animation: blink 0.7s infinite;
        }

        @keyframes blink {
            0% {
                opacity: 0;
            }
            50% {
                opacity: 1;
            }
            100% {
                opacity: 0;
            }
        }

        .title {
            white-space: nowrap;
            overflow: hidden;
        }
        .sidebar {
            width: 60px;
            background: #000000;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding-top: 20px;
            padding-bottom: 20px;
            position: fixed;
            height: 100%;
        }
        .sidebar a {
            color: #000000;
            margin: 20px 0;
            font-size: 1.5rem;
            transition: color 0.3s;
        }
        .sidebar a:hover {
            color: #1e90ff;
        }
        .content {
            margin-left: 80px;
            padding: 20px;
            width: 100%;
        }
        .social-links {
            margin-top: 20px;
        }
        .social-links a {
            margin: 0 10px;
            color: #fff;
            text-decoration: none;
            font-size: 1.5em;
            transition: color 0.3s ease;
        }
        .social-links a:hover {
            color: #020101;
        }
        .nav {
            position: fixed;
            top: 50%;
            left: 0;
            
            transform: translateY(-50%);
            display:flex;
            flex-direction: column;
            background: rgba(0, 0, 0, 0.7);
            border-radius: 0 8px 8px 0;
            padding: 10px;
            z-index: 10000;
        }
        .nav a {
            margin: 10px 0;
            text-decoration: none;
            color: white;
            font-size: 24px;
            display: flex;
            align-items: center;
            transition: background 0.3s, color 0.3s;
            padding: 8px;
            border-radius: 4px;
        }
        .nav a:hover {
            background: #ff7f50;
            color: rgb(255, 255, 255);
        }
        .nav a span {
            margin-right: 8px;
            font-size: 28px;
        }
        .section {
            height: 100vh;
            display: flex;
            justify-content: center;
            align-items: center;
            padding: 20px;
            flex-direction: column;
        }
        .portfolio {
            font-family: 'Times New Roman', sans-serif;
    background-color: #1f1c1c;
    color: #333;
    width: 100%;
    text-align: center;
    padding: 50px 20px;
}

.portfolio-title {
    color: #fff;
    font-family: 'Times New Roman', sans-serif;
    text-decoration: underline;
    font-size: 36px;
    font-weight: bold;
    text-transform: uppercase;
    margin-bottom: 20px;
}

.portfolio-content { text-transform: uppercase;
    color: #000000;
}

.portfolio-content a {
    color: #ff6347; text-transform: uppercase;
    text-decoration: none;
}

.portfolio-content a:hover { text-transform: uppercase;
    text-decoration: underline;
}
.skills, .about, .contact, .achievements {
            background-color: #1f1c1c;
            color: #333;
            width: 100%;
            text-align: center;
            padding: 50px 20px;
        }
        .portfolio { font-family: 'Times New Roman', sans-serif; text-transform: uppercase;
            background: linear-gradient(45deg, #ff9a9e 0%, #fad0c4 99%, #fad0c4 100%);
        }
        #resume {
            padding: 20px; font-family: 'Times New Roman', sans-serif;
            background-color: #ffffff;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
            margin: 20px auto;
            max-width: 900px;
            border-radius: 10px;
            border: 2px solid #007bff;
        }
        #resume h1 {
            text-align: center;
            color: #007bff;
            text-transform: uppercase;
            text-decoration: underline;
            font-size: 36px;
        }
        .resume {
            display: flex; 
            justify-content: space-between;
            flex-wrap: wrap;
        }
        .resume-left, .resume-right {
            width: 48%;
            box-sizing: border-box;
        }
        .resume-item {
            background: #e8e8e8;
            padding: 20px; 
            border-radius: 10px;
            margin-bottom: 20px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
        }
        .resume-item h3 {
            margin: 0;text-decoration: underline;
            font-size: 20px;
            color: #007bff;
            text-align: center;
        }
        .resume-item p, .resume-item ul {
            margin: 10px 0;
            line-height: 1.6;
        }
        .personal-info {
            text-align: center;
        }
        .personal-info img {
            width: 100px;
            height: 100px;
            border-radius: 50%;
        }
        .contact-info p {
            margin: 10px 0;
            line-height: 1.6;
        }
        .skill-bar {
            position: relative;
            background: #ddd;
            border-radius: 20px;
            overflow: hidden;
            margin-bottom: 10px;
        }
        .skill-bar-fill {
            height: 20px;
            line-height: 20px;
            color: #fff;
            text-align: center;
            border-radius: 20px;
        }
        .python { background: #4b8bbe; width: 90%; }
        .java { background: #f89820; width: 85%; }
        .htmlcssjs { background: #e44d26; width: 80%; }
        .c { background: #a8b9cc; width: 75%; }
        .moral {
            text-align: justify;
            font-style: italic;
        }
        .signature {
            text-align: right;
            font-weight: bold;
        }
.about {
            background: linear-gradient(to right, #ffecd2 0%, #fcb69f 100%);
            color: #333;
            border-radius: 15px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            margin: 50px auto;
            max-width: 800px;
            padding: 30px;
        }
        .about h2 {
            font-size: 36px;
            margin-bottom: 20px;
        }
        .about-content {
            font-size: 18px;
            line-height: 1.6;
        }
        .about-content b {
            color: #e94e77;
        }
        .achievements {
            background: linear-gradient(to left, #a1c4fd, #c2e9fb);
        }
        .video {
            max-width: 80%;
            height: auto;
            border-radius: 10px;
            box-shadow: 0px 0px 20px rgba(0, 0, 0, 0.2);
        }
        h2 {
            font-size: 56px;
            margin-bottom: 20px;
         
        }
        h5 {
            font-size: 56px;
            margin-bottom: 20px;
            text-decoration: underline;
        }
        h1 {
            font-size: 60px;
            margin-bottom: 20px;
            text-shadow: #050607;
        }
        h4 {
            font-size: 36px;
            margin-bottom: 20px;
            text-align: left;
        }
        p, a {
            font-size: 18px;
            color: #333;
        }
        a {
            color: #808080;
            text-decoration: none;
        }
        a:hover {
            
            text-decoration: underline;
        }
        #contact{
            padding: 20px;
            background-color: #ffffff;
        }
        .contact-form {
            display: flex;
            flex-direction: column;
            align-items: center;
            max-width: 600px;
            margin: 0 auto;
        }
        .contact-form label {
            font-size: 18px;
            margin-bottom: 10px;
            color: rgb(0, 0, 0);
        }
        .contact-form input,
        .contact-form textarea {
            width: 100%;
            padding: 15px;
            margin-bottom: 20px;
            border-radius: 5px;
            border: 1px solid #000000;
            font-size: 16px;
        }
        .contact-form button {
            background-color: #ff7f50;
            color: rgb(0, 0, 0);
            border: none;
            padding: 15px 30px;
            font-size: 18px;
            border-radius: 10px;
            cursor: pointer;
            transition: background-color 0.3s;
        }
        .contact-form button:hover {
            background-color: #000000;
        }
        #contact {
            display: flex;
            justify-content: space-between;
            align-items: center;
            padding: 20px;
        }
        #contact .map-container {
            width: 50%;
            height: 400px;
        }
        #contact .contact-form {
            width: 45%;
        }
        .map-container iframe {
            
          
            border: 0;
        }
        .resume {
display: flex;
align-self: left;
justify-content: space-between;
border: #007bff;
flex-wrap: wrap;
gap: 20px;
margin-top: 20px;
}
.resume .resume-item {
background: #8f8f8f57;
padding: 20px;
width: 100%;text-align: left;
            border-radius: 50%;
            margin-bottom:5px;
border-radius: 10px;
border: #007bff;
box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
width: calc(50% - 10px);
box-sizing: border-box;
}
.resume .resume-it{
background: #4b494957;
padding: 20px;
width: 100%;
            border-radius: 50%;
            margin-bottom:5000px;
border-radius: 10px;
border: #007bff;
box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
width: calc(50% - 10px);
box-sizing: border-box;
}
.resume .resume-item h3 {
margin: 0;

font-size: 20px;
border: #007bff;
text-align: center;
color: #007bff;
}
.resume .resume-item h1 {
margin: 0;

font-size: 20px;
border: #007bff;
text-align: left;
text-shadow: #3d4146;
text-indent:50%;
text-emphasis-style: bold;
text-decoration-style: double;
text-transform: uppercase;
color: #000000;
}
.resume .resume-item p {
margin: 10px 0;
line-height: 1.6;

}
.resume .resume-item ul {
    text-align: center;
   
list-style-type: disc;
margin-left: 20px;
}
#location{
    font-style: italic;
}     .title {
            white-space: nowrap;
            overflow: hidden;
        }
        .sidebar {
            width: 60px;
            background: #000000;
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            padding-top: 20px;
            padding-bottom: 20px;
            position: fixed;
            height: 100%;
            top: 0;
            left: 0;
        }
        .sidebar a {
            color: #ffffff;
            margin: 20px 0;
            font-size: 1.5rem;
            transition: color 0.3s;
        }
        .sidebar a:hover {
            color: #1e90ff;
        }
        .content {
            margin-left: 80px;
            padding: 20px;
            width: calc(100% - 80px);
        }
        .skills-list {
            width: 80%;
            align-items: baseline;
            background: #ffffff;
            max-width: 800px;
            margin: 0 auto;
            text-align: left;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
width: calc(50% - 10px);
box-sizing: border-box;
        }
        .skill {
            margin: 10px 0;
            background: #c0c0c0;
padding: 20px;
border-radius: 10px;
margin-top: 10px;
            margin-top: 10px;
            box-shadow: 0 4px 6px rgba(0, 0, 0, 0.1);
width: calc(50% - 10px);
box-sizing: border-box;
        }
        .skill-name {
            margin-bottom: 5px;
            font-weight: bold;
        }
        .skill-bar {
            height: 30px;
            background-color: #ebe0e0;
            border-radius: 5px;
            overflow: hidden;
            position: relative;
        }
        .skill-bar-fill {
            height: 100%;
            border-radius: 5px;
            transition: width 2s;
            text-align: right;
            padding-right: 10px;
            line-height: 30px;
            color: rgb(26, 21, 21);
            font-weight: bold;
            
        }
        .python { background-color: #4f504e; }
        .java { background-color: #646362; }
        .htmlcssjs { background-color: #5f5c5b; }
        .c { background-color: #555555; }
        .skill-bar-fill::after {
            content: attr(data-label);
            position: absolute;

            right: 10px;
        }
        .animated-bg {
            animation: animated-bg 1.5s infinite;
        }
        @keyframes animated-bg {
            0% { background-position: 0% 50%; }
            50% { background-position: 100% 50%; }
            100% { background-position: 0% 50%; }
        }
    
.achievement-buttons ol {
    list-style-type: none; /* Remove default list styling */
    padding: 0;
}

.achievement-buttons li {
    margin-bottom: 15px; /* Add space between each list item */
}

.achievement-buttons p {
    margin: 0;
    font-size: 16px;
    line-height: 1.5;
}

.achievement-buttons a {

           background-position: 2px;
            box-shadow: #000000;
    color: #007bff;
    box-shadow: #000000;
            padding: 12px 20px;
            font-size: 18px;
            border-radius: 5px;
            cursor: pointer;
            transition: background-color 0.3s;
            text-decoration: none;
            margin: 5px;
    text-decoration: none;
}

.achievement-buttons a:hover {
    text-decoration: underline;
}

/* Responsive adjustments */
@media (max-width: 600px) {
    .achievement-buttons p {
        font-size: 14px;
    }
}

        footer {
            text-align: center;
            padding: 10px;

         left:0%;
      
            background: #333;
            color: rgb(255, 255, 255);
            font-size: 14px;
            position: fixed;
            bottom: 0;
            width: 100%;
        }
    </style>
</head>
<body>
    <div class="container">
        <section id="home" class="section">
            <!-- Home section content -->
     
        <div class="title-container">
            <div class="title">
                <h1>👋 Hi, welcome Anindita here.</h1>
            </div>
            <h2 class="typing-text"><span id="typed-text"></span><span class="typed-cursor"></span></h2>
        </div>
        <div class="social-links">
            <a href="https://www.linkedin.com/in/anindita-ghosh-25bb47266/" target="_blank"><i class="fab fa-linkedin"></i></a>
            <a href="https://github.com/Anin5604/Anin5604" target="_blank"><i class="fab fa-github"></i></a>
            <a href="https://twitter.com/" target="_blank"><i class="fab fa-twitter"></i></a>
            <a href="https://facebook.com" target="_blank"><i class="fab fa-facebook"></i></a>
            <a href="https://instagram.com" target="_blank"><i class="fab fa-instagram"></i></a>
            
        </div>
    </div>
</section>
<div class="sidebar">
    <a href="#home"><i class="fas fa-home"></i></a>
    <a href="#about"><i class="fas fa-info-circle"></i></a>
 <a href="#resume"><i class="fas fa-file-alt"></i></a>
 <a href="#portfolio"><i class="fas fa-briefcase"></i></a>
   
    <a href="#achievements"><i class="fas fa-trophy"></i></a>
    
    <a href="#contact"><i class="fas fa-envelope"></i></a>
</div>
<section id="about" class="section about">
    <h2>About Me</h2>
    <div class="about-content">
        <p><b>Hello! I'm Anindita Ghosh, a passionate software developer with a love for learning and exploring new technologies. I am a beginner person in computer science and have worked on various projects ranging in  web development .</b></p>
        <p><b>My journey in the tech world began with a curiosity to understand how things work, which led me to pursue a career in software development. Over the years, I have honed my skills in various programming languages and frameworks, and I'm always eager to take on new challenges and expand my knowledge.</b></p>
        <p><b>In my free time, I enjoy reading, hiking, and experimenting with new coding projects. I'm also an avid traveler and love exploring new cultures and cuisines.</b></p>
    </div>
</section>

        <section id="resume" >
            <h1 align="center"><u>RESUME</u></h1>.
        <div class="resume">
            <!-- Anindita Ghosh's Resume -->
            <div class="resume-item">
               
            <div class="personal-info">
                <img src="anindita.jpg" alt="Anindita Ghosh">
                <p align ="justify" class="moral"><b>"If you can think,then you can create "</b></p>
                <p align ="right" class="signature">~Anindita Ghosh</p>
            </div>
           
                        <h3>Summary</h3>
                        <p>As a prospective full-stack software engineer, I'm deeply passionate about developing scalable, high-performance, and reliable software systems.</p>
                        
                   
               
                        <h3>Education</h3>
                        <p><strong>Bachelor of Engineering in Information Technology (2022- 2026)</strong><br>St. Thomas College of Engineering & Technology, Kolkata</p>
                        <p><strong>Class 12th Board (2022)</strong><br>Dum Dum Ananda Ashram Sarada Vidyapith(WBCHSE)</p>
                        <p><strong>Class 10th Board (2020)</strong><br>Baranagore Rajkumari Memorial Girl's High School(WBBSE)</p>
                        <h3>Experience</h3>
                        <p>Excited to announce that I've been selected for a Web Development Internship at IntechtechSoft Services Pvt Ltd! Looking forward to gaining knowledge and experience.</p> </div>
            
                       
              
                           
                              
                            <div class="resume-item">   <h3>Skills</h3>
                                <div class="skill-name"><span i  class="fab fa-python"></span> Python</div>
                                <div class="skill-bar">
                                    <div class="skill-bar-fill python" style="width: 90%;" data-label="90%"></div>
                                </div> <div class="skill-name"><span i  class="fab fa-java"></span> Java</div>
                                <div class="skill-bar">
                                    <div class="skill-bar-fill java" style="width: 85%;" data-label="85%"></div>
                                </div> <div class="skill-name"><span i  class="fab fa-html5"></span> HTML/CSS/JS</div>
                                <div class="skill-bar">
                                    <div class="skill-bar-fill htmlcssjs" style="width: 80%;" data-label="80%"></div>
                                </div>
                                <div>
                            <div class="skill-name"><span i  class="fab fa-laptop-code"></span>C</div>
                        </div>
                            <div class="skill-bar">
                                <div class="skill-bar-fill c" style="width: 75%;" data-label="75%"></div>
                         
                    
                            </div>
                            
                              
                            <h3>Hobbies</h3>
                           
                          <Ol><li>Listening to Music</li>
                          <li>Travelling</li>
                          <li>Photography</li>
                            <li>Exploring New Technologies</li></Ol>
                            <div class="achievement-buttons">
                                <P>To know More click 
                                   👇
                                    </P>
            <a href="CV.pdf" target="_blank"><u>Resume</u></a>
       
        </div>
                            </div>
                            
                            </div>

                    
                    </div>
 </section>
         <section id="portfolio" class="section portfolio">
            <h5 align="left">Portfolio</h5>
            <div class="portfolio-content">
                <p align="center"><b>Here are some of my works:</b></p>
            <ol>
                    <li><p>Tic Tac Toe game website (using HTML, CSS, JS): 👉<a href="tictactoe.html"><u>TicTacToe Game</u></a></p></li>
                    <li><p>Student Admission form (using Python GUI): 👉<a href="form1.jpg"><u>STUDENT-FORM</u></a><font color=#00000> || </font><a href="FORM.jpg"><u>Student Form</u></a><a href="save.jpg"><font color=#00000> || </font><u>Student Form save</u></a><font color=#00000> || </font><a href="STUDENT.csv"><u>Student document</u></a></p></li>
                    <li><p>Calculator (using HTML, CSS, JS): 👉<a href="calculator.html"><u>Basic Calculator</u></a></p></li>
                    <li><p>Income Tax Calculator (using HTML, CSS, JS): 👉<a href="incometaxcalculate.html"><u>Income Tax Calculator</u></a></p></li>
                    <li><p>TO-DO-LIST (using HTML, CSS, JS): 👉<a href="todo.html"><u>TO-DO-LIST</u></a></p></li>
                    <li><p>ONLINEQUIZPLATFORM (using HTML, CSS, JS): 👉<a href="quizplatform.html"><u>ONLINEQUIZPLATFORM</u></a></p></li>
                    <li><p>AGE CALCULATOR (using HTML, CSS, JS): 👉<a href="age_cal.html"><u>AGECALCULATOR</u></a></p></li>
                </ol>
                </div>
                </div>
        </section>
        
        <section id="achievements" class="section achievements">
            
            <h5 align="left" tabindex="uppercase" >Achievements</h5> 
             <p align="center"><b>Here are some of my Certificates:</b></p>

           <div class="achievement-buttons">
    <menu>
        <menu>
            <p>View Certificate (coursera): 👉 <a href="certificate1.pdf" target="_blank"><u>View Certificate (coursera)</u></a></p>
        </menu>
        <menu>
            <p>View Certificate (coursera): 👉 <a href="certificate2.pdf" target="_blank"><u>View Certificate (coursera)</u></a></p>
        </menu>
    <menu>
            <p>View Certificate (coursera): 👉 <a href="certificate3.pdf" target="_blank"><u>View Certificate (coursera)</u></a></p>
        </menu>
    <menu>
            <p>View Certificate (webinar On Quantum Computing): 👉 <a href="quantumieee.pdf" target="_blank"><u>View Certificate (webinar)</u></a></p>
        </menu>
        <menu>
            <p>View Certificate (Course On Udemy): 👉 <a href="udemy.pdf" target="_blank"><u>(Course On Udemy)</u></a></p>
        </menu>
        <menu>
            <p>View Certificate (Course On Udemy): 👉 <a href="udemy1.pdf" target="_blank"><u>(Course On Udemy)</u></a></p>
        </menu>
        <menu>
            <p>View Certificate (Course On Udemy): 👉 <a href="udemy2.pdf" target="_blank"><u>(Course On Udemy)</u></a></p>
        </menu>
    </menu>
</div>
</section>
       
    </div>
<div>
  

    <section id="contact" class="section contact">
        
        <div class="contact-form">
            <h5>CONTACT</h5>
            <p><i class="fas fa-envelope"></i> ganindita10@gmail.com</p>
            <p><i class="fas fa-phone"></i>   +917980456257</p>
            <p><i class="fas fa-map-marker-alt"></i> 24/1, Rajendra Nath Chatterjee Road, Kolkata 700035</p>
            <form>
                <label for="name">Name</label>
                <input type="text" id="name" name="name" required>
                <label for="email">Email</label>
                <input type="email" id="email" name="email" required>
                <label for="message">Message</label>
                <textarea id="message" name="message" rows="5" required></textarea>
                <button type="submit">Send</button>
            </form> <div class="map-container">
                <iframe align="right" src="https://www.google.com/maps/embed?pb=!1m18!1m12!1m3!1d471218.0924057887!2d88.26063980499653!3d22.649671428934672!2m3!1f0!2f0!3f0!3m2!1i1024!2i768!4f13.1!3m3!1m2!1s0x3a02772f8a92440d%3A0x9db2711d8f4b3aeb!2sBaranagar%2C%20Kolkata%2C%20West%20Bengal!5e0!3m2!1sen!2sin!4v1655568543834!5m2!1sen!2sin" allowfullscreen="" loading="lazy"></iframe>
            </div>
           
        </div>
    </section>
    </div>
    <footer>
        &copy; 2024 Anindita Ghosh. All Rights Reserved.
    </footer>

    <script src="https://cdn.jsdelivr.net/npm/typed.js@2.0.12"></script>
    <script>
        var typed = new Typed('#typed-text', {
            strings: ['I Am a Designer', 'I Am a Developer', 'I Am a Teacher ','I Am a Student'],
            typeSpeed: 100,
            backSpeed: 50,
            backDelay: 2000,
            startDelay: 1000,
            loop: true,
            showCursor: true,
            cursorChar: '|',
            
        });
        window .onload=function()
        {
            getLocation();
        }

    </script>
</body>
</html>
