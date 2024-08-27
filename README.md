<h6>How to build:</h6>
<p>
1- Run mvn package in parent project \n
2- Run mvn install in App1 \n
3- Run mvn package in App2 \n

Now you have a jar file in App2/target/App2-0.0.1-SNAPSHOT.jar that you can run by java -jar which includes App1 as dependency.
</p>
