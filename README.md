

To start, run 'npm i' , 'npm install body-parser cors express mongoose nodemon', and 'npm start' for both client and server side.
If at any point one of these commands does not work, run:
  
If an error is thrown, export NODE_OPTIONS=--openssl-legacy-provider on server
then 'npm start' - both on server side. 


The issue is with Node Js V17. More about it: https://stackoverflow.com/questions/69394632/webpack-build-failing-with-err-ossl-evp-unsupported

