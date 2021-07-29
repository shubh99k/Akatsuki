FROM java:8
workdir /app
copy src ./src
run javac ./src/helloworld.java
run dir ./src
env CLASSPATH=./src
cmd ["java","helloworld"]

