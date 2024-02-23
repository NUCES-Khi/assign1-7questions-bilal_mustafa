[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/oYBqdRz8)
# Assignment 1
|Std ID|Name|
|------|-|
|K224020|Mustafa Waqar|
|K224114|Bilal Asif|

## Q1
Write your answer to question 1 here ....
## Q2

    Q2: Examine the AI literature to discover whether or not the following tasks can currently be solved by computers.
       
    1. Playing a decent game of table tennis (Ping-Pong)
         
          According to AI literature computers cannot play table tennis like humans yet.
          While AI has witnessed remarkable progress across various domains, replicating human level or a decent level of table tennis proficiency remains a challenging obstacle.
          
          Accurately analyzing the balls dynamics is important to play.
          However, real world factors like lighting camera limitations and spin can bring uncertainty and errors in object detection and tracking.
          
          Table tennis is a dynamic game demanding real time decision making game based on many factors like ball state, opponents position and context of the game.
          Current AI models lack the understanding of these complex dynamics.
          
          Learning things in pretend situations, like video games, doesn't always work the same way in real life. This is because the pretend world might not have the same rules as the real world, and 
          things can be different. For example, the way things move, the accuracy of sensors, and unexpected things happening in real life can be very different from what the computer learns in                  simulations.
          
          Even though computers are really good at following set patterns and strategies, humans are even better at being creative and changing how they play based on who they're playing against and             how the game is going. Making computers act as flexible and adaptable as humans is still a hard thing to do.

    2. Driving in the Centre of Karachi
  
          Even though humans have made big progress in making cars drive themselves, right now, computers can't navigate safely on their own in busy cities like Karachi or other big urban areas.
          
          Karachi's traffic is really complicated because there are all sorts of vehicles, people walking around, and things happening unexpectedly. 
          Self-driving cars might struggle to handle all of this because they're not yet good at dealing with such complex situations. 
          They might not know how to react when things get really busy or when unexpected things pop up on the road.
          
          Even advanced sensors like LiDAR ( LiDAR — Light Detection and Ranging — is a remote sensing method used to examine the surface of the Earth ) and cameras struggle in challenging scenarios             like poor lighting, dust, and congested spaces.
          High-resolution, constantly updated maps are crucial for autonomous navigation. While maps of Karachi exist, they might not be detailed or dynamic enough for safe self-driving.

    3. Discovering and proving new mathematical theorems

          Scientists have for the first time used artificial intelligence to suggest and prove new mathematical theorems.
          The potential breakthrough came in a collaboration between mathematicians who specialize in pure mathematics at the universities of Oxford and Sydney, alongside Google-owned Deep Mind.
          Machine learning provides a powerful framework that can uncover interesting and provable conjectures in areas where a large amount of data is available, or where the objects are too large to           study with classical methods.
          
          Computers can check all possible cases to prove or disprove a theorem. 
          This is a brute-force approach (algorithmic paradigm that consists of systematically checking all possible candidates for whether or not each candidate satisfies the problems statement)                best suited for well-defined problems with limited possibilities.
          
          AI algorithms can analyze vast amounts of mathematical data to identify patterns and suggest new conjectures or theorems. 
          Here is just a handful of the many computer-based discoveries that could be mentioned:
          - A new formula for pi with the property that it permits one to rapidly calculate binary or hexadecimal digits of pi at an arbitrary starting position, without needing to calculate digits                that came before.
          - Evaluations of Euler sums in terms of simple mathematical expressions.
          - A new result for Mordell’s cube sum problem.

    4. Writing an intentionally funny story.

          Making people laugh is not easy because humor is complicated. It depends on everyone understanding the same culture, the right timing, and the situation. Even though computers are getting              better at understanding language, it's still hard for them to intentionally create funny things.
          Computers struggle to grasp the deeper meaning and intent behind humor. They can process words, but not necessarily the emotions, cultural references, and shared experiences that make                  something funny. 
          Humor usually works by surprising people or doing something unexpected. Although AI can come up with different combinations of things, being truly original and witty may be difficult for               them right now.
          Humor varies a lot from person to person and culture to culture. What one group of people finds funny, another might not . This makes it hard for AI to make universally funny stories without           help from humans who understand different cultures.
          Based on the current literature, computers can't truly write intentionally funny stories in the same way humans do.
          
          Based purely on my personal experience, during a conversation with Apple's Siri, I discovered that it can make funny comments or share short stories that might bring laughter or lighten the            mood. Let's see what AI literature has to say about this.
          Siri has a big collection of pre-written responses in its system. Some of these are made to be funny, using humor styles. It may seem like Siri is making clever jokes, but it's not creating            true creative humor like a person would.
          Siri can analyze your past interactions and preferences to tailor its responses accordingly. If you often respond positively to playful comments, it might choose those responses more often,            giving the impression of a funny personality.
          Siri can generate some text based on random combinations of words and phrases. While these might occasionally happen to be funny by chance, they often lack the specific context and intent              required for true humor.

    5. Translating spoken English into spoken Urdu in real time.
    
        Computers can translate spoken English into spoken Urdu in real-time.
        Accurate speech recognition systems exist for both English and Urdu, enabling real-time input like Google Speech-to-Text, Microsoft Azure Speech Services.
        English-Urdu translation models have been trained using various techniques, including statistical and neural approaches. Neural models generally achieve better accuracy.
        Google Translate, Microsoft Translator, and iTranslate are companies that provide instant translation between English and Urdu, both in text and voice.
        
## Q3

    Q3: Choose a domain that you are familiar with, and write a PAGE description of an agent for the environment. Characterize the environment as being accessible, deterministic, episodic, static, and         continuous or not. What agent architecture is best for this domain?

        Domain: Weather Prediction using Regression

        Here the Agent, looks at a bunch of past weather information to figure out how to predict what the weather will be like in the future. It uses a Machine Learning algorithm called regression,           which helps it understand the connections between the things that happened before like temperature, humidity, etc. and what the weather will be. The idea is to learn from the past to make              really good predictions about the future weather.
        
        Fully accessible, with complete historical weather data available.
        
        Deterministic in the sense that it’s affected by past conditions. However, it's not completely predictable because there's randomness and chaos in the system.
        
        Each prediction can be considered an episode, with a defined start (historical data) and end (predicted future).
        
        The underlying relationships between data and weather patterns remain constant over time.
        
        Both historical data and future predictions involve continuous values e.g. temperature, humidity.
        
        Learning agent would be the best for this domain as this kind keeps getting better with experience, which is great for understanding tricky weather patterns and always getting better at                predicting the weather.
        
## Q4

    Q4: For each of the following activities, give a PEAS description of the task environment. 
        PEAS
        
        Performance Measure:  The Performance Measure guides the AI agent's decision making by assessing the success or failure of its endeavors.
        Environment: The environment refers to the external context where the AI agent operates
        Actuators: Actuators represent the physical or digital mechanisms through which an AI agent executes actions in its environment.
        Sensors: They serve as the agent’s sensory organs to gather information from the environment.

    1. Playing soccer

        Performance measure: The number of goals scored and the ability to prevent the opponent from scoring.
        Environment: A playing field for soccer containing team members, adversaries, a match official, a ball, and diverse weather conditions.
        Actuators: Kicking, running, jumping, heading the ball.
        Sensors: Ball tracking sensors, GPS sensors on players, goal line technology.

    2. Shopping for used AI books on the Internet.
 
        Performance: Find books relevant to your interests, at a good price, and in good condition. 
        Environment: Online marketplaces like Amazon, Facebook Marketplace, or book websites. 
        Actuators: Searching, listings, filtering results, comparing prices, making purchases. 
        Sensors: Textual and Visual content.
        
    3. Playing a tennis match.

        Performance: Scoring points, winning the match, hitting accurate and powerful shots, returning opponent's shots effectively. 
        Environment: A tennis court with an opponent, a tennis ball, and various weather conditions. 
        Actuators: Serving, hitting , volleys, and smashes. 
        Sensors: ball tracking sensors, court sensors, and sensors on the tennis rackets.
        
    4. Knitting a sweater.

        Performance: Creating a well-fitting sweater with even stitches.
        Environment: A workspace with knitting needles, yarn, and  patterns.
        Actuators: The knitter's hands and knitting needles act as actuators
        Sensors: sensors on the knitting machine to monitor the knitting process, and environmental sensors to adjust for temperature and lighting conditions

    5. Bidding on an item at an auction

        Performance: Winning the item at the lowest possible price, considering budget and competition. 
        Environment: auction house with other bidders, an auctioneer, and the item being auctioned. 
        Actuators: Placing bids, increasing bids, and communicating with the auctioneer. 
        Sensors: Bid tracking sensors to monitor current bids, real-time feedback on bidding activity
        
## Q5

    Q5: For each of the following assertions, say whether it is true or false and support your answer with examples or counter examples where appropriate.

    1. An agent that senses only partial information about the state cannot be perfectly rational.

        False.
        An agent with limited information can still be perfectly rational by making the best possible decision.
        For e.g. in chess the agent may not have complete information about the opponent but it can still make the best possible moves based on the information it has.
        
    2. There exist task environments in which no pure reflex agent can behave rationally.
    
        True.
        Pure reflex agents react to the current situation without taking in notice the past experiences.
        For e.g. in rat and maze problem after reaching a dead agent with no possible moves the agent will not backtrack as it does not have past information.

    3. There exists a task environment in which every agent is rational.
    
        False.
        Not every task environment allows for rational behavior by every agent.

    4. The input to an agent program is the same as the input to the agent function.

        False.
        The agent program executes the agent function so the input might differ.
        The program may preprocess or filter data before passing on the information to the function.
        For e.g. in NLP input to the function may be just a sentence or two. But to the program the input is different as sentence tokenization is done, punctuation’s, stop words are removed.

    5. Every agent function is implementable by some program/machine combination.

        False.
        Some functions may require resources or information beyond current available tech.
