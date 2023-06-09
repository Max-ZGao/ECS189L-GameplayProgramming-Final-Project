# GameplayProgramming-Final-Project

# Game Project  Initial Plan
# Core Concept

## Provide a synopsis for your game.

In " **Papa's Bobaria,**" you step into the role of a skilled boba shop barista, tasked with creating delicious and customized drinks for a bustling crowd of customers. As the game begins, you find yourself in the heart of the kitchen, surrounded by various stations and equipment necessary to fulfill orders. Orders will appear at the top of the screen, presenting a combination of random ingredients, flavors, and toppings. You must swiftly navigate the kitchen, visiting stations such as the Topping Station, Powder/Syrups Station, and more.

With a 2-D top-down view, you move your character strategically, grabbing ingredients, combining them, and processing them when necessary. Time is of the essence as you strive to complete orders before they disappear from the list. Prepare to immerse yourself in a fast-paced, addictive boba-making experience that will put your multitasking skills to the test. Can you become the ultimate boba master in "Papa's Bobaria"?

## Describe the core gameplay system of your game.

The core gameplay system of "Papa's Bobaria" revolves around the player's ability to manage time, navigate, and quickly serve drinks. The game is designed with multiple stations and a timer-based mechanic adds an element of challenge. Here are some elements of the gameplay system:

![](RackMultipart20230609-1-u2z8w1_html_35e4552b874f51ae.png)

_Diagram of gameplay system._

1. Order Generation:
  - Randomized Ingredients: Orders are generated with random combinations of ingredients, flavors, and toppings, ensuring each order is unique.
  - Timed Orders: Orders appear at the top of the screen and have a time limit before they disappear from the list. Players must complete the order before it disappears to receive points.
2. Player Movement and Actions:
  - Top-Down View: The player controls a character in a top-down view, navigating the kitchen to reach different stations.
  - Ingredient Handling: The player can hold a limited number of ingredients at a time and walk around the stage to process them.
  - Processing Mechanics: Certain ingredients may(?) require mini-games or quick-time events, simulating actions like boiling boba or shaking a drink.
  - Delivery: Once the order is complete, the player must deliver the finished item to the Serve Station before the order disappears from the list.
3. Stations and Ingredients:
  - Cup Station: The player can grab a cup to start the order.
  - Topping Station: The player can add various toppings to the drink (by using drag and drop mechanics?)
  - Base Station: Offers options like tea, water, or milk. The player can click on the correct container to fill the cup.
  - Powder/Syrups Station: Provides a selection of powders and syrups that can be added to the drink.
  - Ice Station: The player can add ice to the cup.
  - Serve Station: The final station where the player turns in the completed order.
4. Scoring and Progression:
  - Time Tracking: The game may track the time taken to complete each order to encourage speed
  - Score Calculation: Scores are based on accuracy, speed, and customer satisfaction, considering correct ingredients, timely delivery, and customization.
  - (if time allows - ) Progression and Unlockables: As the player achieves high scores and progresses, they can unlock new ingredients, stations, or challenges, providing a sense of achievement and variety.

## Explain your implementation plan to develop your core gameplay system.

_Outline the classes, Unity entities (e.g. GameObjects, ScriptableObjects, and major components), scene hierarchy, and assets you plan to use in the development of your core gameplay system._

**PlayerController[class]** - converts input to player movement/interactions

**CameraController[class]** - controls camera movement to follow player around the kitchen

**Stations[class]** - encapsulates behavior of ingredient/mixing stations (e.g. toppings, blender, etc), either dispenses ingredient or attempts to combine ingredients

**Prefabs (toppings, counters, etc) -** toppings are dispensed, while counters can be interacted with by the player

**Scene hierarchy -** floor and lighting, prefabs (stations, chairs, etc)

## Why do you want to make this game?

_What is appealing to your team about this game? Why did you choose this idea out of all the possible ideas?_

Our team believes that this game is appealing due to its mechanics and theme. The core gameplay mechanics are straightforward, which makes the game accessible. The game has an emphasis on multitasking and time pressure, creating a fun and challenging experience that requires players to be strategic. The boba shop setting is also fun and allows players to fulfill their dreams of working at a boba shop.

## Explain your game and the major systems it is composed of in terms of other games and genres.

_This is the "related works" of your initial plan. What games are closely related to your game in terms of: aesthetics, systems, genre, etc._

In terms of related systems, we took inspiration from the popular cooking-coop game Overcooked. Similar to Overcooked, Papa's Bobaria also features a top-down view of the player in a kitchen setting tasked with creating a drink according to the customer's orders. Some of the systems that are similar to Overcooked are the random order generation that gives a random combination of ingredients, toppings, etc. for the player to make. Furthermore, these orders are timed, which adds pressure to the player.

We are also thinking of adding a more interactive minigrame for some of the stations which may require the player to shake a drink or boil boba with the click of a mouse. While this is still being thought through, this system would be similar to that of the Cooking Mama games which had players prepare a virtual meal step-by-step.

## List your non-core gameplay systems and features.

There are not many features we plan on implementing due to the time constraint. If possible, we'd like to add minigames that use the mouse to simulate the task of making a drink such as stirring or shaking the drink before serving it to the customer.

#


# Your Team

![](RackMultipart20230609-1-u2z8w1_html_14295b971511b6f5.png)

## Member: [Kwantip, ktachasooksaree@ucdavis.edu email]

_ **Input** _ _(2/5): I honestly don't have much confidence in this field but I think I can figure it out. I didn't really choose this role, but it was the only one left so I can fill._

_ **Audio** _ _(3/5): I feel like this field goes hand in hand with the design of the visuals. Either way I think I have an idea of how it should sound like. I chose this role because I think audio is extremely important in games and it's one of the things I pay attention to when I play games (usually not the music, but the sound effects of click different things.)_

_ **Hope** __: I hope I can help out as much as possible and not be a hindrance to my team_

_ **Challenges** __: As mentioned, I'm not very confidence with input, but I (hope) can figure it out. Another challenge I think I will face is trying to coordinate an aesthetic with the visuals. I hope that the sound won't be out of place (like I want it to have the same flow as the rest of the game) when we submit the final game._

##


## Member: [Jason Dao, jkdao@ucdavis.edu]

**Main: Animation & Visuals** - Confidence 4/5: I have created sprites, animation, and artwork for games before so I have some experience in this area. I feel comfortable making engaging and charming visuals for the game. I will need to do more research to figure out how to implement the animations using Unity after they have been created.

**Sub: Press Kit & Trailer** - Confidence 4/5: I have a lot of experience with gameplay footage and video editing so I feel good about creating the trailer. I am mostly concerned about the time constraints for this role, as this is one of the items that must be completed later. Because of this, I hope to be able to contribute more to the actual game development while waiting to create the press kit and trailer.

**Hopes** - I hope that I will be inspired by creating this game and that the game is interesting to play and look at. I've never created a game fully from scratch so I'm hoping to learn more about the development process, mostly everything will be totally new for me.

**Challenges** - I think the biggest challenges will involve working as a team: we have a team of 6 busy students with varying skillsets and we will have to figure out how to coordinate ourselves effectively to complete the project. Unity and C# also still feel a bit foreign to me but I can revisit previous class projects to refresh myself.

## Member: [Max Gao, zhogao@ucdavis.edu]

**Game Logic - Confidence 4** : My role is to manage the game states and game data within your Unity game project. My previous experience in building databases gives me valuable insights and skills that can be applied to implementing the underlying systems that control how the game should behave

**Game Feel - Confidence 5** : My sub role involves enhancing the overall player experience and immersion by fine-tuning various aspects of the game, with experimentation, playtesting, and iteration. As a player myself, I hope to make the gameplay more immersive, engaging, and enjoyable for players.

**Hopes -** I hope to utilize gameplay programming logic from the class class to design mechanics, challenges, and progression systems that keep players engaged and provide a sense of satisfaction and enjoyment. It is also a great experience to improve my programming abilities, game design expertise, or project management skills.

**Challenges -** Integrating with various technical aspects, including coding, physics, graphics, AI, optimization… will be a big challenge for this project. Multi tasking and time management are also vital to a group project. I am committed to facing these challenges head-on, knowing that they will ultimately contribute to my growth.

## Member: [Eriz Sartiga, egsartiga@ucdavis.edu]

**Game Logic - Confidence 4:** In the past couple weeks, I've come to realize that I enjoy programming in this class. I believe this good impression will not only carry my mind through this project but will ultimately lead to a better project. I also feel comfortable with the design patterns presented in the class, which is why I chose the role.

**Gameplay Testing - Confidence 4:** I have some experience with testing gameplay in the past for companies such as Crystal Dynamics. Furthermore, I enjoy playing games similar to the one we will be creating for this project. I believe these two things will help me succeed in this role.

**Hopes:** I hope to apply the design patterns in this class into a successful game. I have no doubts that it will take lots of grueling hours of debugging and testing (as it has been for the past couple weeks), but this practice will make me into a better programmer.

**Challenges:** I think the main challenge of this project will be the time constraint and keeping all of our ideas into the subset of ideas that are achievable. I find it very easy to think of multiple features that would make gameplay more interesting; however, not all of the ideas brought for should be implemented due to time constraints. Furthermore, additional features could make the gameplay too complicated (which is not good for the users).

## Member: [Rongshan Gao, rongao@ucdavis.edu]

**Main: Movement/Physics -** Confidence 4/5: I feel comfortable working with PlayerController implementations and managing user input from previous projects in this class. Additionally, I also feel confident creating fluid camera movement that will be required for a top-down fast paced game like Papa's Bobaria.

**Sub: Press kit/Trailer -** Confidence 3/5: While I have had little experience working with video editing software for trailers and such, I'm sure that I can pick it up with the help of my groupmates, and deliver an exciting trailer for our game.

**Hopes:** I want to make a well designed game that I would personally enjoy playing, and I know that my group mates and I all have very interesting gameplay mechanic ideas that will help this game reach that goal. I hope that we can strike the right balance between finding a good work schedule and implementing as many of our ideas as possible.

**Challenges** : Our biggest challenge will be finding common working time between the 6 of us, as well as prioritizing essential gameplay mechanics when the deadline approaches.

## Member: [Thomas Chen , tcychen@ucdavis.edu email]

**Main: User Interface** - Confidence 4/5: I feel confident in my ability to create the best user interface and provide an exceptional user experience in our game, as I have extensively explored various game interfaces. Drawing inspiration from my exposure to different games, I believe I can learn from their strengths and incorporate the best practices into our game

**Subrole: Narrative Design** - Confidence 3/5: I must admit that I lack experience in Narrative Design, and I've never considered myself a particularly skilled storyteller. However, I firmly believe that I have the ability to create a narrative that will provide players of our game with a refreshing, immersive experience and the best user experience.

**Hopes:** My hope for this game project is to create the game we've all wanted, and along the way, gain valuable insights into the game development process, from stretch to the final delivery.

**Challenges** : I believe there are multiple challenges in this game project. As a group, we need to effectively utilize the strengths of the 6 of us within the limited time we have. Personally, I anticipate challenges in designing the user interface and ensuring a seamless user experience.

![Shape1](RackMultipart20230609-1-u2z8w1_html_237499165a11f2b9.gif)

#


#


# Scheduling

## Provide a timeline for completing your project.

From now till the final presentation we have 3 weeks in total to complete this project. So we have a outline for each week.

Week1: Basic Game Design

Week2: Mechanism Design and Implementation

Week3: Testing and Prestiation

## Schedule for each part of the game ![](RackMultipart20230609-1-u2z8w1_html_4a1d67acb0036139.png)

##


## How would your game be if everything went as planned?

The core gameplay mechanics would be fully implemented and refined. Players would engage in various mini-games and tasks related to running a boba shop, such as taking customer orders, preparing drinks, managing resources, and satisfying customer demands. A diverse selection of mini-games will be implemented, each offering unique challenges and gameplay mechanics. The user interface would be intuitive, providing clear feedback and guidance to players. Extensive testing and quality assurance processes would result in a game free from major bugs, glitches, and stability issues.

## What would the results be if you lost significant time (e.g. you lost two weeks due to unforeseen circumstances)?

With a reduced development timeframe, we would have to prioritize essential features and systems for the core gameplay experience. Minigame upgrade features will not be implemented.

Content creation, such as level design, asset creation, and narrative development, may need to be streamlined to meet the shortened timeline. We may reuse existing assets, simplifying level layouts, or reducing the scope of non-significant elements.

Reduced time also means less time for tuning and optimization after the construction of the overall game, which can negatively impact the player experience.

## If your progress is faster than expected, how would your game change?

We are going to add additional features and enhancements to our game. With more time available, I could introduce additional mini-games to diversify the gameplay experience. Players will be able to decorate boba drinks or manage customer queues.

Additionally, we can implement an upgrade system for devices and stations in the boba shop. Players could use the money earned from their successful gameplay to purchase new and improved equipment, such as advanced blenders, automatic boba cookers, or upgraded tea brewing machines. These upgrades would enhance efficiency, speed, or quality in the mini-games, offering a sense of progression and allowing players to handle more complex orders. Players could hire and train employees to assist them in the mini-games, effectively skipping or speeding up certain tasks. This would provide a strategic element to the gameplay, allowing players to allocate resources and optimize their workflow to maximize efficiency and profits.
