## What is a micro services architecture?
- An application is built as a collection of small, loosly coupled services that can be independantly developed, deployed and scaled
- Each microservice focuses on a specific buisness capability and communicates with other services through API's.
- They can be used break down complex applications, scale individual services and for continuous integration, deployment and delivery. 

## Who uses it in the industry?
- Netflix use it instead of monolith to handle specific tasks like reccomendations, authentification and streaming. 
- Amazon use it for services like AWS, prime and marketplace. 

## Why should we use it?
- Scalability
- Flexibility
- Fault isolation
- Reusability
- Continuous deployment 

## When not to use it?
- Small and simple applications 
- Minimal scalability requirement 
- Strong reliance on interdependancies could introduce unnessecary complexity. 

## Microservice vs 2Tier vs Monolith 
- In monolith, the whole architecture is built as a single unit where all components are connected.
- It's easiar to initially develop, but as it grows it becomes harder to maintane.
- Microservices turns it into smaller, more loosly connected services that can be worked on independantly

- Two-tier consists of a client-tier and a server-tier
- Microservices goes beyond this by having even smaller parts. This allows for each part to handle specific tasks, and communicate with eachother when needed. 

## What is docker?
Docker is a tool that simplifies the deployment and management of applications by packaging them into self-contained units called containers. These containers include everything needed to run the application, making it easy to move and run the application consistently across different environments. 

## Common examples
- App deployment
- Microservices architecture
- Continuous integration/deployment
- Development environments
