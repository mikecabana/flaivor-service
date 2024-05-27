# Fastify Typescript Starter

🚀 A super simple and (mostly) un-opinionated starter app using Fastify and Typescript!

## How to use?

### Prerequisites 

make sure you have at least `node v20.9.0(lts)` and `npm` installed

### Commands

#### Install

If it's the first time trying to run this starter project, install all the dependencies 
~~~terminal
npm install
~~~

#### Start development server

Start the `development` server by running the following command in a terminal from the root folder of the project 
~~~terminal
npm run dev
~~~

If you're in VSCode, run using the debugger by hitting `F5`

#### Build and Start for production

Build the project (outputs to `./dist`)
~~~terminal
npm run build
~~~

Run the built project
~~~terminal
npm start
~~~

## How to use with Docker?

~~~terminal
docker build -t fastify-ts-app .
docker run -it --rm -p 3000:3000 --name fastify-ts-app fastify-ts-app
~~~
