# IBM NLU React App

## IBM Watson services to find sentiments and emotions in text.

### How to build

1. Change to client directory sentimentAnalyzeClient.
`cd sentimentAnalyzeClient`

2. All packages are needed to be installed are listed in package.json. To install and save those packages, run the following command in the terminal.
`npm install --save -s`

3. Run customized package.json to generate and copy the client code to the server.
`npm run-script build`

4. Change to the server directory.
`cd ../sentimentAnalyzeServer`

5. All packages are needed to be installed are listed in package.json. To install and save those packages, run the following command in the terminal.
`npm install --save -s`

6. Install the ibm-watson package in your server side using the following command.
`npm install --save -s ibm-watson@6.1.1`

7. Create .env file in sentimentAnalyzeServer folder.

8. Copy the credentials to point to your Watson NLU credentials from the IBM cloud and add Add the credentials required to the .env file you created.
>API_KEY=<your api key>
>
>API_URL=<your url>

9. Install dotenv to use the .env file in the server application using the following command.
`npm install --save -s dotenv@10.0.0`