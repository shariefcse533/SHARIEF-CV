<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Sharief Shaik - SAP UI5 & Fiori Consultant</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 20px;
      background-color: #f4f4f4;
    }

    header {
      text-align: center;
      padding: 20px;
      background-color: #333;
      color: #fff;
    }

    section {
      margin-bottom: 20px;
      background-color: #fff;
      padding: 20px;
      border-radius: 5px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
    }

    h2 {
      color: #333;
    }

    ul {
      list-style-type: none;
      padding: 0;
    }

    li {
      margin-bottom: 5px;
    }

    .modal {
      display: none;
      position: fixed;
      z-index: 1;
      left: 0;
      top: 0;
      width: 100%;
      height: 100%;
      overflow: auto;
      background-color: rgb(0,0,0);
      background-color: rgba(0,0,0,0.7);
      padding-top: 60px;
    }

    .modal-content {
      background-color: #fefefe;
      margin: 5% auto;
      padding: 20px;
      border: 1px solid #888;
      width: 80%;
    }

    .close {
      color: #aaa;
      float: right;
      font-size: 28px;
      font-weight: bold;
    }

    .close:hover,
    .close:focus {
      color: black;
      text-decoration: none;
      cursor: pointer;
    }
  </style>
</head>
<body>

  <header>
    <h1>Sharief Shaik</h1>
    <p>SAP UI5 & Fiori Consultant</p>
    <p>2 Years of Experience</p>
  </header>

  <section id="contactInfo">
    <h2>Contact Information</h2>
    <ul>
      <li>+91 9491786806</li>
      <li>Nagoorshariefshaik@outlook.com</li>
      <li>Hyderabad, Telangana, India</li>
    </ul>
  </section>

  <section id="education">
    <h2>Education</h2>
    <ul>
      <li>2022 - Completed Graduation in BSc.MPCS from Acharya Nagarjuna University</li>
    </ul>
  </section>

  <section id="languages">
    <h2>Languages</h2>
    <ul>
      <li>English</li>
      <li>Telugu</li>
      <li>Hindi</li>
    </ul>
  </section>

  <section id="interests">
    <h2>Interests</h2>
    <ul>
      <li>Planting</li>
      <li>Sports</li>
      <li>Reading</li>
      <li>Learning New Tech</li>
    </ul>
  </section>

  <section id="skills">
    <h2>Skills</h2>
    <button onclick="openModal()">View Skills</button>

    <div id="skillsModal" class="modal">
      <div class="modal-content">
        <span class="close" onclick="closeModal()">&times;</span>
        <h2>Technical Skills</h2>
        <ul>
          <li>HTML5</li>
          <li>CSS3</li>
          <li>Javascript</li>
          <li>SAP UI5</li>
          <li>Fiori</li>
          <li>OData</li>
          <li>BTP (Business Technology Platform)</li>
        </ul>
      </div>
    </div>
  </section>

  <script>
    function openModal() {
      document.getElementById('skillsModal').style.display = 'block';
    }

    function closeModal() {
      document.getElementById('skillsModal').style.display = 'none';
    }
  </script>

</body>
</html>
