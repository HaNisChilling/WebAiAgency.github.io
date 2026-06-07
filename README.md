# WebAiAgency.github.io

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>AI Automation Agency</title>

    <link rel="stylesheet" href="style.css">
</head>
<body>

<header>
    <div class="container">
        <h2>AI Automation Agency</h2>

        <nav>
            <a href="#services">Services</a>
            <a href="#solutions">Solutions</a>
            <a href="#contact">Contact</a>
        </nav>
    </div>
</header>

<section class="hero">
    <div class="container">
        <h1>Automate Your Business With AI</h1>

        <p>
            Save time, reduce costs, and scale operations using
            AI-powered automation workflows.
        </p>

        <a href="#contact" class="btn">
            Book Free Consultation
        </a>
    </div>
</section>

<section id="services">
    <div class="container">
        <h2>Our Services</h2>

        <div class="grid">

            <div class="card">
                <h3>AI Chatbots</h3>
                <p>Customer support and lead qualification.</p>
            </div>

            <div class="card">
                <h3>Workflow Automation</h3>
                <p>n8n automation for repetitive tasks.</p>
            </div>

            <div class="card">
                <h3>CRM Automation</h3>
                <p>Automatically manage customer data.</p>
            </div>

            <div class="card">
                <h3>Invoice Processing</h3>
                <p>AI extraction and document workflows.</p>
            </div>

            <div class="card">
                <h3>Email Automation</h3>
                <p>Lead nurturing and follow-up sequences.</p>
            </div>

            <div class="card">
                <h3>Reporting Dashboards</h3>
                <p>Power BI and automated analytics.</p>
            </div>

        </div>
    </div>
</section>

<section id="solutions">
    <div class="container">
        <h2>How We Help</h2>

        <div class="workflow">
            Lead Capture
            →
            AI Qualification
            →
            CRM Update
            →
            Automated Follow-up
        </div>
    </div>
</section>

<section id="contact">
    <div class="container">

        <h2>Get a Free Consultation</h2>

        <form id="leadForm">

            <input
                type="text"
                id="name"
                placeholder="Your Name"
                required
            >

            <input
                type="email"
                id="email"
                placeholder="Your Email"
                required
            >

            <input
                type="text"
                id="company"
                placeholder="Company Name"
            >

            <textarea
                id="message"
                rows="5"
                placeholder="Tell us about your automation needs"
            ></textarea>

            <button type="submit">
                Submit
            </button>

        </form>

        <div id="status"></div>

    </div>
</section>

<footer>
    <p>© 2026 AI Automation Agency</p>
</footer>

<script src="script.js"></script>

</body>
</html>


*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:Arial, sans-serif;
    color:#333;
    line-height:1.6;
}

.container{
    width:90%;
    max-width:1200px;
    margin:auto;
}

header{
    background:#111;
    color:white;
    padding:20px 0;
}

header .container{
    display:flex;
    justify-content:space-between;
    align-items:center;
}

nav a{
    color:white;
    margin-left:20px;
    text-decoration:none;
}

.hero{
    background:#f4f4f4;
    padding:100px 20px;
    text-align:center;
}

.hero h1{
    font-size:48px;
    margin-bottom:20px;
}

.btn{
    display:inline-block;
    background:#0066ff;
    color:white;
    padding:12px 25px;
    text-decoration:none;
    border-radius:6px;
}

section{
    padding:70px 20px;
}

.grid{
    display:grid;
    grid-template-columns:repeat(auto-fit,minmax(250px,1fr));
    gap:20px;
    margin-top:30px;
}

.card{
    border:1px solid #ddd;
    padding:25px;
    border-radius:10px;
}

.workflow{
    text-align:center;
    font-size:24px;
    margin-top:30px;
}

form{
    max-width:600px;
    margin:auto;
}

input,
textarea{
    width:100%;
    padding:12px;
    margin-bottom:15px;
    border:1px solid #ccc;
}

button{
    width:100%;
    padding:14px;
    background:#0066ff;
    color:white;
    border:none;
    cursor:pointer;
}

button:hover{
    opacity:.9;
}

#status{
    text-align:center;
    margin-top:20px;
}

footer{
    background:#111;
    color:white;
    text-align:center;
    padding:20px;
}
