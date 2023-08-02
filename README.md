```
____    __    ____  _______  __        ______   ______   .___  ___.  _______    .___________.  ______       _______       ___   .___________. _______       ___       _______   ______     _______      _______      ___      .___  ___.  _______  _______       ___   ____    ____ 
\   \  /  \  /   / |   ____||  |      /      | /  __  \  |   \/   | |   ____|   |           | /  __  \     |       \     /   \  |           ||       \     /   \     |       \ /  __  \   /  _____|    /  _____|    /   \     |   \/   | |   ____||       \     /   \  \   \  /   / 
 \   \/    \/   /  |  |__   |  |     |  ,----'|  |  |  | |  \  /  | |  |__      `---|  |----`|  |  |  |    |  .--.  |   /  ^  \ `---|  |----`|  .--.  |   /  ^  \    |  .--.  |  |  |  | |  |  __     |  |  __     /  ^  \    |  \  /  | |  |__   |  .--.  |   /  ^  \  \   \/   /  
  \            /   |   __|  |  |     |  |     |  |  |  | |  |\/|  | |   __|         |  |     |  |  |  |    |  |  |  |  /  /_\  \    |  |     |  |  |  |  /  /_\  \   |  |  |  |  |  |  | |  | |_ |    |  | |_ |   /  /_\  \   |  |\/|  | |   __|  |  |  |  |  /  /_\  \  \_    _/   
   \    /\    /    |  |____ |  `----.|  `----.|  `--'  | |  |  |  | |  |____        |  |     |  `--'  |    |  '--'  | /  _____  \   |  |     |  '--'  | /  _____  \  |  '--'  |  `--'  | |  |__| |    |  |__| |  /  _____  \  |  |  |  | |  |____ |  '--'  | /  _____  \   |  |     
    \__/  \__/     |_______||_______| \______| \______/  |__|  |__| |_______|       |__|      \______/     |_______/ /__/     \__\  |__|     |_______/ /__/     \__\ |_______/ \______/   \______|     \______| /__/     \__\ |__|  |__| |_______||_______/ /__/     \__\  |__|                                                       `---'

```

### Description
This is a sample Java Spring Boot application that provides an excellent opportunity to explore the benefits of using Datadog APM (Application Performance Monitoring) in microservices environments.

The application has already been developed for you, so the deployment process is made simple. All you need to do is follow the defined steps to deploy the application in your preferred cloud environment.

By deploying and using this application with Datadog APM, you can gain valuable insights into the performance and behavior of your microservices, allowing for better optimization and monitoring in your cloud infrastructure. Happy exploring!

#### Scenario

We will be deploying a sample application comprising two microservices:

1. Employee Microservice: Manages employee data, including employee ID, name, and email. Users can add or delete employee details using this service.
2. Order Microservice: Allows employees to place office hardware orders. It provides the ability to look up the number of items ordered by an employee.

As part of this use-case user responsibilities is to deploy the application in the test environment and closely monitor its performance. Our primary objective is to ensure a seamless end-to-end flow of requests between the two microservices and proactively detect any issues that might impact the application's performance.


### Importance of Datadog Game Day

The Datadog Game Day serves several critical purposes:

* Real-World Incident Simulation: This event simulates real-world incidents that could potentially occur in a production environment. It provides us with valuable hands-on experience in responding to critical situations and effectively handling performance-related incidents.
* Testing Incident Response Capabilities: The game day acts as a practical platform to test and enhance our incident response capabilities. By utilizing Datadog's monitoring tools, we can identify bottlenecks, performance degradations, and potential service breakdowns, allowing us to resolve them swiftly.
* Microservices Monitoring in Action: As our application is built on microservices architecture, the game day will showcase how Datadog's monitoring capabilities adapt and effectively function in a distributed and interconnected environment.
* APM (Application Performance Monitoring) Benefits: Throughout the game day, we will experience the advantages of Datadog's APM feature. It enables us to gain deeper insights into service performance, detect breakdown points, and optimize the overall application performance.
* Plug and Play with Microservices: Datadog's seamless integration with microservices offers a plug-and-play experience. This facilitates easy adoption and monitoring of new microservices in the future without significant disruptions to our monitoring setup.
* Alerting and Insights: Datadog provides various features for generating alerts and capturing insights. During the game day, we will explore different alerting mechanisms to proactively respond to potential issues.


### Getting Started


To perform this usecase, follow these steps:

* Refer to the EmployeeREADME.md and OrderREADME.md files for detailed explanations of both microservices applications. These files contain essential information about the architecture, endpoints, and functionality of the services.
* Install the Datadog agent on your test environment. This agent will collect metrics, traces, and logs, enabling comprehensive monitoring of your microservices.
* Familiarize yourself with the list of requirements for each microservice at three levels of difficulty: easy, normal, and hard. These requirements will guide us in setting up and configuring the monitoring effectively.
* Monitor its performance using Datadog and ensure smooth communication and flow of requests between the Employee and Order microservices.
Use Datadog's APM feature to gain insights into service breakdowns and optimize the application's performance. Set up alerts to detect any issues promptly and respond with efficiency.


### Prerequisites for the Game

Before starting the game, ensure the following prerequisites are met:

* User should have access to an AWS Account (Free tier) and be familiar with using a cloud9 environment via AWS.
* Java version should be 1.8 or above.
* After the game day, it is advised to delete the resources created during the event.
* Outbound connections to the Datadog endpoint (https://app.datadoghq.com/) should be allowed.
* Users will be provided with Datadog access, including the endpoint and API key for a new Datadog account during the game.
* Test applications will be provided during the game for use.


### Three Difficulty Levels in Datadog Game

To complete the Datadog Game, you need to complete all three levels. Each level has specific tasks:

* Easy Level: Install the Datadog agent on the Host.
* Medium Level: Download the Jar files for both applications from the public Git/Bitbucket Repo (https://github.com/surajtikoo/datadog-gameday.git).
* Hard Level: Forward the application logs to Datadog, ensuring no sensitive information is forwarded. Verify the logs and create an alert of your own choice based on error/success scenarios to notify teams.


The Datadog Game Day is an exciting opportunity for learning and improving our incident response skills. Let's embrace the challenge and make the most out of this simulated real-world experience.

Happy monitoring and troubleshooting!

## Note:
Before starting you can refer to the below link to get more insights about what exactly the Datadog APM
https://surajtikoo.medium.com/application-tracing-using-datadog-apm-c91bbf6b2537
https://www.datadoghq.com/product/apm/

