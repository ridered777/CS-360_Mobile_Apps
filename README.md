# CS-360_Mobile_Apps
CS-360 Class Mobile Application Repository

Briefly summarize the requirements and goals of the app you developed. What user needs was this app designed to address?

This application was designed to be a simple inventory application that would be used by a user looking to keep track of an inventory of items.

What screens and features were necessary to support user needs and produce a user-centered UI for the app? How did your UI designs keep users in mind? Why were your designs successful?

The UI for the application was meant to be as simple as possible while still addressing the outlined needs of the user. There is a screen that handles login/registration, a screen for SMS settings, a screen for the database itself and a screen to add or remove an item from the database.

How did you approach the process of coding your app? What techniques or strategies did you use? How could those be applied in the future?

I created the application by following the logical flow of objects through the system and adding support as needed for them. For instance, I started with the login system and after going into that a bit there comes a time when the credentials need to be checked against a database of credentials, that that point I went and created the database.

How did you test to ensure your code was functional? Why is this process important and what did it reveal?

Both running the emulator as well as generating an .apk ensured functionality. I created both a debug and launch version of the .apk to cover all bases. Making sure your code is functional is extremely important and often helps to catch little errors – in this case I had missed a reference on my navigation bar after renaming an activity (fragment) screen, among other things.

Considering the full app design and development process, from initial planning to finalization, where did you have to innovate to overcome a challenge?

My approach and appreciation for the scale of the application went through a very large shift between the creation of the UI and the creation of the code to make it functional. I grossly underestimated the amount of time and effort that would be required for even a simple application such as this one, even with only a few “systems” in place, their reliance on each other makes for a lot more work that I initially expected. Even though I have experience with creating small mobile applications this was the first one that had more than two screens and had this much functionality. Despite this, most of the times I was stuck or unsure or what a given handler needed to do or how to implement it, I was able to find my answer. For this reason, I don’t believe I did much “innovating” to overcome challenges in this application.

In what specific component from your mobile app were you particularly successful in demonstrating your knowledge, skills, and experience?

I think the dataflow for the objects is the most successful way of demonstrating how I grew in this project. The need was there for this to create the item itself from scratch so to use that as an example it has a constructor, purpose-built functions, implementation of those functions, integration with handlers and listeners and finally CRUD usage via the UI.
