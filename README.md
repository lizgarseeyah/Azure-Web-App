## Project Overview

This Azure architecure uses AppService to deploy my static website from a Dropbox. Future implementations will utilize Azure Git to deploy my project as I am making changes.

![diagram](/img/diagram.png)

### Resources Used:

- Azure AppService
- HTML/CSS
- DropBox


### File Descriptions:

- [index.html](https://github.com/lizgarseeyah/Azure-Web-App/blob/master/index.html) - webpage
- [style.css](https://github.com/lizgarseeyah/Azure-Web-App/blob/master/styles.css) - style sheet

### Pre-Lab Configuration:

- Dropbox with website files.

## Procedure:

- In Azure AppService, click "Add".
- Fill out the required information (name, resource group, etc.)
  - Provide the web app a name.
  - Publish: Code
  - Runtime stack: PHP 7.3 (or Node works)
- Select "Review and Create"
- Verify it's running:

![one](/img/one.png) 

Navigate to the created webapp. Under "URL" is where you can view your website.

![two](/img/two.png) 

On the left hand pane, select "Deployment Center":

![three](/img/three.png) 

Configure the deployment to work with Dropbox:

![four](/img/four.png) 

Using the URL in the webapp, open it in a new browser to verify the deployment was successful.
![website](/img/website.png) 
