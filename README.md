# Commands-to-mount-a-REST-API
This repository have commands to Node js with Tyscript, Angular Ando Docker 

# Node js and Typescript
First we created a folder with the following name *"Backend"* or *"Client"* , then on the folder that we created, we need to create a package.json, we will use the following command:
  
   >*npm init --yes*

then we need to install the next dependencies:
  
  >*npm i express morgan cors*
  
  >> ***Express*** is for to create the server
  >
  >> ***Morgan*** is used to see the requests in the console that are made to the server from our Frontend
  >
  >> ***Cors*** is to use to communicate with the other servers

now we need to install Typescript, in same folder, we write the following command in the console:

   >*tsc --init*

that command works to create an archive with the following name *"tsconfig.json"*, in this file we need to uncomment the following instruction *"outDir": "./build"*
the root *./build* save the archive translated of Typescript to json. You can change the name *build* for other that you like put. 

