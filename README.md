# React-node-Photo-gallery
1.React Photo Gallery
2.Source code for react/node photo gallery app

3.Setup a cloundinary account
4.You'll need to create a cloudinary account https://cloudinary.com/users/register/free - there is a free tier.

5.Start the server
6.Clone the repo
7.In the api folder, create a new file called .env. In here, add your cloudinary connection details e.g:

8.API_KEY={YOUR_API_KEY}
9.CLOUD_NAME={YOUR_CLOUD_NAME}
10.API_SECRET={YOUR_API_SECRET}

11.You can get this from your cloudinary dashboard after signing up. **Avoid checking these details in to a public repo - this is effectively your username and password so keep em safe! :) **

12.Open a terminal and run the following from the API folder:


13.npm install
14.npm run server

15.You can check its working by going to localhost:7000/photos in Postman or Chrome
16.Run the Frontend
17.NOTE: Make sure the Node server (in the API folder) is started otherwise the frontend won't work.

18.Clone the repo
19.In the client folder, create a new file called .env. In here, add an environment variable to point to the local node.js server e.g:

20.REACT_APP_API_URL=http://localhost:7000

21.If you change the port the node server runs on for whatever reason make sure to change it here too

22.Open a terminal and run the following from the CLIENT folder:


23.npm install
24.npm start

25.The app should be running on localhost:3000
