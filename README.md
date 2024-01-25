# Pickleball Scheduler
Welcome to PickLeTime! This web application is designed to help users to organize and schedule their games. It is built with React for the frontend, Prisma for database management, Fastify as the backend framework, and SQLite as the database.

## Features

- **User Authentication:** Securely manage user accounts and ensure data privacy.
- **Event Scheduling:** Easily schedule pickleball events and view upcoming games.
- **Participant Management:** Keep track of participants and their availability.
- **Responsive Design:** The app is designed to work seamlessly across various devices.

## Technologies Used

- **React:** A JavaScript library for building user interfaces.
- **Prisma:** A modern database toolkit for TypeScript and Node.js.
- **Fastify:** A fast and low overhead web framework for Node.js.
- **SQLite:** A lightweight and serverless relational database.

## Getting Started
Make sure you have [Node.js](http://nodejs.org/).
Follow these steps to get the Pickleball Scheduler Web App up and running on your local machine:

1. Clone the repository:
```
git clone <repo-name>
```
3. Navigate to the project directory:
```
cd <repo-name>
```
5. Install dependencies
```
cd <repo-name>
npm install
```
4. Install dependencies for frontend
```
cd packages/web
npm install
```
5. Install dependencies for server
```
cd ..
cd packages/server
```
6. Generate Prisma Instance
```
npx prisma generate
npx prisma migrate dev --name init
```
7. Configure .env.example
8. Start the app
```
cd ../..
npm start
```


## Deployment

To deploy this with your current local version, run

```sh
npm run deploy
```

See deployement [here](https://krisvan.github.io/Pickleball-Scheduler/).

After executing these commands, your React frontend should now be running on [localhost:3000](http://localhost:3000/). You can visit this page in your web browser to view your front-end user interface.

## Testing with Continuous Integration

TODO

## Additional Resources

