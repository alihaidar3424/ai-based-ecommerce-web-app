# Ai-based-Ecommerce-web-app

[![Status](https://img.shields.io/badge/status-active-success.svg)]()
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](/LICENSE)

AI-based Shopping system that uses a chatbot to perform all operations from adding, removing items to proceeding to checkout. Web application with a backend server. This project provides the advantages of online shopping to customers of a real shop. It helps to buy products in the shop anywhere through the internet. The customer gets online shopping and home delivery. This system can be implemented in any shop in the locality or multinational branded shops having retail outlet chains.

The web app uses React, Node, Express, MongoDB and Alan.ai for building chatbots and integrating with web and native apps. See [Alan docs](https://alan.app/docs/) before getting started.


# Preview and Working of the Web App ⚒️

## Preview of the Web App
See the project repository for demo media.

## Level 1 DFD Diagram to understand the architecture of the Project
See the project repository for architecture diagrams.



## Release History

We had some previous releases too that we did not initially commit to the repo.

* 0.1.0
    * CHANGE: Update docs (module code remains unchanged)
* 0.1.1
    * CHANGE: Made `Alan Ai Listeners for different voice commands`
    * ADD: Add `getItems(), openCart(), CloseCart()`
* 0.1.2
    * FIX: Multiple Listeners when calling `Alan AI listener module` 
* 0.1.3
    * CHANGE:Made `server.js`
    * ADD: `Mongo DB, Node config`  
* 0.1.4
    * CHANGE:Made `User.js,Model.js,Authcontroller.js,Ordercontroller.js`
    * ADD: `User Schema, Order Schema, Login(), Register(), MakeOrder()`  
* 0.2.0
    * The first proper release
    * CHANGE: Add `OrderDetails(),CancelOrder()`
* 0.2.1
    * Work in progress

## Development setup
Developement setup is pretty simple, first you just need to install all dependencies which is already given in package.json file and then kust run the web app with the commands given below.

- For Client -

```sh
cd client
npm install
npm start
```
- For server - 
```sh
cd server
npm install
npm start
```

Make sure in client/src/utils and then in axios.js make the baseURL as url of the Node's Localhost server.

I have made a dummy test account for to login - 
Username - test
Password  - 1234

For more in depth setup details go to [Contribution Guidelines.](CONTRIBUTING.md)

# Some important point to go through (MUST READ)

1. Most of the issues I will be posting will be related to the client or the frontend side at first.
2. I will be deploying the final web app with all the commited changes in the end to see how much we have improved the web app from its initial version.




# Contribution Guidelines
1. To contribute, open an issue or submit a pull request.
2. Read the [Contribution Guidelines](CONTRIBUTING.md) before contributing.

