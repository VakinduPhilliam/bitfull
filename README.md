
# Bitfull of Work:

Bitfull is an AI powered web app that uses Machine Learning to determine the most relevant Bitbucket project issues and pull requests that require the developer's urgent attention.

The app uses a pretrained Machine Learning model that is fine-tuned to identify genuine in-progress Bitbucket project issues, open pull requests, and active alerts, while filtering out profanity, abuse and irrelevant pull-requests and project issues. 

Bitfull then plots a graph to notify the developer about the most critical project issues, pull requests and alerts that are worth the developer's time. 

The app uses Pandas and Scikit-Learn to build a Machine Learning Profanity Detection Model that also filters out un-important pull-requests and issues. 

For example 'README.md' documentation updates are also ignored by the model, because they aren't critical updates.

<br/>

_Bitfull Interface:_

![Bitfull of Work Interface](/docs/ui1.png)

</br>

![Bitfull of Work Interface](/docs/ui2.png)

</br>

![Bitfull of Work Interface](/docs/ui3.png)

</br>

![Bitfull of Work Interface](/docs/ui4.png)


</br>

## Machine Learning Technologies Used:

- Python3 - programming language used for Machine Learning.

- Pandas - is used for data cleaning and analysis.

- Scikit-learn (SKlearn) - is used for Machine Learning and Statistical Modeling.

- Pip8 or greater - is used for managing python dependency installations.

<br/>

## Installation:

Install the following applications on your PC before running the web app.

- [Node.JS](https://nodejs.org/en/download/current/)

</br>

### Download or Clone app from Github:

Go to https://github.com/VakinduPhilliam/bitfull and download or clone the app.

</br>

### Install NPM dependencies:

Open the unzipped folder in your favorite code editor and install the app's npm dependency modules. 

_npm install_

</br>

Then install python dependencies (Make sure to have pip8 or greater installed).

</br>

_npm run pyinstall_

</br>

### Running the App:

To run the app, execute the command below in the Command terminal. 

_node index.js_

</br>

You should see a message like, "Server running on port: 6700" in your command terminal if the app is running successfully.

Open your browser and visit, http://localhost:6700/ to view the app.
(You must be online for the app to fetch the API from Atlassian.)

