# WEB502 Lab One - Emily Friis

## Web Hosting Environments

### Node.js vs XAMMP:

Node.js is a highly flexibile JavaScript framework. It provides tools that simplify the development of web applications. Node.js' library also provides a built in HTTP server implementation used to create your own web server, but it is significantly distinct from XAMMP.

XAMMP integrates a dedicated web server solution through the Apache HTTP server. It effectively functions as a local server, which allows for local application testing before moving to a remote web server.

## Web Frameworks

Web frameworks refer to a collective set of development tools intended to streamline the creation of web applications. They improve the time efficiency of development by automating common web processes, providing a solid code base, and facilitating collaboration between development teams.

ex/

- Angular -> https://cli.angular.io/

- React -> https://reactjs.org/ -> https://github.com/react-boilerplate/react-boilerplate

### Comparison of Frameworks:

|   | React | Angular |
| --- | --- | --- |
| Applicability | Can be used for both web and mobile, single and multi page apps. | Can be used for both web and mobile, single and multi page apps. |
| Self Sufficiency | Additional libraries needed. | No additional libraries needed. 
| App Structure | Flexible component based structure. | Flexible component based structure. |
| Learning Curve | Simple, requiring little initial knowledge. | Steep, with a high level of depth and complexity. |
| Tools | Sublime Text, Visual Studio, Atom <br> Create React App (CLI) <br> Next.js framework <br> Enzyme, Jest, React-unit | Aptana, Sublime Text, Visual Studio <br> Angular CLI <br> Angular Universal <br> Jasmine, Protractor, Karma |

### Frameworks vs CMSs:

The main difference between frameworks and CSMs is their approach. With a framework, everything must be built from scratch. Alternatively, with a CMS, you have a software application already built and  begin with a number of pre-set features.

### Frameworks vs Libraries:

Not all frameworks use or depend on libraries. The main area of difference is that framework code is the caller and library code is the callee. Frameworks ultimately control the flow of your application, whereas libraries do not.

## Libraries

Originally, when applications had to be written whole, the increase of size and complexity would result in exponentially more bugs. So, a new way to split an application into smaller parts was created, this solution was the basis for what we know as libraries. The next big step was the 'KISS' rule (keep it simple stupid), and thus the idea that a library should do one thing and do it well.

### Issues

The main two issues with libraries are called 'bug propagation' and 'library limitations.'

#### Bug Propagation

The interaction between libraries and their depencies on other libraries are a significant source of bugs. The longer the chain of dependencies, the more likely the propagation of bugs becomes, as any error in the processing of data will continue to cause further issues down the chain.

#### Limitaions

When using libraries, the internal workings are often hidden from you. This is done so a library is kept in a known state. Therefore, because a library can only do a limited number of things, its easier to debug by covering all possible actions a library can do with unit tests. However, you may need to tweak the internals of a library. Often it is better to give up trying to get a library to do something it cannot, or to use a different library. Alternatively, a more advanced resolution would be to access the backed of the library (using a library's advanced mode), which is difficult and uncommonly done. Finally, hacking is a more risky and questionable method to access a library's internals that can often result in bugs if the function of the library is tampered with too heavily.