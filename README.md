# rohitinsocial
<!DOCTYPE html>
<html>

<head>
<meta charset="UTF-8" />
<meta http-equiv-"X-UA-Compatible" content="IE-edge" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />

<title>
Rohit Chavan
</title>

</head>
<script>


         //function that display value 
         function dis(val) 
         { 
             document.getElementById("result").value+=val 
         } 
           
         //function that evaluates the digit and return result 
         function solve() 
         { 
             let x = document.getElementById("result").value 
             let y = eval(x) 
             document.getElementById("result").value = y 
         } 
           
         //function that clear the display 
         function clr() 
         { 
             document.getElementById("result").value = "" 
         } 
      </script> 
      <!-- for styling -->
      <style> 
         .title{ 
         margin-bottom: 10px; 
         text-align:center; 
         width: 210px; 
         color:red; 
         border: solid black 2px; 
         } 
  
         input[type="button"] 
         { 
         background-color:blue; 
         color: black; 
         border: solid black 2px; 
         width:100% 
         } 
  
         input[type="text"] 
         { 
         background-color:white; 
         border: solid black 2px; 
         width:100% 
         } 

      </style> 
<link rel = stylesheet TYPE="css" HREF= stylesheet.css>
   </head> 
   <!-- create table -->



<body BGCOLOR = "SKYBLUE">


<H2><MARQUEE BGCOLOR = "YELLOW"> WELCOME TO HERE ON OFFICIAL SITE OF <B>ROHIT CHAVAN'S</B> SOCIAL MEDIA MANAGEMENT. </MARQUEE></H2>
 <h1><CENTER><FONT COLOR = "RED"> ROHIT RATNAKAR CHAVAN </CENTER></h1>



<P><h3><CENTER><FONT COLOR = "black">Following table indicates the various platform and respective link of Rohit's account.</CENTER></h3></P>
<CENTER>
<TABLE BORDER ='5' WIDTH="600 HIGHT="300" CELLPADDING="20 "CELLPACING="20">
<TR>
<TH COLSPAN=7 BGCOLOR = "navy"><H2><FONT COLOR="GREY">CONNECT WITH <FONT COLOR="RED">'ROHIT'</FONT> ON VARIOUS PLATFORM</FONT></H2></th>
</TR>

<TR BGCOLOR = "green"><FONT COLOR="YELLOW">
<TH><FONT COLOR="YELLOW">YOUTUBE</FONT></TH><TH><FONT COLOR="YELLOW">JOSH APP</TH><TH><FONT COLOR="YELLOW">FACEBOOK</TH><TH><FONT COLOR="YELLOW">INSTAGRAM</TH><TH><FONT COLOR="YELLOW">
TWITTER</TH><TH><FONT COLOR="YELLOW">SNAPCHAT</FONT></TH>
</TR>
<TR>
<TD BGCOLOR = "ORANGE"><ALIGN="RIGHT"><A HREF = "https://youtube.com/channel/UCYpXDu_SuCIzaL1-9ZultNg">GO TO ROHITREACT.X ON YOUTUBE</A></CENTER></TD>
<TD BGCOLOR = "ORANGE"><A HREF = "https://share.myjosh.in/profile/0165cbfd-0a77-4679-9f62-1436972bfd24?u=0xa05938cb951a5216">ROHIT ON JOSH</a></TD>
<TD BGCOLOR = "ORANGE"><A HREF ="https://www.facebook.com/ratnakar.chavan.1">ROHIT ON FB</A></TD>
<TD BGCOLOR = "ORANGE"><A HREF ="https://instagram.com/ratnakar.chavan.1">ROHIT ON INSTA</A></TD>
<TD BGCOLOR = "ORANGE"><A HREF = "https://mobile.twitter.com/Rohitishere7">ROHIT ON TWITTER</A></TD>
<TD BGCOLOR = "ORANGE">Coming Soon!</TD>
</TR>
</TABLE>
</CENTER>
<HR BGCOLOR="RED">

<p><FONT COLOR="black">Here is the simple calculator made by Us. </p>
<p>You can do your calculation through this calculator.</p>


   
      <div class = title >Rohit technical Calculator</div> 
      <table border="2"> 
         <tr> 
            <td colspan="3"><input type="text" id="result"/></td> 
            <!-- clr() function will call clr to clear all value -->
            <td><input type="button" value="c" onclick="clr()"/> </td> 
         </tr> 
         <tr> 
            <!-- create button and assign value to each button -->
            <!-- dis("1") will call function dis to display value -->
            <td> <input type="button" value="1" onclick="dis('1')"/> </td> 
            <td><input type="button" value="2" onclick="dis('2')"/> </td> 
            <td><input type="button" value="3" onclick="dis('3')"/> </td> 
            <td><input type="button" value="/" onclick="dis('/')"/> </td> 
         </tr> 
         <tr> 
            <td><input type="button" value="4" onclick="dis('4')"/> </td> 
            <td><input type="button" value="5" onclick="dis('5')"/> </td> 
            <td><input type="button" value="6" onclick="dis('6')"/> </td> 
            <td><input type="button" value="-" onclick="dis('-')"/> </td> 
         </tr> 
         <tr> 
            <td><input type="button" value="7" onclick="dis('7')"/> </td> 
            <td><input type="button" value="8" onclick="dis('8')"/> </td> 
            <td><input type="button" value="9" onclick="dis('9')"/> </td> 
            <td><input type="button" value="+" onclick="dis('+')"/> </td> 
         </tr> 
         <tr> 
            <td><input type="button" value="." onclick="dis('.')"/> </td> 
            <td><input type="button" value="0" onclick="dis('0')"/> </td> 
            <!-- solve function call function solve to evaluate value -->
            <td><input type="button" value="=" onclick="solve()"/> </td> 
            <td><input type="button" value="*" onclick="dis('*')"/> </td> 
         </tr> 
      </table> 
<p BGCOLOR="RED"><U> [Note: The Advanced level of Calculater is avaiable on TechCalcy]</U>
</p>


<HR>
<CENTER>
<FORM METHOD="POST" ACTION="mailto:rpchavan188@gmail.com">

<H3><B>"Please provide the given Information:"<B></H3>
 1.Enter Your Name:<INPUT TYPE="text" name="urname" size=6 MAXLENGTH="30">
<BR>
2.Enter Your Email ID:<INPUT TYPE= "text" NAME="age" maxlength="30">
<br>
3.How will you rate this Website?
<BR>
<INPUT TYPE="radio" NAME="rate" VALUE="Superb" CHECKED>Superb 
<INPUT TYPE="radio" NAME="rate" VALUE="Very Good"> Very Good
<INPUT TYPE="radio" NAME="rate" VALUE="Good"> Good
<INPUT TYPE="radio" NAME="rate" VALUE="Average"> Average

<br><BR>
4.Comment/Suggestion:
<br>
<TEXTAREA NAME="comments" ROWS="6" COLS="60" WRAP>
</TEXTAREA>
<P><INPUT TYPE="Submit" VALUE="SUBMIT RESPONSE">
</P>
</CENTER>

</FORM>
<HR><HR>
<PRE>
<CENTER>
<FONT COLOR = "GREEN"><H1>THANK YOU FOR GIVING
 YOUR PRECIOUS TIME</H1>
</CENTER>
</PRE>
<HR><HR>
</body>

</html>
