
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">

    <title>Royal Data Solutions | Data Analytics & Business Intelligence</title>

    <meta name="description"
        content="Royal Data Solutions helps businesses turn data into clear insights and better decisions.">

    <style>
        * {
            margin: 0;
            padding: 0;
            box-sizing: border-box;
        }

        body {
            font-family: Arial, sans-serif;
            line-height: 1.6;
            color: #222;
            background: #f5f7fa;
        }

        header {
            background: #0b1f3a;
            color: white;
            padding: 20px 8%;
            display: flex;
            justify-content: space-between;
            align-items: center;
            position: sticky;
            top: 0;
            z-index: 1000;
        }

        .logo {
            font-size: 24px;
            font-weight: bold;
        }

        nav a {
            color: white;
            text-decoration: none;
            margin-left: 25px;
            font-weight: bold;
        }

        nav a:hover {
            color: #4da3ff;
        }

        .hero {
            background: #0b1f3a;
            color: white;
            min-height: 600px;
            display: flex;
            align-items: center;
            padding: 70px 8%;
        }

        .hero-content {
            max-width: 750px;
        }

        .hero h1 {
            font-size: 55px;
            margin-bottom: 20px;
        }

        .hero h2 {
            font-size: 28px;
            color: #4da3ff;
            margin-bottom: 20px;
        }

        .hero p {
            font-size: 20px;
            margin-bottom: 30px;
        }

        .button {
            display: inline-block;
            background: #4da3ff;
            color: white;
            padding: 14px 25px;
            border-radius: 5px;
            text-decoration: none;
            font-weight: bold;
        }

        .button:hover {
            background: #2d82d4;
        }

        section {
            padding: 70px 8%;
        }

        .section-title {
            text-align: center;
            font-size: 35px;
            margin-bottom: 40px;
            color: #0b1f3a;
        }

        .services {
            display: grid;
            grid-template-columns: repeat(3, 1fr);
            gap: 25px;
        }

        .service-card {
            background: white;
            padding: 30px;
            border-radius: 10px;
            box-shadow: 0 4px 15px rgba(0, 0, 0, 0.08);
        }

        .service-card h3 {
            color: #0b1f3a;
            margin-bottom: 15px;
        }

        .about {
            background: white;
            text-align: center;
        }

        .about p {
            max-width: 800px;
            margin: auto;
            font-size: 18px;
        }

        .contact {
            background: #0b1f3a;
            color: white;
            text-align: center;
        }

        .contact .section-title {
            color: white;
        }

        footer {
            background: #061426;
            color: white;
            text-align: center;
            padding: 25px;
        }

        @media (max-width: 768px) {

            header {
                flex-direction: column;
                gap: 15px;
            }

            nav a {
                margin: 0 8px;
                font-size: 14px;
            }

            .hero {
                min-height: 500px;
            }

            .hero h1 {
                font-size: 40px;
            }

            .hero h2 {
                font-size: 23px;
            }

            .hero p {
                font-size: 17px;
            }

            .services {
                grid-template-columns: 1fr;
            }
        }
    </style>
</head>

<body>

    <!-- Navigation -->

    <header>

        <div class="logo">
            Royal Data Solutions
        </div>

        <nav>
            <a href="#home">Home</a>
            <a href="#services">Services</a>
            <a href="#about">About</a>
            <a href="#contact">Contact</a>
        </nav>

    </header>


    <!-- Hero Section -->

    <section class="hero" id="home">

        <div class="hero-content">

            <h1>Royal Data Solutions</h1>

            <h2>Turning Data Into Better Decisions</h2>

            <p>
                We help businesses transform their data into clear,
                meaningful insights that support smarter decisions,
                improve performance and drive growth.
            </p>

            <a href="#contact" class="button">
                Work With Us
            </a>

        </div>

    </section>


    <!-- Services -->

    <section id="services">

        <h2 class="section-title">
            Our Services
        </h2>
<div class="service-card">

    <h3>Python Data Analysis</h3>

    <p>
        We use Python to clean, analyse and explore datasets,
        helping businesses uncover patterns, trends and useful insights.
    </p>

</div>
        <div class="services">

            <div class="service-card">

                <h3>Excel Data Analysis</h3>

                <p>
                    We analyse business data using Excel and create
                    clear reports that help businesses understand
                    their performance.
                </p>

            </div>


            <div class="service-card">

                <h3>Power BI Dashboards</h3>

                <p>
                    We create interactive Power BI dashboards that
                    turn complex data into easy-to-understand
                    visual reports.
                </p>

            </div>


            <div class="service-card">

                <h3>SQL & Database Analysis</h3>

                <p>
                    We use SQL to organise, analyse and extract
                    useful information from business databases.
                </p>

            </div>


            <div class="service-card">

                <h3>Business Intelligence</h3>

                <p>
                    We help businesses discover trends, measure
                    performance and make data-driven decisions.
                </p>

            </div>


            <div class="service-card">

                <h3>Data Visualization</h3>

                <p>
                    We turn numbers and complex datasets into
                    simple visualisations that are easy to understand.
                </p>

            </div>


            <div class="service-card">

                <h3>Business Reports</h3>

                <p>
                    We create professional analytical reports that
                    help business owners understand what their data
                    is telling them.
                </p>

            </div>

        </div>

    </section>


    <!-- About -->

    <section class="about" id="about">

        <h2 class="section-title">
            About Royal Data Solutions
        </h2>

        <p>
            Royal Data Solutions is a data analytics and business
            intelligence company focused on helping organisations
            understand their data and make better decisions.
        </p>

        <br>

        <p>
            We combine data analysis, visualisation and technology
            to transform raw information into useful business insights.
        </p>

    </section>


    <!-- Contact -->

    <section class="contact" id="contact">

        <h2 class="section-title">
            Let's Work Together
        </h2>

        <p>
            Do you have business data that needs to be analysed?
        </p>

        <br>

        <p>
            Email: royaldatasolutions@gmail.com
        </p>

        <br>

        <a href="mailto:royaldatasolutions@gmail.com" class="button">
            Contact Us
        </a>

    </section>


    <!-- Footer -->

    <footer>

        <p>
            © 2026 Royal Data Solutions. All Rights Reserved.
        </p>

    </footer>

</body>

</html> 
