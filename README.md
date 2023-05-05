# BidMyRide : Web Application

## Live Application URL:

#

- Live URL for Project: https://thunderous-treacle-c9f408.netlify.app

## Author:

#

- [Shvet Kantibhai Anaghan](shvetanaghan28@gmail.com)

## About:

#

- The BidMyRide web application is a virtual automobile auction platform that gives buyers and sellers the chance to engage in online car buying and selling. Users can explore available automobiles, submit bids, and compare various cars based on their features and specs using the platform's real-time bidding process. Additionally, the platform offers a thorough transaction history so customers may follow their purchasing and selling activity.

- It is not easy to get a decent price for your car, especially to avoid dealer fees and all hassle. Third-party dealers' ways to sell or buy a car are not popular these days. The idea behind the project is to create a Service that provides a virtual car auction platform that provides an opportunity for both buyers and sellers to get the best value for their money.

## List of Features:

#

- User profile mangement
- Comparison between two cars
- Car Listing Mangement
- History of buying and selling car
- Daily News
- Payment Handling
- Auction Management
- Auction History

## Sources Used:

#

### Video

I took a video of a car from this [Link](https://www.imagin.studio/assets/lifestyle/fiat/bridge_fiat.mp4) with an impressive frontend design, which showcases its sleek and modern look. The frontend of the car is beautifully captured in the video, highlighting its elegant curves and bold design elements. And that I am shoeing in background.

## Folder Structure Used

#

### React App:

```
client
├── public
├── src
│   ├── Assets
│   ├── components
│   ├── constants
│   ├── pages
│   ├── redux
│   ├── utils
|   ├── App.scss
|   ├── App.js
|   ├── index.js
|   └── index.scss
```

The project structure of a React frontend app includes a node_modules directory for storing dependencies, a public directory for static assets, and a src directory containing reusable components in a components directory and page components in a pages directory. The main App.js component serves as the root of the app, while the index.js file is responsible for rendering the app to the index.html file. A package.json file contains information about the project, and a README.md file is often used for documentation.

### Node App:

```
server
├── public
│   ├── assets
│   │   └── documents
│   │   └── images
├── src
│   ├── app.js
│   ├── config.js
│   ├── constants
│   ├── controllers
│   ├── models
│   ├── routes
│   └── utils
└── .env
```

We used an MVC architecture. Controllers, Models, and Routes are the three main folders that make up this file. In order to isolate the business logic from publicly accessible assets like photographs and automobile paperwork, we chose to place the static files outside of the core server code. All of the string constants used in the server code may be found in the directory "constants." When the application expands and new features are integrated into the current project, it becomes extremely crucial. 'config.js' is also crucial when discussing scaling. It includes all of the node application's configuration information, such as the backend server's url.

## Technologies & Libraries Used:

- [React](https://reactjs.org/)
- [Node](https://nodejs.org/en/)
- [npm](https://www.npmjs.com/)
- [react-router-dom](https://www.npmjs.com/package/react-router-dom)
- [axios](https://www.npmjs.com/package/axios)
- [lottie-react](https://www.npmjs.com/package/lottie-react)
- [react-bootstrap](https://www.npmjs.com/package/react-bootstrap)
- [react-dom](https://www.npmjs.com/package/react-dom)
- [react-icons](https://www.npmjs.com/package/react-icons)
- [react-redux](https://www.npmjs.com/package/react-redux)
- [react-scripts](https://www.npmjs.com/package/react-scripts)
- [redux-logger](https://www.npmjs.com/package/redux-logger)
- [sass](https://www.npmjs.com/package/sass)
- [styled-components](https://www.npmjs.com/package/styled-components)
- [styled-react-modal](https://www.npmjs.com/package/styled-react-modal)
- [web-vitals](https://www.npmjs.com/package/web-vitals)
- [archiver](https://www.npmjs.com/package/archiver)
- [bcryptjs](https://www.npmjs.com/package/bcryptjs)
- [cors](https://www.npmjs.com/package/cors)
- [dotenv](https://www.npmjs.com/package/dotenv)
- [express](https://www.npmjs.com/package/express)
- [firebase](https://www.npmjs.com/package/firebase)
- [fs-extra](https://www.npmjs.com/package/fs-extra)
- [jsonwebtoken](https://www.npmjs.com/package/jsonwebtoken)
- [mongoose](https://www.npmjs.com/package/mongoose)
- [multer](https://www.npmjs.com/package/multer)
- [sharp](https://www.npmjs.com/package/sharp)
- [nodemon](https://www.npmjs.com/package/nodemon)

## Prerequisites:

#

To run this project on your machine, You need to install git first. below is the link that will guide you to install Git on your machine.

- [Git Guides - Install Git](https://github.com/git-guides/install-git)

After Installing Git,

The first step is to clone the Group project repo in your machine using the below command. Run the below command at the destination in cmd where you want to clone the repository.

```
git clone https://github.com/ShvetK/BidMyRide.git
```

Next, Change the directory to the client side of the project using:

```
cd .\BidMyRide\client
```

Next step is, run the below command to instal all the packages and dependencies that is required to run the Assignment.

```
npm install
```

You are all set and now just run the client side using following command.

```
npm start
```

Now, To run the server side of the Assignment, open the cmd with the path of the project's repo.

Next, Change the directory to the server side of the project using:

```
cd .\BidMyRide\server
```

Next step is, run the below command to instal all the packages and dependencies that is required to run the Assignment.

```
npm install
```

You are all set and now just run the server side using following command.

```
npm run dev
```

Both the server and client are now up and running.
