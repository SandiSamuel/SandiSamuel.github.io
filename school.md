---
layout: default
title: School
group: "navigation"
---
<head>

    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="description" content="">
    <meta name="author" content="">

    <title>Blog Home - Start Bootstrap Template</title>

    <!-- Bootstrap Core CSS -->
    <link href="css/bootstrap.min.css" rel="stylesheet">

    <!-- Custom CSS -->
    <link href="css/blog-home.css" rel="stylesheet">

    <!-- HTML5 Shim and Respond.js IE8 support of HTML5 elements and media queries -->
    <!-- WARNING: Respond.js doesn't work if you view the page via file:// -->
    <!--[if lt IE 9]>
        <script src="https://oss.maxcdn.com/libs/html5shiv/3.7.0/html5shiv.js"></script>
        <script src="https://oss.maxcdn.com/libs/respond.js/1.4.2/respond.min.js"></script>
    <![endif]-->

</head>

<body>

    <!-- Page Content -->
    <div class="container">

        <div class="row">

            <div class="col-md-8">

            <div class="w3-content w3-section" style="max-width:500px">
              <img class="mySlides" src="https://www.nsu.edu/Assets/design/websites/campus-visitors/web-graphics/bookstore.png" style="width:100%">
              <img class="mySlides" src="https://niccs.us-cert.gov/sites/default/files/images/ce_landing_cybercorps_1.png" style="width:100%">
              <img class="mySlides" src="https://scontent-sjc2-1.xx.fbcdn.net/v/t1.0-9/16196036_10209741923239673_551987663875285424_n.jpg?oh=06ad6913b9f9b77edd0daff178d8fae9&oe=5908E9F3" style="width:100%">
              <img class="mySlides" src="http://ww1.prweb.com/prfiles/2015/02/20/12533783/HackU3.png" style="width:100%">
            </div>

            <script>
            var myIndex = 0;
            carousel();

            function carousel() {
                var i;
                var x = document.getElementsByClassName("mySlides");
                for (i = 0; i < x.length; i++) {
                   x[i].style.display = "none";
                }
                myIndex++;
                if (myIndex > x.length) {myIndex = 1}
                x[myIndex-1].style.display = "block";
                setTimeout(carousel, 4000); // Change image every 4 seconds
            }
            </script>






                <h1 class="page-header">
                    Norfolk State University
                    <img class="img-responsive" src="https://upload.wikimedia.org/wikipedia/en/f/f1/Norfolk_State_University_logo.png" width="150">
                    <!-- <img src="https://www.nsu.edu/Assets/design/websites/campus-visitors/web-graphics/bookstore.png" alt="..." /> -->

                </h1>


                <h2>
                    Graduation
                </h2>
                <p class="lead"> Master of Science in Computer Science, GPA 3.8 May 6, 2017</p>
                <p class="lead"> Bachelor of Science in Computer Science Information Assurance, GPA 3.8 May 9, 2015</p>
                <hr>
                <img src="https://scontent-sjc2-1.xx.fbcdn.net/v/t1.0-9/16196036_10209741923239673_551987663875285424_n.jpg?oh=06ad6913b9f9b77edd0daff178d8fae9&oe=5908E9F3" width= "300">
                <img src="https://scontent-sjc2-1.xx.fbcdn.net/v/t1.0-9/16196036_10209741923239673_551987663875285424_n.jpg?oh=06ad6913b9f9b77edd0daff178d8fae9&oe=5908E9F3" width= "300">
                <hr>


                <!-- Second Blog Post -->
                <h2>
                    <a href="https://www.nsu.edu/cset/csetgraduate/ia/index">Norfolk State University's IA REDI</a>
                </h2>
                <p class="lead">
                    Information Assurance Research, Education, and Development Institute
                </p>
                <p><span class="glyphicon glyphicon-time"></span> All the research that I conducted at NSU was done under the supervision of this Center of Excelence.</p>
                <hr>

                <h4> Network Intrusion Detection: Insider Attack Repository </h4> <p style="font-size:130%;"> Fall 2014 - Spring 2015</p>
                <p>
                    At NSU I developed a repository that consists of common methods used to perform an insider attack  <br/>
                    within a network and the evidence left behind when using Nmap, Wireshark and Metasploit to perform <br/>
                    and trace the attack.
                </p>
                <br/>
                <h4> Network Security Test Bed </h4> <p style="font-size:130%;"> Spring 2014 </p>
                <p>
                    At NSU I developed a Network test bed for both the Linux and Microsoft Windows environment were <br/>
                    the servers in the network test bed provided the functionality of servers in a real network. <br/>
                    This network was used for penetration testing, firewall configuration, ethical hacking, and <br/>
                    to safely deploy and configure tools such as Metasploit, Kali Linux,and Nessus vulnerability scanner. <br/>
                </p>
                <br/>
                <h4> Password Cracking with an Enhanced Word List </h4> <p style="font-size:130%;"> Fall 2013 </p>
                <p>
                    As a student under the National Science Foundation Scholarship for Service, I worked in a team <br/>
                    were we programmed an enhanced wordlist for password cracking. My responsibility in the team was to <br/>
                    combine everyone's code into one program, in addition to programming my share of algorithms <br/>
                    to crack an eight charater password with letters,numbers, and special charaters.
                </p>
                <hr>
                <h2>
                    Clubs and Activities
                </h2>
                <ul>
                    <li><a href="https://www.nsf.gov/funding/pgm_summ.jsp?pims_id=504991">National Science Foundation Scholar</a> Fall 2013 - Fall 2016</li>
                    <li><a href="https://www.acm.org"> Association for Computing Machinery (ACM)</a> Fall 2012 - Spring 2016</li>
                    <li><a href="https://www.nsu.edu/cset/csetgraduate/ia/index-old-2014">Information Assurance Club</a> Fall 2012 - Spring 2016</li>
                    <li><a href="https://www.nsu.edu/cset/csetgraduate/ia/index-old-2014">Cyber Security Club</a> Fall 2014 - Spring 2016</li>
                    <li><a href="https://www.nsu.edu/cset/csetgraduate/ia/outreach">Voulenteer Instructor at local High Schhol's Cyber Security Club</a> Fall 2016 - Spring 2017</li>
                    <li><a href="http://hackathon.dominionenterprises.com">Participant in Dominion Enterprise Hackathon</a> Fall 2013 - Fall 2016</li>
                    <li><a href="https://www.youtube.com/watch?v=D7byqUtUj8M&list=PLWD6fDSwwBzwcHFnsqW0S3hh8DfGObEyY&index=1">Participant in Sandia National Laboratory TRACER FIRE</a> June 2013</li>
                    <li><a href="https://www.llnl.gov/news/cyber-defenders-boot-camp-prepares-students-mission-critical-roles-wake-opm-breach">Participant in Lawrence Livermore National Laboratory Capture the Flag Competition </a> Summer 2015 & 2016</li>
                    <li><a href="https://energy.gov/videos/make-energy-bay-area-maker-faire">Volunteer for the Department of Energy at the 2016 Maker Faire</a> May 2016</li>


                </ul>

                <hr>
                <img class="img-responsive" src="https://niccs.us-cert.gov/sites/default/files/images/ce_landing_cybercorps_1.png" width= "300" alt="">
                <img class="img-rounded" src="https://scontent.xx.fbcdn.net/v/t1.0-9/16266080_10209765057498015_1451756851237599845_n.jpg?oh=269f03bf39a57517d1f0053fbb90ba1a&oe=58FFD945" width="200">
                <img class="img-responsive" src="http://ww1.prweb.com/prfiles/2015/02/20/12533783/HackU3.png" width= "400" alt="">

                <hr>


<h3 id="grades"><a href="">Undergraduate Classes and Grades</a></h3>

<table border="1" frame="box" width="100%" class="table">
  <tr>
    <td>
      <table>
        <tr>
          <td>When</td><td>Class</td><td width="300">Description</td><td>Grade</td><td>Units</td>
          </tr><tr>
          <td>S 12</td><td>CSC 150</td><td>Computer Literacy</td><td>A</td><td>3</td>
          </tr><tr>
          <td>F 12</td><td>CSC 170L</td><td>Computer Programming Lab 1</td><td>B</td><td>1</td>
          </tr><tr>
          <td>F 12</td><td>CSC 170</td><td>Computer Programming</td><td>A</td><td>3</td>
          </tr><tr>
          <td>S 13</td><td>CSC 260L</td><td>Computer Programming Lab 2</td><td>A</td><td>1</td>
          </tr><tr>
          <td>S 13</td><td>CSC 260</td><td>Computer Programming 2</td><td>A</td><td>3</td>
          </tr><tr>
          <td>F 13</td><td>CSC 435</td><td>Computer Security 1</td><td>A</td><td>3</td>
        </tr>
      </table>
      </td><td nowrap="nowrap">
      <table>
        <tr>
          <td>When</td><td>Class</td><td width="300">Description</td><td>Grade</td><td>Units</td>
          </tr><tr>
          <td>F 13</td><td>CSC 101</td><td>Intro to Computer Sci</td><td>P</td><td>1</td>
          </tr><tr>
          <td>S 14</td><td>CSC 492</td><td>Independent Study</td><td>A</td><td>3</td>
          </tr><tr>
          <td>S 14</td><td>CSC 380</td><td>Software Engineering</td><td>B+</td><td>3</td>
          </tr><tr>
          <td>S 14</td><td>CSC 295</td><td>Java Programming</td><td>A</td><td>3</td>
          </tr><tr>
          <td>S 14</td><td>CSC 292</td><td>Unix/C Programming</td><td>A</td><td>3</td>
          </tr><tr>
          <td>SMR 14</td><td>CSC 455</td><td>Mgmt of Information Security</td><td>A</td><td>3</td>
        </tr>
      </table>
    </td>
    </tr><tr>
    <td nowrap="nowrap">
      <table>
        <tr>
          <td>When</td><td>Class</td><td width="300">Description</td><td>Grade</td><td>Units</td>
          </tr><tr>
          <td>F 14</td><td>CSC 498</td><td>Computer Sci Seminar</td><td>A</td><td>1</td>
          </tr><tr>
          <td>F 14</td><td>CSC 468</td><td>Computer Architect</td><td>A</td><td>3</td>
          </tr><tr>
          <td>F 14</td><td>CSC 464</td><td>Operating Systems</td><td>A</td><td>3</td>
          </tr><tr>
          <td>F 14</td><td>CSC 445</td><td>Computer Network Defence</td><td>A</td><td>3</td>
          </tr><tr>
          <td>F 14</td><td>CSC 430</td><td>Data Communication</td><td>A</td><td>3</td>
          </tr><tr>
          <td>F 14</td><td>CSC 268</td><td>Computer Organization</td><td>A</td><td>3</td>
        </tr>
      </table>
      </td><td nowrap="nowrap">
      <table>
        <tr>
          <td>When</td><td>Class</td><td width="300">Description</td><td>Grade</td><td>Units</td>
          </tr><tr>
          <td>S 15</td><td>CSC 499</td><td>Computer Sci Seminar 2</td><td>A</td><td>2</td>
          </tr><tr>
          <td>S 15</td><td>CSC 420</td><td>Database Principles and Design</td><td>A</td><td>3</td>
          </tr><tr>
          <td>S 12</td><td>CSC 361</td><td>Survey of Program Lang</td><td>A</td><td>3</td>
          </tr><tr>
          <td>&nbsp; </td><td>&nbsp; </td><td>&nbsp; </td><td>&nbsp; </td><td>&nbsp; </td>
          </tr><tr>
          <td>&nbsp; </td><td>&nbsp; </td><td>&nbsp; </td><td>&nbsp; </td><td>&nbsp; </td>
          </tr><tr>
          <td>&nbsp; </td><td>&nbsp; </td><td>&nbsp; </td><td>&nbsp; </td><td>&nbsp; </td>
        </tr>
      </table>
    </td>
  </tr>
</table>



            </div>

        </div>
        <!-- /.row -->

        <hr>

    </div>
    <!-- /.container -->

    <!-- jQuery -->
    <script src="js/jquery.js"></script>

    <!-- Bootstrap Core JavaScript -->
    <script src="js/bootstrap.min.js"></script>
