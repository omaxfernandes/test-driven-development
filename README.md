# Test Management (TDD)

This repository contains a environment for running services with `Docker Compose`. 

## The structure is organized into two folders: 

├── test-driven-development/  
│   └── docker-compose.yaml  
└── README.md  

## To start the environment, navigate to the folder with:  
`cd tes-driven-development`  

## Then, run the command to start the containers:  
`docker-compose up -d`  

## You can stop and remove the containers with:  
`docker-compose down`  

## To run the tests, execute the following command in the container terminal:  
`pytest`  

Ensure Docker is installed on your machine before running the commands.
