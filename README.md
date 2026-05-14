<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>Senior Civil Engineering Resume</title>

<style>
    * {
        margin: 0;
        padding: 0;
        box-sizing: border-box;
        font-family: Arial, Helvetica, sans-serif;
    }

    body {
        background: #e9ecef;
        display: flex;
        justify-content: center;
        padding: 30px;
    }

    .resume {
        width: 900px;
        display: flex;
        background: white;
        box-shadow: 0 10px 30px rgba(0,0,0,0.1);
    }

    /* LEFT PANEL */
    .left {
        width: 32%;
        background: #1f3b5c;
        color: white;
        padding: 25px;
    }

    .profile {
        text-align: center;
        margin-bottom: 20px;
    }

    .profile img {
        width: 120px;
        height: 120px;
        border-radius: 50%;
        object-fit: cover;
        border: 3px solid white;
    }

    .name {
        font-size: 20px;
        margin-top: 10px;
        font-weight: bold;
    }

    .title {
        font-size: 13px;
        opacity: 0.8;
    }

    .section {
        margin-top: 25px;
    }

    .section h3 {
        font-size: 14px;
        margin-bottom: 10px;
        border-bottom: 1px solid rgba(255,255,255,0.3);
        padding-bottom: 5px;
    }

    .section p, .section li {
        font-size: 12px;
        line-height: 1.6;
        opacity: 0.9;
    }

    ul {
        list-style: none;
    }

    /* RIGHT PANEL */
    .right {
        width: 68%;
        padding: 30px;
    }

    .header h1 {
        font-size: 26px;
        color: #1f3b5c;
    }

    .header h2 {
        font-size: 14px;
        color: gray;
        margin-top: 5px;
    }

    .block {
        margin-top: 25px;
    }

    .block h3 {
        color: #1f3b5c;
        font-size: 16px;
        margin-bottom: 10px;
        border-bottom: 2px solid #1f3b5c;
        padding-bottom: 5px;
    }

    .job {
        margin-bottom: 15px;
    }

    .job-title {
        font-weight: bold;
        color: #333;
    }

    .company {
        font-size: 13px;
        color: gray;
    }

    .desc {
        font-size: 13px;
        margin-top: 5px;
        line-height: 1.6;
        color: #444;
    }

    .badge {
        display: inline-block;
        background: #1f3b5c;
        color: white;
        padding: 3px 8px;
        font-size: 11px;
        border-radius: 5px;
        margin-top: 5px;
    }

</style>
</head>

<body>

<div class="resume">

    <!-- LEFT -->
    <div class="left">

        <div class="profile">
            <img src="profile.jpg" alt="Profile">
            <div class="name">YOUR NAME</div>
            <div class="title">Senior Civil Engineering Associate</div>
        </div>

        <div class="section">
            <h3>ABOUT</h3>
            <p>Highly experienced Civil Engineering professional specializing in Structural Detailing, QA/QC, BOQ, and Project Management with strong field and technical background.</p>
        </div>

        <div class="section">
            <h3>SKILLS</h3>
            <ul>
                <li>AutoCAD 2D/3D</li>
                <li>Structural Detailing</li>
                <li>BOQ / Quantity Surveying</li>
                <li>QA/QC Inspection</li>
                <li>Procore Project Management</li>
                <li>Rebar Scheduling (BBS)</li>
            </ul>
        </div>

        <div class="section">
            <h3>CONTACT</h3>
            <p>📞 +63XXXXXXXXX</p>
            <p>📧 email@example.com</p>
            <p>📍 Quezon City, Philippines</p>
        </div>

    </div>

    <!-- RIGHT -->
    <div class="right">

        <div class="header">
            <h1>YOUR NAME</h1>
            <h2>Structural Detailing Specialist | Project Engineer | OSH SO3 Certified</h2>
        </div>

        <div class="block">
            <h3>PROFESSIONAL SUMMARY</h3>
            <p class="desc">
                Senior Civil Engineering Associate with 10+ years of experience in construction, structural detailing,
                quantity surveying, QA/QC, and project execution for high-rise and infrastructure projects.
            </p>
        </div>

        <div class="block">
            <h3>EXPERIENCE</h3>

            <div class="job">
                <div class="job-title">Structural Drafter / AutoCAD Technical II</div>
                <div class="company">CTIPilipinas, Inc. | 2024 - Present</div>
                <div class="desc">Structural drafting for infrastructure projects following DPWH standards.</div>
            </div>

            <div class="job">
                <div class="job-title">Project Engineer</div>
                <div class="company">Newington Builder Inc. | 2023 - 2024</div>
                <div class="desc">Site execution, manpower coordination, and project scheduling.</div>
            </div>

            <div class="job">
                <div class="job-title">Civil Engineer / Rebar Engineer</div>
                <div class="company">Multiple Companies | 2019 - 2023</div>
                <div class="desc">Quantity take-off, BBS, QA/QC inspection, and cost estimation.</div>
            </div>

        </div>

        <div class="block">
            <h3>CERTIFICATIONS</h3>
            <span class="badge">SO3 Certified</span>
            <span class="badge">Procore Certified</span>
            <span class="badge">AutoCAD Specialist</span>
            <span class="badge">OSH Safety Officer</span>
        </div>

    </div>

</div>

</body>
</html>
