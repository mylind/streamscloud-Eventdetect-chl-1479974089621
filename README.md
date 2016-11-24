#Streaming Analytics Event Detection Starter Application
Welcome to the Streaming Analytics service powered by IBM Streams! This starter application demonstrates how to configure and control the Streaming Analytics service through its REST API. The application is written in Node.js using the SDK for Node.js runtime in Bluemix.

Licensed under the Apache License (see [License.txt](https://hub.jazz.net/project/streamscloud/EventDetection/overview#https://hub.jazz.net/git/streamscloud%252FEventDetection/contents/master/License.txt)).

## Getting Bluemix ready for the starter application

To get Bluemix ready for the Event Detection starter application, you need to:
1. Sign up for [Bluemix](https://ace.ng.bluemix.net/) and log in.

- [Install the cf command-line tool](https://www.ng.bluemix.net/docs/starters/install_cli.html).

- Create an application in the Bluemix web portal using the **SDK for Node.js** runtime. Remember the name you give your application, you will need it later on. 

- Add the Streaming Analytics service to your application from the Bluemix web portal.


## Pushing the Event Detection starter application to Bluemix

After you meet these prerequisites, you are ready to download and push the starter application to Bluemix:

1. Click the **download** button "Download the contents of this branch as a zip file" in this browser tab.


- After the download completes, extract the .zip file.

- Rename the root directory of the extracted zip to match the name you gave your application in Bluemix.
		
- On the command line, `cd` to the renamed directory. For example:
		cd myapp
		
- Connect to Bluemix:

		cf api https://api.ng.bluemix.net

- Log into Bluemix and set your target org when prompted:

		cf login

- Deploy your app. For example:

		cf push myapp

- Access your Node.js application by clicking on the route displayed near the top of your application's overview page in Bluemix.


##Required components

The following components are required by the EventDetection starter application.  These components are documented in the package.json file.
- https
- express
- jade
- async
- fs
- form-data
- errorhandler
- body-parser
- Node.js

