# How to fork and clone

One quick note about cloning this project. If you wish to make commits and push the code up after cloning this repo, you should fork the project first. In order to own your own copy of this repository, you have to fork it so you get your own copy on your own profile!

You can see the fork button in the top right corner of every GitHub project; click it and a copy of the project will be added to your GitHub profile under the same name as the original project.

![alt text](https://i.ibb.co/1YN7SJ6/Screen-Shot-2019-07-01-at-2-02-40-AM.png "image to fork button")

After forking the project, simply clone it the way you would from the new forked project in your own GitHub repository and you can commit and push to it freely!


# After you fork and clone:

## Install dependencies

In your terminal after you clone your project down, remember to run either `yarn` or `npm install` to build all the dependencies in the project.

## Set your firebase config

Remember to replace the `config` variable in your `firebase.utils.js` with your own config object from the firebase dashboard! Navigate to the project settings and scroll down to the config code. Copy the object in the code and replace the variable in your cloned code.

![alt text](https://i.ibb.co/6ywMkBf/Screen-Shot-2019-07-01-at-11-35-02-AM.png "image to firebase config")


## Set your stripe publishable key 

Set the `publishableKey` variable in the `stripe-button.component.jsx` with your own publishable key from the stripe dashboard.

![alt text](https://i.ibb.co/djQTmVF/Screen-Shot-2019-07-01-at-2-18-50-AM.png "image to publishable key")

## Things to set before you deploy

Remember to add a file called `.env` to the root folder! In that `.env` file remember to add a `STRIPE_SECRET_KEY` value equal to your own secret key from your stripe dashboard. You can find it in the same place where you found your publishable key in the developers tab under api keys. You will have to enter the password in to reveal it! 

![alt text](https://i.ibb.co/wpLx8Lh/Screen-Shot-2019-07-01-at-2-26-26-AM.png "image to secret key")

You will also need to connect your existing Heroku app to this new forked and cloned repo, or you have to create a new Heroku app and push to it. A quick refresher on how to do either of these:

