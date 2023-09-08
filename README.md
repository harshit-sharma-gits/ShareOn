# ShareOn
A Simple File Sharing Web Appilcation that let's you share files with your friends via cloud! You can also email them the download link to the files.

## Working [GIF]
![Working GIF of shareon application](https://github.com/harshit-sharma-gits/ShareOn/assets/75475819/ef4be23b-ab7a-471e-9433-8453e767deb2)


Previously I hosted this project on Microsoft Azure, but that subscription is now over :)
So it won't be available for you to browse over the internet. But you can still set it up on your local system, and it's pretty easy.
Make sure that nodeJS is installed on your system.

## How to use this on your local system?

1. Clone this repository
   ```
   git clone https://github.com/harshit-sharma-gits/ShareOn
   ```

2. Rename the `.env.example` to `.env`. This file will contain the MongoDB Connection URL, and SMTP HOST details.
   
3. Run the following commands:
   ```
   cd server
   npm install
   npm start
   ```
   Now the server should be up and running on your local system.

4. The frontend or the `client` is simple HTML, CSS, and JavaScript. So open the index.html in your browser, and you should be able to run the app just like I did in the Above GIF.

Fin ✨
