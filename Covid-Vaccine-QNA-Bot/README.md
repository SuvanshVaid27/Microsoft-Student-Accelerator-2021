# vaccine-qna

This project is a part of the submission for Microsoft Student Accelerator (MSA) 2021. Here is the link to the deployed website: https://covid-qna-flask.azurewebsites.net


# Idea 

### The Problem
Covid Vaccines are being made available to a large segment of the Australian Public. However, despite the efforts from the government, there are many australians who still have vaccine hesitancy. One of the major reasons for this is the spread of misinformation and fake news, be it through news channels, word of mouth or social media channels. 

### Proposed Solution
Through this project, a web-based qna bot is proposed which answers all the vaccine related questions of a user with regards to the official vaccine information provided by gov.au and aims to reduce the spread of misinformation which would subsequently lead to more people getting vaccinated. 

### Future Scope
This project could be further developed into a vaccine information website which provides essential vaccine related news. Also, natural language functionality could also be added to provide the user with the exact search results from the government website for any covid vaccine queries. 


# Approach

### Azure AI solution
To implement the proposed idea, a conversatonal AI approach was used to create an artificial intelligence workload that deals with dialogs between AI agents and human users. Microsoft Azure provides QnA Maker and Azure Bot Service to build a bot. To create a web based application, Azure also provides Web App service to build, deploy and manage powerful web apps. 

### Why AI?
A conversational AI chatbot can easily engage with people on a level that feels personal and even empathetic – like talking to a helpful assistant. Chatbots and voice bots can answer questions and help people to solve their needs, without any actual human intervention. Also, in the given case, there is already a database of questions and answers on the offical au website. Thus, a smart NLP based AI chatbot could easily learn from the question-answer pairs and even be able to answer queries which are not exactly similar to the trained questions. 


# Implementation

<img src="https://github.com/SuvanshVaid27/vaccine-qna/blob/main/static/lifecycle.png" width="700" height = "500" title="lifecycle">

1. Gathering frequently asked vaccine questions
Firstly, the question answer pairs were manually collected from the official [website](https://www.health.gov.au/initiatives-and-programs/covid-19-vaccines/is-it-true) of the department of health Australia. 

2. Creating a bot solution
To create a bot solution, a combination of two core technologies on Microsoft Azure was used:
* QnA Maker: This cognitive service enables you to create and publish a knowledge base with built-in natural language processing capabilities. This tool helped easily create a knowlegde base of all the question-answer pairs by using the document that was prepared in step 1. 
* Azure Bot Service: This service provides a framework for developing, publishing, and managing bots on Azure. With a few simple steps, a bot was created that responds intelligently to the vaccine related questions over multiple communication channels.

3. Creating a website and embedding the web chat control:
To create a website for the user to interact with, a python app was created using the Flask framework. The bot created in step 2 was then embedded into the website specifying the secret within the iframe tag. 

4. Deploying the website on Web App:
To deploy the website, the code was uploaded on local Github and then used in the Azure Web App service in a development server. 

# Tech Stack
1. Python
2. Flask 
3. HTML, CSS
4. Azure App Service
5. Azure Cognitive Service


# Installation

To run this web application on your own system, follow the steps given below:

Step 1. Clone the project.

```bash
  git clone https://github.com/SuvanshVaid27/vaccine-qna.git
```

Step 2. Install dependencies
```bash
  pip install -r requirements.txt
```

Step 3. Run the application
```bash
  flask run
```

# Video Demonstration

<img src="https://github.com/SuvanshVaid27/covid-qna/blob/main/static/app-demo.gif" width="700" height = "500" title="Dashboard">




