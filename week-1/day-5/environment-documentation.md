## Learning Goals

In this lesson we're going to learn about the following topics:

- What tools you'll need in order to create a front end application.
- How to use some of the most essential tools for a front end developer.
- What is documentation and how you can use it to improve your workflow.

## Introduction to environment

A development environment is a collection of procedures and tools for developing, testing and debugging an application or program.

The development environment normally has three server tiers, called development, staging and production. All three tiers together are usually referred to as the DSP.

- Development Server: Here is where the developer tests code and checks whether the application runs successfully with that code. Once the application has been tested and the developer feels that the code is working fine, the application then moves to the staging server.
- Staging Server: This environment is made to look exactly like the production server environment. The application is tested on the staging server to check for reliability and to make sure it does not fail on the actual production server. This type of testing on the staging server is the final step before the application could be deployed on a production server. The application needs to be approved in order to deploy it on the production server.
- Production Server: Once the approval is done, the application then becomes a part of this server.

In this lesson, we will refer to the environment as the set of tools you're going to use when creating a front end application. Specifically, we're going to talk about the following:

- Your code editor or IDE.
- Package managers.
- Collaboration tools.
- Version control.

Besides that, we're also going to take a brief look at documentation and why you need to use it for most of your web development projects.

### Your code editor or IDE

An IDE, or Integrated Development Environment, is a tool that enables programmers to consolidate the different aspects of writing a web application or any other kind of program.

IDEs increase programmer productivity by combining common activities of writing software into a single application: editing source code, building executables, and debugging.

In most cases, the terms `code editor` and `IDE` are interchangeable. There are some instances where this is not the case, but as web developers we can use both terms indistinctly.

Up to this point you've been using Visual Studio Code as your code editor/IDE. However, there are many functionalities of VS Code that you haven't used yet that will help you write better apps in a more efficient way:

- Specific extensions for advanced functionalities.
- Integrations with other tools.

We'll see how to use VS Code more effectively as we go along. For now, you can take a look at some ideas [in this article](https://javascript.plainenglish.io/a-guide-to-the-20-best-vscode-extensions-for-frontend-developers-f75a5d716091).

### Package managers

When you're working on a complex project, most of the time you won't need to build every functionality from scratch. Instead, you can access other people's code by using something called a `package manager`.

These tools allow you to install "dependencies"; that is, third - party bits of software that somebody else wrote and that can solve different problems for your application. Most web projects include varying numbers of dependencies, which in turn might even include some sub dependencies of their own!

Dependencies can range from very small utilities like a tool that allows you to create better browser alerts, to full blown frameworks/libraries like `React` or `Vue`.

In order to properly use libraries, you will need what's called a `package manager`. This tool allows you to download libraries directly from online repositories and include them in your projects seamlessly.

We're going to use a package manager called `npm`. You can access a guide on how to install it for Windows [here](https://phoenixnap.com/kb/install-node-js-npm-on-windows).

### Collaboration tools

When faced with a major development project, many developers might think the best approach is to divide and conquer. After all, doesn't it make more sense to have everyone work on different parts of the project at the same time and put it all together in the end?

Not always. While having different team members working on separate parts of a coding project might make sense sometimes, it will also mean that there's poorer communication, a harder debugging process and an excessive reliance on every single programmer. When you're dealing with larger projects or working with bigger teams, you'll need to work alongside other coders in order to get the best results and use a collaborative approach.

In a nutshell, collaborative coding is an approach to software development where pairs or teams of programmers work together on a project by coding each other's ideas or editing each other's code.

There are different types of collaborative coding setups; we'll review some of the most popular ones here.

#### Pair programming

Pair programming involves two developers working at a single workstation. One developer serves as the driver, and the other as the navigator.

The driver uses the workstation and writes code while the navigator reviews the code in real-time. Every so often, the two developers will switch roles, so each has a chance to guide the project's direction and translate solutions into real code.

In general, the navigator's job is to define the strategic direction of the code and propose what it should do. The driver, on the other hand, is in charge of the "tactical" aspects and focuses on writing code and making sure it does what it's supposed to do and follows company guidelines for variable naming, commenting, and so on.

A pair programming project can consist of two developers with similar skills and experience, or it might bring together a senior developer who mentors a junior developer during the project.

#### Mob programming

The idea behind mob programming is similar to pair programming, except it involves more than two people. At any given time, one driver developer is at the workstation while the other navigator programmers guide the driver to write the code.

While mob programming sounds a bit chaotic, the truth is that it's an excellent way to bring a development team together to create a better software product. That is, if the mob programming team follows a few rules.

First, they need to follow the driver-navigator principle. For a developer's idea to make it to the computer, it must go through the hands of another developer. That means that navigators need to communicate their ideas clearly enough for the driver to be able to turn them into code.

At the same time, drivers are encouraged to ask clarifying questions, including the logic behind a particular idea. But, at no point should the driver start writing code that doesn't follow the direction of the navigators.

Second, mob programming works better when everyone has the chance to navigate. That's why successful mob programming projects rotate through drivers, often using a strict timer system.

Finally, all communications between team members must be respectful and considerate. Sure, there will be disagreements. In fact, a big advantage of mob programming is that team disagreements can be settled openly and honestly.

Still, everyone on the mob programming team must remember that everyone has something valid to contribute, and it's vital to stay on the same side.

#### Code sharing

Unlike pair programming and mob programming, code sharing involves the traditional setup of each developer working on their own machines to write their own code. But, with a code-sharing setup, members of the development team have the opportunity to review, revise, debug, and add to each other's code.

As you can imagine, code sharing can only work when there's a solid version control system in place to avoid duplicate work and ensure that everyone is working from the latest code scripts. There are a few specialized platforms designed for code-sharing developers to work either in real-time or asynchronously.

[In this article](https://console.dev/code-collaboration-pair-programming/) you can see some of the best collaboration tools available.

### Version control tools

A very closely related topic to collaboration environments is version control. Version control, also known as source control, is the practice of tracking and managing changes to software code. Version control systems are software tools that help software teams manage changes to source code over time.

Version control software keeps track of every modification to the code in a special kind of database. If a mistake is made, developers can turn back the clock and compare earlier versions of the code to help fix the mistake while minimizing disruption to all team members.

At the same time, version control tools allow team members to review each other's code and integrate their changes and additions together in a more efficient way.

In future lessons we'll talk in detail about some of the most popular version control tools, like `git`.

## Documentation

Technical documentation in software engineering is the umbrella term that encompasses all written documents and materials dealing with software product development.

All software development products, whether created by a small team or a large corporation, require some related documentation. And different types of documents are created through the whole software development lifecycle (SDLC).

Documentation exists to explain product functionality, unify project-related information, and allow for discussing all significant questions arising between stakeholders and developers.

Documenting a project can involve many different things, from creating a `README.md` file to adding comments to important parts of your code. Here we'll see a few basics on why and how to create good documentation.

### Why write documentation?

There are several reasons you will want to include documentation in any web development project you have to tackle:

- For yourself. Oftentimes, when you stop working on a project for a while and try to get back into it down the line, you'll have forgotten why you did different things or your reasoning behind parts of your code. Documentation will help you alleviate this problem.
- For others. If you work on a team, it's imperative that you help your colleagues understand what you're doing and why.

### Tips on creating good documentation

1. Include A README file that contains a brief description of the project, installation instructions and a short example/tutorial.
2. Allow issue tracker for others.
3. Document your code with comments.
4. Apply coding conventions, such as file organization, comments, naming conventions, programming practices, etc.
5. Include information for contributors.
6. List all the version of the files along with the major edits you did in each version.

You can learn more about how to write good documentation [here](https://www.freecodecamp.org/news/how-to-write-good-documentation/).

## Lesson Overview

In this lesson we've talked about a lot of different aspects involved in the web development process. We've seen:

- What a coding environment is and a few tricks on how to use it.
- What a package manager is.
- How to use NPM as our package manager.
- Why collaboration tools are important and the different options there are.
- Why and how to include documentation in a web development project.
