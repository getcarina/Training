title: Carina for Account Management and Sales
author: Kim Tryce <kim.tryce@rackspace.com>
date: 2016-03-16
description: Script for EContent training

##What are Containers and Carina?
In October 2015 Rackspace announced at the Openstack Summit the release of our containers offering, Carina.  

Containerization is a big buzz word at the moment, but what is "a container"? The most  popular systems that manage containers are Docker and Kubernetes by Google.  In Malcolm Gladwell's book "The Tipping Point," he refers to the adoption process of ideas.  We are currently at the Early Adopters phase of the tipping point curve and it's rapidly moving towards the Early Mainstream.  So hop on the train and learn about Carina and how it can help you and your customers succeed in the next wave of technology.

A stock definition of a container is: Technology that allows the deployment & execution of an application in an all-in-one package that includes its dependencies, libraries, binaries, user files & settings, and all other required configuration files.  
What does this actually mean?  Let's go back in hosting history.
Back when Rackspace started we were known for your typical LAMP stack where we sold a server to a customer.  We then moved into the age of Cloud where we could have a multi-tenant solution.  A cloud instance acts similarly to a VM where you have a hypervisor that dictates what operating system you are using as well as how much RAM and hard drive space you need.  Containerization is the next generation of technology where there is not a need for a hypervisor and OS, or "guest OS."  The result is that containers provision faster, utilize fewer resources and have a smaller footprint.  This means a cost and time savings for your customer as well as an efficiency hardware gain for Rackspace. Win win!

In short, containerization is a disruptive, revolutionary technology!

Now that we know about containers, what is Carina?
Pitch: Carina is the first public cloud service to combine this level of performance, simplicity, and affordability for running containerized workloads – the next paradigm for distributing, running, and managing applications.

There are a few things to keep in mind about Carina.
1) Carina is Rackspace's attempt to get in the container competition early.
2) Carina is targeted towards developers that are self-sufficient.
3) Carina was a divergent from traditional Rackspace products.  How?  Carina lives at getcarina.com and is labeled as a product by Rackspace vs living within the rackspace.com banner.
4) Carina is a full disclosure product and all information needed to use the product can be found within our extensive documentation at https://getcarina.com/docs/
5) A good way to keep up to date on Carina information is to subscribe to our blog where we provide a weekly wrap-up with any pertinent updates. https://getcarina.com/blog/

Now that we know what Carina is, how does Carina work?
Carina uses Docker Swarm Command Line Interface (CLI) tools.
Carina securely builds managed container clusters
Carina spins up in under a minute.  It's really really fast.

I've mentioned Docker a couple times now.  A good description of Docker: "Docker is a tool that can package an application and its dependencies in a virtual container that can run on any Linux server. This helps enable flexibility and portability on where the application can run, whether on premises, public cloud, private cloud, bare metal, etc." - 451 Research

Unlike traditional platform-as-a-service offerings or complex tools that are opaque and expensive to run at scale, Carina allows developers to control how applications are packaged, how the environment is set up, and what happens when the application is deployed.  Developers having control = happy developers.

You may be saying at this point, wait Kim, why would someone want to use Carina instead of just using Docker since Docker is available and Open Source? Well, it's complicated to run containers.  Containers focus primarily on the packaging, distribution, and management of your applications.  They do not focus on the low level specifics of infrastructure they require. Carina solves these problems.

To sum up Carina offers:
Simplicity of a “zero infrastructure” environment managed by expert Rackers
Speed of bare metal infrastructure and “instant-on” capabilities
Greater control & flexibility with native Docker® tooling

Bragging rights: We are better than AWS, Google, and Azure.
Faster deployment (as little as 45 seconds)
Bare-metal infrastructure (vs VMs)
Open-source, non-proprietary (easy-to-use)

## Who are Carina customers?

Install base & new customers in ALL segments
VP Engineering/Director of IT Operations/Developers
Customers that are development focused
Some industries and verticals include media, gaming, website hosting, analytics, marketing automation, data science
If you're speaking with a customer and they mention: containers, Docker, deployment speed, compute power, scalability, elasticity, bare-metal, consistent performance, high-volume workloads, dynamic workload demands... they may be interested in Carina.

What does it solve for those customers?
Solves for portability challenges as in dev to test to production environments
Solves for performance
And Solves for ease-of-use

Some Workloads and Use Cases include:
Large-scale application development
DevOps seamless production delivery of applications
Data science or massive-scale modeling requiring consistent, repeatable environments

## Pricing
Carina is currently in beta and it is FREE.
There is no charge for either container clusters or the underlying infrastructure
At this time, there is no timetable for a full production and commercialized GA offering

If you have enterprise customers interested in Carina, just email carina@rackspace.com

## Some things to keep in mind
Carina is currently a free public beta offering in pre-release version
Not recommended for live production workloads
It is not supported by Rackspace Fanatical Support; it is self-managed support by user community
Carina is not recommended for legacy applications
Carina runs only on Rackspace Public Cloud infrastructure

## The Carina Website

In order to really get a feel for Carina, let's play with it!
The first order of business is to head over to getcarina.com  

Let's go through a quick tour of the site.
The landing page enables customers to signup with an email and password.  If you already have a Rackspace cloud account, you would use your username and password for that.
Important note: A customer does NOT have to enter in credit card information when signing up for Carina.  This results in a low barrier to entry.

At the top of the page we have a couple tabs that leads to a large repository of information.

After clicking on "documentation" and scrolling down to the bottom you can see we have a few sections: Getting Started, Concepts, Tutorials, Troubleshooting, Reference, Container Ecosystem
We're already on the Getting Starting page so let's click on the first article, "Overview of Carina"(https://getcarina.com/docs/overview-of-carina/)
As you can see, the top of the page has the heading, the author is our own Everett Toews based out of our Austin office, the publish date, and a hyperlink to edit the article on Github.  Github is our source of truth for all documentation on Carina.  If you find a typo or error, you can log into Github and submit a pull request for any needed changes.  If you aren't familiar with Github, you can just reach out to us via other channels which we'll go over at the end of this training.
As we scroll through this article you can see that a lot of the information I gave at the start of this training is available in this article.  We want everyone to be self sufficient in using Carina and that's why we are very particular with our documentation.

If we click on Concepts this is a great repo of documentation informing the customer about higher level strategic information around Docker, containers, security, etc.  Great area to go and read if you want to learn more about what is behind Carina.  Some like to start in this area and then drill down into the product itself.  Whatever works best for the learning style of the user.

Next up is Tutorials.  This section is awesome.  We take the approach of having actual examples versus hypothetical examples. This will be an area you'll send customers if they have questions on how to complete a specific function.  If the tutorial doesn't exist for the action your customer needs, let us know and we'll work on creating that tutorial!

The troubleshooting area is just that.  We captured questions and issues customers have had and created content to explain work arounds and further information on issues.

Within the reference area, I would like to point you to the article of "Carina FAQ".  This has questions from pricing to operations.  Great resource for customers.

Our last section in documentation is Container Ecosystems.  Since containers is a new technology we wanted to make sure and offer documentation that goes into the conversations happening in the industry.  Want to know how to design your container infrastructure?  Go here. Want to know some best practices? Go here.

Next, let's click on "blog" at the top of the page.
Our blog page can be subscribed to via RSS feed and our blogs are posted in chronological order from the most recent to the oldest.

One aspect of our blog is that anyone can submit a blog post.  Carina team members, Rackers outside of the Carina team, and customers alike have all written blog posts on getcarina.com.

If you don't have time to keep up with all the blog posts, there is one post I would suggest keeping an eye out for, and that's our Weekly Updates.

Let's scroll down to the latest Weekly Update at the time of this recording.
All of our weekly updates start with just that "weekly update" so it's easy to find.  We publish our weeklies Friday of each week.

As you can see from this weekly update, there were a ton of updates to distribute (https://getcarina.com/blog/weekly-news-athon/) including information about an incident, latest feature adds, and any tutorials or blog posts that really inform the customers.

If you want to submit a blog post, just reach out to the team and we'll get you set up.

Getting back to the landing page of getcarina.com, the next tab is Community.
At the top of the page, you'll see a link to our status.getcarina.com page.  Let's click that.
If you or your customers say Carina is down, this is where to go and find out the latest operational status as well as previous incident root cause analysis (RCA)
Going back to community.getcarina.com you'll see a link of feedback, issues, and questions.
By clicking into one of the topics "Missing control icon in carina web ui" (https://community.getcarina.com/t/missing-control-icon-in-carina-web-ui/134) you can see this post was submitted by a user that noticed a UI aspect had disappeared. Our very own Keith Bartholomew replied with the issue number and link to Github where the source of truth resides for tracking this issue.  As mentioned above, we are a very transparent team and this is a very transparent product.

The last tab on the getcarina.com page also brings us to the status.getcarina.com page mentioned above.

Yes! We made it through the tour of the website.  As mentioned, this is the place to go for all the things about Carina.

## Let's see how Carina works!
As a finally to wrap up this business level training of Carina, I wanted to provide a visual representation of what using Carina looks like.  You can follow along and spin up your own Carina clusters, if you wish.
Zero to Hero GUI: https://www.youtube.com/watch?v=FEzVdcwbPc4

That's it!  So simple to use.  One of the main takeaways I want you all to have is to walk away knowing we WANT YOUR FEEDBACK! We are an active group who seeks out feedback and suggestions from our Rackers and our users.
You can contact us a couple different ways:
Rackspace Slack #carina
carina@rackspace.com
https://community.getcarina.com/
Github: https://github.com/getcarina
Freenode IRC #carina: https://webchat.freenode.net/?channels=carina

We are a fully globally distributed team with Rackers based in Austin, San Antonio, and Work From Home. If you have questions about the Carina team its self, reach out to one of our leaders: Jesse Noller, Ken Perkins, Kim Tryce, Steve Wilson

Thank you so much for staying with me and learning about this exciting new technology.  

Excersizes

Match the vocab word:
Containers - virtualization layer runs as an application within the operating system (OS)
Docker - wrap up a piece of software in a complete filesystem that contains everything it needs to run
Carina - offers performance, container-native tools, and portability without sacrificing ease of use
Kubernetes - open source container cluster manager by Google
Microservice Architecture - a set of narrowly focused, independently deployable services

Quesitons:
Which takes up the least physical resources?
Dedicated Server
Virtual Machine
*Container

What is Docker's recommendation mentioned in the Container design philosophy article within Carina's documentation?
run only one process per container

What is the URL for our FAQ?
https://getcarina.com/docs/reference/faq/

Who wrote the blog post about Fallout Four?
Kyle Kelley

Where can I go to contanct the Carina team?
Slack #carina
Freenode IRC #carina
Community Forums
*All of the above



