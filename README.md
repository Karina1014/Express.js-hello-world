
# Hello World with Express.js 🌎

This project demonstrates a simple web server created with Express.js, a fast, unopinionated, and minimalist web framework for Node.js. The server responds with a "Hello World" message, showcasing basic Express.js functionality.

## 🚨 About the Project 🚨  
This is an important message related to the project. Please read it carefully before proceeding:  

- **main Branch**: Contains the app with the `Dockerfile`, ready to build and uploaded to DockerHub.  
- **productionJS Branch**: Contains the deployed version of the app on Render.  

## Built With

This project is built using:  

[![Express.js](https://img.shields.io/badge/Express.js-4.17.1-blue?style=for-the-badge&logo=express&logoColor=white&labelColor=101010)](https://expressjs.com/)  
[![Node.js](https://img.shields.io/badge/Node.js-16.0.0-green?style=for-the-badge&logo=node.js&logoColor=white&labelColor=101010)](https://nodejs.org/)  
[![Docker](https://img.shields.io/badge/Docker-Containerization-blue?style=for-the-badge&logo=docker&logoColor=white&labelColor=101010)](https://www.docker.com/)  

 
## Getting Started

### Clone the Repository

To get started, clone the repository to your local machine by using the following command:

```
git clone https://github.com/Karina1014/Express.js-hello-world.git
```


## Prerequisites

Before you begin, ensure the following:

1. **Visual Studio Code (VSC):**
   - Make sure you have **Visual Studio Code** installed on your laptop.
   - Open the `index.js` file in the VSC editor to edit or review the code.

2. **Node.js Installation:**
   - Ensure you have **Node.js** installed.
   - You can check your Node.js version by running this command in your terminal:

     ```bash
     node --version
     ```

---

## Installation

Follow these steps to get your project up and running:

* Navigate to the project directory:

Change to the project folder:

``` bash
cd Hello-world-Javascript-docker
```

* Install dependencies:

Install the required dependencies using npm:

 ``` bash
  npm install
 ```
### Running the Project
Start the project:

* Run the following command to start the application:
 ``` bash
  npm start
 ```
* Access the application:

Open any browser and type the following URL to view the application:

![image](https://github.com/user-attachments/assets/9ac068e8-beb7-46b9-9473-482b69bf2c76)


## How to run with docker
You will need:

* Docker - DockerDesktop installed
* DockerHub account

## Image in DockerHub

You need a Docker Hub account and to update your JS image.

![image](https://github.com/user-attachments/assets/5547c34d-4b4b-44c7-89fb-5af57f106716)

### Download image
```
docker pull karina1014/hello-world-javascript:v1.0
```

### View the results
You can open de CMD and run this :
```
docker run -it karina1014/hello-world-javascript:v1.0
```

Use this command to confirm that the image is available in your Docker environment.

![image](https://github.com/user-attachments/assets/11e059af-15bc-477b-beac-55c38607a6c9)

## Result 
View the Hello World



