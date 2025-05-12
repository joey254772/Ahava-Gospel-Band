# Ahava-Gospel-Band
index.html
<!DOCTYPE html>
<head>
    <title>Ahava Gospel Band</title>
     <!--viewport meta tag-->
     <meta name="viewport" content="width=device-width, initial-scale=1.0">
     <link rel="stylesheet" href="style.css">
</head>
<body>
    
    <nav class="navbar">
        <ul>
            <li><a href="#home">Home</a></li>
            <li><a href="#about">About Us</a></li>
            <li><a href="#events">Events</a></li>
            <li><a href="#contact">Contact</a></li>
        </ul>
    </nav>
    

 <!-- Home Section -->
 <section id="home" class="box home-section">
    <h1>Welcome to Our Website where we Spread Love & Hope in Jesus Christ through Music</h1>
    <p>Through the power of music, we create moments of worship, reflection, and joy that resonate deeply with the soul. Our melodies carry messages of hope, love, and renewal, inviting hearts to experience a divine connection.</p>
    </p>

<section id="about" class="content">
    <h2>About Ahava Gospel Band</h2>
    <p>Ahava Gospel Band is a family of love, dedicated to spreading hope through gospel music. Our mission is to inspire, uplift, and unite people through faith-based melodies.</p>
</section>

<div id="more-info">
    <h2> MOTTO/SLOGAN</h2>
    <p>The motto/slogan of the band is Echoes of Grace</p>

    <h3>MISSION OF THE BAND.</h3>
    <p>Our mission is to spread love and hope in Jesus Christ through music.
        We aim to inspire, unite and uplift people from all walks of  life using our songs to share the message of hope, faith, joy, love and redemption.
        </p>

    <h3> VISION OF THE BAND.</h3>
    <p>Our vision is to be a global voice of hope and healing, reaching hearts and communities through music. 
        We aspire to create an environment where the power of gospel music brings people closer to God’s love, ignites transformation and inspires a life of faith,purpose and righteousness.
        </p>

        <section id="scope" class="scope-section">
            <h3 class="scope-title">Scope of Operation</h3>
            <p class="scope-description">The band operates within the following scopes:</p>
            <div class="scope-container">
                <div class="scope-item">
                    <h4>🎶 Ministering through Music</h4>
                    <p>Worship experiences, street worship, and normal Sunday services.</p>
                </div>
                <div class="scope-item">
                    <h4>🏫 High School Ministry</h4>
                    <p>Spreading the word of God to the young generation in high schools.</p>
                </div>
                <div class="scope-item">
                    <h4>❤️ Charity Works</h4>
                    <p>Visiting prisons, hospitals, and children's homes to provide support and hope.</p>
                </div>
                <div class="scope-item">
                    <h4>🌍 Missions</h4>
                    <p>Evangelism, outreach programs, and crusades to spread the gospel.</p>
                </div>
            </div>
        </section>
        
     <p>Join us in worship, ministry, and mission as we share the message of faith, joy, and redemption and Let your voice echo grace. Be part of our journey in ministry!</p>
</div>
</section>


<section id="events" class="events">
    <h2>Upcoming Events</h2>
    <p>We minister through worship sessions, street evangelism, high school outreach, and charity work.</p>

    <div class="event">
        <h3>Sunday Worship Service</h3>
        <p>Date: Every Sunday | Location: Local Church | Time: 10 AM</p>
    </div>

    <div class="event">
        <h3>High School Ministry</h3>
        <p>Date: Monthly | Various Schools | Time: Scheduled per visit</p>
    </div>

    <a href="#contact" class="cta">Book Us for an Event</a>
</section>

<section id="contact" class="contact">
    <h2>Get in Touch</h2>
    <p>Email: <a href="mailto:ahavagospelband@gmail.com">ahavagospelband@gmail.com</a></p>
    <p>Phone: <a href="tel:+254768330067">+254 768 330067</a></p>

    <form>
        <label>Name:</label>
        <input type="text" required>

        <label>Email:</label>
        <input type="email" required>

        <label>Message:</label>
        <textarea required></textarea>

        <button type="submit">Send Message</button>
    </form>
</section>

<footer>
    <p>&copy; 2025 Ahava Gospel Band | All Rights Reserved</p>
</footer>
</body>
</html>

style.css
/* General Styling */
body {
    font-family: "Poppins", sans-serif;
    text-align: center;
    margin: 0;
    padding: 0;
    background-color: lightseagreen
    color: #2c3e50;
}

/* Navbar */
/* Navbar Styling */
.navbar {
    background: #2c3e50;
    padding: 15px;
    text-align: center;
}

.navbar ul {
    list-style: none;
    padding: 0;
    margin: 0;
    display: flex;
    justify-content: center; /* Ensures horizontal alignment */
    gap: 20px; /* Adds spacing between links */
}

.navbar ul li {
    display: inline;
}

.navbar ul li a {
    text-decoration: none;
    color: white;
    font-weight: bold;
    padding: 12px 20px;
    border-radius: 5px;
    background: #e67e22;
    transition: background 0.3s ease-in-out;
}

.navbar ul li a:hover {
    background: #d35400;
}

.navbar {
    background-color: skyblue;
    padding: 15px;
}

.navbar ul {
    list-style: none;
    padding: 0;
}

.navbar ul li {
    display: inline;
    margin: 0 15px;
}

.navbar ul li a {
    text-decoration: none;
    color:black;
    font-weight: bold;
    background: #e67e22;
    padding: 10px 15px;
    border-radius: 5px;
}

/* Home Section */
#home {
    background: url('https://images.pexels.com/photos/1755086/pexels-photo-1755086.jpeg?auto=compress&cs=tinysrgb&w=600') no-repeat center center/cover;
    color: skyblue
    padding: 100px;
}

.home-section h1 {
    font-size: 3em;
}

.home-section p {
    font-size: 1.2em;
    max-width: 80%;
    margin: auto;
}

/* More Info Section */
#more-info {
    background: lightblue;
    padding: 50px;
    border-radius: 10px;
    width: 80%;
    margin: auto;
}

/* Scope Section Styling */
.scope-section {
    background-color: #f5f5f5;
    padding: 50px;
    text-align: center;
    border-radius: 10px;
    width: 80%;
    margin: auto;
}

.scope-title {
    font-size: 2em;
    color: #2c3e50;
    margin-bottom: 10px;
}

.scope-description {
    font-size: 1.2em;
    color: #444;
    margin-bottom: 20px;
}

.scope-container {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    gap: 20px;
}

.scope-item {
    background: white;
    padding: 20px;
    border-radius: 10px;
    width: 250px;
    box-shadow: 2px 2px 10px rgba(0,0,0,0.1);
    transition: transform 0.3s ease-in-out;
}

.scope-item:hover {
    transform: scale(1.05);
}

.scope-item h4 {
    color: #e67e22;
    font-size: 1.5em;
    margin-bottom: 10px;
}

.scope-item p {
    color: #2c3e50;
    font-size: 1.1em;
}

/* About Section */
#about {
    background: url('https://images.pexels.com/photos/1755086/pexels-photo-1755086.jpeg?auto=compress&cs=tinysrgb&w=600') no-repeat center center/cover;
    color: black;
    padding: 80px;
}

/* Events Section */
.events {
    background: #e67e22;
    color: white;
    padding: 80px;
}

.event {
    background: lightblue
    color: #2c3e50;
    padding: 20px;
    margin: 10px auto;
    width: 80%;
    border-radius: 10px;
}

/* Contact Section */
.contact {
    background: #2c3e50;
    color: white;
    padding: 80px;
}

.contact a {
    color: #e67e22;
    text-decoration: none;
}

/* Call-to-Action Buttons */
.cta {
    display: inline-block;
    padding: 10px 20px;
    background:black;
    color: white;
    text-decoration: none;
    font-size: 18px;
    border-radius: 5px;
}

footer {
    background: #2c3e50;
    color: white;
    padding: 20px;
    margin-top: 20px;
}


