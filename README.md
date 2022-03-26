# Auth0--authentication-guide

1.We navigate to the applications section and we click on +create Application

<img width="1379" alt="Screenshot 2022-03-23 at 21 33 03" src="https://user-images.githubusercontent.com/74420607/159799482-3fdeafa2-8d77-4f00-85ad-6f408f320ca1.png">
<hr/>
2.Select the app type(sigle page,native,etc...)

<img width="741" alt="Screenshot 2022-03-23 at 21 34 40" src="https://user-images.githubusercontent.com/74420607/159799710-8f4a84bb-4a0f-49dc-a4d3-e2bc949d9f17.png">
<hr/>
3.we choose single app and we need to select the technology we want to use

<img width="884" alt="Screenshot 2022-03-23 at 21 36 19" src="https://user-images.githubusercontent.com/74420607/159799914-68311c3c-239a-485b-a6f5-da57ed0cc65f.png">
<hr/>
4.We choose react and we move on settings to copy Domain and Client ID

<img width="751" alt="Screenshot 2022-03-23 at 21 40 35" src="https://user-images.githubusercontent.com/74420607/159800472-c8f5f6f2-e3d3-4732-8822-3615c4030051.png">
<hr/>
5.Element to configure (Callback URL,Logout URL ,Allow Web Origin) to http://localhost:3000 or the Url of our app 

![image](https://user-images.githubusercontent.com/74420607/159800596-f6ffb76d-99a8-41da-a03e-db8b9bbbedd5.png)
<hr/>
6.We can install Auth0 on react directory

![image](https://user-images.githubusercontent.com/74420607/159800776-faca2e37-c93c-4211-a209-46617d8162f6.png)
<hr/>
7.Wrap the App Components with the AuthProvider

![image](https://user-images.githubusercontent.com/74420607/159800894-61b13ed8-63f7-4545-babc-ba73d9131b17.png)
<hr/>
8.Now we can add Login and logout Component

![image](https://user-images.githubusercontent.com/74420607/159801011-57db9edf-5e2f-47dc-953a-21c8efa38378.png)

![image](https://user-images.githubusercontent.com/74420607/159801065-599f3810-a9da-4a69-8234-320c6d450398.png)
<hr/>
9.Will be able to see the login form at this point

![image](https://user-images.githubusercontent.com/74420607/159801213-2b3fc6ae-7433-4878-9f85-e2297a6e2107.png)
<hr/>
10. we can use the useAuth0 to show the user info ,handle load and authentication

![image](https://user-images.githubusercontent.com/74420607/159801414-d9bba06a-b1af-47f6-936c-cb76dbd89f8a.png)
