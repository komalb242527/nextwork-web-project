# Java Web App Deployment with AWS CI/CD.

Welcome to this project combining Java Web app development and AWS CI/CD tools!

<br>

## Table Of Contents
- [Introduction] (#Introduction)
- [Technologies] (#Technologies)
- [Setup] (#Setup)
- [Contact] (#Contact)
-[Conclusion] (#Conclusion)

<br>

## Intoduction
This project is used for an introduction to creating and deploying a Java-based web app using AWS, Especially their CI/CD tools.
The deployment pipeline i am building around the java web app in this repository is invisible to the end-user, but makes a big impact by automating the software release processes.

- I am doing this project to learn more about CI/CD and get hands on experience in automating the flow from developing code to deploying web app.
- This fits into my career goals because i want to become a Devops Engineer

<br>

## Technologies
Here's what i am using for this project:

- **Amazon Ec2**: I am developing my web app on amazon EC2 virtual servers, so that software development and deployment happens entirely on cloud.
- **Additional Tools Used**: Key Pairs, SSH Connection, intalled Git, Maven and Java to generate the web App.
-- **VSCode**: For my IDE, i chosee Visual Studio Code. It connects directly to my development EC2 instance, making it easy to edit code and manage files in the cloud.
-- **GitHUB**: All my Web App code is stored and versioned in the Github repository.
-- **[Coming Soon] AWS codeartifact**: Once it is rolled out, CodeArtifact will store my artifacts and dependecies, which is great for high availbility and speeding up my project's build process.
-- **[Coming Soon] AWS CodeDeploy**: Ocne it is rolled out, Codedeploy will automate my deployment process across EC2 instances.
-- **[Coming Soon] AWS CodePipeline**: Once it is rolled out, codepipeline will automate the entire process from Github to Codedeploy, integrating build, test, and deployment steps into one efficient workflow.

<br>

## Setup
To get this project up and running on your local machine, follow these steps:

1. Clone the repository:
    ```bash
    git clone https://github.com/komalb242527/nextwork-web-project.git
    ```
2. Navigate to the project directory:
    ```bash
    cd nextwork-web-project
    ```
3. Install dependencies:
    ```bash
    mvn install
    ```
    <br>

    ## Contact
    If you have any questions or comments about my CI/CD project, please contact: Komal - [email@example.com](mailto: komalb242527@gmail.com)

    <br>

    ## Conclusion
    Thank you for exploring this project!. I'll continue to build this pipeline and apply my learnings to future projects.

