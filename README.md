# Simple Project 1
Reference from [Mkyong article](https://www.mkyong.com/maven/how-to-create-a-java-project-with-maven/). Thank you!

### Features
- Using java, maven and git
- Uses [maven-shade-plugin](https://maven.apache.org/plugins/maven-shade-plugin/) to provides the capability to package the artifact in an uber-jar, including its dependencies and to shade - i.e. rename - the packages of some of the dependencies.

### How to setup git project from local to GitHub:
                
1. Go to project directory
2. git init
2. git add .
3. git commit -m "Initial commit."
4. git remote add origin https://github.com/snickernetgithub/mvn-simple-proj.git
5. git pull --allow-unrelated-histories
6. git pull
6. git push

### How to execute the jar file:
> java -jar target/mvn-simple-proj-1.0-SNAPSHOT.jar 123456
