
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>bcrec</title>
    <style>
        .LOGO {
            position: absolute;
            top: 0px;
            left: 100px
        }

        .TEL {
            position: absolute;
            top: 0px;
            right: 100px;
        }

        .ALL {
            position: absolute;
            background-color: rgb(254, 254, 254);
            width: 1500px;
            height: 40px;
            top: 100px;
            border-radius: 10px;
            box-shadow: 5px 5px 5px 5px rgb(68, 25, 211);
            color: rgb(0, 0, 0);
            background-image: linear-gradient(rgb(255, 255, 255), rgb(36, 19, 189));
        }

        .HOME {
            position: absolute;
            top: 10px;
            left: 30px;
            float: left;
        }

        .ABOUT {
            position: absolute;
            left: 90px;
            top: 10px;
            float: left;
        }

        .INSIDE {
            position: absolute;
            background-color: rgb(212, 212, 212);
            color: rgb(0, 0, 0);
            font-size: 10px;
            border-style: solid;
            border-width: 5px;
            border-color: rgb(152, 204, 201);
            width: 150px;
            height: 200px;
            top: 20px;
            z-index: 1;
            display: none;

        }

        .ABOUT:hover .INSIDE {
            display: block;
            transition: 2s;
        }

        .DEPARTMENT {
            position: absolute;
            float: left;
            left: 190px;
            top: 10px;
        }

        .COURSE {
            position: absolute;
            float: left;
            left: 300px;
            top: 10px;
        }

        .FACULTY {
            position: absolute;
            float: left;
            left: 370px;
            top: 10px;
        }

        .INSIDE {
            position: absolute;
            background-color: rgb(212, 212, 212);
            color: rgb(0, 0, 0);
            font-size: 10px;
            border-style: solid;
            border-width: 5px;
            border-color: rgb(152, 204, 201);
            width: 150px;
            height: 200px;
            top: 20px;
            z-index: 1;
            display: none;
        }

        .FACULTY:hover .INSIDE {
            display: block;
            transition: 2s;
        }

        .R_and_D {
            position: absolute;
            float: left;
            left: 450px;
            top: 10px;
        }

        .MOU {
            position: absolute;
            float: left;
            left: 500px;
            top: 10px;
        }

        .IQAC {
            position: absolute;
            float: left;
            left: 560px;
            top: 10px;
        }

        .inside_iqac {
            position: absolute;
            background-color: rgb(212, 212, 212);
            color: rgb(0, 0, 0);
            font-size: 10px;
            border-style: solid;
            border-width: 5px;
            border-color: rgb(152, 204, 201);
            width: 150px;
            height: 130px;
            top: 20px;
            z-index: 1;
            display: none;
        }

        .IQAC:hover .inside_iqac {
            display: block;
        }

        .placement {
            position: absolute;
            float: left;
            left: 610px;
            top: 10px
        }

        .inside_placement {
            position: absolute;
            background-color: rgb(212, 212, 212);
            color: rgb(0, 0, 0);
            font-size: 10px;
            border-style: solid;
            border-width: 5px;
            border-color: rgb(152, 204, 201);
            width: 150px;
            height: 60px;
            top: 20px;
            z-index: 1;
            display: none;
        }

        .placement:hover .inside_placement {
            display: block;
        }

        .Approval {
            position: absolute;
            float: left;
            left: 720px;
            top: 10px
        }

        .inside_approval {
            position: absolute;
            background-color: rgb(212, 212, 212);
            color: rgb(0, 0, 0);
            font-size: 10px;
            border-style: solid;
            border-width: 5px;
            border-color: rgb(152, 204, 201);
            width: 150px;
            height: 130px;
            top: 20px;
            z-index: 1;
            display: none;
        }

        .Approval:hover .inside_approval {
            display: block;
        }

        .ACHIVEMENT {
            position: absolute;
            float: left;
            left: 820px;
            top: 10px
        }

        .inside_achivement {
            position: absolute;
            background-color: rgb(212, 212, 212);
            color: rgb(0, 0, 0);
            font-size: 10px;
            border-style: solid;
            border-width: 5px;
            border-color: rgb(152, 204, 201);
            width: 150px;
            height: 130px;
            top: 20px;
            z-index: 1;
            display: none;
        }

        .ACHIVEMENT:hover .inside_achivement {
            display: block;
        }

        .admission {
            position: absolute;
            float: left;
            left: 940px;
            top: 10px
        }

        .NRF23 {
            position: absolute;
            float: left;
            left: 1060px;
            top: 10px
        }

        .insideNRF23 {
            position: absolute;
            background-color: rgb(212, 212, 212);
            color: rgb(0, 0, 0);
            font-size: 10px;
            border-style: solid;
            border-width: 5px;
            border-color: rgb(152, 204, 201);
            width: 150px;
            height: 130px;
            top: 20px;
            z-index: 1;
            display: none;
        }

        .NRF23:hover .insideNRF23 {
            display: block;
        }

        .NOTICE {
            position: absolute;
            float: left;
            left: 1120px;
            top: 10px
        }

        .FEEDBACK {
            position: absolute;
            float: left;
            left: 1200px;
            top: 10px
        }

        .CONTACT {
            position: absolute;
            float: left;
            left: 1300px;
            top: 10px
        }

        .image {
            position: absolute;
            left: 250px;
            top: 200px;
        }

        .rec {
            position: absolute;
            left: 100px;
            top: 800px;
            z-index: 1;
        }

        .line {
            position: relative;
            left: 200px;
            right: 50px;
            top: 800px;
            width: 900px;
            background-color: blue;
        }

        .box {
            position: absolute;
            height: 900px;
            top: 850px;
            width: 300px;
            border: 2%;

            left: 100px;
            background-color: rgb(215, 212, 212);
            border-radius: 5px;
        }

        .add {
            background-color: aqua;
            border-radius: 5px;
        }

        .box2 {
            position: absolute;
            top: 850px;
            left: 420px;

        }

        .midline {
            position: absolute;
            top: 1170px;
            left: 420px;
        }

        .pinline {
            position: absolute;
            top: 1250px;
            left: 420px;
            background-color: rgb(127, 196, 196);
            border: 2px;
            border-radius: 4px;
            border-color: black;
            border-width: 2px;
        }

        .addline {
            position: absolute;
            top: 1320px;
            left: 370px;
            border: 2px;
            border-radius: 4px;
            border-color: black;
            border-width: 2px;
        }

        .downline {
            position: absolute;
            top: 1400px;
            left: 420px;
            background-color: rgb(127, 196, 196);
            border: 2px;
            border-radius: 4px;
            border-color: black;
            border-width: 2px;
        }

        .alumni {
            position: absolute;
            top: 1460px;
            left: 420px;
        }

        .text2 {
            position: absolute;
            text-size-adjust: 40px;
            border: double;
            border-color: black;
        }

        .thirdrow {
            position: absolute;
            top: 840px;
            left: 700px;
            width: 250px;
            height: 50px;
        }

        #A {
            position: absolute;
            top: 1060px;
            left: 750px;
            background-color: rgb(171, 171, 232);
            border-radius: 10px;
        }

        #B {
            position: absolute;
            top: 1080px;
            left: 770px;
            background-color: rgb(171, 171, 232);
            border-radius: 10px;
        }

        #C {
            position: absolute;
            top: 1100px;
            left: 720px;
            background-color: rgb(171, 171, 232);
            border-radius: 10px;
        }

        #D {
            position: absolute;
            top: 1120px;
            left: 745px;
            background-color: rgb(171, 171, 232);
            border-radius: 10px;
        }

        #E {
            position: absolute;
            top: 1140px;
            left: 730px;
            background-color: palevioletred;
            border-radius: 10PX;
        }

        #F {
            position: absolute;
            top: 1160px;
            left: 710px;
            background-color: palevioletred;
            border-radius: 10PX;
        }

        #G {
            position: relative;
            top: 1145px;
            left: 70px;
            width: 270px;
        }

        #H {
            position: relative;
            top: 1070px;
            left: 70px;
            width: 270px;

        }

        .text {
            position: absolute;
            top: 1200px;
            left: 690px;
            width: 270px;
        }

        .text1 {
            position: absolute;
            top: 1250px;
            left: 690px;
            width: 270px;
            border: 2PX;
            border: double;
        }

        .student {
            position: absolute;
            top: 1500px;
            left: 690px;
            width: 270px;
        }

        .online {
            background-color: pink;
        }

        .lastrow {
            position: absolute;
            top: 850px;
            left: 990px;
            background-color: azure;
        }

        .bottom {
            position: absolute;
            top: 2000px;
            left: 250px;
            background-color: rgb(95, 95, 217);
            width: 1000px;
            height: 200px;
            border-radius: 10px;
        }

        .a {
            color: rgb(0, 0, 0);
        }

        .name1 {
            position: absolute;
            left: 1108px;
            top: 808px;
            width: 200px;
            height: 22px;
            background-color: blue;
        }
        .img1{
            position: absolute;
            left: 1108px;
            top: 0px;
            width: 10px;
            height: 10px;
        }
    </style>
</head>

<body>
    <center>
        <div class="LOGO">
            <img src="logo-cap-8-N.jpg" alt="">
        </div>
        <div class="TEL">
            Tel: +91-343-2504106,2501353 <br>
            Mob: +91-6297128554 <br>
            Fax: +91-343-2504059,2503424 <br>
            Mail: info@bcrec.ac.in <br>
        </div>
    </center>
    <div class="ALL">
        <a href="https://bcrec.ac.in/bcrec_old/" target="_blank">
            <div class="HOME">HOME <b>|</b></div>
        </a>
        <div class="ABOUT">ABOUT US <b>|</b>

            <div class="INSIDE">
                <a href="BCREC_SOCIETY_STRUCTURE_PRESENT.pdf" target="_blank">
                    <p>BOARD OF TRUSTERS
                        <hr>
                    </p>
                </a>
                <a href="BCREC_BOG_STRUCTURE_PRESENT.pdf" target="_blank">
                    <p>BOARD OF GOVERNER
                        <hr>
                    </p>
                </a>
                <a href="">
                    <P>MINUTER OF MEETING
                        <hr>
                    </P>
                </a>
                <a href="BCREC_STRATEGIC_PLAN.pdf" target="_blank">
                    <P>STATEGIC PLAN
                        <hr>
                    </P>
                </a>
                <a href="BCREC_BEST_PRACTICES.pdf" target="_blank">
                    <P>BEST PRACTISE
                        <hr>
                    </P>
                </a>
                <a href="BCREC_DISTINCTIVENESS.pdf" target="_blank">
                    <P>INTITUTIONAL DISTINGUSNESS</P>
                </a>
            </div>
        </div>
        <a href="https://bcrec.ac.in/bcrec_old/dept_ce_NAAC.htm">
            <div class="DEPARTMENT">DEPARTMENT <b>|</b>
            </div>
        </a>
        <a href="https://bcrec.ac.in/bcrec_old/courses.htm">
            <div class="COURSE">COURSE <b>|</b></div>
        </a>
        <div class="FACULTY">FACULTY <b>|</b>
            <div class="INSIDE">
                <a href="BCREC_FACULTY.pdf" target="_blank">
                    <p>list
                        <hr>
                    </p>
                </a>
                <a href="BCREC_SERVICE_RULES.pdf" target="_blank">
                    <p>Code of Conduct</p>
                </a>
            </div>
        </div>
        <a href="BCREC_R&D.pdf" target="_blank">
            <div class="R_and_D">R&D <b>|</b></div>
        </a>
        <a href="BCREC_MOU.pdf" target="_blank">
            <div class="MOU">MOU <b>|</b>
            </div>
        </a>
        <div class="IQAC">IQAC <b>|</b>
            <div class="inside_iqac">
                <a href="BCREC_IQAC_WEB_DOCUMENT.pdf" target="_blank">
                    <p>About</p>
                </a>
                <hr>
                <a href="BCREC_IQAC_COMPOSITION.pdf" target="_blank">
                    <p>Composition</p>
                </a>
                <hr>
                <a href="BCREC_IQAC_MEETINGS.pdf" target="_blank">
                    <p>Meeting</p>
                </a>
                <hr>
                <a href="BCREC_IQAC_REPORT.pdf" target="_blank">
                    <p>Report</p>
                </a>
            </div>
        </div>
        <div class="placement">PLACEMENT <b>|</b>
            <div class="inside_placement">
                <a href="BCREC_TRAINING.pdf" target="_blank">
                    <p>TRANING</p>
                </a>
                <hr>
                <a href="BCREC_PLACEMENT_INFORMATION.pdf" target="_blank">
                    <p>PLACEMENT INFORMATION</p>
                </a>
            </div>
        </div>
        <div class="Approval">APPROVAL <b>|</b>
            <div class="inside_approval">
                <a href="BCREC_AICTE_APPROVAL.pdf" target="_blank">
                    <p>AICTE
                        <hr>
                    </p>
                </a>
                <a href="https://srv15-bcrec.in/vc/Approval/BCREC_UNIVERSITY(MAKAUT).pdf" target="_blank">
                    <p>UNIVERSITY(MAKAUT)
                        <hr>
                    </p>
                </a>
                <a href="BCREC_WEB_NBA.pdf" target="_blank">
                    <p>NBA
                        <hr>
                    </p>
                </a>
                <a href="https://bcrec.ac.in/bcrec_old/NAAC_Approval.pdf" target="_blank">
                    <p>NNAC</p>
                </a>
            </div>
        </div>
        <div class="ACHIVEMENT">ACHIVEMENT <b>|</b>
            <div class="inside_achivement">
                <a href="BCREC_PROGRESSION.pdf" target="_blank">
                    <p>POGRESSION
                        <hr>
                    </p>
                </a>
                <a href="BCREC_SPORTS.pdf">
                    <p>SPORTS
                        <hr>
                    </p>
                </a>
                <a href="BCREC_LOCAL_CHAPTER.pdf">
                    <p>LOCAL CHAPTER
                        <hr>
                    </p>
                </a>
                <a href="BCREC_AWARD_ACCOLADES.pdf">
                    <p>AWARD AND ACCLOADS
                        <hr>
                    </p>
                </a>
            </div>
        </div>
        <div class="admission">
            <a href="https://bcrec.ac.in/bcrec_old/admission.htm" target="_blank">ADDMISSION <b>|</b></a>
        </div>
        <div class="NRF23">NRF23 <b>|</b>
            <div class="insideNRF23">
                <a href="https://bcrec.ac.in/bcrec_old/NIRF-1.pdf" target="_blank">
                    <p>ENGENERRING
                        <hr>
                    </p>
                </a>
                <a href="https://bcrec.ac.in/bcrec_old/NIRF-3.pdf" target="_blank">
                    <p>OVERALL
                        <hr>
                    </p>
                </a>
            </div>
        </div>
        <div class="NOTICE">
            <a href="https://bcrec.ac.in/bcrec_old/noticeboard.htm">NOTICE <b>|</b></a>
        </div>
        <div class="FEEDBACK">
            <a href="https://bcrec.ac.in/bcrec_old/feedback.html">FEEDBACK <b>|</b></a>
        </div>
        <div class="CONTACT">
            <a href="https://bcrec.ac.in/bcrec_old/contact.htm">CONTACT</a>
        </div>
    </div>
    <div class="image">
        <img src="images.jpg" width="1000px" height="600px">
    </div>
    <div class="rec">
        <img src="recruiter1.jpg" alt="">
    </div>
    <div class="line">
        <div>
            <CEnter>

                <marquee behavior="scroll" direction="left">TCS, WIPRO, HP, INFOSYS, CAPGEMINI, MAHINDRA SATYAM, ATOS,
                    MICROSOFT, PPL, BOSCH, HUAWEI, VOITH PAPER, IOT, TIL, GODREJ, L&T, ITD CEM, SEW, PIAGGIO, SANMAR,
                    SYNTEL
            </CEnter>
            </marquee>
        </div>
    </div>
    <div class="name1">
        <div>
            <a href="https://bcrec.ac.in/bcrec_old/student-corner.html"><font color="red"> <b>|</b>__STUDENT CORNER</font></a>
        </div>
    </div>
    <div class="box">
        <ul>
            <li>NIRF Ranking 2022 (201-250)</li>
            <li>NBA Accredited Courses CSE, ECE, IT, EE, ME</li>
            <li>Accredited with 'B+' Grade by NAAC w.e.f. 13/09/2021</li>
            <li>Estd. August,2000</li>
            <li>Currently Offering B.Tech in nine engineering disciplines</li>
            <li>Separate FMS offering programmes</li>
            <li>Separate MCA Dept. offering MCA programmes</li>
            <li>M.Tech programme offered by ECE, EE, CSE, ME</li>
            <li>Central Library</li>
            <li>Fully equipped language lab( in collaboration with IIT, Kgp.)</li>
            <li>Multi Gym</li>
            <li>Separate hostel for boys and girls</li>
            <li>ATM and Banking facility in campus</li>
        </ul>
        <center>
            <a href="https://bcrec.ac.in/bcrec_old/mba.htm"><img src="MBA200x1234.png" width="250px"></a><br>
            <img src="50th.png" width="250px">
            <p>
                <font><b>Call for Admission :</b></font> 9333928874/ 9832131164/ 9932245570 / 9434250472
            </p>
            <div class="add">
                <p>
                    <font><b>Any Query related to payment</b></font><br>
                    contact Accounts Department
                    BCREC and BCRECAPC
                    Mobile: 7001380141 / Phone - 0343-2501353 extn. 278
                    Email : accounts@bcrec.ac.in
                </p>
            </div>
            <font><b>MOU between BCREC and CAMBRIDGE MARKETING COLLEGE, UK </b></font>
        </center>
    </div>
    <div class="box2">
        <font color="red"><b><u>PLACEMENTS</u></b></font><br>
        <center>
            <a href="https://bcrec.ac.in/bcrec_old/placement.htm"><img src="p5.jpg" alt=""></a><br>
            <img src="maxresdefault.jpg" width="250px">
        </center>
    </div>
    <div class="midline">
        <ul>
            <li>Placement 2021 | 2022 | 2023 </li>
            <a href="MBAPlacement.pdf">
                <li>MBA placement</li>
            </a>
            <a href="PlacementNotice.pdf">
                <li>placement notice</li>
            </a>
        </ul>
    </div>
    <div class="pinline">
        <ul>
            <a href="https://bcrec.ac.in/bcrec_old/principaldesk.htm">
                <li>From Principle desk</li>
            </a>
            <a href="https://bcrec.ac.in/bcrec_old/gsdesk.htm">
                <li>From Genaral seceratary desk</li>
            </a>
        </ul>
    </div>
    <div class="addline">
        <ul>
            <hr>
            <p>BCREC Mail Already signed up? <a
                    href="https://accounts.google.com/v3/signin/identifier?continue=https%3A%2F%2Fmail.google.com%2Fmail%2F&hd=bcrec.ac.in&osid=1&sacu=1&service=mail&flowName=GlifWebSignIn&flowEntry=AddSession&dsh=S-419318759%3A1720885888624339&ddm=0">Login</a>
            </p>
            <hr>
        </ul>
    </div>
    <div class="downline">
        <p>visit : Dr. B.C.Roy Polytechnic,<br>
            URL:<a href="https://www.bcrp.ac.in/" target="_blank"> www.bcrp.ac.in</a>
        </p>
    </div>
    <div class="alumni">
        <ul type="square">
            <a href="https://docs.google.com/forms/d/1kbOSvh1Aaj-cI-k3a-gpLecSDl50zBcB9bjTBCm_lgg/edit" target="_blank">
                <li><b>BCREC</b>Alumani Registration</li>
            </a>
            <a href="https://www.bcrecalumni.org/" target="_blank">
                <li><b>BCREC</b>Alumani</li>
            </a>
            <a href="https://bcrec.net.in/alumni.html">
                <li>Our Flipbook -2020 Passout</li>
            </a>
            <li>
                <font color="blue"><b>ELEVTROQUEAST</b></font><i> 3rd Edition</i>
            </li>
            <div>
                <a href="https://mesiicon.in/" target="_blank">
                    <li>IEEE confence mesiicon 2022</li>
                </a>
            </div>
        </ul>
        <img src="Horizon23.jpeg" width="250px">
        <div class="text2">
            <p>
                <center>
                    <a href="Civiloholic.pdf" target="_blank">Civiloholic e-Magazine of Civil Engineering Department</a>
                    <br>
                    ------------------ <br>
                    <a href="https://bcrec.ac.in/bcrec_old/#">e-Magazine: MECH THINK of Mechanical Engineering
                        Department</a> <br>
                </center>
            </p>
        </div>
    </div>
    <div class="thirdrow">
        <p>NEWS AND EVENTS</p>
        <marquee behavior="" direction="up" onmouseover="this.stop();" onmouseout="this.start();" height="150px">
            <font color="red">
                <a href="AntiRagging_helpline.pdf">Anti Ragging Help Line</a> <br><br>
                <a href="AICTE-IDEA Lab-1st-BCREC.pdf">BCREC Secures FIRST POSITION in AICTE-Idea Labs Network</a>
                <br><br>
                <a href="https://www.youtube.com/watch?v=tkKn84s6tEE">Placement video 2023</a> <br><br>
                <a href="irf22.pdf">BCREC in NIRF Ranking 2022</a> <br><br>
                <a href="https://bcrec.ac.in/bcrec_old/#">NBA Accredited Courses CSE, ECE, IT, EE, ME</a> <br> <br>
                <a href="AICTE-IDEA.pdf">BCREC WINS PRESTIGIOUS AICTE-IDEA LAB PROJECT</a> <br><br>
                IIT Kharagpur agrees to hand-hold and support BCREC in achieving the goals that NEP-2020 envisagesb
                <br><br>
                <P>BCREC Help Line No : 6297128554</P> <br><br>
                <a href="Workingdays_wef_01042022.pdf">Working days for Dr. B.C. Roy Group of Institutions, Durgapur
                    w.e.f. 1st April, 2022</a>
                <a href="Online_payment_procedure.pdf">Online Payment Procedure</a>
            </font>
        </marquee>
        <hr>
    </div>
    <center>
        <div>
            <div id="A">
                <a href="https://srv15-bcrec.in/idealab/" class="a"> <font>AICTE IDEA LAB</font></a>
            </div>
            <div id="B">
                <a href="https://bcrec.ac.in/bcrec_old/iic-bcrec.htm" class="a">
                    <font>IIC-BCREC</font>
                </a>
            </div>
            <div id="C">
                <a href="https://srv15-bcrec.in/vc/repository/bcrec-repo.pdf" class="a">
                    <font>BCREC-DATA REPOSITORY</font>
                </a>
            </div>
            <div id="D">
                <a href="https://srv15-bcrec.in/vc/repository/bcrec-repo.pdf" class="a">
                    <font>ADMISSION QUERY</font>
                </a>
            </div>
            <div id="E">
                <a href="https://bcrecdgp.ac.in/erp/Forms/frmStudentLoginBcrp.aspx" class="a">PAY FEE ONLINE BCREC</a>
            </div>
            <div id="F">
                <a href="https://bcrecdgp.ac.in/erp/Forms/frmStudentLoginBcrp.aspx" class="a">PAY FEE ONLINE BCREC APC</a>
            </div>
            <div id="G">
                <hr>
            </div>
            <div id="H">
                <hr> <br>
            </div>
        </div>
        <div class="text">
            <ul>
                <li>Registration No BCREC 2021-22 </li>
            </ul>
        </div>
        <div>
            <div class="text1">
                <ul>
                    <li>Students are hereby advised to deposit their semester fee within 31st July, 2023 :</li> <br>
                    <li> Academic Calendar for Even Semester (January 2023 to June 2023) </li> <br>
                    <li>Academic Calendar (July 2023 to June 2024) <br> </li>
                </ul>
            </div>
        </div>
        <div class="student">
            <ul type="square">
                <li>Student's Corner: <a href="https://bcrec.ac.in/bcrec_old/NOC.pdf">NOC FormNOC</a><a
                        href="https://bcrec.ac.in/bcrec_old/NOC_BCREC_APC.pdf"> BCREC APC</a> |<a
                        href="https://bcrec.ac.in/bcrec_old/wbscc.pdf"> WBSCC</a></li>
                <li>Student's Corner: <a href="https://bcrec.ac.in/bcrec_old/anti-ragging_measures.pdf">Anti-Ragging
                        Committee</a> | <a href="https://www.antiragging.in/">Online Anti-Ragging</a></li>
                <li><a href="https://bcrec.ac.in/bcrec_old/free_seats.pdf">WBFS</a> (Free Seats)</li>
                <li><a href="https://bcrec.ac.in/bcrec_old/hostel.htm"> Hostel Facilities</a> | <a
                        href="https://bcrec.ac.in/bcrec_old/Hostel_Rules_Book.pdf">Hostel Rules</a></li>
                <li> <a href="https://bcrec.ac.in/bcrec_old/Newadmission.pdf">Advertisement Admission 2023</a></li>
                <li>
                    <font color="red"> NEWSLETTER (Vol. 3, Issue 1)</font>
                </li>

            </ul>
            <br><br>

            <p>visit: Dr. B.C.Roy College of Pharmacy & Allied Health Sciences, URL: <a
                    href="https://www.bcrcp.ac.in/">www.bcrcp.ac.in </a>| <a
                    href="https://www.bcrcp.ac.in/">www.bcrcp.org</a></p>
            <div class="online">
                <p> <a href="https://bcrecdgp.ac.in/admission/Forms/frmLoginNew.aspx">ONLINE ADMISSION APC</a></p>
            </div>
            <video controls src="https://youtu.be/9Kx22rJ024o?si=wnpSJbKuE8dFn5Hn" type="vedio/mp4"></video>
        </div>
        <div class="lastrow">
            <div>
                +
                <font color="red"><b>DISCLOSURES</b></font>
            </div>
            <div>
                <ul>
                    <li>

                        <a href="https://bcrec.ac.in/bcrec_old/AICTE_MANDATORY_DISCLOSURE.pdf" class="a">Mandatory Disclosures</a>
                    </li>
                    <li> <a href="https://bcrec.ac.in/bcrec_old/anti-ragging_measures.pdf" class="a">Anti-Ragging Measures</a>
                    </li>
                    <li> <a href="https://bcrec.ac.in/bcrec_old/EOA2023-2024.pdf"class="a">AICTE Approval'23</a>
                    </li>
                    <li> <a href="https://bcrec.ac.in/bcrec_old/MAKUT_Appv.pdf"class="a">MAKAUT Approval'23</a>
                    </li>
                    <li> <a href="https://bcrec.ac.in/bcrec_old/NAAC_SSR.pdf"class="a">NAAC SSR</a>
                    </li>
                    <li> <a href="https://bcrec.ac.in/bcrec_old/NAAC_AQAR.pdf"class="a">NAAC AQAR</a>
                    </li>
                    <li> <a href="https://bcrec.ac.in/bcrec_old/NAAC-AQAR-2021-22.pdf"class="a">NAAC AQAR 2021-22</a>
                    </li>
                    <li> <a href="https://bcrec.ac.in/bcrec_old/Policy_Scholarship.pdf"class="a">Policy Document Scholarship</a>
                    </li>
                    <li><a href="https://bcrec.ac.in/bcrec_old/Policy_Grn_Env_21.pdf"class="a">Green & Clean Environment</a></li>
                    <li><a href="https://srv15-bcrec.in/vc/Finance/audit-report.pdf"class="a">Audit Reports</a></li>
                </ul>
            </div>
            <div>
                <font color="red"><b>ADMISSION</b></font>
            </div>
            <div>
                <ul>
                    <li><b><a href="https://bcrecdgp.ac.in/admission/Forms/frmLoginNew.aspx">ONLINE ADMISSION</a></b>
                    </li>
                    <li><a href="https://bcrec.ac.in/bcrec_old/admission_details.pdf"class="a">View Admission Details '23</a></li>
                    <li><a href="https://bcrec.ac.in/bcrec_old/OFFERLETTERENGG.pdf"class="a">Offer Letter B.Tech'23</a></li>
                    <li><a href="https://bcrec.ac.in/bcrec_old/OfferLetterLateralBTech.pdf"class="a">Offer Letter B.Tech Lateral'23</a></li>
                    <li><a href="https://bcrec.ac.in/bcrec_old/OfferLetter_MCA.pdf "class="a">Offer Letter MCA'23 </a></li>
                    <li><a href="https://bcrec.ac.in/bcrec_old/mba.htm"class="a">Commencement of MBA'23</a></li>
                    <li><a href="https://bcrec.ac.in/bcrec_old/mtech.pdf"class="a">Commencement of M.Tech'23</a></li>
                </ul>
            </div>
            <div>
                <font color="red"><b>DOWNLOADS</b></font>
            </div>
            <div>
                <ul>
                    <li><a href=""class="a">Brochure'23</a> | Prospectus'23</li>
                    <li><a href=""class="a">Prospectus MBA '22</a></li>
                    <li><a href=""class="a">Prospectus BCRECAPC '22</a></li>
                    <li><a href=""class="a">Fee Structure B.Tech'23 </a></li>
                    <li><a href=""class="a">Fee Structure B.Tech Lat.'23 </a></li>
                    <li><a href=""class="a">Fee Structure MCA'23 </a></li>
                    <li><a href=""class="a">Fee Structure MBA'23</a></li>
                    <li><a href=""class="a">Fee Structure BBA'23</a></li>
                    <li><a href=""class="a">Fee Structure BBA in SC'23</a></li>
                    <li><a href=""class="a">Fee Structure BCA'23 </a></li>
                    <li><a href=""class="a">Fee Structure BOPTOM'23 </a></li>
                    <li><a href=""class="a">Fee Structure B.Sc MLT'23 </a></li>
                    <li><a href=""class="a">Fee Structure Hosp.Mgmt'23 </a></li>
                    <li><a href=""class="a">Fee Structure M.Tech '23 </a></li>
                    <li><a href=""class="a">Affidavit Anti Ragging - Student</a></li>
                    <li><a href=""class="a">Affidavit Anti Ragging - Guardian</a></li>
                </ul>
            </div>
            <div>
                <font color="red"><b> Quick links</b></font>
            </div>
            <div>
                <ul>
                    <li><a href="" class="a"> Dept. of Higher Education, WB</a></li>
                    <li><a href="" class="a">CET Entrance 2022</a></li>
                    <li><a href=""class="a">wbjeeb.in | wbjeeb.nic.in</a></li>
                    <li><a href="" class="a">aicte-india.org | makautexam.net</a></li>
                    <li><a href="" class="a">wbut.ac.in | webscte.co.in</a></li>
                    <li>visit : <a href="" class="a ">Pharmacy & Allied Health Sc.</a></li>
                    <li>visit : <a href="" class="a">Dr. B.C.Roy Polytechnic</a></li>
                    <li><a href="" class="a">AICTE Feedback Form</a></li>
                    <li><a href="" class="a">NPTEL Local Chapter</a></li>
                    <li><a href="" class="a">Spoken Tutorial IIT Bombay Nodal Center</a></li>
                    <li><a href="" class="a">Brain-storming Sessionby VC/MAKAUT</a></li>
                    <li><a href="" class="a">IEEE-NCETSTEA-2020</a></li>
                    <li><a href="" class="a">BCREC Alumni</a></li>
                    <li><a href="" class="a">BCREC Right to Information</a></li>
                    <li><a href="" class="a">Statutory Declaration NAAC</a></li>
                    <li><a href="" class="a">Gender Sensitization Action Plan</a></li>
                    <li><a href="" class="a">Intellectual Property Policy</a></li>
                    <li><a href="" class="a"> BCREC APC</a></li>
                </ul>
            </div>
        </div>
        <div class="bottom">
            <p>
                <a href="https://bcrec.ac.in/bcrec_old/index.htm" class="a">Home </a>| <a
                    href="https://bcrec.ac.in/bcrec_old/about.htm" class="a">About us</a> | <a
                    href="https://bcrec.ac.in/bcrec_old/infrastructure.htm" class="a">Infrastructure </a>|<a
                    href="https://bcrec.ac.in/bcrec_old/courses.htm" class="a">Courses</a> | <a
                    href="https://bcrec.ac.in/bcrec_old/faculty.htm" class="a">Faculty</a> | <a
                    href="https://bcrec.ac.in/bcrec_old/placement.htm" class="a">Placement</a> | <a
                    href="https://bcrec.ac.in/bcrec_old/noticeboard.htm" class="a"> Notices </a>| <a
                    href="https://bcrec.ac.in/bcrec_old/Current_openings.pdf" class="a">Appointments </a>|<a
                    href="https://bcrec.ac.in/bcrec_old/free_seats.pdf" class="a"> WBFS</a> | <a
                    href="https://bcrec.ac.in/bcrec_old/netbanking.pdf" class="a">ePayment</a> | <a
                    href="https://bcrec.ac.in/bcrec_old/publication.pdf" class="a">Publications</a> | <a
                    href="https://bcrec.ac.in/bcrec_old/contact.htm" class="a">Contact u</a>
            </p>
            <p>Disclaimer: All the contents of this site are only for general information or use. BCREC, Durgapur
                excludes any warranty, express or implied, as to the quality, accuracy and completeness of the site.
                BCREC, Durgapur will not be liable for any damages arising from the use of this site.</p> <br>
            <hr><br>
            <p>Copyright 2023 BCREC | Powered by e Pariseva</p>
        </div>
        <!-- <div class="img1">
            <img src="download.jpg" alt="">
        </div> -->
    </center>
</body>

</html>
