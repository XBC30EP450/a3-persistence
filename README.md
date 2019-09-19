<h1>Nyankotracker</h1>
<em>https://a3-javiermarcos.glitch.me/</em>

<p>
This is an application tailored for players of the mobile game The Battlecats. The game in question
features a gacha mechanic, which means that players will unlock a vast array of units as they play.
This application aims to make it easier to keep track of the level of each unit by providing a more
convenient way to browse through their collection than the game currently allows.
</p>

<p>
Entering the URL "https://a3-javiermarcos.glitch.me/gimmethegoods" will prompt the server to
provide all data currently stored in the database.

The following is a list of all middleware used:
  <b>Passport:</b> 			Authentication middleware
  <b>Cookie-Parser:</b> Facilitates accessing cookies.  Passport dependency.
  <b>Body-Parser:</b>		Facilitates sending and receiving JSON objects
  <b>Express-Session:</b>	Allows keeping track of user sessions. Passport dependency.
  <b>Helmet:</b>			A collection of 13 middleware aimed to enhance security
  <b>Morgan:</b>			Shows incoming requests in the server console. Used for debugging
  <b>lowdb:</b>				Allows creation and management of persistent databases
  <b>Filesync:</b>			lowdb dependency
  <b>Passport-local:</b>		Allows implementation of local authentication strategies on Passport.
  <b>Bcrypt:</b>				Encryption middleware. Used to encrypt stored passwords.
</p>

<h2>Technical Technical achievements:</h2>
<ol>
  <li>Improved security through the implementation of the Helmet  middleware.</li>
  <li>Implemented encryption, used to safeguard users' passwords.</li>
  <li>Added the ability for users to delete their accounts.</li>
</ol>

<h2>Design achievements</h2>
<ol>
<li>Improved the site's appearance with the Marx CSS template.</li>
<li>Provided a clean, expandable layout for users to look at their collection of units.</li>
<li>Added personality to the site by adding a function that displays comical text at random on each visit.
   (A similar feature is found in the game this tool is based on).</li>
</ol>


<p>
Getting used to the different the required middleware posed quite the challenge, especially figuring
out how to get passport up and running. On top of that, I am still getting the hang of properly using
POST and GET requests to send data back and forth. That said, however, designing the HTML document
went quite smoothly in comparison
</p>
<p>
The use of passport and lowdb being required set some restriction on what programs I could build.
I chose to create this database since it would be relatively simple to do while being related to one
of my interests, and perhaps one day, a much more useful tool.
</p>
<p>
I used the Marx CSS template for this project (https://github.com/mblode/marx). This is a rather
small project, and it's meant to be a tool first and foremost. Because of this, the simple design
offered by this template seemed the most appealing. While some adjustments and tweaks were made,
these were few and minor changes.
</p>
