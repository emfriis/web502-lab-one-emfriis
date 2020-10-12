# WEB502 - Lab Four - Emily Friis

## User Roles and Accounts

### User Types Provided by the Framework

Wordpress' default installation comes with five distinct user roles:

- Administrator ~ Full control over all site information (Users, Posts, Settings, Plugins, Themes e.t.c.)

- Editor ~ Control over site content (Add, Modify, Publish & Delete both Posts & Comments)

- Author ~ Control over own content (Add, Modify, Publish & Delete Own Posts)

- Contributor ~ Some control over own content (Add, Modify, & Delete Own Posts, but cannot Publish or Upload Files)

- Subscriber ~ Viewer (Can only Modify Own User Information and Comment)

In the administrator menu, under 'Users,' you can add, modify, and delete user accounts, managing which roles are applied to them.

![users](https://i.imgur.com/OgAA4Cs.png)

Using this panel, I created an example user account for each user role.

![usersetup](https://i.imgur.com/I3i8dtG.png)

![accounts](https://i.imgur.com/LNfC9fY.png)

### Managing User Roles

Wordpress' default user roles can be edited using a number of plugins, for this lab, I elected to use the plugin 'User Role Editor'. This plugin allows you to create new user roles and modify existing ones; additionally being able to edit each role's specific permissions and capabilities within the site.

![manageusers](https://i.imgur.com/lmGScUi.png)

## Deployment

### Deployment Types

Several options for deployment of sites exist:

- Shared Hosting ~ Most commonly used by small/medium traffic websites. Each instance on the server draws computing resources so each which proportionally slow down the whole server, making it less ideal for larger entities.

- VPS Hosting ~ With VPS you have full control over your service, as each isntance has its own partition of the server.

- Dedicated Hosting ~ With Dedicated Hosting you acquire full control over a server. This can be expensive and may require you to complete some amount of configuration. This option provides the most freedom, but is also expensive and inefficent if used incorrectly.

- Cloud Hosting ~ Cloud Hosting refers to where multiple servers are used to pool resources such as to provide a more reliable and scalable solution. It also promotes redundancy by storing files in multiple data-centers per the infrastructure of cloud hosting.

### Site Deployment

I deployed a WordPress site using Heroku. I linked a GitHub repository with my site's content and deployed it to Heroku.

![url](https://i.imgur.com/NZdFwbR.png)

![herokusite](https://i.imgur.com/Th5QseM.png)