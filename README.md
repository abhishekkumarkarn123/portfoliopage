<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Abhishek Kumar | Portfolio</title>
    <script src="https://unpkg.com/react@17/umd/react.production.min.js"></script>
    <script src="https://unpkg.com/react-dom@17/umd/react-dom.production.min.js"></script>
    <script src="https://unpkg.com/babel-standalone@6/babel.min.js"></script>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 20px;
            background-color: #f3f4f6;
            text-align: center;
        }
        .container {
            max-width: 800px;
            margin: auto;
            background: white;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #333;
        }
        ul {
            list-style-type: none;
            padding: 0;
        }
        li {
            background: #e5e7eb;
            margin: 5px;
            padding: 10px;
            border-radius: 5px;
        }
        .contact a {
            display: block;
            margin-top: 10px;
            text-decoration: none;
            color: #007bff;
        }
    </style>
</head>
<body>

    <div id="root"></div>

    <script type="text/babel">
        function Portfolio() {
            return (
                <div className="container">
                    <h1>Abhishek Kumar</h1>
                    <p>IT Professional | Web Developer |</p>
                    
                    {/* About Section */}
                    <h2>About Me</h2>
                    <p>I am an IT entry level professional working in Siemens with expertise in SCADA systems, networking, and web development.</p>

                    {/* Skills Section */}
                    <h2>Skills</h2>
                    <ul>
                        <li>SCADA Systems & RTU Devices</li>
                        <li>Network Security</li>
                        <li>Web Development (HTML, CSS, JavaScript, React)</li>
                        <li>linux, sql</li>
                    </ul>

                    {/* Projects Section */}
                    <h2>Projects</h2>
                    <ul>
                        <li>SCADA Monitoring System - Real-time data monitoring</li>
                        <li>Movie Rating Prediction - Machine Learning project</li>
                        <li>Personal Portfolio Website - Built using React</li>
                    </ul>

                    {/* Contact Section */}
                    <h2>Contact</h2>
                    <div className="contact">
                        <p>Email: <a href="mailto:abhishekkumarkarn28@gmail.com">abhishekkumarkarn28@gmail.com</a></p>
                        <p>Phone: +91 9102935460</p>
                        <p>GitHub: <a href="https://github.com/abhishek" target="_blank">github.com/abhishek</a></p>
                        <p>LinkedIn: <a href="https://www.linkedin.com/in/abhishek-kumar-karn-4a9757195?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app" target="_blank">https://www.linkedin.com/in/abhishek-kumar-karn-4a9757195?utm_source=share&utm_campaign=share_via&utm_content=profile&utm_medium=android_app</a></p>
                    </div>
                </div>
            );
        }

        ReactDOM.render(<Portfolio />, document.getElementById('root'));
    </script>

</body>
</html>
