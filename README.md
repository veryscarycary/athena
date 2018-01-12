# Athena

Smart support platform that focuses on providing high quality solutions, reducing customer pain points, and delivering relevant knowledge to decision makers.

## Table of Contents

1. [Project Files](#project-files)
2. [Team](#team)
3. [Contributing](#contributing)
4. [Requirements](#requirements)
5. [Usage](#usage)
    1. [Installing Dependencies](#installing-dependencies)
    2. [To Run](#to-run)

## Project Files

This application was built with service-oriented architecture in mind. Therefore, this project contains services that are spread over a number of github repos(one per service). These necessary project files can be found by visiting the following links:

   https://github.com/Wistful-Bison/athena  (this repo!)
   https://github.com/Wistful-Bison/athenaApp
   https://github.com/Wistful-Bison/athenaUser
   https://github.com/Wistful-Bison/athenaTicket
   https://github.com/Wistful-Bison/athenaKb
   https://github.com/Wistful-Bison/athenaKbSearch


## Team

  - __Product Owner__: Bradford Melluish
  - __Scrum Master__: Cary Meskell
  - __Development Team Members__: Amelia Brown
  
## Contributing

  - Front-end: Amelia Brown
  - Front-end: Cary Meskell
  - Back-end: Bradford Melluish

## Requirements

    Node 6.2.2 or similar
    MongoDB
    PostgreSQL
    ElasticSearch-2.4.1
    Webpack
    ...
    
    Refer to each repo's package.json for libary dependencies

## Usage

In order to run this application, you will first need to clone down and install the dependencies from each respective service. The full instructions are listed below:

Download:
  
  In Terminal, from within desired parent directory:
  
      git clone https://github.com/Wistful-Bison/athena.git athena
      git clone https://github.com/Wistful-Bison/athenaApp.git athenaApp
      git clone https://github.com/Wistful-Bison/athenaUser.git user
      git clone https://github.com/Wistful-Bison/athenaTicket.git ticket
      git clone https://github.com/Wistful-Bison/athenaKb.git kb
      git clone https://github.com/Wistful-Bison/athenaKbSearch.git kbSearch

## Installing Dependencies

      brew install node

  In Terminal, from within the root directory:

      cd athena
      npm install
      
      cd ..
      cd athenaApp
      npm install
      
      cd ..
      cd user
      npm install
      
      cd ..
      cd ticket
      npm install
      
      cd ..
      cd kb
      npm install
      
      cd ..
      cd kbSearch
      npm install

## To Run
  
 Start databases:
    
         In Terminal, mongod
         Start postgreSQL server
      
 Start elasticSearch:
         
         In Terminal, cd <elasticsearch_directory>
         In Terminal, bin/elasticsearch
     
 Start services:
     
         In Terminal in parent directory, cd athena
         In Terminal, npm start   // runs nodemon for user, ticket, kb, and kbSearch services
         
 Start app:
     
         In Terminal in parent directory, cd athenaApp
         In Terminal, webpack --watch
         In Terminal, npm start
         
 Visit http://localhost:3000 and Voila!


![alt tag](http://i.imgur.com/ClxpTCd.jpg)
