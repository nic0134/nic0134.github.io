<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Portfolio Resume</title>
<style>
    body {
        margin: 0;
        font-family: Arial, sans-serif;
        background: #dcdcdc;
    }

    .container {
        display: flex;
        width: 95%;
        margin: 20px auto;
        height: 90vh;
        background: #5a5a5a;
    }

    /* Left icon sidebar */
    .sidebar {
        width: 60px;
        background: #005b82;
        display: flex;
        flex-direction: column;
        align-items: center;
        padding-top: 70px;
        gap: 10px;
    }

    .icon {
        width: 40px;
        height: 40px;
        border: 1px solid black;
        background: #0077aa;
        display: flex;
        justify-content: center;
        align-items: center;
        color: white;
        font-size: 20px;
    }

    /* Profile card */
    .profile-card {
        width: 180px;
        background: linear-gradient(#005b82, #000);
        color: white;
        text-align: center;
        padding: 30px 10px;
    }

    .profile-pic {
        width: 120px;
        height: 160px;
        margin: 0 auto 30px;
        border: 2px solid #003f5c;
        display: flex;
        justify-content: center;
        align-items: center;
        color: white;
        background: rgba(255,255,255,0.05);
    }

    .profile-card h2 {
        margin: 10px 0 5px;
        font-size: 22px;
    }

    .profile-card p {
        margin: 5px 0;
        font-size: 14px;
    }

    .links {
        margin-top: 25px;
        text-align: left;
        padding: 0 15px;
    }

    .links a {
        color: white;
        text-decoration: underline;
        display: block;
        margin: 5px 0;
        font-size: 14px;
    }

    /* Main content */
    .main-content {
        flex: 1;
        padding: 30px;
        color: white;
    }

    .main-content h1 {
        text-align: center;
        margin-top: 100px;
        font-size: 40px;
        font-weight: normal;
    }

    .about {
        color: black;
        font-size: 18px;
        margin-bottom: 40px;
    }
</style>
</head>
<body>

<div class="container">

    <div class="sidebar">
        <div class="icon">👤</div>
        <div class="icon">📋</div>
        <div class="icon">📞</div>
        <div class="icon"></div>
    </div>

    <div class="profile-card">
        <div class="profile-pic">INSERT pic of u</div>
        <h2>Nicholas Sayed</h2>
        <p>Cybersecurity</p>
        <p><strong>CONTACT INFO</strong></p>

        <div class="links">
            <a href="#">LinkedIn</a>
            <a href="#">Handshake</a>
        </div>
    </div>

    <div class="main-content">
        <div class="about">
            <p><strong>About me</strong></p>
            <p>Nico Sayed</p>
            <p>Cyber</p>
            <p>From Redmond</p>
        </div>

        <h1>OBJECTIVE</h1>
    </div>

</div>

</body>
</html>
