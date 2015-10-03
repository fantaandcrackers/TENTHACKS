Get started with Blog22
-----------------------------------
Welcome to Personality Insights Java Web Starter application!

This sample application demonstrates how to write a Java Web application (powered by WebSphere Liberty) that uses the IBM Watson Personality Insights service and deploy it on Bluemix.

1. [Install the cf command-line tool](https://www.ng.bluemix.net/docs/#starters/BuildingWeb.html#install_cf).
2. [Download the starter application package](https://console-classic-20151002-205310.ng.bluemix.net:443/rest/../rest/apps/5ba0343b-8666-439f-91e5-b9488aede6a1/starter-download).
3. Extract the package and `cd` to it.
4. Connect to Bluemix:

		cf api https://api.ng.bluemix.net

5. Log into Bluemix:

		cf login -u arthur.shir@gmail.com
		cf target -o arthur.shir@gmail.com -s dev

6. Compile the Java code and generate the war package using ant.

		ant

7. Deploy your app:

		cf push Blog22 -p output/webApp.war

8. Access your app: [http://Blog22.mybluemix.net](http://Blog22.mybluemix.net)
