#f0f0f0;
            color: #333;
            overflow: hidden;
        }
        .container {
            max-width: 800px;
            margin: auto;
            padding: 20px;
            background: white;
            border-radius: 8px;
            box-shadow: 0 2px 10px rgba(0, 0, 0, 0.1);
        }
        h1, h2 {
            color: #4CAF50;
        }
        .section {
            margin-bottom: 20px;
            padding: 15px;
            border: 1px solid #ddd;
            border-radius: 5px;
            background: #fafafa;
        }
        .tech-stack {
            display: flex;
            flex-wrap: wrap;
        }
        .tech {
            background: #e0e0e0;
            border-radius: 5px;
            padding: 10px;
            margin: 5px;
        }
        .connect {
            display: flex;
            flex-direction: column;
        }
        .connect a {
            margin: 5px 0;
            color: #4CAF50;
            text-decoration: none;
        }
        .connect a:hover {
            text-decoration: underline;
        }
        #particles-js {
            position: absolute;
            width: 100%;
            height: 100%;
            z-index: -1;
        }
    </style>
</head>
<body>
    <div id="particles-js"></div>
    <div class="container">
        <h1>Hello, I'm [Your Name]!</h1>
        <div class="section about-me">
            <h2>About Me</h2>
            <p>I'm a passionate developer with a love for creating innovative solutions. I enjoy working with various technologies and continuously learning new skills.</p>
        </div>
        <div class="section tech-stack">
            <h2>Tech Stack</h2>
            <div class="tech">Java</div>
            <div class="tech">JavaScript</div>
            <div class="tech">Python</div>
            <div class="tech">HTML & CSS</div>
            <div class="tech">React</div>
            <div class="tech">Node.js</div>
        </div>
        <div class="section connect">
            <h2>Let's Connect</h2>
            <a href="https://linkedin.com/in/yourprofile" target="_blank">LinkedIn</a>
            <a href="https://twitter.com/yourprofile" target="_blank">Twitter</a>
            <a href="mailto:youremail@example.com">Email</a>
        </div>
    </div>
    <script src="https://cdn.jsdelivr.net/particles.js/2.0.0/particles.min.js"></script>
    <script>
        particlesJS.load('particles-js', 'https://raw.githubusercontent.com/VincentGarreau/particles.js/master/particles.json', function() {
            console.log('callback - particles.js config loaded');
        });
    </script>
</body>
</html>