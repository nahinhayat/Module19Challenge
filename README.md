Module 19 Challenge

Description:

This challenge consists of creating a Streamlit application which can be used to find a fintech professional. The application displays the candidate's information such as their wage and rating. There is a sidebar that allows you to choose a candidate, set an amount of hours you would like to hire them for, and send a transaction for this through the Ethereum blockchain. 

Details:

The process to get this application running begins with entering a seed phrase into the .env file as a variable. The code to create an Ethereum account using the seed phrase to generate a private key is already present:

![screenshot1](https://github.com/nahinhayat/Module19Challenge/blob/main/module19screenshots/screenshot1.png)

Then we import multiple functions that will be used in our application from another file:

![screenshot2](https://github.com/nahinhayat/Module19Challenge/blob/main/module19screenshots/screenshot%202.png)

The code for writing the application is mostly complete, there are a few variables and functions that need to be defined. After this is all done, we have the streamlit application diaply the transaction hash for the transaction involving sending the Ether to the candidate:


![screenshot3](https://github.com/nahinhayat/Module19Challenge/blob/main/module19screenshots/screenshot3.png)

Here are the results of successfully completing the transaction displayed in Ganache. The first image displays the account that sent the Ether, the second shows the information for the transaction itself:

![ganacheaccount](https://github.com/nahinhayat/Module19Challenge/blob/main/module19screenshots/ganache%20account%20screenshot.png)

![ganachetransaction](https://github.com/nahinhayat/Module19Challenge/blob/main/module19screenshots/ganache%20transaction%20screenshot.png)

Author: Nahin Hayat https://www.linkedin.com/in/nahinhayat/