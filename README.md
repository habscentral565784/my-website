<html>
<head>
    <title>My Personal Website</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            background-color: lightblue;
        }
        h1 {
            text-align: center;
            color: white;
        }
        .container {
            width: 80%;
            margin: auto;
        }
        .section {
            background-color: white;
            padding: 20px;
            margin: 10px;
            border-radius: 10px;
        }
        .bio {
            display: flex;
            align-items: center;
        }
        .bio img {
            width: 200px;
            height: 200px;
            border-radius: 50%;
            margin-right: 20px;
        }
        .bio p {
            font-size: 18px;
        }
        .resume {
            display: grid;
            grid-template-columns: 1fr 2fr;
            gap: 20px;
        }
        .resume h2 {
            margin-top: 0;
        }
        .resume ul {
            list-style: none;
            padding-left: 0;
        }
        .resume li {
            margin-bottom: 10px;
        }
        .resume span {
            font-weight: bold;
        }
        .contact {
            display: flex;
            justify-content: space-around;
        }
        .contact a {
            text-decoration: none;
            color: black;
            font-size: 20px;
        }
    </style>
</head>
<body>
    <h1>My Personal Website</h1>
    <div class="container">
        <div class="section bio">
            <img src="my_photo.jpg" alt="My photo">
            <p>Hi, I'm John Doe, a web developer and a hobbyist photographer. I love creating beautiful and functional websites using HTML, Javascript and CSS. I also enjoy taking photos of nature, animals and people. I live in Oshawa, Ontario, Canada with my wife and two kids.</p>
        </div>
        <div class="section resume">
            <h2>My Resume</h2>
            <div class="education">
                <h3>Education</h3>
                <ul>
                    <li><span>Bachelor of Science in Computer Science</span>, University of Toronto, 2019 - 2023</li>
                    <li><span>High School Diploma</span>, Oshawa Secondary School, 2015 - 2019</li>
                </ul>
            </div>
            <div class="experience">
                <h3>Experience</h3>
                <ul>
                    <li><span>Web Developer</span>, ABC Inc., Jan 2023 - Present
                        <ul>
                            <li>Developed and maintained various web applications using HTML, Javascript and CSS</li>
                            <li>Implemented responsive design, user interface and user experience features</li>
                            <li>Collaborated with other developers, designers and clients to deliver high-quality products</li>
                        </ul>
                    </li>
                    <li><span>Web Developer Intern</span>, XYZ Ltd., Sep 2022 - Dec 2022
                        <ul>
                            <li>Assisted in developing and testing web applications using HTML, Javascript and CSS</li>
                            <li>Learned and applied best practices and industry standards</li>
                            <li>Received positive feedback and mentorship from senior developers</li>
                        </ul>
                    </li>
                </ul>
            </div>
            <div class="skills">
                <h3>Skills</h3>
                <ul>
                    <li>HTML, Javascript, CSS</li>
                    <li>React, Angular, Vue</li>
                    <li>Node.js, Express, MongoDB</li>
                    <li>Git, GitHub, VS Code</li>
                    <li>Photoshop, Lightroom, Illustrator</li>
                </ul>
            </div>
            <div class="awards">
                <h3>Awards</h3>
                <ul>
                    <li><span>Best Web Design Award</span>, University of Toronto, 2023</li>
                    <li><span>First Place in Hackathon</span>, XYZ Ltd., 2022</li>
                    <li><span>Honour Roll Student</span>, Oshawa Secondary School, 2019</li>
                </ul>
            </div>
        </div>
        <div class="section contact">
            <h2>Contact Me</h2>
            <div class="links">
                <a href="mailto:john.doe@example.com"><img src="email_icon.png" alt="Email icon"> john.doe@example.com</a>
                <a href="https://www.linkedin.com/in/john-doe/"><img src="linkedin_icon.png" alt="LinkedIn icon"> John Doe</a>
                <a href="https://www.github.com/john-doe/"><img src="github_icon.png" alt="GitHub icon"> john-doe</a>
            </div>
        </div>
    </div>
</body>
</html>

