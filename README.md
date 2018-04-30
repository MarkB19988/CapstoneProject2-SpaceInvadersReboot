# Space Assault

## 1.0 Project Management Documentation

### 1.1 Project Overview, Aims and Objectives

##### Overview

'Space Assault' will be a rebooted version of the classic arcade game 'Space Invaders'. It will keep the main goal of the game which is to defend your base from ailien attackers by destroying them before they land, but will incorporate more features to add more depth to the game. The feature will include things like PvP multiplayer, Power ups and new enemy types.

##### Project Aims

1. During this project I will aim to create a more challenging, rebooted version of the classic game 'Space Invaders' 

2. I will create a multiplayer enviroment in which 2 players can interact with eachother

3. I will create a intuative control scheme for the player

4. I will create a leaderboard that is stored on a database

5. I will implement 5 new power-ups that can aid the player.

6. I will aim to have this project ready to be delivered by the 23rd of March 2018


##### Project Objectives

1. To create a multiplayer enviroment I will create a database system using google firebase. I will then run a test to make sure that both players ships can be seen and move when the other play moves, When both players ships move correctly this objective will be met. This will be completed by the 19th March 2018.

2. To make sure that my controls are intuative, I will be running playtests with my peers. To measure how close I am to an intuitive control shceme I will be asking participents to rate the controls out of 10 for how easy they were to understand and figure out. If the average respose is atleast a 7 out of 10, this objective will be met. I will aim to have this complete by the 15th of March.

3. To create my leaderboard database I will also be using google firebase. To check if all players will be able accesss the database I will be putting placeholder values in the database and testing the ingame leaderboard to see if it displays those values. If it does display those values, this objective will be met. I will aim to have this completed by the 15th of March.

4. To make sure that the new power-ups work as intend I will be creating a test level that spawns infinite copies of each new power-up. I will then collect this power-up and compare the ingame effects it gives to the intended effects. If the effects match, then this objective will be complete. I will aim to have this completed by the 18th of March.


### Project Management Plan

### 1.2 Communication

As this is a solo project communication outside of working hours with team members will not be required, howerver there are several key dates that I will be presenting my progress on to my peers and the final product demonstration. Both of which will require me to deliver a presentation to show my ideas and my progress.

on the 11th of March I will be presenting my ideas to my peers. for this I will be making a power point presentation and presenting it to the class. I will be using a mix of verbal, visual and non verbal (body language) communication to convey my points to my peers

On the 26th of March I will be presenting my final product to my peers. Again I will be making a powerpoint presentation and using the same communication styles. However this time I will be also running a demo of the full game for my peers to play and I will be asking questions and collecting feedback from them aswell.

### 1.3 System Requirements/Resources
In order to complete this project, I will need access to the following:

##### Unity
I will be using Unity to develop my game as it can easily be used to develop for the PC platform which I plan to develop the game for. I also have a lot of past experience with Unity having used it to develop past projects.

##### Internet Access
I will need internet access to help me collect secondary research data through sources such as public reports and web articles, and my primary research as I plan to use online surveys to collect data. Additionally, web access can help me work more efficiently as I can save my work to the cloud and work from home as well as in class.

##### Computers With Apropriate Specs
I will need a computer that has capable techinical specifications to run my required software e.g. Unity. I will be checking Unity's minimum requirements to make sure my system(s) meet them and will run without issues.

### 1.4 Cost
As I will be developing for PC and possibly Android, I won't need to purchase developers licences as these platforms can be developed for and launched on for free. The cost for a Unity Pro licence is $125 per month. This is where a considerable ammount of the money that is spent on this project will go. Realistically, to account for possible delays I would need to purchase atleast 3 months of Unity Pro to make sure that I complete the project, this puts my Unity costs at $375.

I will need a system that I can develop on from home. My PC is fully capable of running development software and meets Unity's system requirements by a considerable margain. The cost for my home system was $970, although the purchase was made several years ago, I believe it is still a relevent factor to be included in the cost of my project.

My home internet access costs $45.99 per month and is required for this project for the reasons stated in section 1.2.1. So assuming the project runs for 3 months I will include 4 months of internet access in the cost of the project for contingency incase of delays. This totals $183.96

All other software that I will need to create presentations and documentation is free (Microsoft Office, Google Docs ect.)

In total I put the cost of this projects development at $1528.96

### 1.5 Scope 
The game must stay close to the style and theme of the original Space Invaders while adding new features. Our new features should not change the way in which space invaders itself is played. They player must still have the same ovjective of destroying ships before they reach the ground.

We will be adding new ships with new abilities for the player to face, such as a ship that fires multiple shots at once, or ones that move faster than the others so must be taken out first. Despite this, no ships will add new objectives to the game or change the end goal for the player. Similarly, new powerups that the player can collect can change how the players ship behaves or how it fires, but will not change the fact that the player must stay on the bottom of the screen and defend against the invading ships.

### 1.6 Time Mangement/Schedule 

#### Gantt Chart

My Gantt Chart shows how long I will be expecting to work on each section for (timeframe)

![spaceassault-gant-chart](https://i.imgur.com/zhoxB4N.png)

#### Work Breakdown Structure (User Stories)

Each of my user stories will be assigned a point value based on the challenge that they provide (1 for easy, 5 for challenging). I will use these points to map a burndown chart to help further manage my time effectively and to provide milestones for completion.

#### 1. As a user I would like to be able to open the game 
###### Point Value = 1
###### This is a simple task as all I have to do is make the game run on the computer without crashing at startup

#### 2. As a user i would like to be able to view the controls (How to play)
###### Point Value = 2
###### To implement this I will add a new option to the main menu for the player to click on a view information on all of the controls. the section will be titled 'How to Play'

#### 3. As a user I would like to be able to easily navigate the menu
###### Point Value = 2
###### I will make the main menu easy to navigate I will be allowing the user to navigate the menu using either the mouse or the keyboard arrow key or 'W A S D'

#### 4. As a user I would like to be able to move my character around
###### Point Value = 2
###### The player will have a choice between using either the arrow keys of 'W A S D' to control his ship so all I need to do is test both of these control methods to make sure they work correctly

#### 5. As a user I would like to be able to see the enemy ships
###### Point Value = 2
###### All I have to do is test if the NPC ships are rendering and moving correctly 

#### 6. As a user I would like to be able to shoot at the enemy ships and have them be destroyed
###### Point Value = 3
###### The fire button will be bound to the space bar, so I'll have to test if this keybinding is working correctly. Also I will ahve to test the collision detection between the projectiles and the enemy ships to make sure that hits are regestering

#### 7. As a user I would like to be able to keep track of my score
###### Point Value = 2
###### All ships will be assigned a different point value depending on their type. I will make a section appear at the top of the screen that shows the players current score and test each ships point value

#### 8. As a user I would like to be able to know how many lives I have left
###### Point Value = 3
###### The same as the previous user story except with the players lives. I will also need to test the collision detection between the player and the NPC's projectiles.

#### 9. As a user I would like to be able to know when the game is over
###### Point Value = 1
###### Display a 'Game Over' screen when the player runs out of lives

#### 10. As a user I would like to be able to view the high scores
###### Point Value = 4
###### More complex as I will have to create a database to hold all of the high scores and make sure that each player can access this database whenever they click on the leaderboard option in the main menu

#### 11. As a user I would like to be able to see my friend control his ship on my screen (multiplayer)
###### Point Value = 5
###### More complex as I will have to create a database to store the position of all NPC's and both players. The database will need to be accessed in real time to provide updates to each client

#### 12. As a user I would like to be able to know when my friend loses a life
###### Point Value = 4
###### A similar counter will be displayed alongide player one's lives but will need access to the database to retrieve information on player two's current lives

#### 13. As a user I would like to be able to leave the game at any point
###### Point Value = 1
###### Implement an in-game option to leave to the main menu

### Sprint Structure
I have 4 weeks until the project deadline so in order to manage my time and workload I will be dividing my user strories into four week long sprints that have a similar point value each week. My sprints are as follows:





| Week and Date | Stories Being Worked On | Sprint Point Value | Comments |
|----------------------------|------------------------------|----------------------|--------------------------------|
| Week 1 (23rd of Febuary - 2nd of March)           | The user stories I will be aiming to complete this week are stories 1, 2, 3, 4 and 5. | These give me a total point value for this week of 9. | Completing these 5 stories will also provide me with the core mechanics that I can build upon to complete my future sprints.|
| Week 2 (2nd of March - 9th of March)          | The user stories I will be aiming to complete this week are stories 6, 7 and 8. | These give me a total point value of 8 | Completing these 3 stories will give me the main body of my game and a early demo that I can test and get other people to play for feedback. |
| Week 3 (9th of March - 16th of March)            | The user stories I will be aiming to complete this week are stories 9, 10 and 13. | These give me a total for value for this week of 6 | This is the lightest week in terms of workload so this is where I could make up for lost time or get ahead on next weeks work. Completing these 3 stories will provide the game with its leaderboard functions and the leave game button will allow the player to restart the game with ease. |
| Week 4 (16th of March - 23rd of March)           | The user stories I will be aiming to complete this week are stories 11 and 12. | These give me a total for this week of 9. | This is the last week I have before the project deadline. At this point the game will have a fully working single player so this week will be focused on building the multiplayer. This is what I believe to be the most dificult aspect so as the previous week has less of a point value I may be able to start working on this weeks work earlier. |

### Burndown Chart
This burndown chart shows how well I kept to my sprint schedule and tracks how many points I had left to complete at any given time

![Imgur](https://i.imgur.com/iptYhM7.jpg)

### 1.7 Risks
The project runs several risks that could cause problems that would set back the project, they consist of the following:

##### Cost Management
One possible risk to the project is one of cost. I could have underestiated the cost of something that I need to complete the project. This would undexpectedly drive up costs midway through the project and could stop the project completely if the money could not be found in time.

##### Hardware/Software Issues
Hardware such as my home PC or the internet router could become damaged or simple break and stop working. This would have a huge impact on the progress of the project as I would be unable to work from home until I got the computer repaired, this would also drive up costs. If the router broke or the internet stopped working for other reasons, I would not be able to access online articles/books for research. I would also not be able to access any work stored on cloud servers form wherever the internet went down.

##### Personal Illness/Emergency
Personal illness or an emergency personal matter could force me to take time away from the project and as the project had a fixed deadline, this could result in the project being incomplete by this date due to not enough time being allocated to the project.

### 1.8 Contingency Plans
To try and reduce the impact these risks could have on the project I have put in place some coningecy plans to account for each risk, they are as follows:

##### Cost Management Contingency
To account for any possible unexpected cost increases, In the total cost estimate for the project I have included and 30% overhead to act as a saftey measure that can be used to pay any unexpected costs that may arise during the project. As this money is accounted for before the project is started, I can guarentee that the money will be availible at any point during the project should it be needed.

##### Hardware/Software Issues Contingency
To account for PC issues. I will have all the software that I need installed on multliple machines (Home desktop, Personal laptop and College computers). By having these back-up systems to work from, I will be able to continue my work from any one of these machines as my work will be stored on the cloud. To account for internet issues and being unable to access my cloud data, I will always keep an up ot date backup of my project on a external harddrive so I can still take this to any machine and work on my project even without internet access

##### Personal Illness/Emergency Contingency
To account for personal illness or emergencys, in my schedule I have set the completed date for my project 10 days ahead of the deadline for the project. By using my time effectively and creating a well thought out schedule I am able to have spare time included in the schedule that can be used up by emergency situations without pushing the project completion beyond the deadline.

### 1.9 Quality Assurance

In order to assure a high quality in my finished game Inwill be running extensive tests during the development of the game to assure thst all of the features I will be implementing work as intended. For example I will be testing the controls separately from the multiplayer connectivity to assure thst each one works correctly without interference from another feature. Only after all features work independently will I put them all together. By doing this I can minimize the amount of bugs that my game could have at launch

Once all of the features are together and the game is working I will start running playtests. My playtests will involve me getting 5 different people to play my game. They will fill out a feedback form and report any bugs they encounter while playing. During the playtest I will also be taking Quality of Life suggestions from the testers to further improve the quality of my game.

### 1.10 Feasibility Report

##### Products and Services
'Space Assault' is a planned reboot and reimagining of the classic 1978 arcade game 'Space Invaders'. This reboot will add a numerous new features into the game while retaining the original concept and goals of the game, which is to destroy the enemy ships before they land. The features that will be added to the game are the idea of power-ups that the player can pick up that will change the behaviour of his ship (e.g. new weapons, faster movement, defence repairing). The most promenent feature that will be added is the introduction of PvP muliplayer in which one player takes on the role of defence and another player take on the role of the attackers, sending in more ships using points that they accumulate by destroying the defenders blockades and shields.

##### Technology Considerations
The technology required to complete this project has already been aquired. This includes high speed internet access that is already availible at the college campus and my home internet package that I pay for monthly, the costs of which have already been added up and included in the cost of the project in section 1.3. The software needs are also met, as the college as well as my home PC both have access to Unity and IDE software. This coupled with the internet access allows me to work on the project from anywhere using the cloud, all of which has also been calclulated into the total costs for the project. Hardware requirements must also be considered as the computers I have access too must also be able to run the software required. Fortunatly both the college computers and my home PC meet Unity's minimum requirements by a significant margain, so no issues should arise in this area and the project should go ahead without any readily aparent technical issues.

##### Product Marketplace

### 1.11 Research Project (How to Reduce Vulnerabilities In Software During Development)

##### Introduction
Software development is the process of making a system or application.
A key part of building a system is making that system secure. While new vulnerabilities in existing systems can be exposed at any time, it is always important to try and minimize or reduce the vulnerablities in a system during it's development. In order to make sure that I take the correct steps I will be undertaking a research project to determine what I can do to reduce the vulnerabilities in my game during development.

##### What Are Vulnerabilities?
Software vulnerabilities are bugs, glitches or flaws that can be found in a piece of software or an operating system. Vulnerabilities can be left in software entirely by accident if the correct precautions are not taken to identify and reduce said vulnerabilities.

##### How Does This Research Link To My Project Aims and Objectives?
By performing this research of software vulnerabilities I will be able to use what I learn to reduce the vulnerabilities in my game during development. As the game will have a multiplayer aspect to it. The will be an even greater need for a secure connection with no vulnerabilities that can be exploited. This research will help me to understand how to test for vulnerabilities and how to better reduce the risks of vulnerabilities being implemented into my software by accident.

##### Difference Between Qualitative and Quantitative Research
There are two distinctive types of research that can provide different types of data, these are Qualitative and Quantitative research. Qualitative research refers to more detailed data that is not numerical, such as interviews and case studies. This type of research provides a more in depth look into the area of your research and allows for mroe detailed conclusions to be drawn. Quantitative research refers to information gathered that is numerical and can be quantified. This type of research is best used in surveys that have a large number of participents as this type of data can be collected quickly. It can be used to create charts and graphs to provide a visual representation of the views of the participents on a given subject or question.

##### Methods of Information Gathering
For this research project I will be performing both qualitative and quantitative research in order to get a wide range of data to draw conclusions from. For my qualitative data I will be conducting two case studies on different cyber attacks or security breaches in order to find out how these attacks happened and what was done to prevent future attacks. For my quantitative data I will be creating a survey that I will be giving out a survey to programming students studying at various levels to find out how much programmers know about cyber security and if they practice good security themselves.

##### Survey Participent Demographic
For my survey I will be targeting programmers that are studying and various levels, this will range from level 2 all the way up to level 5 students. I am targeting programmers because these are the people that will need to thing about software vulnerabilities the most and will need to come up with ways to reduce these vulnerabilities while creating their software. The reason I have chosen to give the survey to programmers at various levels of study is to see if the ammount of experience a programmer has affects their knowledge of security and how to reduce software vulnerabilities. The participents themselves can be of any race or gender as this would have no effect of their programming abilities. As long as they study programming at a level between 2 and 5 then they cna fill out the survey.

##### Sampling Approach and Method
For my survey I will be using stratified sampling to chose people to fill out my survey. Anyone who studies programming can ask to be a participent up to a maximum of 20 people. However I will be choosing a specific number of people for each level group to fill out the survey. This is because I want to see if their is a correlation between the level of study and their knowledge of software vulnerabilities. For this reason I need to make sure I get participents from each level group.

The only issue of bias that could arise is if someone from my class filled out a survey for my level 4 programmer grouping. They could want to make jokes on my survey and not give accurate answers. So for this reason I will be trying to avoid having any participents I know personally.

##### Ethical Issues with Data Collection
To avoid any ethical issues arising auring my research with regards to consent forms and sensitive data about participents, I will not be asking any participents for any sensitive data at all. The survey will be anonymous for any and all participents, they will only have to state their level of study on the survey, the rest of the questions are a test of their knowledge.

#### Case Study Overview
In order to understand how to reduce vulnerabilities during development I will be performing two case studies on recent cyber attacks that have exploited vulnerabilities in existing software. By analysing how these attacks were successful and how they were stopped I will be able to better understand how these vulnerabilities were fixed or mitigated and use these techniques in my project.

##### Case Study 1 (WannaCry Ransomware Attack)

###### What Happened?
On the 12th of May 2017, a computer virus began to infect computers worldwide, this virus was called 'WannaCry'. WannaCry is a type of virus called 'Ransomware' that is designed to hold a person's data hostage by threatening to delete it or encrypting it. In the case of WannaCry, it did both. (However no reports of permanent data deletion were recorded after the attack had ended). Once WannaCry had encrypted a person's data, the virus demanded a payment to be made of $300 in bitcoin and if not paid within 14 days, it doubled to $600. 

The virus spread using a backdoor in older windows systems tbat was exposed by the US government after they admited to having knowledge of hundereds of unpatched vulnerabilities in a variety of systems. The reason this backdoor vulnerability hadnt been patched is because the most affected operating system, Windows XP, was beyond if service life and had stopped recieving updates from Microsoft in 2011. This lwft the operating system very vulnerable to new viruses snd attacks. 

While most personal computers no longer run Windows XP, many older businesses and organisations have not upgraded theor operating system and still run Windows XP despite the security issues it brings. This was the main reason that WannaCry was able to cause so much damage and disruption in such a small length of time. The organisation that was most affected by the attack and thst was also the most talked about is tbe British National Health Service (NHS). The attsck crippled the NHS and affected their patient records and appointment logs so many who had scheduled appointments were delayed while the attack was dealt with.

###### How Was It Stopped?
On the 19th of May 2017 a killswitch was discovered within the virus' code that when activated, stopped the virus from spreading to any new machines. The killswitch itself was a string of cose than ran just before the encryption took place thst attempted to connect to an unregistered domain. if the attempt to connect was unsuccessful then the virus continued on to encrypt the data and spread. However once the person who spotted the killswitch registered the domain and put up a website at that address, the connection became successful and the virus then stopped before it affected the system it was on.

While this was successful in stopping the spread of WannaCry, it didnt help get back data that was already encrypted on other machines. What made thid worse is that despite a strong campaign to tell people not to pay as there was no guarantee that their data would be unencrypted, many people did pay. Resulting in the person(s) behind the attack making upwards of $100,000 during the course of the attack. But despite this there were no reports of anyones data being unencrypted after paying, Leaving many thinking that the data would be unrecoverable forever.


##### Case Study 2 (Ashley Madison Data Breach)

###### What Happened?
In July 2015, a group calling themselves "The Impact Team" stole the user data of Ashley Madison, an website that made it easy for its users to have affairs. The group accessed the company's user data and secretly copied it. They then threatened to leak it to the general public if the service was not shutdown 'immediately'. The company refused to shut the website down and initially claimed that any personal data had been erased. The website posted the following message on its twitter page.

###### "At this time, we have been able to secure our sites, and close the unauthorized access points. We are working with law enforcement agencies, which are investigating this criminal act. Any and all parties responsible for this act of cyber-terrorism will be held responsible. Using the Digital Millennium Copyright Act (DMCA), our team has now successfully removed the posts related to this incident as well as all Personally Identifiable Information (PII) about our users published online."

As they did not shut down the website as per demand, the company was on the look out for any leaks of users sensitive information and on the 18th and 20th of August 2015, the group leaked more that 25 gigabytes of the companys data, including users sentitive information. The data was uploaded to Bittorrent and was availible for anyone to download that had access to the dark web (as that is where the link to the torrent was posted). 

##### Primary Research

To help me find out what developers can do to reduce vulnerabilites I will be conducting a survey that I will give to students studying software development at various levels to find out what they know about cyber security and software vulnerabilities. Using this information I will be aiming to answer 3 key questions. These are:

###### 1. Do software developers understand what good cyber security? does this understanding grow with more experience?

By finding out if software developers understand good cyber security I can see if there is a correlation between how much knowledge they have in software vulnerabilities and how much experience they have in software development. This information cal then tell me if less experienced developers would need to have their code checked by a more experienced collegue in order to reduce the vulnerabilities of software during development. As less of an understanding may make their software more vulnerable.

###### 2. How highly do software developers value negative testing in reducing software vulnerabilities?

This is a very simple question that I will grade on a scale of 1 to 10, but I can use this data to check the reliability of my survey. for example, some participents may state that they have a good knowledge of security and software vulnerabilities, however may say that they don't value negative testing (which is a key technique in reducing software vulnerabilities). This would show me that they perhaps don't have as much of an understanding as they think they do.

###### 3. Do software developers know what software vulnerabilities are?

In order to reduce software vulnerabilities during development you must first know what vulnerabilities are. A possible way to reduce vulnerabilities during development is to train your staff to understand what they are if they do not have a good understanding. While developers should have a good understanding of what vulnerabilities are, I am going to answer this question to see if this is the case.

##### Table of Results
Below is a table of all of the survey results that I collected.

![Imgur](https://i.imgur.com/QBto2ob.png)



## 3.0 Design Documentation

### 3.1 Introduction
'Space Assault' will be a rebooted version of the classic arcade game 'Space Invaders'. It will keep the main goal of the game which is to defend your base from ailien attackers by destroying them before they land, but will incorporate more features to add more depth to the game. The feature will include things like PvP multiplayer, Power ups and new enemy types.

### 3.2 Game Objectives
The primary objective of the game is to survive as long as you can against infinite waves of attacking alien ships. The alien ships will move from side to side and slowly descend. The player controls a single ship that they can move left or right along the bottom of the screen and can shoot upwards to destroy enemy ships. If just one ship mskes it to the ground, the game is over. They play accumulates points by destroying enemy ships. Each ship has a different point value.

### 3.3 User Stories

###### As a user I would like to be able to open the game 
###### As a user i would like to be able to view the controls (How to play)
###### As a user I would like to be able to 

### 3.4 Genre
'Space Assault' will be a 2D arcade game, the game will be very similar to the original 'Space Invaders'

### 3.5 Platform 
I will be designing and developing my game for use on PC and will be looking to release the game via the Steam platform. I chose to develop for this platform for two reasons. Firstly I believe that I can create a better multiplayer enviroment on PC than on other platforms as I have more experience in developing games for the PC platform than I do for other platforms and this experience will equate to a higher quality game. Secondly I believe thst the PC platform is the most suitable for this game as the player will need to clearly see important information and have accurate controls thst sre not easy to missclick. This is the reason why I chose to not initially develop for the mobile platform however a mobile release has not been ruled out in the future.

### 3.6 Features

### 3.7 Overall Design

### 3.8 Coding 

#### 3.8.1 Algorithms

#### 3.8.2 IDE Used 

#### 3.8.3 Coding Standards

#### 3.8.4 Debugging 

### 3.9 Concept Art

### 3.10 Flowcharts

## 4.0 Evaluation 

### 4.1 Testing

### 4.2 Effectiveness of Testing

### 4.3 Critical Evaluation of My Performance

### 4.4 Critique Descision Making and Reasoning

### 4.5 Did I Meet The Project Aims?

### 4.6 Did I Meet The Software Requirements?

### 4.7 Did I Meet The Clients Requirements?
