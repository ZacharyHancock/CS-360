# CS-360
Android Weight Tracking App
Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?
WeightWare is an Android app that helps users track their daily weight and try to stay consistent with reminders. The app helps address the need for a simple, user-fiendly tool to log weight progress.

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?
To meet user needs the app includes a login screen, a data table screen that has a RecyclerView and Cardview to make it a nice visualm and a page to enbale SMS reminders. The UI was designed to stay minimal and non obstrusive, to try to minimize the amount of steps to open the app and input a weight.

How did you approach the process of coding your app? What techniques or strategies did you use? How could those techniques or strategies be applied in the future?
The coding process focused on creating modular components liek the database helper, CRUD operatiosn for the DB, UI layoutsm and SMS functions. This strategy to focuson each infividual component wi;; help further projects by allowing me to be able to break down a large project into tiny pieces to tackle one at a time.

How did you test to ensure your code was functional? Why is this process important, and what did it reveal?
I tried to implement and test each function as I go to ensure its integration. This approach revealed the small bugs as I go rather than a big debugging mess when I dont test as I go. 


Consider the full app design and development process from initial planning to finalization. Where did you have to innovate to overcome a challenge?
Challegnes mainly icluded the SMS reminders in the emulator and ensuring the db was funcitonaing properly and linked with the RecyclerVoew. I solved these by researching the Android API and how the SMS permissions work and refine the database helper and adapter for the RecyclerView logic so they would work well together.

In what specific component of your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?
The database linked with the RecyclerView best demonstrates my skills. It combined database integration with a real-time updating UI, allowing users to easily add and remove entries. Overall the improved my understanding of Android mobile computing and how to properly boild down a project to each component to ensure proper integration of different libraries.
