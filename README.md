<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <title>Community Outreach - Powerpuff Style</title>
    <link href="https://fonts.googleapis.com/css2?family=Montserrat:wght@400;700&family=Roboto:wght@400;500&display=swap" rel="stylesheet">
    <link rel="stylesheet" href="css/styles.css">
    <style>
        body {
            font-family: 'Roboto', sans-serif;
            background-color: #fceef5; /* Light pink background */
            color: #333;
            margin: 0;
            padding: 0;
        }

        h1, h2, h3 {
            font-family: 'Montserrat', sans-serif;
            color: #e91e63; /* Powerpuff pink */
        }

        header {
            background-color: #64b5f6; /* Powerpuff blue */
            padding: 20px 0;
            color: white;
            box-shadow: 0 2px 5px rgba(0, 0, 0, 0.2);
        }

        header .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        header .logo {
            width: 100px;
            /* Replace with a powerpuff themed logo */
            background: url('https://scontent.fmnl9-1.fna.fbcdn.net/v/t1.15752-9/480152442_1655060911789271_6832058476989511027_n.jpg?_nc_cat=110&ccb=1-7&_nc_sid=9f807c&_nc_eui2=AeEeNH1YB4NyqqjTGWkMsn5-zou4EVBKOdPOi7gRUEo504GZHT8oO1pTTpeWilYR5qcbUYLxj0Ena_hWoV04av1L&_nc_ohc=yJBrWbiqihEQ7kNvgEtePkX&_nc_oc=AdixpLPMTXKaye5fXRlNKU4jTInKpyadJqfq00WHMgTmrM2tc5_kENIm23iXQwZk2xo&_nc_zt=23&_nc_ht=scontent.fmnl9-1.fna&oh=03_Q7cD1gEBY4gDNARlOrJquIxY__ZKUHS9sWraDFPoxj2z45bU7g&oe=67E3CFF8') no-repeat center center/contain;
            height: 80px;
        }

        nav ul {
            display: flex;
            list-style-type: none;
            gap: 20px;
        }

        nav ul li a {
            color: white;
            font-size: 16px;
            text-decoration: none;
            transition: color 0.3s ease;
        }

        nav ul li a:hover {
            color: #ffc107; /* Powerpuff yellow on hover */
        }

        .hero {
            background: url('https://scontent.fmnl9-4.fna.fbcdn.net/v/t1.15752-9/476600820_3985508991662688_8890333099293520392_n.jpg?stp=dst-jpg_s2048x2048_tt6&_nc_cat=105&ccb=1-7&_nc_sid=9f807c&_nc_eui2=AeHxGBmX3IQCbLtLveMszzisJ3FYJ-rU0O0ncVgn6tTQ7TpxDljweZVbOwDj67wv71XpGcCDDL37edbLhpU_Z0xQ&_nc_ohc=oagtzu-qHBkQ7kNvgFTVK9_&_nc_oc=AdgKroP-VvbfR4Ho_6rpxrHAdzEabh77I_PRbjIp9EZk2bU6bUtLtDjP7uzGY9i2hhU&_nc_zt=23&_nc_ht=scontent.fmnl9-4.fna&oh=03_Q7cD1gGEIRs_kWJHgX9r8j-zGyA8-3p0m2FhZNthupt17t-fNQ&oe=67E3CEC4') no-repeat center center/cover;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        .hero h1 {
            font-size: 48px;
            margin-bottom: 10px;
        }

        .hero p {
            font-size: 24px;
        }

        button {
            padding: 12px 20px;
            background-color: #ffc107; /* Powerpuff yellow */
            color: #333;
            border: none;
            font-size: 18px;
            cursor: pointer;
            border-radius: 5px;
            transition: background-color 0.3s ease;
        }

        button:hover {
            background-color: #fdd835; /* Lighter yellow on hover */
        }

        section {
            padding: 40px 0;
        }

        .about, .contact {
            background-color: #b2ebf2; /* Light blue */
            text-align: center;
        }

        .projects {
            background-color: #fff;
			 background: url('https://scontent.fmnl9-7.fna.fbcdn.net/v/t1.15752-9/480839407_658828466595211_1519963699154902212_n.jpg?_nc_cat=104&ccb=1-7&_nc_sid=9f807c&_nc_eui2=AeGghMnPoE6beN5-DaxukoN06woY8bY6QaDrChjxtjpBoKFQQOHRMbnkDzkVJ_5QVxAyFBn4Qb3F2l6qcjikH_TL&_nc_ohc=VtHdt6lUKIEQ7kNvgGpqjix&_nc_oc=AdiP4x1lKo2zzqWvPzZfOCJ9mikfOpWDpA3mw8oL5vOXf40pfM3H4XFvS58KgjIoCYU&_nc_zt=23&_nc_ht=scontent.fmnl9-7.fna&oh=03_Q7cD1gFbsGLeLJ5kzmhSHGcKd4AgmNFV_S-lFpj9MZM0eJGfNg&oe=67E3F10A') no-repeat center center/cover;
            height: 400px;
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
            text-shadow: 2px 2px 4px rgba(0, 0, 0, 0.5);
        }

        .container {
            max-width: 1200px;
            margin: 0 auto;
            padding: 0 20px;
        }

        .project-card {
            display: flex;
            justify-content: space-between;
            background-color: #f8bbd0; /* Light pink card */
            margin: 20px 0;
            padding: 20px;
            box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
            border-radius: 8px;
			animation-name: blossom;
			animation-duration: 5s;
			animation-iteration-count: infinite;
        }
		
		@keyframes blossom {
		    0% { background-color: lightpink;}
			50% { background-color: #fdd835;}
			100% {background-color: lightblue}
			}

        

        .card-content {
            flex: 1;
            padding-left: 20px;
        }

        .card-content h3 {
            color: #e91e63;
            font-size: 24px;
        }

        .contact ul {
            list-style-type: none;
        }

        .contact ul li {
            font-size: 18px;
            margin-bottom: 10px;
        }

        .contact a {
            color: #64b5f6;
        }

        footer {
            background-color: #81c784; /* Light green footer */
            color: white;
            padding: 20px 0;
            text-align: center;
        }
		
			@keyframes jeonghan {
	    0%{transform: rotate(0deg); background-color: #64b5f6;}
		25%{transform: rotate(20deg); background-color: #BAD8B6;}
		50%{transform: rotate(40deg); background-color: #fceef5;}
		75%{transform: rotate(60deg); background-color: #64b5f6;}
		100%{transform:rotate(100deg); background-color: #BAD8B6;}
	}
	
	    @keyframes choi {
	    0%{transform: rotate(0deg); background-color: #64b5f6;}
		25%{transform: rotate(20deg); background-color: #BAD8B6;}
		50%{transform: rotate(40deg); background-color: #fceef5;}
		75%{transform: rotate(60deg); background-color: #64b5f6;}
		100%{transform:rotate(100deg); background-color: #BAD8B6;}
	}
	
        @keyframes the8 {
	    0%{transform: rotate(0deg); background-color: #64b5f6;}
		25%{transform: rotate(20deg); background-color: #BAD8B6;}
		50%{transform: rotate(40deg); background-color: #fceef5;}
		75%{transform: rotate(60deg); background-color: #64b5f6;}
		100%{transform:rotate(100deg); background-color: #BAD8B6;}
	}  
	
	#hannie {
	   width: 100px;
	   height: 100px;
	   background-color: #8D77AB;
	   transform: translate(300px, 300px);
	   
	   animation-name: jeonghan;
	   animation-duration: 4s;
	   animation-iteration-count: infinite;
	   border-radius: 30%;
	}
	
	#cheol {
	   width: 100px;
	   height: 100px;
	   background-color: #fceef5;
	   transform: translate(320px, 300px);
	   
	   animation-name: choi;
	   animation-duration: 4s;
	   animation-iteration-count: infinite;
	   border-radius: 30%;
	}
	
	#minghao {
	   width: 100px;
	   height: 100px;
	   background-color: #64b5f6;
	   
	   animation-name: the8;
	   animation-duration: 4s;
	   animation-iteration-count: infinite;
	   border-radius: 30%;
	}
		
    </style>
</head>
<body>
    <header>
        <div class="container">
            <div class="logo"></div>
            <nav>
                <ul>
                    <li><a href="#home">Home</a></li>
                    <li><a href="#about">About</a></li>
                    <li><a href="#projects">Projects</a></li>
                    <li><a href="#contact">Contact</a></li>
                </ul>
            </nav>
        </div>
    </header>

    <section id="home" class="hero">
        <div class="hero-content">
            <h1>Welcome to Community Outreach!</h1>
            <p>Making a positive impact in our community!</p>
            <button><a href="#projects" style="color:#333; text-decoration:none;">Get Involved</a></button>
        </div>
    </section>

    <section id="about" class="about">
        <div class="container">
            <h2>About Us</h2>
            <p>We are a group of passionate individuals dedicated to creating lasting change in our community, one mission at a time. Join us and be a hero!</p>
        </div>
    </section>
	
	<section id="han" class="hero">
	        <div id=choi>
            <div id="hannie"></div>  
            <div id="cheol"></div> 
			<div id="minghao"></div> 
			<div id="dk"></div> 
			</div>
    </section>

    <section id="projects" class="projects">
        <div class="container">
            <h2>Our Missions</h2>
            <div class="project-card">
                <img src="images/cleanup.jpg" alt="Community Cleanup">
                <div class="card-content">
                    <h3>Community Cleanup!</h3>
                    <p>Join us for a citywide cleanup event and help us keep our neighborhood clean!</p>
                </div>
            </div>
            <div class="project-card">
                <img src="images/volunteer.jpg" alt="Volunteers Helping">
                <div class="card-content">
                    <h3>Volunteer with Us!</h3>
                    <p>We offer a variety of volunteer roles that help make a difference in the community..</p>
                </div>
            </div>
        </div>
    </section>

    <section id="contact" class="contact">
        <div class="container">
            <h2>Contact Us</h2>
            <p>We'd love to hear from you! Reach out to us with any questions or to get involved.</p>
            <ul>
                <li>Email: info@communityoutreach.org</li>
                <li>Phone: (123) 456-7890 POWER-UP</li>
                <li>Follow us: <a href="https://www.facebook.com/powerpuffgirls" target="_blank">Facebook</a></li>
				<li>Outreach Vid Link: <a href="https://drive.google.com/file/d/15U2NBCjBTCpI3bacGG_NCqGG7WQ0yHwz/view" target="_blank">Video Link</a></li>
            </ul>
        </div>
    </section>

    <footer>
        <div class="container">
            <p> © 2025 Community Outreach. All Rights Reserved.</p>
        </div>
    </footer>
</body>
</html>
