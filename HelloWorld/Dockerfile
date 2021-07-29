from java:8
workdir /app
copy src ./src
run dir ./src
run javac ./src/HelloWorld.java
ENV CLASSPATH=./src
cmd ["java","HelloWorld"]

