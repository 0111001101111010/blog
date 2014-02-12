title: Dominion Enterprises Hack University Hackathon #2
date: 2014-02-11 23:53:51
tags: lanica
---


Dominion Enterprises Hackathon
=====

A hackathon (also known as a hack day, hackfest or codefest) is an event in which computer programmers and others involved in software development, including graphic designers, interface designers and project managers, collaborate intensively on software projects.

This was Dominion's Seventh hackathon and second edition of HackU, a hackathon where schools were invited across Virginia. Paired with three coaches and given 24 hours, each team was read a challenge on gameification and set off to build something. None of the members of our team had more that a few hours of experience with titanium and almost none with Lanica. 

The inspiration
======
The concept of the game came from staring off the 20th floor of Dominion Enterprises. We were using the windows as white boards, and one of our team mates suggested a game where you dodged obstacles and projectiles on a motorcycle. But then we thought it would be more fun to be the one chucking the obstacles. 

Neighborhood Watch was thus born. 
A pack of reckless motorists have invaded your neighborhood. Protect your neighbors as they cross the street by egging the cars before anyone gets hurt.

Playstore: https://play.google.com/store/apps/details?id=com.DWS.neighborhoodwatch
Github:  https://github.com/stanzheng/HackU2

Day1:
---
At the end of day one 

Day2: 
----





Some of the Cool Stuff From Platino
======
Here are some of the notable ways we used parts of the game engine; The game engine did much of the heavy lifting and kept the game in the development zone. Writing in a familiar codebase of javascript, it was easier to produce. We did run into a few hic-cups and nuances in appcelerator and platino 


Sprite Collisions 
---
- The sprites along with being really easy to to import also inherited collision. This made it easy to do create listeners and events for when vehicles hit pedestrians or when the eggs hit the cars. 

Camera Pan
---
- The beginning animation was created using a sprite image and a pan. Super easy to create an pseudo animated home screen. In addition, both of the home and end screens were created by sprites that we hoped to create into animated span screens. 


Transforms
----
- The vehicle sprites were created with vehicle view sprites that we then rotated. This way we only needed a single sprite that we then could animate.
- Jossling was also a feature we utilized to make the sprites seem less linear. It multiplied the sprites with a coefficient to of random bounciness, which made our assets come alive. 


Platino 
-----
- The animations of Grandma tossing the eggs were created using transform along with Platino constants. This made it easy for to say, go from point A->B but in a curved way or in a zig zag.   
- Generally platino being built off of appcelerator opened up a lot common tasks in the framework.In our app we were able to render full html pages for about and planned to create a UI for settings using titanium UI windows. 



Created with love by The Grumpies
----
Stanley Zheng @stanzheng http://github.com/stanzheng
Jose Mateo @jmate003 http://github.com/jmate003
Onapha Rattana @cosmicmeow http://github.com/cosmicmeow
Trisha Tobias @aureately http://github.com/aureately
Anthony Bittle @guywithnose http://github.com/guywithnose
Chris Ryan @chrisryan http://github.com/chrisryan
Brandon Beigay
Krishna
