<h1>User Centric Front-End Development Project</h1>

<p>This project is the first milestone project for the Code Institute. For this project, I chose to do create a website for the band Panic! At The Disco, one of my favourite bands.
My intention was to create a website that was streamlined and easy to follow for existing fans to keep up/interact with the band, and for new, potential fans who want to find out more about the band.</p>

<h2>UX</h2>
<p>This website is intended for people who are interested in the band.It allows them to listen to/watch music/videos from the band at their leisure on the website.</p>

<p>My website will allow (potential)fans to listen to and watch content from the band, and allow them to book/request the band to perform for them at an event such as a Christmas party or a wedding.</p>

<h3>User Stories</h3>
<ul>
<li>As a (potential)fan, I want to be able to find out about the band and it's members.</li>
<li>As a (potential)fan, I want to be able to find out about new content when and/or if it is available.</li>
<li>As a (potential)fan, I want to be able to listen to audio clips from the band on their website.</li>
<li>As a (potential)fan, I want to be able to watch (music)videos of the band while on their website.</li>
</ul>

<h3>Wireframes</h3>
<ul>
<li><a href= "/assets/images/wireframes/Wireframe 1.jpg" target= "_blank">Mobile Wireframe 1</a></li>
<li><a href= "/assets/images/wireframes/Wireframe 2.jpg" target= "_blank">Mobile Wireframe 2</a></li>
<li><a href= "/assets/images/wireframes/Wireframe 3.jpg" target= "_blank">Desktop Wireframe 1</a></li>
<li><a href= "/assets/images/wireframes/Wireframe 4.jpg" target= "_blank">Desktop Wireframe 2</a></li>
</ul>

<h2>Features</h2>

<h3>Existing Features</h3>
<ul>
<li>"Home" - This is the landing page where visitors to the website are welcomed. It gives some flavour text about the band and includes a link to "The Band" page of the website.</li>
<li>"Sign Up" - This is a feature of the "Home" page where people can sign up to receive notifications of new music/content from the band via email service.</li>
<li>"Store" section - This is a feature of the "Home" page that links the user to the band's merchandise store where they may purchase items to support the band.</li>
<li>"Twitter feed" - This is a live twitter feed of the band's that allows users to view the latest happenings from the band.</li>
<li>"The Band" - This page contains information on all current band members, including links to their personal instagram and twitter accounts, and a link to the "Media" page of the website.</li>
<li>"Media" - This is where visitors of the website can listen to clips of the bands music and watch some of their music videos. It also contains links to various music apps where users may listen to/download/purchase music by the band.</li>
<li>"Book us" section - This is an advert placed on the "Media" page leting the user know that they can book the band for parties/functions, along with a link to the "Contact" page.</li>
<li>"Contact" - This page contains a form for users to fill out in order to request the band to play at an event that they are having.</li>
<li>"Social links footer" - A permanent feature on every page that links to the general social accounts of the band, allowing users to keep up to date with their activities.</li>
</ul>


<h3>Features Left to Implement</h3>
<ul>
<li>Page on website to inform users of the band's charity "Highest Hopes Foundation" and how they can get involved if they so wish.</li>
</ul>

<h2>Technologies Used</h2>

<ul>
<li><a href= "https://jquery.com/" target= "_blank">JQuery</a> -Supports responsive navbar at top of page.</li>
<li><a href= "https://popper.js.org/" target= "_blank">Popper JS</a> -Supports responsive navbar at top of page.</li>
<li><a href= "https://getbootstrap.com/docs/4.1/getting-started/introduction/" target= "_blank">Bootstrap JS</a> -Supports responsive navbar at top of page.</li>
<li><a href= "https://getbootstrap.com/docs/4.1/getting-started/introduction/" target= "_blank">Bootstrap CSS</a> -Supports grid layout and stylings used throughout website, including but not restricted to the navbar and forms.</li>
<li><a href= "https://publish.twitter.com/#" target= "_blank">Twitter JS</a> -Supports twitter feed at bottom of "Home" page.</li>
</ul>


<h2>Testing</h2>

<p>I have tested the website extensively on different screen sizes, from mobile to desktop.The navbar is responsive at smaller screen sizes, and displays correctly at larger ones. All the audio and video files work. I have tested all the forms included in the website and they all function accordingly.</p>
<ol>
<li>
<p>Notification email form:</p>
<ol>
<li>Go to the "Home" page</li>
<li>Try to submit the empty form and verify that an error message about the required fields appears</li>
<li>Try to submit the form with an invalid email address and verify that a relevant error message appears</li>
<li>Try to submit the form with all inputs valid and verify that a success message appears.</li>
</ol>
</li>
<li>
<p>Booking form:</p>
<ol>
<li>Go to the "Contact" page</li>
<li>Try to submit the empty form and verify that an error message about the required fields appears</li>
<li>Try to submit the form with an invalid email address and verify that a relevant error message appears</li>
<li>Try to submit the form with all inputs valid and verify that a success message appears.</li>
</ol>
</li>
<li>
<p>Audio files:</p>
<ol>
<li>Go to the "Media" page</li>
<li>Click on the play button and verify that the audio files play.</li>
</ol>
</li>
<li>
<p>Video files:</p>
<ol>
<li>Go to the "Media" page</li>
<li>Click on the play button and verify that the video files play.</li>
</ol>
</li>
</ol>
<p>My project is responsive at all screen resolutions. On the "Media" page the Spotify players are placed underneath an image of the single cover with the track title, for larger screens, 992px +, these are aligned opposite each other, whilst on smaller screens, 991px or less, they appear below each other in a pattern that allows better page flow.</p>


<h3>Bugs</h3>
<p>During testing I noticed that on an iPad pro, the screen layout of some pages distorts and displays a gap at the bottom of the page below the footer. I tried altering paddings and margins to offset this for larger resolutions, but that only distorted it on smaller ones.
As such, I will continue to edit the CSS code to try and fix the problem.</p>

<h2>Deployment</h2>
<p>I have pushed the code to a remote repository in GitHub where I have published the site on GitHub Pages.

Here is the link:<a href= "https://liammcgcistudent.github.io/ucd-milestone-project" target="_blank">https://liammcgcistudent.github.io/ucd-milestone-project</a></p>


<h2>Credits</h2>
<h3>Content</h3>
<p>The text for "Home" was copied from the Wikipedia article <a href= "https://en.wikipedia.org/wiki/Panic!_at_the_Disco" target= "_blank"></a></p>
<p>The text for "The Band" was copied from the Wikipedia article <a href= "https://en.wikipedia.org/wiki/Brendon_Urie" target= "_blank"></a></p>

Media
<p>The photos used in this site were obtained from:
<ul>
<li>Page Icon <a href="https://cdn.shopify.com/s/files/1/0001/8022/4052/products/panic-at-the-disco-logo-sticker-s8022_08db9aaa-2cf8-4ace-a1b5-0432d1213332_1200x1200.jpg?v=1521505157" target="_blank">https://cdn.shopify.com/s/files/1/0001/8022/4052/products/panic-at-the-disco-logo-sticker-s8022_08db9aaa-2cf8-4ace-a1b5-0432d1213332_1200x1200.jpg?v=1521505157</a></li>
<li>Band Image <a href="https://en.wikipedia.org/wiki/File:Panic!_At_The_Disco_Shorty_Awards_2015.png" target="_blank">https://en.wikipedia.org/wiki/File:Panic!_At_The_Disco_Shorty_Awards_2015.png</a></li>
<li>Background Image <a href="https://www.thinglink.com/scene/852988253874159616" target="_blank">https://www.thinglink.com/scene/852988253874159616</a></li>
<li>Brendon Urie Image <a href="https://static.independent.co.uk/s3fs-public/thumbnails/image/2018/06/18/17/screen-shot-2018-06-18-at-17.13.32.png?width=1368&height=912&fit=bounds&format=pjpg&auto=webp&quality=70" target="_blank">https://static.independent.co.uk/s3fs-public/thumbnails/image/2018/06/18/17/screen-shot-2018-06-18-at-17.13.32.png?width=1368&height=912&fit=bounds&format=pjpg&auto=webp&quality=70</a></li>
<li>Brendon Thank You Image <a href="https://i.pinimg.com/originals/42/68/9a/42689acc3819ee4f6a3f878a92d5c7c4.png" target="_blank">https://i.pinimg.com/originals/42/68/9a/42689acc3819ee4f6a3f878a92d5c7c4.png</a></li>
<li>Album Cover 1 <a href="https://en.wikipedia.org/wiki/Pray_for_the_Wicked#/media/File:PATD_PFTW.jpg" target="_blank">https://en.wikipedia.org/wiki/Pray_for_the_Wicked#/media/File:PATD_PFTW.jpg</a></li>
<li>Album Cover 2 <a href="https://en.wikipedia.org/wiki/Death_of_a_Bachelor#/media/File:Death_of_a_Bachelor.jpg" target="_blank">https://en.wikipedia.org/wiki/Death_of_a_Bachelor#/media/File:Death_of_a_Bachelor.jpg</a></li>
<li>Album Cover 3 <a href="https://en.wikipedia.org/wiki/I_Write_Sins_Not_Tragedies#/media/File:Panic!_at_the_Disco_-_I_Write_Sins_Not_Tragedies.png" target="_blank">https://en.wikipedia.org/wiki/I_Write_Sins_Not_Tragedies#/media/File:Panic!_at_the_Disco_-_I_Write_Sins_Not_Tragedies.png</a></li>
</ul>
</p>

<p>The videos used for this project are as follows:
<ul>
<li>Hey Look Ma, I Made It <a href= "https://www.youtube.com/watch?v=BzbxacRr5Gk" target="_blank">https://www.youtube.com/watch?v=BzbxacRr5Gk</a></li>
<li>Say Amen (Saturday Night) <a href= "https://www.youtube.com/watch?v=jVXauWq9Hwg" target="_blank">https://www.youtube.com/watch?v=jVXauWq9Hwg</a></li>
</ul>
</p>

<h3>Acknowledgements<h3>
I received inspiration for this project from the song and music video for "High Hopes" by Panic! At The Disco. I wanted to choose a topic that I was enthusiastic about for my project, and as I am a big fan of Panic! I chose to create a website for them.