# DevOps Introduction

- IT before DevOps:

Before DevOps, the teams that worked on the software projects would all be separate. Each team had their own jobs that they worked on, and there was little to no communication between them.

Working in silos, Development and Operations teams don't communicate effectively. Development would develop, then pass to operations. When operations encountered errors, operations would have to pass back to Development so little communicacion between the teams. Development and production environments are often different so it can take anywhere from weeks to months for the Operations team to review the work the developers have done, slowing things down for them.

That is why the concept of devops was born. DevOps is trending and hot in the IT world as it has been adopted by most top companies.

### Infrastructure Revolution

- Growth of cloud computing and allows scaling on demand. It allows us to save money. Cloud computing allows all of the above, just for a subscription fee. Or by paying as much as used.


### Application Design Patterns

- Monolith: everything in the same place, with no backup. All the code and the different parts of it are built together. Use for very small projects.
- N-tier: seperate front and back end. Have differents team working in the front and back end. Processing, data management, and presentation functions are kept physically and logically separate.
- Microservice: lots of different teams working. Each service is seperate with different teams. All aspects are seperated from all other aspects.

### Software Development Methodology

- Waterfall: Simple but non-adaptable if things dont go perfectly you will have serious problems at the end. each stage of development takes place in sequence. Hard to track back when finding errors at late stages, dependencies right the way to the end (sequence, hard to track back, fix issues)
- Agile: Iterative and flexible, responds to change and creates more robust products. Iterations, meaning no dependencies(iterations, easier to fix bugs)

### Challenges in IT

- Challenges in new SDLC (the four pillars of DevOps):

What does DevOps offer?

1. Ease of use:

We can create our own environment in our local machine to test the code. But we specify what we have installed (windows, vagrant, virtualbox, what version), so that someone else can create the same environment to check that everything works correctly.

2. Flexibility

Not everyone uses the same technology, which allows us to adapt to different technologies to be able to use the code. You want to realeases your app in the differents platforms.

3. Robustness

Robustness is the ability of a computer system to deal with errors during execution and to deal with erroneous entries. Be sure that everything works.

4. Cost

The clear example is Cloud Computing to manage the cost, scaling on demand.

A successful DevOps implementation turns challenges into benefits

### What is DevOps?
 
A term related to enterprise softwware development. DevOps = Dev + Ops (Developers & Testers + IT Operations)

- A collaboration of Development and Operations.
- A culture which promotes collaboration between Dev and Ops Team to deploy code to production faster in an automated & repeatable way.
- A practice of development and operation engineers taking part together in the whole service lifecycle.
- An aproach through which superior quality software can be deployed quickly and with more reliability.
- An alignment of development and IT operations with better communication and colaboration.
- Academics definition (from Wikipedia): a set of practices intended to reduce the time between committing a change to a system and the change being placed into normal production, while ensuring high quality. Moving changes from developemtn to production with shorter time and higher quality.

### DevOps Value (CAMS Model)

- Sharing
- Measurement
- Automation
- Culture: everyone need to adapt it. Not only one member.

### DevOps Principles

- Customer-centric action
- End-to-end responsibility
- Continuous improvement
- Automate everything
- Work as one team
- Monitor and test everything

### Stages in DevOps lifecycle

1. Continuos Development
2. Continuos Testing
3. Continuos Integration
4. Continuos Deployment
5. Continuous Monitoring: We find out the problems before the users find it. We need to be sure that product is live.

### DevOps Tools/DevOps Arhictecture and Platform

- Ansible
- Chef
- Git
- Jenkins
- Bamboo
- Nagios
- AWS
- Puppet
- Saltstack
- Gradle
- Eclipse
- Many others

For continuos integration: Jenkins, Bamboo
For continuos testing: TestComplete, Apache JMeter, Se
For continuos monitoring: logstash, kibana, splunk
For continuos delivery: Azure, AWS, containerization(Docker)

### DevOps implementation

- Cloud Platform (AWS, GCP, Azure)
- Infrastructure Architecture (virtualization, containerization)
- DevOps implementations: 
    1. Infrastructure as Code (IaC)
    2. Infrastructure as a Service (IaaS)
    3. Infrastructure as a Platform (IaaP)
    4. Infrastructure as a Product

### Risk Register

Chance of occurrence of events, the potential damage and the risk

### DevOps conclusion:

DevOps is a culture that everybody need to adopt.

DevOps impacts:
- Culture
- Collaboration as a team (People/teams)
- Principles
- Automation tools
- Software development Lifecycle
- System Quality
- Cost Efficiency
- Business Value

- Will you be a good DevOps engineer?

1. Understaing automation tools.
2. Knowledge of testing.
3. Soft skills.
4. Be an excellent Sysadmin.
5. Deploy virtualization.
6. Hands-on experience in network and storage
7. Knowledge of coding.
8. Security aspects of the IT organization.

## QUESTIONS:

**- What is DevOps?**

DevOps is an amazing software development methodology that combines software development (Dev) with IT operations (Ops) participating together in the entire service life-cycle.

To understand it we have a developer and developers are responsible for things suchs as new product features, bug fixes, security updates and code refactoring and much more. The development team are building products and eventually will have to deploy to a development environment to check integrations and various other aspects of the product. Development environments can vary wildly to production environments. So when deploying from development to production, warning and errors often occur. Here is when operations teams come to the stage. Operations teams are responsible for managing service, ensuring that services are running and products are running correctly. Basically, that are sufficiently monitored and the server uptime is maintained and largely growing capacity as the product.

So, DevOps is a culture that bridges the gap between development and operation teams, in order that they can build, test, and release software faster.

**- Why do we need DevOps/Why should we use it?**

In the past, before DevOps, the companies use to have issues with interactions between development, testing and deployment teams. They used to work individually so there was no coordination and communicaciont and they had a lot of problems putting everything together to get the product. The teams that worked on the software projects would all be separate. Each team had their own jobs that they worked on, and there was little to no communication between them and development and production environments are often different so code that works for the developers can end up with bugs when moved into production.

For the reason that before, the development and operations team used to work in silos (This means, such as the inability to work efficiently between the areas or business units that comprise them). It may seem to operations that development are merely thworing the problems and issues over the water operations to deal with and from a developer's perspective, it can scene operations can be very slow and lacking the frequency that the development team need to deliver. So as both had development and operations team were working in silos, the key aspects of DevOps is breaking no solos down and having the two teams working closer together, sharing responsibilities, beginning to deploy the infrastructure development need as code and being able to automate all these processess. So these are the main principles of why we need devops, of which the benefits will be: cloud deployment reduce costs and make projects scalable, promotes colaboration culture and helps superior product creation in less time.

**- Benefits of DevOps practices?**

As we already know what devops is and why this culture needs to be implemented, now we are going to talk about the good practices of which devops have to be supported.

They are continuos integration, continuos delivery in continuos deployment, often simply known as CI/CD. So now we are going to talk about CI and CD practices in more depth. 

- Continuos Integration: we have a development team building products, writing test to ensure that the product work correctly and storing that code in a source control system to allow other developers to work on it.

- Continuos delivery: the next step will be to engage with the operations team and work together to deploy onto either on premise or cloud infrastructure. Utilizing infrastructure as code and ensuring the order test pass here too. Everything should be stored together to ensure that version control is continued thoroughout the entire product. Now a server will manage all of them. The server will connect to git. Monitor any changes and then in turn run all of the practices. So once the test have passed, then move to a pre production environment and complete the same practice to ensure that quality is running throughout.

Continuous delivery is an extension of continuous integration to make sure that you can release new changes to your customers quickly in a sustainable way. This means that on top of having automated your testing, you also have automated your release process and you can deploy your application at any point of time by clicking on a button. In continuous Delivery the deployment is completed manually.

- Continuos Deployment: Continuous Deployment goes one step further than continuous delivery, with this practice, every change that passes all stages of your production pipeline is released to your customers, there is no human intervention, and only a failed test will prevent a new change to be deployed to production.

Finally all of these practices combined and runnint test all the way through to production is known as continuos deployment.

**- What are the benefits of devops?**

Companies that incorporate DevOps practices get more done, plain and simple. With a single team composed of cross-functional members all working in collaboration, DevOps organizations can deliver with maximum speed, functionality, and innovation. Technical Benfits: Continuous software delivery and faster resolution of problems. Cultural Benefits: More productive teams and higher employee engagemet. Business Benefits:Faster delivery of features and improved communication and collaboration.

In turn, this will deliver faster time to market, improved team collaboration, continous release cycles, automated and scalable environments, and most importantly increased quality due to automated testing throughout.

Benefits: Faster deliver time, continuos release and deployment, decreased rate of failures and fixes in DevOps.
