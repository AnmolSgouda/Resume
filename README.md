# Resume
<!DOCTYPE html>
<html>
    <head>
        <title>Resume</title>
        <style>
       .bod{
          height: 95vh;
          width: 800px;
         
          border: 10px solid ;
          border-color:black rgb(26, 20, 20) darkgray black;
          margin:auto;
       }
       .bod h1{
           background-color: rgb(92, 12, 78);
           color: aliceblue;
           text-align: center;
       }
       .bod h2{
           background-color: darkgray;
       }
       .cont{
           /* display: inline-block; */
           float: right;
           
       }
      .cont ul{
           list-style: none;
       }
       .cont ul li{
           float: left;
           background-color: gray;
        }
        li a{
            display: block;
            text-decoration: none;
            padding: 3px 4px;
        }
        .cont a:hover{
            background-color: orange;
            color: white;
        }
   .child{
       display: none;
   }
   .droupdown:hover
   .child{
       display: block;
   }
   .bb li a{
       font-size: 30px;
       color: blue;
   }
   .bb li a:hover{
      color: chartreuse;
   }
   .oo ol li a{
       font-size: 20px;
       color: blue;
   }
   .oo ol li a:hover{
      color: chartreuse;
   }
    </style>
    </head>
    <body>
        <div class="cont">
        <ul>
            <li class="droupdown" style="width: 103px ;height: 26px; color: blue;font-size: 20px;padding-top: 1px;margin-right: 47px;margin-top: 18px;" >CONTACT
            <div class="child">
                <a href="file:///C:/HTML/mini%20project%20attachment.html" target="_blank">Number</a>
                <a href="file:///C:/HTML/mini%20project%20attachment.html" target="_blank">Email</a>
                <a href="file:///C:/HTML/mini%20project%20attachment.html" target="_blank"> Adress</a>
        </div>
        </li>
        </ul>
    </div>
           <div class="bod">
               <div class="pic">
               <img src="ds.png"style= "height: 40px;float:right ;padding:38px 10px" >
            </div>
            <br>
            <h1 >Anmol S Gouda</h1>
            <br>
            <br>
            <p><b><i>"Eager to contribute sucess through hardwork and always motivated to learn,grow and excel in my field"</i></b></p>
            <h2>TECHNICAL SKILLS</h2>
            <ul><b>
                <li>Programming Languages: C,C++,Java,Python</li>
                <li>Technology : HTML,CSS,Js</li></b>
            </ul>
            <h2>EDUCATION</h2>
            <table border='5'  cell spacing='2' style="width: 100%;">
                <tr>
                    <th><b>YEAR</b></th>
                    <th><b>STANDARD</b></th>
                    <th><b>COLLEGE</b></th>   
                </tr>
                <tr>
                    <th>2018-2022</th>
                    <th>Bachelor of Technology</th>
                    <th>NMAM Institute of tec</th>
                </tr>
                <tr>
                    <th>2016-2018</th>
                    <th>Class XII:Bipc</th>
                    <th>St.Josephs COLLEGE</th>
                </tr>
                <tr>
                    <th>2015-2016</th>
                    <th>Class X</th>
                    <th>St.Josephs school</th>
                </tr>
            </table>
            <div class="bb">
            <h2>MY PROFILE</h2>
            <ul>
                <li><a href="https://www.linkedin.com" target="_blank">LINKEDIN</a> </li>
                <li><a href="https://git-scm.com" target="_blank">GIT_LINK</a></li>
            </ul>
        </div>
        <h2>PROJECTS</h2>
        <div class="oo" >
            <ol type="I">
               <li>  <a href="new.html" target="_blank"> REGISTRATION FORM</a></li>
               <li>  <a href="LogniPage.html" target="_blank"> LOGIN FORM</a></li>
            </ol>
        </div>
           </div>
         
    </body>
</html>
