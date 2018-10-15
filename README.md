# WORK IN PROGRESS.......................

## Node Web Boilerplate (Traditional Express-Node.js Web App)
Clean and minimalistic boilerplate to start your NodeJs web application project.

### 📂 Current Tools
This project currently supports the following:
- **Platform:** node
- **Back-end Framework**: express
- **Template Engine**: handlebars
- **CSS Framework**: bootstrap
- **Unit Testing**: mocha
- **Database**: mysql
- **Authentication**: google,email
- **Deployment**: heroku

### ⭐ Good for
  - Building a basic nodeJs app.
  - Stand-alone scripting and automation tool.
  - Fully customizable project.
  - Clean file structuring.
  - Following standard naming conventions so collaborators/team8s can understand easily your code.
  - Securing your login and api key details by using environment variable -- [dotenv](https://github.com/motdotla/dotenv)

### 📂 Prerequisites
 - NodeJs, git installed in your local environment.
 - .env file -- Yes you need this!

### 📝 Usage
1. Clone the repo to your local environment.
  - In the command prompt run the following commands:
    ```
    $ git clone https://github.com/yortrosal/node-web-boilerplate.git
    $ cd node-web-boilerplate
    ```
2. run ```$ npm install``` to install initial dependencies.
3. Make sure you have .env file available.
   Or generate one:  ```$ cp .env.example .env``` (edit it with your secret keys and other credentials)
4. Once you have the .env file setup in the main directory.
5. run ▶️ ```$ npm start``` to start the program. It will run the script from the app.js file.
6. Modify the package.json file. Edit the project name and other stuff.
7. Finally, start and build your application scripts. Customize your project however you like.

###  📘 Why is it important to use env file?
It has variety of usage. Find out [more](https://codeburst.io/process-env-what-it-is-and-why-when-how-to-use-it-effectively-505d0b2831e7).
But the sole purpose of using .env file for our project is to secure our credentials such as logins, api keys, and other important stuff. It is important not to include your .env file when you in our repository specially when your project is public.

### 💬 Tech Support
  - If things went wrong, google it first. People ahead of you have had similar issues in the past and solved it.
  - Last resort. -- Contact Jorge. He'd be happy to help you.

### Credit
This project is inspired by [megaboilerplate](http://megaboilerplate.com).

### 🎩 Authors
  - Jorge Rosal - [GitHub](https://github.com/yortrosal)
  - your name here...

### 📜 License
The MIT License (MIT) Jorge Rosal
