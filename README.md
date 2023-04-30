Download Link: https://assignmentchef.com/product/solved-fit2102-assignment-1-functional-reactive-programming
<br>



<h1>Task description</h1>

In this assignment we will use the RxJS Observable stream explored in the Week 4 worksheet to create the <a href="https://www.youtube.com/watch?v=MU4psw3ccUI">classic Space Invaders game (YouTube)</a> in an SVG image hosted in the <strong>spaceInvaders.html </strong>webpage.  The YouTube video is meant to give you an idea of the basic gameplay, but yours needn’t look the same or work in precisely the same way.  You will also need to write a report detailing the design of your game. The baseline functionality required for a passing grade, what needs to be included in your report and a list of alternative ideas for achieving an HD, are listed below.

<strong>Minimum requirements. </strong>All of these requirements must be reasonably executed to achieve a

passing grade (detailed marking rubric below).

<ul>

 <li>Implement a one-player Space Invaders game with a spaceship movable by mouse (while the mouse cursor is over the svg canvas) or by keyboard.</li>

 <li>Rows of aliens should appear and move across and down the screen.</li>

 <li>The aliens should fire bullets at the user. If the user is hit by one bullet, the user will die and the game will end</li>

 <li>Indicate the score for the player.</li>

 <li>A 1-2 page PDF report detailing your design decisions and use of functional programming techniques discussed in the course notes.</li>

</ul>

<strong>Full Game:</strong>

<ul>

 <li>Meets minimum requirements</li>

 <li>The user has shields, which disintegrate over collisions – Smooth and usable game play.</li>

 <li>Able to restart when game finishes</li>

 <li>The game progresses to a new level after all aliens are shot</li>

 <li><em>See </em><a href="https://www.youtube.com/watch?v=it0sf4CMDeM"><em>video</em></a><em> for an idea of appropriate gameplay</em></li>

</ul>

All the above need to be implemented in a good functional reactive programming style to get a good grade. To get a higher grade you have to use a little creativity and add some functionality of your own choice — suggestions below.

<strong>Ideas for getting an HD</strong>.  Any one or more of the following (or something of your own devising with a similar degree of complexity) done well (on top of the basic functionality described above) will earn you an HD provided it is implemented using the functional programming ideas we have covered in lectures and tutes:

<ul>

 <li>Create unit tests and create a file <strong>tests/main.test.js</strong></li>

 <li>Incorporate gameplay from other classic arcade games — e.g., breakout, galaga, etc.</li>

</ul>

Add power-ups to the game — larger shields, slower aliens, faster spaceship, etc.

<ul>

 <li>Add combination bonuses, e.g if you hit 5 aliens in a row.</li>

 <li>Advanced (not recommended unless you already know how): Make a distributed multiplayer version, wrapping the comms in Observable (you’ll have to provide your own server for this).</li>

 <li>Your own ideas!</li>

</ul>

Some of the above will require a little independent research. That’s what computer science is all about!

<strong>Report. </strong>Your report should be 1- 2 pages in length, plus up to one page per extension, where you should:

<ul>

 <li>Include basic report formatting headings/paragraphs – Include diagrams as necessary.</li>

 <li>Summarise the workings of the code and highlight the interesting parts.</li>

 <li>Give a high level overview of your design decisions and justification.</li>

 <li>Explain how you tried to follow the FRP style.</li>

 <li>How you manage state throughout your game.</li>

</ul>

<strong>Marking</strong>.  The goal of this assignment is to assess your understanding of FRP. The marking is done in two parts.

<ol>

 <li>Implementation of game features.</li>

 <li>Use and understanding of proper functional programming style.</li>

</ol>

The idea here is that adding features to Space Invaders will grant you a higher grade <em>under the condition </em>that it is done in proper Functional and FRP style. For an example of the proper style, refer to the example <a href="https://tgdwyer.github.io/asteroids/">Asteroids Game described in the</a> <a href="https://tgdwyer.github.io/asteroids/">Course Notes</a>. Code that does not use Observable will not get a passing grade; code which relies on imperative code will be penalised. To achieve a mark in the HD range you need to implement a complete Space Invaders game with good style and a choice few additional features, as above.

<h1>Additional information</h1>

Similar to the tutorial exercises we will provide you with a starter project which you can download in a zip file from Moodle that contains:

<ul>

 <li><strong>html </strong>currently just an empty SVG object. Your Space Invaders game goes here! Add instruction text to the page to explain how to play your Space Invaders game.  Make sure the instructions are sufficient that we can properly try out all of your features.</li>

 <li><strong>ts </strong>source code for your Space Invaders game. This is where most of your work will go.</li>

</ul>

<strong>Tips for getting started</strong>.




Complete the Week 4 Tutorial Worksheet Observable exercises and begin studying Observable in the <a href="https://tgdwyer.github.io/functionalreactiveprogramming/">course notes</a>.

<ul>

 <li>In week 5 Tutorial you will complete <strong>ts</strong></li>

 <li>Once you have completed the above, work through the example <a href="https://tgdwyer.github.io/asteroids/">Asteroids Game </a><a href="https://tgdwyer.github.io/asteroids/">described in the Course Notes</a>. Follow the same framework to begin adding functionality to <strong>spaceInvaders</strong><strong>.ts </strong>as above.</li>

</ul>

<strong>More tips.</strong>

<ul>

 <li>Finish all the JavaScript and TypeScript tutes (up to the first part of Week 5) and the course notes FRP material first. They are designed to give you the experience you need to prepare for this assignment.</li>

 <li>Come to the workshops and tutes for important tips and assistance.</li>

 <li>Attend consultations given by the teaching team.</li>

 <li>Any general questions should be directed to the Ed forums when possible. However, try to avoid posting potential solutions. If you cannot make the consultations, you may make a <strong><em>private </em></strong>post with Staff on the assignment with code.</li>

 <li>Your code should include brief comments to explain logic and design choices where necessary or to refer to detailed explanations in your report. Please do not add comments that are self evident from the code, e.g.:</li>

 <li>const x = 1; // variable x is set to 1.</li>

 <li><strong>Start as soon as possible</strong>. Do not leave the assignment until it’s too late.</li>

</ul>

<strong>Recommended coding practises.</strong>

<ul>

 <li>Structure your program in a consistent and coherent manner (group relevant functions, declarations, and variables together)</li>

 <li>Use block/section comments to clearly layout each part of your code</li>

 <li>Use nice indenting and formatting (can look into formatters if you wish <a href="https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode">prettier</a> <a href="https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify">beautify</a>)</li>

 <li>Use camelCase for names and UPPER_CASE for constants</li>

</ul>