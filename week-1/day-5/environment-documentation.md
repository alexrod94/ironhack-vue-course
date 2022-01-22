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
- Collaboration tools & version control.

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

### Collaboration tools & version control
