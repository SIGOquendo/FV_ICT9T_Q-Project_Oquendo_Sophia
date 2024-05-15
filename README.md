<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Log in Page</title>
	<style>
		body {
			background-color: #a4a2eb;
		}
	</style>
</head>
<body>
	<center>
		<br/>
		<h1>Log in</h1>
		<img src="id_pic.PNG">
		<br/><br/>
		<label>Email:</label>
		<br/>
		<input type="email" name="email" id="email" style="background-color:#b6a2eb; border-color:#435d91;"/>
		<br/><br/>
		<label>Password:</label>
		<br/>
		<input type="password" name="password" id="password" style="background-color:#b6a2eb; border-color:#435d91;"/>
		<br/><br/>
		<button type="button" class="btn btn-primary" ><a href="mainpage.html">Log in</a></button>
		<button type="button" class="btn btn-primary" >Cancel</button>
		<br/><br/>
	</center>
	<script>
		window.alert("Welcome to the login page!");
	</script>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Main Page</title>
	<style>
		body {
			background-color: #a4a2eb;
		}
		#one {
			width: 50px;
			length: 50px;
		}
	</style>
</head>
<body>
	<nav class="navbar navbar-expand-md bg-success">
    <a class="navbar-brand" href=""><img id="one" src="Logo.PNG"></a>
    <div id="topnav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" href="page2.html">First Quarter</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="page3.html">Second Quarter</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="page4.html">Third Quarter</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Search Bar</a>
        </li>
      </ul>
    </div>
  </nav>
  <br/><br/>
  <center>
  	<img id="image" src="id_pic.PNG"><br>
  	<span><h1>My Online Portfolio</h1></span>
    <p>Name: Sophia Oquendo</p>
    <p>Grade and Section: 9-Topaz</p>
    <p>These are some of the projects that I have worked on throughout this school year</p>
    <br/>
  	<a href="page2.html"><p id="viewQ1">View 1st Quarter</p></a>
  	<a href="page3.html"><p id="viewQ2">View 2nd Quarter</p></a>
    <a href="page4.html"><p id="viewQ3">View 3rd Quarter</p></a>
    <button onclick="window.alert('hi there!')">Hello</button>
  </center>
  <script type="text/javascript">
  	function firstquarter(){
  		document.getElementById('viewQ1').innerHTML="View Quarter 1 Project"; //lets you view 1st Quarter
  	}
  	function secondquarter(){
  		document.getElementById('viewQ2').innerHTML="View Quarter 2 Project"; //lets you view 2nd Quarter
  	}
    function thirdquarter(){
      document.getElementById('viewQ3').innerHTML="View Quarter 3 Project"; //lets you view 3rd Quarter
    }
  </script>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>1st Quarter</title>
	<style>
		body {
			background-color: #a4a2eb;
		}
		#one {
			width: 50px;
			length: 50px;
		}
	</style>
</head>
<body>
<nav class="navbar navbar-expand-md bg-success">
    <a class="navbar-brand" href=""><img id="one" src="Logo.PNG"></a>
    <div id="topnav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" href="page2.html">First Quarter</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="page3.html">Second Quarter</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="page4.html">Third Quarter</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Search Bar</a>
        </li>
      </ul>
    </div>
  </nav>
<center>
	<table border="2" cellpadding="15" cellspacing="5" bordercolor="#8584b8" bgcolor="#8c84b8">
		<tr>
			<th colspan="3" bgcolor="#a4a2eb"><h1><font face="Garamond" color="#363573">Noli Me Tangere Characters</h1></th></font>
		</tr>
		<tr>
			<th bgcolor="#c8a9eb"><font face="Garamond" color="#363573"><a href="#Ibarra">Ibarra</a><br/><a href="#Maria Clara">Maria Clara</a><br/><a href="#Elias">Elias</a><br/><a href="#Kapitan Tiago">Kapitan Tiago</a></br/><a href="#Padre Damaso">Padre Damaso</a><br/><a href="#Padre Salvi">Padre Salvi</a><br/></font></th>
			<th bgcolor="#c8a9eb"><font face="Garamond" color="#363573"><a href="#Don Rafael">Don Rafael</a><br/><a href="#Pilosopo Tasyo">Pilosopo Tasyo</a><br/><a href="#Dona Victorina">Doña Victorina</a><br/><a href="#Don Tiburcio">Don Tiburcio</a><br/><a href="#Sisa">Sisa</a><br/><a href="#Basilio">Basilio</a><br/></font></th>
			<th bgcolor="#c8a9eb"><font face="Garamond" color="#363573"><a href="#Crispin">Crispin</a><br/><a href="#Dona Consolation">Doña Consolacion</a><br/><a href="#Alferez">The Alferez</a><br/><a href="#Padre Sibyla">Padre Sibyla</a><br/><a href="#References">References</a>
		<tr>
			<th bgcolor="#c8a9eb"><img src="https://static.wikia.nocookie.net/noli-me-tangere/images/d/d9/AviIbarra.png/revision/latest?cb=20200523011813" width="140px" height="140px" alt="Ibarra"></th>
			<th bgcolor="#c8a9eb" colspan="2"><font face="Garamond" color="#363573">
				<dl>
					<label id="Ibarra>"><dt><b>Crisostomo Ibarra</b></dt><br/></label>
					<dd>A wealthy Filipino who studied out of the country</dd>
					<dd>idealistic and outspoken</dd>
					<dd>Wishes to build a school in San Diego</dd>
					<dd>fiancee of Maria Clara</dd>
				</dl>
			</th></font>
		</tr>
			<tr>
				<th bgcolor="#c8a9eb"><img src="https://static.wikia.nocookie.net/noli-me-tangere/images/4/4e/AviMariaClara.png/revision/latest?cb=20200523015219" width="140px" height="140px" alt="Maria Clara"></th>
				<th bgcolor="#c8a9eb" colspan="2"><font face="Garamond" color="#363573">
					<dl>
						<label id="Maria clara"><dt><b>Maria Clara</b></dt><br/></label>
						<dd>daughter of Padre Damaso, born after an affair</dd>
						<dd>fiancee of Ibarra</dd>
						<dd>trustworthy, respectful and loyal</dd>
					</dl>
				</font></th>
			</tr>
			<tr>
				<th bgcolor="#c8a9eb"><img src="https://static.wikia.nocookie.net/noli-me-tangere/images/4/41/AviElias.png/revision/latest?cb=20200523015847" width="140px" height="140px" alt="Elias"></th>
				<th bgcolor="#c8a9eb" colspan="2"><font face="Garamond" color="#363573">
					<dl>
						<label id="Elias"><dt><b>Elias</b></dt><br/></label>
						<dd>one of the most sought after criminals in San Diego</dd>
						<dd>master boater</dd>
						<dd>Ibarra's friend</dd>
						<dd>wishes to start a revolution</dd>
					</dl>
				</font></th>
			</tr>
			<tr>
				<th bgcolor="#c8a9eb"><img src="https://static.wikia.nocookie.net/noli-me-tangere/images/d/da/AviTiago.png/revision/latest?cb=20200523043309" width="140px" height="140px" alt="Kapitan Tiago"></th>
				<th bgcolor="#c8a9eb" colspan="2"><font face="Garamond" color="#363573">
					<dl>
						<label id="Kapitan Tiago"><dt><b>Kapitan Tiago</b></dt><br/></label>
						<dd>Maintains relations with members of Catholic Church</dd>
						<dd>A wealthy Filipino from Binondo</dd>
						<dd>Wishes to marry his daughter off to a rich man</dd>
					</dl>
				</font></th>
			</tr>
			<tr>
				<th bgcolor="#c8a9eb"><img src="https://static.wikia.nocookie.net/noli-me-tangere/images/8/8d/AviDamaso.png/revision/latest?cb=20200523011955" width="140px" height="140px" alt="Padre Damaso"></th>
				<th bgcolor="#c8a9eb" colspan="2"><font face="Garamond" color="#363573">
					<dl>
						<label id="Padre Damaso"><dt><b>Padre Damaso</b></dt><br/></label>
						<dd>Franciscan Priest</dd>
						<dd>corrupt, racist and shameless</dd>
						<dd>Maria Clara's father</dd>
						<dd>Responsible for the murder of Don Rafael</dd>
					</dl>
				</font></th>
			</tr>
			<tr>
				<th bgcolor="#c8a9eb"><img src="https://static.wikia.nocookie.net/noli-me-tangere/images/2/2c/AviSalvi.png/revision/latest?cb=20200525132124" width="140px" height="140px" alt="Padre Salvi"></th>
				<th bgcolor="#c8a9eb" colspan="2"><font face="Garamond" color="#363573">
					<dl>
						<label id="Padre Salvi"><dt><b>Padre Salvi</b></dt><br/></label>
						<dd>Spanish Priest</dd>
						<dd>controls Padre Damaso's post</dd>
						<dd>an exploitative strategist</dd>
						<dd>admires Maria Clara</dd>
					</dl>
				</font></th>
			</tr>
			<tr>
				<th bgcolor="#c8a9eb"><img src="https://static.wikia.nocookie.net/mariaclaraatibarra/images/c/cb/Don_Rafael_character_image.png/revision/latest?cb=20230122031722" width="140px" height="140px" alt="Don Rafael"></th>
				<th bgcolor="#c8a9eb" colspan="2"><font face="Garamond" color="#363573">
					<dl>
						<label id="Don Rafael"><dt><b>Don Rafael</b></dt><br/></label>
						<dd>Crisostomo's father</dd>
						<dd>criticized Spanish friars</dd>
						<dd>died in prison</dd>
						<dd>accused of heresy and sedition</dd>
					</dl>
				</font></th>
			</tr>
			<tr>
				<th bgcolor="#c8a9eb"><img src="https://static.wikia.nocookie.net/noli-me-tangere/images/6/63/AviTasio.png/revision/latest?cb=20200523015218" width="140px" height="140px" alt="Pilosopo Tasyo"></th>
				<th bgcolor="#c8a9eb" colspan="2"><font face="Garamond" color="#363573">
					<dl>
						<label id="Pilosopo Tasyo"><dt><b>Pilosopo Tasyo</b></dt><br/></label>
						<dd>named Don Anastasio</dd>
						<dd>thought of as crazy by townsfolk</dd>
						<dd>pessimistic</dd>
						<dd>gives advice to Ibarra and helped Don Rafael</dd>
					</dl>
				</font></th>
			</tr>
			<tr>
				<th bgcolor="#c8a9eb"><img src="https://static.wikia.nocookie.net/noli-me-tangere/images/1/13/AviVictorina.png/revision/latest?cb=20200523015710" width="140px" height="140px" alt="Dona Victorina"></th>
				<th bgcolor="#c8a9eb" colspan="2"><font face="Garamond" color="#363573">
					<dl>
						<label id="Dona Victorina"><dt><b>Doña Victorina</b></dt><br/></label>
						<dd>pretends to act like a Spanish woman</dd>
						<dd>wants her nephew to marry Maria Clara</dd>
						<dd>married Don Tiburcio</dd>
						<dd>childless</dd>
					</dl>
				</font></th>
			</tr>
			<tr>
				<th bgcolor="#c8a9eb"><img src="https://static.wikia.nocookie.net/mariaclaraatibarra/images/6/67/Don_Tiburcio_character_image.png/revision/latest?cb=20230122031536" width="140px" height="140px" alt="Don Tiburcio"></th>
				<th bgcolor="#c8a9eb" colspan="2"><font face="Garamond" color="#363573">
					<dl>
						<label id="Don Tiburcio"><dt><b>Don Tiburcio</b></dt><br/></label>
						<dd>Spanish husband of Doña Victorina</dd>
						<dd>One of the guests at Kapitan Tiago's party</dd>
						<dd>a con artist</dd>
					</dl>
				</font></th>
			</tr>
			<tr>
				<th bgcolor="#c8a9eb"><img src="https://static.wikia.nocookie.net/noli-me-tangere/images/e/eb/AviSisa.png/revision/latest?cb=20191130021219" width="140px" height="140px" alt="Sisa"></th>
				<th bgcolor="#c8a9eb" colspan="2"><font face="Garamond" color="#363573">
					<dl>
						<label id="Sisa"><dt><b>Sisa</b></dt><br/></label>
						<dd>Mother of Crispin and Basilio</dd>
						<dd>an abused wife</dd>
						<dd>regards her children as her only treasures</dd>
						<dd>passes away due to terrible mental state</dd>
					</dl>
				</font></th>
			</tr>
			<tr>
				<th bgcolor="#c8a9eb"><img src="https://static.wikia.nocookie.net/noli-me-tangere/images/e/ef/AviBasilio.png/revision/latest?cb=20200523020145" width="140px" height="140px" alt="Basilio"></th>
				<th bgcolor="#c8a9eb" colspan="2"><font face="Garamond" color="#363573">
					<dl>
						<label id="Basilio"><dt><b>Basilio</b></dt><br/></label>
						<dd>brother of Crispin</dd>
						<dd>son of Sisa</dd>
						<dd>works as a sexton</dd>
						<dd>plays a role in El Filibusterismo</dd>
					</dl>
				</font></th>
			</tr>
			<tr>
				<th bgcolor="#c8a9eb"><img src="https://static.wikia.nocookie.net/noli-me-tangere/images/7/7b/AviCrispin.png/revision/latest?cb=20200523014743" width="140px" height="140px" alt="Crispin"></th>
				<th bgcolor="#c8a9eb" colspan="2"><font face="Garamond" color="#363573">
					<dl>
						<label id="Crispin">Crispin<dt><b></b></dt><br/></label>
						<dd>brother of Basilio</dd>
						<dd>son of Sisa</dd>
						<dd>works as a sexton</dd>
						<dd>Went missing after being accused of stealing</dd>
					</dl>
				</font></th>
			</tr>
			<tr>
				<th bgcolor="#c8a9eb"><img src="https://static.wikia.nocookie.net/mariaclaraatibarra/images/3/37/Do%C3%B1a_Consolacion_character_image.png/revision/latest?cb=20230121081841" width="140px" height="140px" alt="Dona Consolation"></th>
                <th bgcolor="#c8a9eb" colspan="2"><font face="Garamond" color="#363573">
                	<dl>
                		<label id="Dona Consolation">Doña Consolacion<dt><b></b></dt><br/></label>
                		<dd>wife of the Alfarez</dd>
                		<dd>ashamed of being a Filipino</dd>
                		<dd>cruel to Sisa</dd>
                		<dd>thinks others should respect her</dd>
                	</dl>
                </font></th>
            </tr>
            <tr>
            	<th bgcolor="#c8a9eb"><img src="https://static.wikia.nocookie.net/mariaclaraatibarra/images/5/5d/Alferez_character_image.png/revision/latest?cb=20230228114353" width="140px" height="140px" alt="Alfarez"></th>
                <th bgcolor="#c8a9eb" colspan="2"><font face="Garamond" color="#363573">
                	<dl>
                		<label id="Alferez"><dt><b>The Alferez</b></dt><br/></label>
                		<dd>no known name</dd>
                		<dd>husband of Doña Consolacion</dd>
                		<dd>alcoholic</dd>
                		<dd>mortal enemy of the priests</dd>
                	</dl>
                </font></th>
            </tr>
            <tr>
            	<th bgcolor="#c8a9eb"><img src="https://static.wikia.nocookie.net/mariaclaraatibarra/images/5/56/Padre_Sibyla_character_image.png/revision/latest?cb=20230125012459" width="140px" height="140px" alt="Padre Sibyla"></th>
                <th bgcolor="#c8a9eb" colspan="2"><font face="Garamond" color="#363573">
                	<dl>
                		<label id="Padre Sibyla"><dt><b>Padre Sibyla</b></dt><br/></label>
                		<dd>Catholic priest</dd>
                		<dd>monitors Ibarra</dd>
                		<dd>curate of the Binondo district</dd>
                	</dl>
                </font></th>
            </tr>
            <tr>
            	<th bgcolor="#c8a9eb" colspan="3"><font face="Garamond" color="#363573">
            		<label id="References">References:</label>
            		<ol>
            			<li>Character Descriptions:
            			    <ul>
            			    	<li><a href="https://noypi.com.ph/noli-me-tangere-characters/#father-sibyla" target="self">https://noypi.com.ph/noli-me-tangere-characters/#father-sibyla</a></li>
            			    </ul>
            			</li>
            			<li>Images:
            				<ul>
            			    	<li><a href="https://noli-me-tangere.fandom.com/wiki/Crisostomo_Ibarra" target="self">https://noli-me-tangere.fandom.com/wiki/Crisostomo_Ibarra</a></li>
            			    	<li><a href="https://noli-me-tangere.fandom.com/wiki/Maria_Clara" target="self">https://noli-me-tangere.fandom.com/wiki/Maria_Clara</a></li>
            			    	<li><a href="https://noli-me-tangere.fandom.com/wiki/Elias" target="self">https://noli-me-tangere.fandom.com/wiki/Elias</a></li>
            			    	<li><a href="https://noli-me-tangere.fandom.com/wiki/Capitan_Tiago" target="self">https://noli-me-tangere.fandom.com/wiki/Capitan_Tiago</a></li>
            			    	<li><a href="https://noli-me-tangere.fandom.com/wiki/Padre_Damaso" target="self">https://noli-me-tangere.fandom.com/wiki/Padre_Damaso</a></li>
            			    	<li><a href="https://noli-me-tangere.fandom.com/wiki/Padre_Salvi" target="self">https://noli-me-tangere.fandom.com/wiki/Padre_Salvi</a></li>
            			    	<li><a href="https://mariaclaraatibarra.fandom.com/wiki/Don_Rafael" target="self">https://mariaclaraatibarra.fandom.com/wiki/Don_Rafael</a></li>
            			    	<li><a href="https://noli-me-tangere.fandom.com/wiki/Pilosopo_Tasio" target="self">https://noli-me-tangere.fandom.com/wiki/Pilosopo_Tasio</a></li>
            			    	<li><a href="https://noli-me-tangere.fandom.com/wiki/Do%C3%B1a_Victorina" target="self">https://noli-me-tangere.fandom.com/wiki/Do%C3%B1a_Victorina</a></li>
            			    	<li><a href="https://mariaclaraatibarra.fandom.com/wiki/Don_Tiburcio" target="self">https://mariaclaraatibarra.fandom.com/wiki/Don_Tiburcio</a></li>
            			    	<li><a href="https://noli-me-tangere.fandom.com/wiki/Sisa" target="self">https://noli-me-tangere.fandom.com/wiki/Sisa</a></li>
            			    	<li><a href="https://noli-me-tangere.fandom.com/wiki/Basilio" target="self">https://noli-me-tangere.fandom.com/wiki/Basilio</a></li>
            			    	<li><a href="https://noli-me-tangere.fandom.com/wiki/Crispin" target="self">https://noli-me-tangere.fandom.com/wiki/Crispin</a></li>
            			    	<li><a href="https://mariaclaraatibarra.fandom.com/wiki/Do%C3%B1a_Consolacion" target="self">https://mariaclaraatibarra.fandom.com/wiki/Do%C3%B1a_Consolacion</a></li>
            			    	<li><a href="https://mariaclaraatibarra.fandom.com/wiki/Alferez" target="self">https://mariaclaraatibarra.fandom.com/wiki/Alferez</a></li>
            			    	<li><a href="https://mariaclaraatibarra.fandom.com/wiki/Padre_Sibyla" target="self">https://mariaclaraatibarra.fandom.com/wiki/Padre_Sibyla</a></li>
            			    </ul>
            			   </li>
            			</ol>
            		</font>
            	</th>
            </tr>
        </table>
</center>
  <br/><br/>
	<button type="button" class="btn btn-primary" ><a href="mainpage.html">back</a></button>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>2nd Quarter</title>
	<style>
		body {
			background-color: #a4a2eb;
		}
		#one {
			color: teal;
			text-align: center;
		}
		td {
			background-color: rgb(188, 196, 250, 1.0);
			border: 10px solid lavender;
		}
		li {
			color: rgb(111, 38, 230, 1.0);
		}
		#two {
			color: teal;
		}
		#number {
			width: 50px;
			length: 50px;
		}
		}
	</style>
</head>
<body>
<nav class="navbar navbar-expand-md bg-success">
    <a class="navbar-brand" href=""><img id="number" src="Logo.PNG"></a>
    <div id="topnav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" href="page2.html">First Quarter</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="page3.html">Second Quarter</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="page4.html">Third Quarter</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Search Bar</a>
        </li>
      </ul>
    </div>
  </nav>
<div id="one">
		<h1>Welcome to the Philippines!</h1>
	    <p>travel guide</p>
    </div>
    <table>
    	<tr>
    		<td>
    			<ol>
    			    <li>
    				    <strong><div id="two">San Agustin Church</div></strong><br/><br/>
    				    <ul>
    				    	<li>Location: General Luna St, Manila, 1002 Metro Manila, Philippines</li>
    				    	<li>Timings: 8:00 AM to 12:00 PM and 1:00 PM to 6:00 PM</li>
    				    	<li>Price: Php 89 per head</li>
    				    </ul>
    				</li>
    			</ol>
    		</td>
    		<td>
    			<img src="https://thequeensescape.com/wp-content/uploads/2020/01/San2BAgustin2BChurch2BMuseum-08.jpg" width="500px" height="300">
    		</td>
    	</tr>
    	<tr>
    		<td>
    			<ol>
    				<li>
    					<strong><div id="two">National Museum of the Philippines</div></strong><br/><br/>
    					<ul>
    						<li>one of the best Philippines places to visit, if you want to explore and learn more about the culture, history, and tradition of the country</li>
    						<li>Location: P. Burgos Drive, Rizal Park, Manila, Philippines</li>
    						<li>Timings: 10 AM to 5 PM; Closed on Monday</li>
    					</ul>
    				</li>
    			</ol>
    		</td>
    		<td>
    			<img src="https://museu.ms/remote.jpg.ashx?width=1000&height=450&format=jpg&mode=crop&scale=both&404=no_image.gif&urlb64=aHR0cHM6Ly9tdXNldW1zLmJsb2IuY29yZS53aW5kb3dzLm5ldC9kYXRhL0RvY3VtZW50cy9NVVNFVU1TL3BobWFuYW11b2Z0aHBoLzM4OTYzNi9lZWQwNWI4NDIxMmU0ODQ3YTYxOGYxZTc4NWY1Yzg4MS5qcGc&hmac=kepd19FUZX4" width="500px" height="300">
    		</td>
    	</tr>
    	   	<tr>
    		<td>
    			<ol>
    				<li>
    					<strong><div id="two">Chocolate hills</div></strong><br/><br/>
    					<ul>
    						<li>considered to be one of the most picturesque Philippines places to visit</li>
    						<li>Location: Bohol, Philippines</li>
    						<li>Price: 50 PHP per head</li>
    					</ul>
    				</li>
    			</ol>
    		</td>
    		<td>
    			<img src="https://www.travelandleisure.com/thmb/Uyi3xc1u5Z3hUbSGSDqaJMoOV9s=/1500x0/filters:no_upscale():max_bytes(150000):strip_icc()/chocolate-hills-PHIL0116-3a853dd3c6704d84bb5162bb37404279.jpg" width="500px" height="300">
    		</td>
    	</tr>
    	   	<tr>
    		<td>
    			<ol>
    				<li>
    					<strong><div id="two">Banaue Rice Terraces</div></strong><br/><br/>
    					<ul>
    						<li>this mud and stone terraced rice field was declared as a World Heritage Site by UNESCO in 1995</li>
    						<li>Location: Nueva Vizcaya - Ifugao - Mountain Province Rd, Banaue, Ifugao, Philippines</li>
    						<li>Price: 20 PHP per head</li>
    					</ul>
    				</li>
    			</ol>
    		</td>
    		<td>
    			<img src="https://media2.thrillophilia.com/images/photos/000/367/510/original/1614174738_1614149383_shutterstock_1462704626.jpg.jpg?w=753&h=450&dpr=1.0" width="500px" height="300">
    		</td>
    	</tr>
    	   	<tr>
    		<td>
    			<ol>
    				<li>
    					<strong><div id="two">Puerto Princesa Subterranean River National Park</div></strong><br/><br/>
    					<ul>
    						<li>Location: Puerto Princesa, MIMAROPA, Philippines</li>
    						<li>Timings: 8 AM to 4 PM</li>
    						<li>Price: PHP 500 per head</li>
    					</ul>
    				</li>
    			</ol>
    		</td>
    		<td>
    			<img src="https://media2.thrillophilia.com/images/photos/000/367/509/original/1614174714_1614149228_shutterstock_489906367.jpg.jpg?w=753&h=450&dpr=1.0" width="500px" height="300">
    		</td>
    	</tr>
    	   	<tr>
    		<td>
    			<ol>
    				<li>
    					<strong><div id="two">Siargao</div></strong><br/><br/>
    					<ul>
    						<li>one of the famous places in the Philippines for surfing</li>
    						<li>you can go trekking, snorkelling, deep sea diving and surfing</li>
    						<li>Location: Towards the Northeast coast of Mindanao, Philippines</li>
    					</ul>
    				</li>
    			</ol>
    		</td>
    		<td>
    			<img src="https://media2.thrillophilia.com/images/photos/000/373/184/original/1621935231_shutterstock_1177486879.jpg?w=753&h=450&dpr=1.0" width="500px" height="300">
    		</td>
    	</tr>
    	<tr>
    		<td colspan="2"><input type="submit" name="submit" id="submit" value="See more"></td>
    	</tr>
    	<tr>
    		<td colspan="2"><div id="two">References:<br/><br/>
    			<a href="https://www.thrillophilia.com/places-to-visit-in-philippines">https://www.thrillophilia.com/places-to-visit-in-philippines</a><br/>
    			<a href="https://thequeensescape.com/a-tour-around-san-agustin-church-and-museum-in-intramuros-manila-philippines/#google_vignette">https://thequeensescape.com/a-tour-around-san-agustin-church-and-museum-in-intramuros-manila-philippines/#google_vignette</a><br/>
    			<a href="https://www.travelandleisure.com/attractions/landmarks-monuments/chocolate-hills-philippines">https://www.travelandleisure.com/attractions/landmarks-monuments/chocolate-hills-philippines</a><br/>
    			<a href="https://museu.ms/museum/details/16724/national-museum-of-the-philippines">https://museu.ms/museum/details/16724/national-museum-of-the-philippines</a><br/>
    		</td>
    	</tr>
    </table>
	<button type="button" class="btn btn-primary" ><a href="mainpage.html">back</a></button>
</body>
</html>

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Q2Project</title>
	<style>
		img {
      width: 90px;
      length: 90px;
    }
    td {
      background-color: rgb(188, 196, 250, 1.0);
      border: 10px solid lavender;
    }
    p {
      text-align: center;
    }
    a {
      text-align: center;
    }
    h1 {
    	text-align: center;
    }
    body {
    	background-color: #a4a2eb;
    }
	</style>
</head>
<body>
	<nav class="navbar navbar-expand-md bg-success">
    <a class="navbar-brand" href=""><img id="one" src="Logo.PNG"></a>
    <div id="topnav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" href="page2.html">First Quarter</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="page3.html">Second Quarter</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="page4.html">Third Quarter</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Search Bar</a>
        </li>
      </ul>
    </div>
  </nav>
	<nav class="navbar navbar-expand-md bg-success">
    <a class="navbar-brand" href="#"><img src="https://m.media-amazon.com/images/M/MV5BZDg3OGMwM2MtNjczNi00YWQ2LWIwNmItZjU0YzNiNjE2ZjFmXkEyXkFqcGdeQXVyODQyNDI4ODg@._V1_.jpg"></a>
    <div id="topnav">
      <ul class="navbar-nav">
        <li class="nav-item">
          <a class="nav-link" href="#">Home</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">People</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Internet Series</a>
        </li>
        <li class="nav-item">
          <a class="nav-link" href="#">Contact Us</a>
        </li>
      </ul>
    </div>
  </nav>
	<a href="https://www.youtube.com/@ThomasSanders"><h1>Thomas Sanders</h1></a>
	<table>
		<tr>
			<td>
				<img src="https://static.wikia.nocookie.net/phineasandferb/images/4/46/Thomas_Sanders.jpg/revision/latest?cb=20200828215518"><br/><p></p>
			</td>
			<td colspan="3">
				<p>Born in Gainseville, Florida, and known mostly for his content on Vine and Youtube</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
				<h1>Sanders Sides</h1>
			</td>
		</tr>
		<tr>
			<td>
				<h1>Character</h1>
			</td>
			<td>
				<h1>Description</h1>
			</td>
			<td>
				<h1>Extra info</h1>
			</td>
			<td>
				<h1>Quote</h1>
			</td>
		</tr>
		<tr>
			<td>
				<img src="https://static.wikia.nocookie.net/kinverse/images/b/b2/Roman.jpg/revision/latest?cb=20200929235104">
				<br/><p>Roman</p>
			</td>
			<td>
				<p>Representation of Thomas' creativity and passion</p>
			</td>
			<td>
				<p>The only right-handed side</p>  
			</td>
			<td>
				<p>time out for thee and time out for thee, focus on issues or focus on me - Roman</p>
			</td>
		</tr>
		<tr>
			<td>
				<img src="https://static.wikia.nocookie.net/sanders-sides/images/9/95/Loganformer.jpg/revision/latest/scale-to-width-down/250?cb=20170918232532">
				<br/><p>Logan</p>
			</td>			
			<td>
				<p>Representation of Thomas' logic and reasoning</p>
			</td>
			<td>
				<p>Has vocab cards for slang</p>
			</td>
			<td>
				<p>I don't think I'm smarter than everyone else, I know I'm smarter than everyone else - Logan</p>
			</td>
		</tr>
		<tr>
			<td>
				<img src="https://static.wikia.nocookie.net/sanders-sides/images/9/92/Pattoncurrent.png/revision/latest?cb=20171008232409">
				<br/><p>Patton</p>
			</td>
			<td>
				<p>Representation of Thomas' sense of morality</p>
			</td>
			<td>
				<p>Dad of the group</p>
			</td>
			<td>
				<p>♪ Singin' to myself. 'Cause I'm not uncomfortable at all. ♪ - Patton </p>
			</td>
		</tr>
		<tr>
			<td>
				<img src="https://static.wikia.nocookie.net/sanders-sides/images/d/d1/Virgilcurrent.png/revision/latest/scale-to-width-down/250?cb=20180219175828">
				<br/><p>Virgil</p>
			</td>
			<td>
				<p>Representation of Thomas' anxiety</p>
			</td>
			<td>
				<p>A previous dark side</p>
			</td>
			<td>
				<p>you tried, you failed, let's go to sleep - Virgil</p>
			</td>
		</tr>
		<tr>
			<td>
				<img src="https://static.wikia.nocookie.net/sanders-sides/images/3/37/Deceit.PNG/revision/latest/scale-to-width-down/250?cb=20180205184357">
				<br/><p>Janus</p>
			</td>
			<td>
				<p>Representation of Thomas' deceit</p>
			</td>
			<td>
				<p>Based on work such as Jekyll & Hyde</p>
			</td>
			<td>
				<p>So... I suppose now we begin compiling a list of people we need to... nudge... ...down a flight of stairs until they hold another round of callbacks? - Janus</p>
			</td>
		</tr>
		<tr>
			<td>
				<img src="https://static.wikia.nocookie.net/sanders-sides/images/6/61/Remusfront.png/revision/latest/scale-to-width-down/250?cb=20190625073730">
				<br/><p>Remus</p>
			</td>
			<td>
				<p>Representation of Thomas' Intrusive thoughts</p>
			</td>
			<td>
				<p>"Twin" of Roman</p>
			</td>
			<td>
				<p>Speaking of suggestions, when are you actually going to jump out of a moving car? I've been bringing it up for years. Mm, still nothing. - Remus to Thomas
</p>
			</td>
		</tr>
		<tr>
			<td colspan="4">
				<p>Refereces:</p>
				<a href="https://sanders-sides.fandom.com/wiki/Roman_Sanders?wikia-footer-wiki-rec=true#Current_form">https://sanders-sides.fandom.com/wiki/Roman_Sanders?wikia-footer-wiki-rec=true#Current_form</a><br/>
				<a href="https://phineasandferb.fandom.com/wiki/Thomas_Sanders">https://phineasandferb.fandom.com/wiki/Thomas_Sanders</a><br/>
				<a href="https://kinverse.fandom.com/wiki/Roman_Sanders">https://kinverse.fandom.com/wiki/Roman_Sanders</a><br/>
				<a href="https://sanders-sides.fandom.com/wiki/Roman_Sanders?wikia-footer-wiki-rec=true#Current_form">https://sanders-sides.fandom.com/wiki/Roman_Sanders?wikia-footer-wiki-rec=true#Current_form</a><br/>
				<a href="https://sanders-sides.fandom.com/wiki/Patton_Sanders?wikia-footer-wiki-rec=true">https://sanders-sides.fandom.com/wiki/Patton_Sanders?wikia-footer-wiki-rec=true</a><br/>
				<a href="https://sanders-sides.fandom.com/wiki/Logan_Sanders?wikia-footer-wiki-rec=true">https://sanders-sides.fandom.com/wiki/Logan_Sanders?wikia-footer-wiki-rec=true</a><br/>
				<a href="https://sanders-sides.fandom.com/wiki/Virgil_Sanders?wikia-footer-wiki-rec=true#Current_form">https://sanders-sides.fandom.com/wiki/Virgil_Sanders?wikia-footer-wiki-rec=true#Current_form</a><br/>
				<a href="https://sanders-sides.fandom.com/wiki/Janus_Sanders?wikia-footer-wiki-rec=true">https://sanders-sides.fandom.com/wiki/Janus_Sanders?wikia-footer-wiki-rec=true</a><br/>
				<a href="https://sanders-sides.fandom.com/wiki/Remus_Sanders?wikia-footer-wiki-rec=true">https://sanders-sides.fandom.com/wiki/Remus_Sanders?wikia-footer-wiki-rec=true</a><br/>
				<a href="https://www.imdb.com/title/tt7504014/">https://www.imdb.com/title/tt7504014/</a>
			</td>
		</tr>
	</table>
	<button type="button" class="btn btn-primary" ><a href="mainpage.html">back</a></button>
</body>
</html>
