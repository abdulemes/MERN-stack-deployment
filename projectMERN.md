# Project Workflow

## Setting up VM environment

Step 1 - Initializing a VM using a vagrant box name from vagrant cloud.

Step 2 - Opening the vagrantfile to edit and enable public IP address using vim editor.

Step 3 -  Bringing up the VM. 

![IMG_9548](https://user-images.githubusercontent.com/93732510/162269164-92d2de00-28bc-4e5f-906c-d0d18ac280f5.jpg)

Step 4 - Now we can log into the VM via ssh.

![IMG_9549](https://user-images.githubusercontent.com/93732510/162269671-f093186b-5525-4a60-8648-3310b25304ac.jpg)

## Backend configuration

Step 1 - apt package manager is first of all updated and upgraded. 

![IMG_9550](https://user-images.githubusercontent.com/93732510/162272078-066e7b9d-d350-4f14-a669-8ed880936686.jpg)

Step 2 - Location of node.js software is gotten from ubuntu repository.

![IMG_9551](https://user-images.githubusercontent.com/93732510/162272621-00e09d56-d445-4bb0-849c-0ca3f787238e.jpg)

Step 3 - node.js is then installed and this comes with npm package manager.

![IMG_9552](https://user-images.githubusercontent.com/93732510/162273276-aeff9e05-84b1-4a05-91e4-11d18aacfecb.jpg)

Step 4 - Next is to check node and npm have been installed by checking the version. 

![IMG_9553](https://user-images.githubusercontent.com/93732510/162273725-a9c66577-9f51-4625-b7b7-a6f80f8ce23a.jpg)

Step 5 - In this step the project directory is created where npm is then initialized.

![IMG_9554](https://user-images.githubusercontent.com/93732510/162274447-ce2d36f1-a48f-4b20-88ca-8f1098a7684d.jpg)

Step 6 - Installing express as a framework for node.js

![IMG_9556](https://user-images.githubusercontent.com/93732510/162278775-52b7e848-b425-4174-a754-21f90dab3e65.jpg)

Step 7 - An index.js file is created and dotenv is also installed. 

![IMG_9557](https://user-images.githubusercontent.com/93732510/162279643-e4db31b2-01d8-4d18-a9dd-b56ddc80de77.jpg)

Step 8 - Index.js file is then open vim editor and code from documentation is pasted in the file.

![IMG_9558](https://user-images.githubusercontent.com/93732510/162280519-39c11bb5-0163-4bd5-b8d5-f5296773a494.jpg)

Step 9 - node index.js command is then run to check that the server is running. 

![IMG_9559](https://user-images.githubusercontent.com/93732510/162281147-2800a438-530e-472a-ad58-fb1f5ac84a75.jpg)

Step 10 - We check the server in the browser using public IP address on port 5000

![IMG_9560](https://user-images.githubusercontent.com/93732510/162281990-96981916-3ded-4070-9717-8de7b3b33e12.jpg)

Step 11 - A file is created in routes directory where each task endpoint is defined.

![IMG_9562](https://user-images.githubusercontent.com/93732510/162489784-c8dcb7f9-815e-4c85-9c8b-9a9610c1a88a.jpg)

![IMG_9561](https://user-images.githubusercontent.com/93732510/162489923-73176133-5c72-4d5f-92fc-5ca9a188b551.jpg)

Step 12 - To create a schema and model for mongodb, mongoose is installed. 

![IMG_9566](https://user-images.githubusercontent.com/93732510/162490546-cb257308-0a28-41f2-b712-2ceebc059852.jpg)

Step 13 - Todo file is then created in model directory where the mongoose code will be saved.

![IMG_9568](https://user-images.githubusercontent.com/93732510/162491348-c31108cc-e455-4c0b-ba7a-4aee3f7f5622.jpg)

![IMG_9569](https://user-images.githubusercontent.com/93732510/162491809-3cde710a-a92d-4e5d-85ce-32085b4bba48.jpg)

Step 14 - There is need to now update the api file in routes directory to use the new model defined.

![IMG_9570](https://user-images.githubusercontent.com/93732510/162502326-82a08720-8ac9-4d07-a56d-59f7208d0556.jpg)

Step 15 - Mongodb database is configured using mlab to serve as database for the application.

![IMG_9572](https://user-images.githubusercontent.com/93732510/162502779-a25037ea-fcc8-4a51-9a8f-cdf955f8cfb2.jpg)

Step 16 - Now an environment variables file is created as defined in previous index file. 

![IMG_9573](https://user-images.githubusercontent.com/93732510/162503441-520a2695-ae66-4097-bb61-da5b57084e3d.jpg)

![IMG_9574](https://user-images.githubusercontent.com/93732510/162503538-91617438-84f9-4b9c-82ae-31eb2c6d7aeb.jpg)

Step 17 - Here the index.js file is updated to reflect the use of .env so that node.js can connect to database.

![IMG_9575](https://user-images.githubusercontent.com/93732510/162503989-087e10b9-75a1-46b8-a3d2-f24bf243b741.jpg)

Step 18 - The server is then started to see check that the database connected successfully.

![IMG_9578](https://user-images.githubusercontent.com/93732510/162504963-20c98cf2-119b-40ba-8ace-bc405ae48fa7.jpg)

## Use of RESTful API to test backend configuration.

Step 1 - A POST request to API is created.

![IMG_9582](https://user-images.githubusercontent.com/93732510/162507880-8cba2a54-8644-4a4c-84c4-a22b57c84e91.jpg)

Step 2 - A GET request to the API is created. 

![IMG_9583](https://user-images.githubusercontent.com/93732510/162508047-8a5fb3c9-cc61-4bb5-8740-5842f08ea26f.jpg)

## FrontEnd configuration

Step 1 - A client directory is created for where the react code will be.

![IMG_9585](https://user-images.githubusercontent.com/93732510/162508653-1fe5deb2-1605-4192-bc80-5bc3a35df8dd.jpg)

Step 2 - Concurrently and nodemon is installed.

![IMG_9588](https://user-images.githubusercontent.com/93732510/162508899-a4f534a9-31de-4e9a-8da7-8047dfde8105.jpg)

Step 3 - The package.json file is updated to reflect the concurrently and modemon installed.

![IMG_9589](https://user-images.githubusercontent.com/93732510/162520650-be0be594-2631-4e0b-af5d-3aa0589d6124.jpg)

Step 4 - Proxy configuration is also added to the package.json file so it can be accessed from its port in the browser.

![IMG_9591](https://user-images.githubusercontent.com/93732510/162522542-0c2e1ae9-d5dc-499d-bb73-9c5a685e7366.jpg)

Step 5 -  The server is then started and viewed via the browser usin public IP address and port number.

![IMG_9592](https://user-images.githubusercontent.com/93732510/162524291-79e75c4f-5e4b-4c2f-b64d-ede1a1e5c3ba.jpg)

![IMG_9594](https://user-images.githubusercontent.com/93732510/162524464-2961d9b8-e86e-45ed-a470-56abb09da966.jpg)

Step 6 - In this step, the react components are setup in respective files in the components directory. 

![IMG_9596](https://user-images.githubusercontent.com/93732510/162525385-348dd3b4-f576-4137-985d-f1dcac3f9359.jpg)

Step 7 - The application code is then put in respective files, statring with index.js file

![IMG_9597](https://user-images.githubusercontent.com/93732510/162525861-852bece1-d5e4-4055-9238-ba55566d4a57.jpg)

Step 8 - Axios is intalled as HTTP client for browser and node.js.

![IMG_9598](https://user-images.githubusercontent.com/93732510/162526233-58ad7f76-f092-4427-ab23-f86746331ba4.jpg)

Step 9 - Application is copied into ListTodo.js file

![IMG_9600](https://user-images.githubusercontent.com/93732510/162526617-5b6696d7-eb83-47c8-b08e-fe896f7c8fdc.jpg)

Step 10 - Application is copied into Todo.js file.

![IMG_9601](https://user-images.githubusercontent.com/93732510/162526767-6cfb74b1-1284-468b-9c09-484e3b838c66.jpg)

Step 11 - Application code is copied into App.js file.

Step 11 - Application code is copied into App.css file in the src directory. 

![IMG_9602](https://user-images.githubusercontent.com/93732510/162526950-9df9da53-2da1-47e3-987e-0378cf4e1e15.jpg)

Step 12 - Application code is copied into index.css in the src directory. 

![IMG_9603](https://user-images.githubusercontent.com/93732510/162527171-d5ecdf76-aa57-4843-8915-9945069c0e55.jpg)

Step 13 - Now in Todo directory the server is started by running npm run dev command and output is checked in browser. 

![IMG_9605](https://user-images.githubusercontent.com/93732510/162529033-32dccbe1-9bf4-48c6-956c-2be0127baafd.jpg)

