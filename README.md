A readme file to test if Jenkins is working properly

# What is Jenkins
- Jenkins is a CI CD tool
- Free & Open Source
- Written in Java

## Getting Started
- Get jenkins.war and find the location of the file
- Run the following command: 
```bash
java -jar jenkins.war --httpPort=9191
```
- Open the internet browser and go to http://localhost:9191

## CLI Usage
- For CLI Docs: http://localhost:9191/cli/
- jenkins-cli.jar is found on this page
- For terminal instructions: 
```bash
java -jar jenkins-cli.jar -s http://localhost:9191/ -webSocket help
```
- open terminal and run following
- Change 'TestJob' to name of app. The final '-s' shows the build log
```bash
java -jar jenkins-cli.jar -s http://localhost:9191/ build TestJob -s
```

- For error logging in: 
```bash
java -jar jenkins-cli.jar -s http://localhost:8080 /help --username ＜userName＞ --password ＜password＞
```

​
