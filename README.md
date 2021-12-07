<!DOCTYPE html>
<html lang="en">
<html>

    <!--
        Design Inspirations
        -------------------------------------------------------------------------
        MAN(1)                        Manual pager utils                        
NAME
       man - an interface to the system reference manuals
SYNOPSIS
       man [man options] [[section] page ...] ...
       man -k [apropos options] regexp ...
       man -K [man options] [section] term ...
       man -f [whatis options] page ...
       man -l [man options] file ...
       man -w|-W [man options] page ...
DESCRIPTION
       man  is  the system's manual pager.  Each page argument given to man is
       normally the name of a program, utility or function.  The  manual  pag.....
     -->
     
	<head>
		<title style="float: left;" >Pavel(1)</title>
		<meta charset="UTF-8">
        <meta name="viewport" content="width=device-width, initial-scale=1.0">
		<style>
			* {
				box-sizing: border-box;
				/* margin: 0;
				padding: 0; */
				/* display: block; */
			}
			body {
				font-family: Source Code Pro, monospace, monospace;
				font-size: 0.9em;
				background-color: silver;
				position: relative;
			}
			div.body-container{
				position: relative;
				
			}
			div.container {
				max-width: 55em;
				margin: auto;
				background-color: #22232A;
				height: 40em;
				/* margin-bottom: 0!important;		 */

				padding-left: 10px;
				padding-right: 10px;
				padding-top: 10px;
				padding-bottom: 10px;
				/* position: absolute; */
			}
			div.topbar {
				color: chartreuse;
				background-color: #656565;
				border-color: lightpink;
				height: 35px;
				max-width: 55em;
				min-width: 55em;
			
				padding: 10px;
				margin: auto;
				padding-left: 15em;

				font-weight: bolder;
				/* position: absolute; */
			}			
			h1, h2, h3, p {
				font-size: 1em;
				margin-top: 0;
				margin-bottom: 0;
			}
			.command, .argument {
				font-weight: bold;
			}
			div.container div h1 {
				font-weight: normal;
			}
			div, p.indented {
				margin-bottom: 1em;
				color: #af7ef0;
			}
			div.section div {
				margin-left: 4em;
				color: white;
			}
			div, p.linked {
				margin-bottom: 1em;
				color: yellowgreen;
			}
			p.indented {
				margin-left: 2em;
			}
			a {
				color: tomato;
				font-weight: bold;
				text-decoration: none;

			}
			div.bang{
				color:skyblue;
				/* font-weight: bold; */
				font-size: 1.1em;
			}

			
		</style>
	</head>
	<body onload="colour()">
		<div class="body-container" >
			<div class="topbar">
				nullpointer@pointer-house:~/home/usr
			</div>		
			<div class="container">	
				<div class="bang">
					<p>[nullpointer@reckless ~]$ man pavel</p>
				</div>
				<div>
					<h1>Pavel(1)</h1>
				</div>
	
				<div class="section">
					<h2>NAME</h2>
					<div>
						<p>Document — Atikur Rahman</p>
					</div>
				</div>
	
				<div class="section">
					<h2>SYNOPSIS</h2>
					<div>
						<p><span class="command"><a href="https://ar-pavel.netlify.app/"> Pavel</a></span> [<span class="argument">options</span>]</p>
					</div>
				</div>
	
				<div class="section">
					<h2>DESCRIPTION</h2>
					<div>
						<p>Competitive Programmer.&thinsp; Develops operations and sometimes operates development.&thinsp; Mainly programs in C++, but has occasional flings with Java, Python, JavaScript, and C.</p>
					</div>
				</div>
	
				<div class="section">
					<h2>OPTIONS</h2>
					<div>
						<h3>--disclaimer</h3>
						<p class="indented">Rolling release.</p>
					</div>
				</div>
	
				<div class="section">
					<h2>ALSO KNOWN AS</h2>
					<div>
						<p>pavel</p>
					</div>
				</div>
	
				<div class="section">
					<h2>ENVIRONMENT VARIABLES</h2>
					<div>
						<h3>HOME</h3>
						<p class="indented">Dhaka, Bangladesh</p>
						<h3>VIRTUAL HOME</h3>
						<p class="linked"><a href="https://github.com/ar-pavel">github</a>(11), <a href="mailto:atikur2667@gmail.com">atikur2667@gmail.com</a>, <a href=https://www.stopstalk.com/user/profile/arpavel> stopstalk</a>(6), <a href="https://www.facebook.com/hibernatingdaemon">facebook</a></a></p>
					</div>
				</div>
	
				<div class="section">
					<h2>SEE ALSO</h2>
					<div>
						<p> <a href="https://ar-pavel.netlify.app/"> Check it out</a>  if a colorful GUI  gives your eyes more comfort.</p>
<!-- 						<p> Update is on the way... </P> -->
					</div>
				</div>
				<span class="bang" >
					<div style="float:left; color:skyblue">[nullpointer@reckless ~]$  </div>
					<div id="show" style="display: none; color:white; padding-left: 15.5em;">  _ </div>					
				</span>
				
			</div>
			
		</div>
		<script> 
			var likha = "";
			function colour() {
				likha += "A";	  
				setInterval(function() { 	 
					
					if (document.getElementById('show').style.display == 'none') {
						document.getElementById('show').style.display = "block"; 
					}else{
						document.getElementById('show').style.display = "none"; 
					} 	
					// document.getElementById('show').style.set	  
				
				}, 800); 	  
			} 
		</script> 

	</body>
</html>
