
Project Name : Facebook_Login 
 
prerequisites:
1. IDE: Eclipse IDE
2. Server : apache-tomcat-8.0.32
3. JAVA : 1.8

Steps:
1- put the war file in the webapps folder "Facebook_Login.war"
2- start the tomcat server
3- hit the url : http://localhost:8080/Facebook_Login

About Application:
we have created the application in which we login via facebook oauth.
for this we have created 3 java file and their functionalities are below:-
1. FBConnection.java : the java file is used to make the connection form facebook (by using FB_APP_ID ,FB_APP_SECRET and REDIRECT_URI) and provide successfully authentication.
2. FBGraph.java : this java file is used to get JSON data by their accessToken and parse the json and put in the map.
3. FabHotelHomePage.java : this java file is used (mainly this is servlet) to render successfully logined page to the user.

Othe Details :
Facebook account Details:-
name : Harikesh Kumar
App ID : 1098214170268176
Api version : v2.7
App Secret : a011f4e9574401a860560a52534a2ec5
REDIRECT_URI = "http://localhost:8080/Facebook_Login/fbhome";