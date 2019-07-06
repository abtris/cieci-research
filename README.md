# Continuous Integration Engine Configuration Interface (CIECI) Research

Create Continuous Integration Engine Configuration Interface (CIECI)
CNCF create great work with specification interface about Container Storage (CSI), Service Mesh Interface (SMI), Cloud Events Specification and others. I think [The Continuous Delivery Foundation](https://cd.foundation) (CDF) have to work on similar standards for future CI/CD systems.

I worked with many Continuous Integration Engine (CIE) and that is just a few in a big pile that you can find it. In the latest years, I worked with Jenkins, TeamCity, CircleCI, TravisCI, and Wercker. I’m making training for Hudson/Jenkins for years.

You can see how many systems are similar and still not easy interoperable. 
I think that CDF should work on the specification that can be extended and use in every CIE  for easy use for developers who start or maintain configuration of the build pipelines. 

What we need. Simple format, DSL or YAML based that define the basics (steps, artifacts, machine setup). What is a build type, languages, tools, and steps how to do it? The second main thing is workflow, if you have bigger builds you need run them in parallel, make a matrix for support multiple version programming language, server or client.

I don’t think that we need it 100% compatibility between format but we need to create a common specification that can be used by all CIE for simplifying test each other.

I create [repository with my small research](https://github.com/abtris/cieci-research) and there is my analysis of how CIE works with configuration and if you missing one please create PR, contributions are welcome. We can compare what is important and what we can omit. 

Is this just my opinion or do you think that can help developers to adopt new and modern CIE? I think we can work with modern tools that can easily on click generate configuration from your language specification on creating project action without dependency on CIE that can and is changed in the project timeline.
