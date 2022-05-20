# MERN-markdown
This project was created using the MERN stack (MongoDB, Express JS, React js and Node js) inspired by Markdown note-taking apps like Inkdrop and Notion


## Installation

In order to install the project on your local machine, clone the github repo with the following command:

```
  git clone https://github.com/luisruiz3012/MERN-markdown/
```

Then open the project folder on your terminal (make sure to have 2 terminal tabs or use 2 terminal to run frontend and backend)


In one terminal, open the backend project and run the following command to run the docker-compose file to have access to mongoDB (You must have Docker-compose installed on your local machine to use this file), or you can use your normal mongoDB connection.

```
docker-compose up -d
```

After that, make sure to add a .env file on the backend folder and add your environment variables like the mongoDB connection string and port (You can use the .env.example file as a guide)

After that, docker-compose will be executed on the background and the enviroment variables will be configured, so now you can then use the following command to run the backend:

```
npm install && npm run dev
```

if you are using yarn:

```
yarn add && yarn dev
```


On the other terminal open the frontend folder inside the project folder and run the following command

```
npm install && npm start
```

If you are using yarn use:

```
yarn add && yarn start
```

This will open the project on http://localhost:3000/ so you can test it



## Technologies:

For this project, on the frontend I used React JS and react-markdown (https://github.com/remarkjs/react-markdown) for the markdown functionallity and other plugins like remark-gfm rehype-raw for additional markdown functionallities, as well as vanilla CSS for the project styling.

For the backend I used docker-compose to run a local instance of MongoDB without installing it on a local machine, as well as Node JS and Express JS for the backend and routing functionallity and finally Mongoose for the MongoDB connection.
