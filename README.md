
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>College of Science and Technology</title>
    <link rel="stylesheet" href="style.css">
    <link rel="icon" type="final/x-icon" href="c:\Users\lenovo\Desktop\final\icon.JPG">

   <style>
        body {
            font-family: 'Roboto', sans-serif;
        }

        ul {
            list-style-type: none;
            margin: 0;
            padding: 0;
            overflow: hidden;
            background-color: #00008B;
        }

        ul li {
            float: left;
        }

        ul li a, .dropbtn {
            display: inline-block;
            color: white;
            text-align: center;
            padding: 14px 16px;
            text-decoration: none;
        }

        ul li a:hover, .dropdown:hover .dropbtn {
            background-color: #111;
        }

        ul li.dropdown {
            display: inline-block;
        }

        .dropdown-content {
            display: none;
            position: absolute;
            background-color: #f9f9f9;
            min-width: 160px;
            z-index: 1;
        }

        .dropdown-content a {
            color: black;
            padding: 12px 16px;
            text-decoration: none;
            display: block;
            text-align: left;
        }

        .dropdown-content a:hover {
            background-color: #ddd;
        }

        .dropdown:hover .dropdown-content {
            display: block;
        }

        p {
            margin: 20px;
        }

        h2 {
            text-align: center;
        }

        div.gallery {
            border: 3px solid yellow;
        }

        div.gallery:hover {
            border: 3px solid gold;
        }

        div.gallery img {
            width: 100%;
            height: auto;
        }

        div.desc {
            padding: 10px;
            text-align: center;
        }

        * {
            box-sizing: border-box;
        }

        .responsive {
            padding: 0 6px;
            float: left;
            width: 24.9999%;
        }

        @media only screen and (max-width: 700px) {
            .responsive {
                width: 49.9999%;
                margin: 6px 0;
            }
        }

        .clearfix::after {
            content: "";
            display: table;
            clear: both;
        }
    </style>
</head>
<body>
    <div>
        <marquee bahavior="slide" direction="left" scrollamount="8">
          <img src="c:\Users\lenovo\Desktop\final\banner.JPG" alt="Final" style="width:100%">
        </marquee>
    </div>
  <ul>
        <li><a href="index.html">Home</a></li>
        <li><a href="news.html" target="_blank">News</a></li>
        <li><a href="faculty.html" target="_blank">Faculty Members</a></li>
        <li><a href="training.html" target="_blank">Professional Training</a></li>
        <li><a href="videos.html" target="_blank">Videos CoST</a></li>
        <li class="dropdown">
            <a href="javascript:void(0)" class="dropbtn">Bachelor Programs</a>
            <div class="dropdown-content">
                <a href="IT.html" target="_blank">Information Technology <span style="font-style: italic; color: blue;">since 2003</span></a>
                <a href="CS.html" target="_blank">Computer Science <span style="font-style: italic; color: blue;">since 2003</span></a>
                <a href="ETC.html" target="_blank">Electronics and Telecommunication <span style="font-style: italic; color: blue;">since 2003</span></a>
                <a href="GDM.html" target="_blank">Graphic Design and Multimedia <span style="font-style: italic; color: red;">New 2026</span></a>
                <a href="BMIT.html" target="_blank">Business Management Information Technology <span style="font-style: italic; color: red;">New 2026</span></a>
                <a href="NECS.html" target="_blank">Network Engineering and Cyber Security <span style="font-style: italic; color: red;">New 2026</span></a>
                <a href="DSAI.html" target="_blank">Data Science and Artificial Intelligence <span style="font-style: italic; color: red;">New 2026</span></a>

   </div>
        </li>
        <li class="dropdown">
            <a href="javascript:void(0)" class="dropbtn">Computer Labs</a>
            <div class="dropdown-content">
                <a href="Lab1.html" target="_blank">Multimedia Lab</a>
                <a href="Lab2.html" target="_blank">E-learning Lab</a>
                <a href="Lab3.html" target="_blank">Networking Lab</a>
                <a href="Lab4.html">IT Center Lab</a>
            </div>
        </li>
    </ul>
    <p>
        ស្វាគមន៍មកកាន់មហាវិទ្យាល័យវិទ្យាសាស្ត្រ និងបច្ចេកវិទ្យានៃសាកលវិទ្យាល័យកម្ពុជា។ សម្រាប់ប្អូនៗសិស្សានុសិស្ស ដែលមានបំណងចង់បន្តការសិក្សាថ្នាក់បរិញ្ញាបត្ររង និងថ្នាក់បរិញ្ញាបត្រ។ សូមចុះឈ្មោះជាមួយយើងឥឡូវនេះ ឬអាចអញ្ជើញមកកាន់សាកលវិទ្យាល័យផ្ទាល់ក៏បាន។
    </p>
    <p>
        Welcome to College of Science and Technology of The University of Cambodia. For everyone who wishes to pursue any AA and BA degrees of the study programs, please register now or visit the campus of The University of Cambodia.
    </p>

  <div style="text-align:center">
        <h2>Studying Activities in CoST</h2>
    </div>
  <div class="responsive">
        <div class="gallery">
            <a target="_blank" href="c:\Users\lenovo\Desktop\final\a.JPG">
                <img src="c:\Users\lenovo\Desktop\final\a.JPG" alt="Cinque Terre" width="600" height="400">
            </a>
            <div class="desc">Web Development-HTML CSS</div>
        </div>
    </div>

 <div class="responsive">
        <div class="gallery">
            <a target="_blank" href="c:\Users\lenovo\Desktop\final\b.JPG">
                <img src="c:\Users\lenovo\Desktop\final\b.JPG" alt="Forest" width="600" height="400">
            </a>
            <div class="desc">Studying Multimedia Lab</div>
        </div>
    </div>
    <div class="responsive">
        <div class="gallery">
            <a target="_blank" href="c:\Users\lenovo\Desktop\final\c.JPG">
                <img src="c:\Users\lenovo\Desktop\final\c.JPG" alt="Northern Lights" width="600" height="400">
            </a>
            <div class="desc">Studying IT Center Lab</div>
        </div>
    </div>

  <div class="responsive">
        <div class="gallery">
            <a target="_blank" href="c:\Users\lenovo\Desktop\final\d.JPG">
                <img src="c:\Users\lenovo\Desktop\final\d.JPG" alt="Mountains" width="600" height="400">
            </a>
            <div class="desc">Graduation</div>
        </div>
    </div>
     <div class="clearfix"></div>

  <div class="container">
        <span onclick="this.parentElement.style.display='none'" class="closebtn">&times;</span>
        <img id="expandedImg" style="width:100%">
        <div id="imgtext"></div>
    <div>
    <h2 style="color:white; background-color:darkblue;">
        <marquee behavior="scroll" direction="right" scrollamount="6">
            <img src="c:\Users\lenovo\Desktop\final\cost.JPG" alt="final" style="width:130px; height:50px;">
            ស្វាគមន៍! IT EXPERT College Science and Technology
        </marquee>
    </h2>
    </div>

   <div style="text-align:center">
    <h2>Computer Labs College CoST</h2>
    </div>

   <div class="responsive">
        <div class="gallery">
            <a target="_blank" href="c:\Users\lenovo\Desktop\final\e.JPG">
                <img src="c:\Users\lenovo\Desktop\final\e.JPG" alt="Cinque Terre" width="600" height="400">
            </a>
            <div class="desc">Multimedia Lab</div>
        </div>
    </div>

   <div class="responsive">
        <div class="gallery">
            <a target="_blank" href="c:\Users\lenovo\Desktop\final\f.JPG">
                <img src="c:\Users\lenovo\Desktop\final\f.JPG" alt="Forest" width="600" height="400">
            </a>
            <div class="desc">Networking Lab</div>
        </div>
    </div>
    
   <div class="responsive">
        <div class="gallery">
            <a target="_blank" href="c:\Users\lenovo\Desktop\final\g.JPG">
                <img src="c:\Users\lenovo\Desktop\final\g.JPG" alt="Northern Lights" width="600" height="400">
            </a>
            <div class="desc">IT-Center Lab</div>
        </div>
    </div>

   <div class="responsive">
        <div class="gallery">
            <a target="_blank" href="c:\Users\lenovo\Desktop\final\h.JPG">
                <img src="c:\Users\lenovo\Desktop\final\h.JPG" alt="Mountains" width="600" height="400">
            </a>
            <div class="desc">IT-Center Lab</div>
        </div>
    </div>
<div class="clearfix"></div>

<footer>
<div style="background-color: #00008B; color: white; text-align: center; padding: 10px;">
    <img src="c:\Users\lenovo\Desktop\final\uc.png" alt="University Logo" style="width: 50px; height: auto; display: block; margin: 0 auto 10px;">
    <h5 style="margin: 0;">Copyright &copy; University of Cambodia</h5>
</div>
</footer>

