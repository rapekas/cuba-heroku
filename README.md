# cuba-platform-heroku
Cuba Platform project deployment on Heroku

There is a Cuba Platform deployed for Heroku (using WAR).

1. Pull/download files
2. Deploy a project using command 'gradle buildWar'
3. Launch using command:
heroku jar:deploy webapp-runner-8.5.11.3.jar --includes ./libs/postgresql-9.4.1212.jar:./libs/tomcat-dbcp-8.5.11.jar:./modules/core/web/META-INF/war-context.xml:./build/distributions/war/app.war
4. Read the documentation: https://doc.cuba-platform.com/manual-6.4/heroku_deployment.html

You can deploy your CUBA application using GitHub repo as source for your Heroku Cloud. You may find details in the documentation mentioned.
...
