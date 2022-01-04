# Basic-in-Kotlin
Notes App

<b> Problem Statement: </b>

One of the most used components in our daily life is paper. According to a survey, on an average, a human use 27kgs of paper annually and this thesis is about impact of usage of paper on our environment. Paper can easily be crumpled and messy and Easy to lose or misplace. Difficult to share and understand handwritten document. Also, Prone to spelling error. Piled up papers is unattractive to the eye.

<b> Proposed Solution: </b>

This Note-taking applications enable users to type or write on their devices just as they would on paper and allow to access, store and update a note anytime. On average typing is faster than handwriting. One can add links in your notes as references. Can erase or edit text without messing up the pages and has almost unlimited pages to write on
C:\Users\anshi\OneDrive\Desktop\notesappC
<img width="200" height=”433 src="https://user-images.githubusercontent.com/75130949/148074680-d2c57a3f-f19c-4858-855e-df17cbe298ca.jpg " 


![image](https://user-images.githubusercontent.com/75130949/148077016-da035c2e-e6ca-44a0-965a-438d2c4ea703.png)
![image](https://user-images.githubusercontent.com/75130949/148077099-fb5f541d-94c9-4280-a4bc-54748fa3d2a8.png)


![Notes App](https://user-images.githubusercontent.com/75130949/148075098-38195924-c431-4d93-82f2-a2a55acbd215.jpg)
![Notes App](https://user-images.githubusercontent.com/75130949/148075185-cc85024f-d19b-4796-87af-d870d644d2ba.jpg)
![Notes App](https://user-images.githubusercontent.com/75130949/148075294-4a133b9a-2ae8-4316-bb48-2803831ef6b0.jpg)
 
<b> Functionality & Concepts used: </b>

We built a simple Notes Application in which we will be displaying the list of notes in Recycler View which is added by the user. Along with that, we will be also able to add a new note to your app. We will be using Room Database for storing data in users’ devices. The App has a very simple and interactive interface which helps user to create their notes, also hint text are provided to guide them.

- Constraint Layout: Most of the activities in the app uses a flexible constraint layout, which is easy to handle for different screen sizes.
- Simple & Easy Views Design: Use of familiar audience EditText with hints and interactive buttons made it easier for user to create notes. Apps also uses App Navigation to switch between different screens.
- LiveData & Room Database: We are also using LiveData and Room Database to update & store data provided by user, any changes made by user is updated and shows the time when it was last updated .
- ViewModel : View Modal acts as a communication centre between repository and UI. The ViewModel instances survive Activity/Fragment recreation.
- Repository & Entity: a class that t is mainly used to manage multiple sources of data and an annotated class that is used to describe a database table when we are working with Room
- DAO: used for mapping SQL queries to functions.

<b> Application Link & Future Scope : </b>

To increase the knowledge and efficiency within organizations, sharing and tracking of information has become a priority. Note-taking applications have made a dent in the professional market, with most organizations committed to at least one application. Individually, business professionals may choose to use their own note-taking applications to track their roles within the company.


