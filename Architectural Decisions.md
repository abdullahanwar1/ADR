Architectural Decisions

Assignment#3



Scenairo#4: Modern transportation Company 



ADR 1: Choosing the type of Mobile App.

Decision: I have decided to make a native app which will be compatible with both IOS and Android.

Rationale: Native apps generally have more security features mainly when making transactions through the application. Native apps can work efficiently when not connected to the internet. They are faster and provide a better response compared to other types. Native app also provides customized push notification service in mobile phone. So native app will be the best choice.

Status: Approved 

Consequences: creating a native app means we must create two separate apps for Android and Ios which take a lot of time. It can be expensive by getting two separate paths for app. Both apps need to be updated separately by time which is a lot of effort. 

ADR 2:  Selecting UI Framework.

Decision: I will use Swift UI for IOS and Jetpack Compose for Android.

Rationale: Both Swift Ui and Jetpack Compose use a Modern syntax and provides modern designs which build up an attractive interface. Both frameworks are faster and responsive. These frameworks can speed up the mobile app development process. It’s easy to maintain these frameworks so it takes less time to update the interfaces or remove the problems.

Status: Approved 

Consequences: For these frameworks we need to understand and learn about them first because these are not like the old ones. These frameworks require newer software both in IOS and Android so these will not work on the old devices. There are certain limitations also on this framework, so we need to study about the limitations as well.


ADR 3:  Selection of Backend Language.

Decision: I will use Node.js as the backend Language for the app 

Rationale: it has a big library which provides a wide range of packages which can be used in development of App.it can be easily integrated with many databases.it can handle various operations at a time. Node.js is considered as very resourceful backend language and it has a large support. 

Status: Approved 

Consequences: Node.js can only be used if you’re familiar with JavaScript.

ADR 4: Permissions.

Permissions will include permissions like Location services, Internet, Camera, Contacts, payment and billing, device storage and Notifications.

Decision: Only ask for permissions when necessary, depending on the feature being used, and ensure that clear explanations are provided for each required permission.

Rationale: Asking permissions can reduce the fraudulent activities in the app. People will have more trust over the app as their data is not neglected, it is safe within the app. it strengthens apps integrity and it’s less likely to be removed from the App store.  So, it makes the app more user-friendly.

Status: Approved

Consequences: Some users won’t allow permissions which will not let users allow them to use all the features of the app. Users might have privacy concerns by giving the app permissions over their phone. The app needs to be made that easy for users that it still works when user deny some permissions.


ADR 5:  Storage of Data. 

Decision: we will utilize the local storage for user data and will have backend cloud storage for app data. Data transfer and communication will be encrypted. 

Rationale: the data will be encrypted and secured within the app. Security will be guaranteed. It will reduce the data fetch time.  Cloud sources for backend will be reliable. 

Status: Approved 

Consequences:  It will be a lot of cost for buying cloud storage and then maintaining the data in it. User trust will be lost if the data security is not handled properly. It will be complex and difficult to transfer the dta within the app and cloud storage.

