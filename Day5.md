# Task 5

## Install Maven
```bash
sudo apt install maven
```
![image](https://github.com/user-attachments/assets/a1c7b760-d02d-403d-8213-48898f1ce463)

## Fork the repo on github

![Screenshot 2025-03-22 141833](https://github.com/user-attachments/assets/88425eb9-5440-41a3-a38a-61ebf9b04feb)


## Configure Jenkins
 - In Jenkins go to `configure jenkins` > `tools`
 - Locate JDK section
 - Uncheck `Install Automatically`
 - Name `Java 17`
 - Go to terminal and enter the command and get the java 17 path:

```bash
update-java-alternatives --list 
```

 - paste the java path in `JAVA_HOME`

![image](https://github.com/user-attachments/assets/e71ecf62-8ba8-4cf5-8cd5-1ef1e1cb694e)

## Fork The Repo and build the pipeline
![image](https://github.com/user-attachments/assets/f2e44ee3-189b-47cf-9a10-c1d205661051)
