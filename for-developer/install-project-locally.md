---
description: >-
  Install the project on your local dev server before you start to secondary
  develop the App.
---

# Install Project Locally

Copy the project folder \(App\) to your computer, let's suppose to place the project folder to /home/User/App on Mac OS or D://App on Windows.

Then open the terminal App or DOS, and run the following command to install the dependencies.

`npm install`

You may wait for a new minutes, once all dependencies are installed. Then, go to the app folder, and start the local server with the following commands:

`cd /home/User/App   
npm start`

it will automatically launch the local server and open http://localhost:3000 in the browser window. 

Then, you can preview the App on your local computer. We recommend to use Chrome browser and preview the App in iPhone mode via Developer Tools.

![](../.gitbook/assets/image%20%2814%29.png)

If you have customized the app files, you can use `npm run build` command to compile the app and all final files will be generated in the **build** folder.

