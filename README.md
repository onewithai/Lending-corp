<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>The Lending Corporation Client App</title>
    <link href="https://fonts.googleapis.com/css2?family=Open+Sans:wght@300;400;600&display=swap" rel="stylesheet">
    <style>
        /* General Body Styles */
        body {
            font-family: 'Open Sans', Arial, sans-serif; /* Using Google Font */
            line-height: 1.7; /* Slightly increased line height for readability */
            margin: 0;
            padding: 0;
            background-color: #f8f8f8; /* Lighter background */
            color: #333;
            -webkit-font-smoothing: antialiased; /* Better font rendering */
            -moz-osx-font-smoothing: grayscale;
        }

        /* Container for content */
        .container {
            width: 90%; /* Slightly wider for modern screens */
            max-width: 960px; /* Max width to prevent content from stretching too wide */
            margin: auto;
            overflow: hidden;
            padding: 30px 0; /* More padding top/bottom */
        }

        /* Header Styles */
        header {
            background: #2c3e50; /* Darker, more professional header */
            color: #fff;
            padding: 1.5rem 0;
            text-align: center;
            box-shadow: 0 4px 8px rgba(0,0,0,0.1); /* Subtle shadow */
        }
        header h1 {
            margin: 0;
            font-size: 2.8em; /* Larger heading */
            letter-spacing: 1px; /* Slight letter spacing */
        }
        header p {
            font-size: 1.1em;
            opacity: 0.9; /* Slightly faded subtitle */
        }

        /* Section Styles */
        .section {
            background: #fff;
            padding: 30px; /* More internal padding */
            margin-bottom: 25px; /* More space between sections */
            border-radius: 10px; /* More rounded corners */
            box-shadow: 0 4px 15px rgba(0,0,0,0.08); /* More pronounced shadow */
            border-top: 5px solid #3498db; /* A distinct top border */
        }
        h2 {
            color: #3498db; /* Brighter blue for headings */
            font-size: 2.2em;
            margin-bottom: 20px;
            border-bottom: 2px solid #eee; /* Underline for headings */
            padding-bottom: 10px;
        }
        p {
            font-size: 1.05em;
            margin-bottom: 15px;
        }

        /* Loan Options List Styles */
        ul {
            list-style: none;
            padding: 0;
        }
        ul li {
            background: #ffffff; /* White background for list items */
            margin-bottom: 15px;
            padding: 20px;
            border-left: 6px solid #3498db; /* Thicker left border */
            border-radius: 8px; /* Rounded corners for list items */
            box-shadow: 0 2px 8px rgba(0,0,0,0.05); /* Subtle shadow for items */
            transition: transform 0.2s ease-in-out, box-shadow 0.2s ease-in-out; /* Smooth transition for hover */
        }
        ul li:hover {
            transform: translateY(-5px); /* Lift effect on hover */
            box-shadow: 0 6px 20px rgba(0,0,0,0.1); /* More shadow on hover */
        }
        ul li h3 {
            color: #2c3e50; /* Darker heading for list items */
            margin-top: 0;
            font-size: 1.6em;
            margin-bottom: 10px;
        }
        ul li p {
            font-size: 0.95em;
            line-height: 1.5;
            color: #555;
        }

        /* Contact Info Styles */
        .contact-info p {
            margin: 10px 0; /* More spacing for contact lines */
            font-size: 1.1em;
        }
        .contact-info a {
            color: #3498db; /* Link color */
            text-decoration: none; /* No underline by default */
            font-weight: 600;
            transition: color 0.2s ease-in-out;
        }
        .contact-info a:hover {
            color: #2980b9; /* Darker blue on hover */
            text-decoration: underline;
        }
        /* Style for the website link as a button */
        .contact-info .website-link-button {
            display: inline-block; /* Allows padding and margin */
            background-color: #3498db; /* Button background */
            color: #fff; /* Button text color */
            padding: 12px 25px; /* Padding for button */
            border-radius: 5px; /* Rounded button corners */
            text-decoration: none; /* No underline */
            margin-top: 15px;
            transition: background-color 0.3s ease, transform 0.2s ease;
        }
        .contact-info .website-link-button:hover {
            background-color: #2980b9; /* Darker on hover */
            transform: translateY(-2px); /* Slight lift */
            text-decoration: none; /* Ensure no underline on hover */
        }

        /* Footer Styles */
        footer {
            text-align: center;
            padding: 25px;
            background: #2c3e50; /* Matches header background */
            color: #fff;
            margin-top: 30px; /* Space above footer */
            font-size: 0.9em;
        }
    </style>
</head>
<body>
    <header>
        <div class="container">
            <h1>The Lending Corporation</h1>
            <p>Your Partner in Financial Solutions</p>
        </div>
    </header>

    <div class="container">
        <section class="section">
            <h2>Our Loan Options</h2>
            <p>Explore the diverse range of financial solutions tailored to your needs, whether you're looking for a residential loan, commercial financing, or specialized programs.</p>
            <ul>
                <li>
                    <h3>Residential Loans</h3>
                    <p>Helping individuals find the best loan for their personal needs, including conventional, self-employed, and foreign national programs.</p>
                </li>
                <li>
                    <h3>Commercial Loans</h3>
                    <p>Facilitating improvements and helping businesses get operations running smoothly.</p>
                </li>
                <li>
                    <h3>Real Estate Broker & Builder Partnerships</h3>
                    <p>Assisting real estate brokers and their clients with the loan process, and partnering with builders to finance new homes.</p>
                </li>
                <li>
                    <h3>Specialized Programs</h3>
                    <p>Including venture capital, asset depletion program, jumbo/super jumbo loans, non-warrantable condo financing, and investor programs.</p>
                </li>
            </ul>
        </section>

        <section class="section contact-info">
            <h2>Contact Us</h2>
            <p>Reach out to us for quick and easy loan processing, flexible closing, and 24/7 customer support.</p>
            <p><strong>Website:</strong> <a href="http://www.thelendingcorporation.com" target="_blank" class="website-link-button">Visit Our Website</a></p>
            <p><strong>General Inquiries:</strong> [Insert General Inquiry Email/Phone Number Here]</p>
            <p><strong>Loan Officer Support:</strong> [Insert Loan Officer Support Email/Phone Number Here]</p>
        </section>
    </div>

    <footer>
        <div class="container">
            <p>&copy; 2025 The Lending Corporation. All rights reserved.</p>
        </div>
    </footer>
</body>
</html>
