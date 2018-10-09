# HSBC-Client-Questioner-1

1) Exception handling,
Try-catch-finally , checked unchecked exception, exception in inheritance, throws keyword, throwable, throw, super class subclass validity rules in exception
2) Interface, variable access in interface, method overriding with class and interface
3) method overloading, method overriding
4) static methods in inheritance
5) method hiding - field hiding
6) multithreading, synchronized, block level synchronization, thread based exceptions
7) access specifiers
8) different types of maps and most effecient one
9) explain any design pattern in details
10) == and equals on different objects

https://developer.android.com/studio/build/
https://www.netguru.co/codestories/3-ways-how-to-implement-certificate-pinning-on-android

1) Pillers of Android
2) Content Provider explain with example and Syntax
3) Download multiple files 
4) Activity life cycle
5) Difference between fragments add and replace method
6) Launch modes and difference between Single Top and Single Task
7) Recycler View Implementation and handle if you get different type of data
8) Interface ? If Interface having Constructor?
9) Abstraction
10) Difference between package name and application I'd
11) How to check device is rooted ?
12) How to check sensors are available ?
13) FCM explain process
14) Http get and post
15) HttpURL connection in detail
16) AsyncTask
17) Which collection classes you used ?
18) Which will you prefer from below
HashMap hashmap = new HashMap()
Map map = new HashMap ()
19) Dependency Injection
20) Fragment with no ii
21) MVP where you call web service in MVP
22) Security

HSBC question list 

1 android components
2 Broadcast receiver 
3 Is is possible to add file write operation code in onreceive () method of Broadcast receiver
4 Launcher mode
5 UI scenario 
6 Constraint layout
7 custom view
8 Android permission
9 how to handle the app if user denied the permission
10 Project history
11 project explaination
12  to set app as pdf viewer
13 SSL pinning
14 Dependacy injection
15 Activity sequences scenario ( For That which Intent Flags are used)

Questions List: 
1. How do we secure the app.
2. SSL pinning
3. Asymmetric Encryption
4. Android Fragments and Activities
5. How fragment back stack work on add() and replace()
6. Life cycle changes of fragment on add to backstack
7. Service 
8. How we communicate activity from service
9. Thread service
10. Intent servit
11. multiple images download approach in background
12. Impact of thread and service on app
13. Launch modes of android
14. effect of launch modes when activity is in backstack
15. Push Notification
       GCM and FCM
16. Do we need same a/c for console and playstore
17. Limitations of a/c
18. how we get notification from server
19. Multi device notification
20. Notification - Image and video upload limitations
21. Constraints Layout and usage
22. Scenario for constraint layout
23. if gallery app is not present and we fire an implicit intent.. then what will happen
24. Scenario : Rotation lifecycle for activity or fragment
25. alternative methode for rotation
26. Data Binding library
27. Hashmap and hashtable, difference and which is fast.
28.Scenario : Stub class and impl class. which design pattern will use for that and explain
29. Single-ton class 
30. Avoid copy of single ton class
31. ClassNotFoundException and NoClassDefinationFoundException, when above error will get
32. Final keyword for class , variable and method
33. String Buffer and String Builder
34. Restful Service Integratio. and Working
35. InputStreamReader and BufferedReader difference
36. Abstraction 
37. Scenario : Amazon bank to withdraw money from barclays . how will achive above scenario
38. Listview and recycler view
39. scenario : how to change list to grid view
40. explain onBindView()
41. Sticky header how will mange in list view
42. difference between Item and Header
43. started service and Intent service difference
44. Background method of intent service
45. storage option in android any third party 
46.Public key pinning
47. What is certificate authority
48. MVP/MVC ( display contact list and send all contact to server on click of button )
49. Unit testing

Kotlin::::
50. Configuration of kotlin
51. Var and Val Difference
52. Companion Object
53. How to call kotlin class method to java class
54. How to handle null pointer exception in kotlin
55. Elvis operator

How to implement AsyncTask in MVP
Proguard
How to check if device is rooted
Loaders
Set priority in broadcast
Sticky broadcast
FCM send image upstream
Implementation for Mockito

Knowledge point - to disable copy from sensitive fields like password for security purpose, setCustomActionModeCallback listener with all overridden methods returning false.
This will disable copy functionality from editing field.
Knowledge point - to enable public key pinning with OkHttp/Retrofit, create CertificatePinner instance with CertificatePinner.Builder() giving hostName & Sha256 hash of SslCertificate and set that instance to OkHttpClient with certificatePinner() method.
Sending HSBC interview questions asked today,

-Tell me about yourself 
-Asked experience in kotlin 
-started android questions
-tell me about new views in Android 
-gave a design and told to implement that design, wanted to know about views and viewgroups that i will use and approaches for efficiency
-started questions on fragment 
-onBackPress method scenarios with fragment
-gave me problem statement on paper and asked questions on the same concept
- asked activity and lifecycle with scenarios 
- asked usage of bundle with scenarios
- then asked about dependency injection and frameworks used and questions on them
- asked on retrofit and questions like how to pass headers etc
- continuing this asked if let's say a 401 response code scenario is to be handled how would be the approach to write the code
- next started with java 
- gave an interface example, asked questions like can I declare a variable inside and access it,  can method be protected etc
- gave an example of inheritance and asked questions on accessing static variable in parent through child object variable, asked questions around this
- Done from my side, do you have any questions

Knowledge point : we need to use ExifInterface from android.support.media package & not a framework ExifInterface from android.media package. This resolves runtime exception [ failed to connect to camera service ] when we try to get Camera instance with Camera.open() for own camera functionality implementation. This exception occurs only on Android 9 devices if we had used framework implementation of ExifInterface class and targetSdk is 28.

ExifInterface class is used to read tags from raw image data. Framework class has known security bug in lower Android versions, so use same class from android.support.media package.
