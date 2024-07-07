# Use an official OpenJDK image with JDK from the Docker Hub
FROM openjdk:11-jdk-slim

# Set the working directory inside the container
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Compile the Java program
RUN javac Hello.java

# Run the application
CMD ["java", "Hello"]
