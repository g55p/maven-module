<h4>How to build:</h6>
<br>
<p>
1- Run mvn package in parent project <br>
2- Run mvn install in App1 <br>
3- Run mvn package in App2 <br>

Now you have a jar file in App2/target/App2-0.0.1-SNAPSHOT.jar that you can run by java -jar which includes App1 as dependency.
</p>
