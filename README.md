# Commands-to-mount-a-REST-API
This repository have commands to Node js with Tyscript, Angular Ando Docker 

# Node js and Typescript
First we created a folder with the following name *"Backend"* or *"Server"* , then on the folder that we created, we need to create a package.json, we will use the following command:
  
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

Now we need to create a command that we will use to translate Typescript to Json, and other command to refresh the server. those commands we will write in the package.json, to more specific in the scripts part. before than that we wil install this dependen:

  >*npm -i nodemon -D*
  
  >> ***Nodemon*** is a tool that helps develop node.js based applications by automatically restarting the node application when file changes in the directory are detected.

After that, in the scripts part, we need to write this:

  >*"build": "tsc -w",* (this part with the comma)
  >*"dev": "nodemon build/index.js"*

the root build/index.js is the root of the file that the open the port.

Finally, run those coman with the following structure:
  
  >*npm run ***"the name of the command created"****

Those commands that we installed and created, it only to create a server with Node js, using Typescript. If you need to connect some database, I will recommend to see the following videos:

  >[Angular Mysql CRUD Tutorial, REST API Node & Typescript](https://www.youtube.com/watch?v=lxYB79ANJM8&t=961s)
  >
  >[Microsoft SQL Server & Nodejs REST API CRUD](https://www.youtube.com/watch?v=ReK0kscoF8o&t=2118s) ***(this video only use Node js and json)***

If you want to connect to the Microsoft SQL Server using typescript, I leave you a link to my repository to see an example of how to do it
  >[Repository Microsoft SQL Server & Nodejs](https://github.com/Pegre369/Microsoft-SQL-Server-SQLServer-Nodejs)


