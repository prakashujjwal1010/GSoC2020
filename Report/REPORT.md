# GSoC 2020 Final Report

#### Project Name: 
Sugarizer Game Activity Pack 
#### Organisation:
Sugar labs
#### Student: 
Prakash Ujjwal
#### Mentors:
Ashish Aggarwal and Lionel Laské 

### Project Introduction:
The name of the project is Sugarizer Game Activity Pack which consists of two activities - Mind Math activity and Tangram activity. These two activities are requested by Sugarizer deployment in Saint-Ouen.
* Mind Math Activity 
  * https://github.com/llaske/sugarizer/pull/817:
  * The Mind Math game activity is an engaging mathematical game which will encourage students to solve mathematical puzzles and will help in student’s development of computational fluency. The student is given five random numbers and should use the four basic arithmetic operations to build an operation that will result in the given output. The activity will have features like timer, multiplayer mode, localisation etc
* Tangram Activity 
  * https://github.com/llaske/sugarizer/pull/831
  * The Tangram activity will be an activity to play the traditional Tangram game. It will be a very joyful activity for children which involves a deep thinking activity, and which boosts visual-spatial and arithmetic skills of children. The activity will have features like timer, multiplayer mode, localisation etc.



> Sugarizer is a free/libre learning platform. The Sugarizer UI use ergonomic principles from The Sugar platform, developed for the One Laptop per Child project and used every day by more than 2 million children around the world.


### Mind Math Activity
##### Tasks Completed:
* Sugarizer look & feel: use of Sugar toolbar and palette
* Single Player mode and all of its workflows.
* Network integration: integrate Sugarizer presence to share the activity on the network so that multiple users could play together. Multiplayer player mode and all of its workflows implementation along with the Leaderboard screen.
* Question generation and hint generation algorithms.
* Timer and non timer mode 
* Result screen 
* Sugarizer storage: load/save content into the Journal
* Localisation:  User can use activity in different languages
* Tutorial: an integrated documentation should be integrated to explain each feature of the activity
* Responsive: content should adapt to any screen size, a fullscreen button should allow to mask the toolbar for smaller screens
* Multi-device support: should work on any browser (Chrome, Firefox, Safari) and any platform (Android, iOS, Windows, Linux, MacOS) supported by Sugarizer

*Play Screen*

![Play Screen](../screenshots/mindmath-1.png)

*Result Screen*

![Result Screen](../screenshots/mindmath-2.png)

*LeaderBoard*

![LeaderBoard](../screenshots/mindmath-3.png)

### Tangram Activity
##### Tasks Completed:
* Sugarizer look & feel: use of Sugar toolbar and palette
* Single Player mode and all of its workflows
* Network integration: integrate Sugarizer presence to share the activity on the network so that multiple users could play together. Multiplayer player mode and all of its workflows implementation along with the Leaderboard screen.
* Random Tangram generation algorithm integration.
* Algorithm to check if the tangram is solved or not.
* Set of Default tangrams 
* Setting Mode added and all of its workflows 
* Timer and non timer mode
* Result screen 
* Sugarizer storage: load/save content into the Journal
* Localisation:  User can use activity in different languages
* Tutorial: an integrated documentation should be integrated to explain each feature of the activity
* Responsive: content should adapt to any screen size, a fullscreen button should allow to mask the toolbar for smaller screens
* Multi-device support: should work on any browser (Chrome, Firefox, Safari) and any platform (Android, iOS, Windows, Linux, MacOS) supported by Sugarizer


![main](../screenshots/tangram-1.png)

*Play Tangrams of many types and categories*

![main-1](../screenshots/tangram-14.png)
![main-2](../screenshots/tangram-3.png)

*Easy game difficulty showing outlines*

![easy](../screenshots/tangram-6.png)

*Medium game difficulty only silhouette*

![medium](../screenshots/tangram-7.png)

*Timer Mode*

![Timer Mode](../screenshots/tangram-9.png)
![result screen](../screenshots/tangram-10.png)

*Setting Mode / Screen*

![setting mode](../screenshots/tangram-4.png)

*Create new Tangrams*

![setting mode](../screenshots/tangram-5.png)

*Create new Tangram Category*

![setting mode](../screenshots/tangram-11.png)

*Multiplayer Mode*

![multiplayer mode](../screenshots/tangram-12.png)

*leaderboard*

![Leaderboard](../screenshots/tangram-13.png)

### Miscellaneous
#### Worked on Chess Activity
* https://github.com/llaske/sugarizer/pull/702
*chess*
![chess](../screenshots/chess.png)

### Personal Notes:
Google Summer of Code has been a super comfortable and fun experience for me. I’ve explored Vue.js, konva.js, implemented and studied many wonderful algorithms and found so many interesting things regarding the same. In GSoC, Whenever I got stuck somewhere or had to deal with problems or bugs , my mentors were always there to help me.
I would love to be the maintainer for these activities and would try to solve issues regarding the same in the future. Also I would always be an active contributor in sugar Labs. 

