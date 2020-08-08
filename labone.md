# WEB502 - Lab One - Emily Friis

## Node.js vs XAMMP:

Node.js is a highly flexibile JavaScript framework. It provides tools that simplify the development of web applications. Node.js' library also provides a built in HTTP server implementation used to create your own web server, but it is significantly distinct from XAMMP.

XAMMP integrates a dedicated web server solution through the Apache HTTP server. It effectively functions as a local server, which allows for local application testing before moving to a remote web server.

## Installing Frameworks:

To install my frameworks I used the architecture provided by XAMMP to implement a locally hosted development environment. First, I configured the Apache web server and MySQL database management system, making sure they were assigned to open ports. Secondly, I created database for each framework and created a user with full access to each database. Next, I downloaded the files for each framework, and extracted their contents into the htdocs folder in xammp's directory. From there, I was able to configure each using the database name and user details I had set up earlier.

## Framework Comparison:

|  | WordPress | Joomla | Drupal |
| --- | --- | --- | --- |
| Difficulty of Learning | Easy | Moderate | Advanced |
| Performance | Fast until Higher Traffic | Slower | Faster |
| Free Plugins Available | >50000 | >7000 | >37000 |
| Security | Moderate | Moderate | Good |
| Search Engine Optimisation | Good | Basic | Good |
| Theme Availability | Good | Moderate | Poor |

(Guru99, (n.d.))

(Clarion Tech, (n.d.))

(Rai, 2020)

## Context of each CMS within the Industry:

WordPress provides an easy and quick to apply solution for any web startup, requiring no previous web development experience. It is well supported with a huge number of free plugins and themes available. Has a wide variety of applications, but requires more advanced hosting and database solutions to have better scalability.

Joomla introduced a more moderate solution, ideally used by someone with previous experience with PHP frameworks, but still accessable to beginners. Plugin availability is reasonably diminished. Best used for medium sized eCommerce or social network solutions.

Drupal is the more powerful of the CMSs I have listed, boasting excellent performance, security, and SEO, making it a more attractive solution for larger scale Ecommerce. It requires significantly more experience to work with, and does suffer somewhat from a lesser availability of themes.

## Local and Remote Environments:

Local environments refer to when the files for your web application are located on your local machine. Comparitively, with remote environments, an external hosting service is used to host the application's files. Typically, local environments are ideal for the development stage of an application, as updates can be made asynchronously without affecting anything, before being integrated later. Remote environments provide significant boosts to uptime and performance, being necessary for the deployment of an application to a workable state.

## CMS Setup:

For my CMS, I chose to use WordPress. After installing and configuring it, I was able to administer the site's content and settings. Using the admin page, you are able to add, edit, and remove all kinds of content (posts, media, pages, comments); as well as managing themes, plugins, users, tools, and settings. For my application's theme, I chose to use 'Hestia' as it provides a clean aesthetic and is compatible with my chosen Ecommerce plugin. To install it, I downloaded the requisite files from the developer's website and copied them to the themes folder in my WordPress site's folder. I then implemented placeholder pages for my site in addition to the pages created by my plugin. Finally, I implemented site navigation, using the menus section of the administrator panel - adding a primary menu with links to the site's main pages.

## References

Guru99. (n.d.). *CMS Comparison: Joomla vs WordPress vs Drumal in 2020*. https://www.guru99.com/joomla-vs-wordpress-vs-drupal.html

Clarion Tech. (n.d.). *WordPress vs Joomla vs Drupal: The Real Difference*. https://www.clariontech.com/blog/wordpress-vs.-joomla-vs.-drupal-the-real-difference

Rai S. (2020, May 20). *Drupal vs WordPress vs Joomla: Which is the best CMS Platform in 2020?*. Themegrill. https://themegrill.com/blog/drupal-vs-wordpress-vs-joomla/#:~:text=In%20conclusion%2C%20Drupal%20is%20the,and%20need%20a%20simple%20framework.