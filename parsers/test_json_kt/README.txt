javac -cp "json.kt-0.1.0.jar" TestJSONParsing.java

jar cvfm TestJSONParsing.jar META-INF/MANIFEST.MF json.kt-0.1.0.jar TestJSONParsing.class

java -jar TestJSONParsing.jar