# Use an official OpenJDK runtime as a parent image
FROM openjdk:11

WORKDIR /usr/src/app

COPY . .

RUN javac edu/miu/cs/cs425/App.java

CMD ["java", "-cp", ".", "edu.miu.cs.cs425.App"]
