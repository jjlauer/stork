server:
	mvn -e compile exec:java -Dexec.classpathScope="compile" -Dexec.mainClass="com.fizzed.stork.examples.helloserver.HelloServer" -Dexec.args="server conf/hello-server.yml"

assembly2:
	mvn clean assembly:assembly

assembly:
	stork-maven-assembly
