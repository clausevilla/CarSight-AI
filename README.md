# CarSight-AI
Final project for the Building AI course of the University of Helsinki.

## Summary
***CarSight AI*** is an app based on AI methodologies made for and by car enthusiasts. Its main use is to identify any type of car and its specifications through computer vision, such as model name and engine characteristics. This is done by employing AI and machine learning algorithms to analyze the different images submitted by users into the app; such pictures will be able to be shared, aiming to create an engaging community and promoting interaction. 

## Background
>The main advantage this tool will offer is to create a source of ***accessible knowledge***.
Nowadays high-end cars are seen by many as a work of art, managing to combine design with aerodynamics to craft an engineering masterpiece. 

As an avid sharer of this vision, I firmly believe CarSight AI will contribute to the idea of ***analyzing automobiles as any piece of art***: information about its history and crafting details could entice users to acquire further learning about its related aspects (country of production or historical context, per instance). 

Nowadays there is a ***clear shortage of apps*** that accomplish this objective. Conveying the vision of exotic cars as a cultural insight could cope with the **current lack of accessibility** to the topic, and create a well-rounded base of knowledge for all interested individuals.

## How is it used?

1. The app shall allow picture-taking of cars in all environments, with automobile detection even in night-time conditions (highways, day-light parking areas, underground parkings, roads, etc.)
> [!NOTE]
> When the settings get too dark or the user is too close for easy recognition, the app can pop up messages to advise using flash or standing further/closer from the vehicle.
   
2. It will most likely be directed towards young adults, as most car enthusiasts start developing curiosity for the topic at a young age. However, the user-friendliness of the app will allow the interface to be used by all types of users regardless of their age.
   
3. The main screen will simply be a list of the 10 most recently saved cars, and the bottom of the page will visibly have the picture-taking icon. When the user takes the picture the AI will be triggered to gather and display the respective information about the vehicle.
  
4. After the picture has been taken the user will be able to save the picture and its respective AI-generated data in its private car list.
   
> [!IMPORTANT]
> For protection reasons, the app will automatically blur the plate license of the vehicle.
  
5. There will be a common gallery with pictures from all users who wish to share their findings; before sharing, users will be able to specify their preferences via picture filtering. 
Thus, the user will be able to see only content that aligns with his preferences (eg. only antique cars, or just Ferrari models).

6. The Q&A page will allow users to ask their individual questions on the site, to be answered by AI or real-time users.

## Prototype:

<img src="https://github.com/user-attachments/assets/4ca0856d-2808-49af-83ca-59e35fdc61e5" width="300">
<img src="https://github.com/user-attachments/assets/e6fc55a0-e7f3-4a01-a8a5-ab72c75e478c" width="300">
<img src="https://github.com/user-attachments/assets/a69e1264-406c-4506-bc60-c6533c85b2ca" width="300">
<img src="https://github.com/user-attachments/assets/c22b94b4-a34a-4a6a-9dd9-7cc1afb5a098" width="300">
<img src="https://github.com/user-attachments/assets/e5d54e69-5b18-47ea-9c20-0a671f568b3e" width="300">



## Data sources and AI methods

The data will come from different reliable online sources, such as each car's specific brand website for all the vehicle characteristics.
For the Q&A section, the answers will mostly come from either any user (and will be verified) or by an AI methodology itself, which will use multiple sites to contrast the information and provide a reliable answer.


## Challenges

### Main limitations include:
* Cars with external appearance modifications (such as special colors, spoilers or other components) may confuse the AI when determining the correct model.
* It will be challenging to always recognize and blur the plate by the AI as each one presents a different style depending on the country.
* The AI might need frequent updates to stay current with new car models and changes.
* The system might struggle to handle a large influx of users and images.
* The AI's performance might degrade with low-resolution or poor-quality images.

### Ethical considerations:
> [!CAUTION]
> * Respect the privacy of both the car owner and the user on the page by not revealing the location where any picture has been taken or other compromising information.
* The images taken by the user shall not be used for any other purpose, and the app must always ask for consent from the user.
* Measures should be taken to prevent the misuse of the app, such as identifying stolen cars or infringing on intellectual property rights.
* There should be a clear mechanism for users to report issues with the AI's performance.

## What next?

How could your project grow and become something even more? What kind of skills, what kind of assistance would you need to move on? 
I would require more knowledge of AI methodologies and their respective algorithm implementations to make a complete object-detection application. Per instance, enrich my knowledge in machine learning, data engineering (to handle picture datasets), cloud computing and essentially software development.

As possible improvements, I could integrate with automotive databases, insurance companies, and car dealerships; as well as expand the app to identify other vehicle types (e.g., motorcycles, trucks) to build a stable community. Joining a group of experienced developers to target CarSight AI could most likely improve the current model, and contribute positively with the AI implementation.


## Acknowledgments

For the demo example: 
[Official Ferrari Website](https://www.ferrari.com/auto/ferrari-488-gtb)
[Wikipedia Information Extract](https://en.wikipedia.org/wiki/Ferrari_488)

