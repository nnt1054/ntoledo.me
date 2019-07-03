---
layout: post
title:  "CMS API Overview"
date:   2019-06-09
categories: projects
tags: cms_api
---

<h3 style='color:red'> page still in super rough development :) </h3>

#### Overview
Hello hey :)  
This project is still in the planning stage of the planning stage, so this page will be nowhere near its final draft.  I want to somehow capture the thought process and all my considerations somewhere, so this page will be full of rambling text about how I reach the design rather than an outline of the design itself first.

#### Background
I can at least start this off by explaining the original motivations behind this project/product.  Basically, half a year ago I was interesting in delving into freelance web development in the future.  To develop a portfolio and gain a bit of experience, I decided to take up making a portfolio site for a friend.  The portfolio was going to be based around illustrations and large images of their artwork.  Rather than setting up a github site, I wanted to abstract all the actual code and backend from the client.  Also, I wanted the client to be able to upload and rearrange their own portfolio images and content as they pleased without my having them intervene.  The idea would be having them log into an admin console with their own account, with permission restricted to their own content and be able to modify content through there.  After searching around for free self-hosted CMS's, the closes thing I've found was Strapi, an open source headless CMS.  However, the project doesn't support non admin users for accessing the admin console.  They do have plans to support this on their roadmap, but its set to be implemented late 2019.  So, I've decided to take this idea up as a project, and develop this myself.  In addition to these requirements, I'd like to make this a product especially for freelancers self host their own servers and client websites, and allow them to centralize their content for multiple clients.

There are several things I'd like to gain from this project.  First, I do have actual plans of utilizing this product in the future, for if I decide to delve more into freelance web development, as well as for mainting content or at least parts of my current jekyll site/blog.  Second, I'm taking this oppurtunity to learn more about API development (since this will be technically an API) and software infrastructure.  To elaborate on the software infrastruture, I'd like to figure out how to make the project modular enough to support different databases and database solutions.  Or at least modular and customizeable enough to streamline it to adapating to other backends.  Will this mean I should or shouldn't create ORM's and whatnot, I'm not entirely sure yet.  In addition, I want to make sure the API will support multiple frontends and query methods.  This basically means I need to attempt to support RESTful API's, GraphQL, SOAP and JSON responses.  I'm not entirely sure what exactly needs to be 'supported', but I might have to poke around with other common front end frameworks such as Vue.js and React to figure out what should be done.

For now I've settled on implmenting this project using Node.js and Express.js, since I feel like these are useful tools I'd like experience with in the future.  Also, I believe its easier to develop applications designed for the web in Javascript (as opposed to python), since Javascript is primarily used in most other web technologies.  Also, I'm preemptively assuming I'll be using either Vue.js or React to implmement the Admin interface.



<!--Hey haha I'm still in the planning stage for the planning stage.-->
<!--How do you even start a 'product'?  In general, most people will start off by just making an MVP (minimum viable product), but if I'm going for a BDUF (big design up front) kind of thing, I want to make a sprint entirely just for the planning stage?-->

<!--Basically determine resources, collections which are sets of resources, URL's which are paths to resources.  -->
<!--And then try and determine the HTTP methods.  Another question to consider would be whether or not to create POST and UPDATE endpoints, since technically you should only be updating the content through the ADMIN api.  If I choose to include the POST and UPDATE endpoints, would the admin interface somehow make use of this?  -->
<!--Along that topic, should I make the API itself first or the admin interface?  On a different note, don't forget to use HTTP response codes! Also support filtering through the API and not just through the admin.-->
<!--Also think about mimicking wordpress's guidelines and usability. -->

<!--#### Tasks To Do-->

<!--1. Write out description of project and specifications-->
<!--2. Draw out infrasctructure diagrams-->
<!--3. Make low spec to high spec wireframes-->
<!--4. figure out implementation and design architectures-->
<!--  * hello :)-->
<!--  * core questions: how do u support multiple databases?-->
<!--  * things to look into: -->