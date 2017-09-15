# ojai-spark-connector-sample

Login as MapR User:

git clone https://github.com/jatin7/ojai-spark-connector-sample.git
cd ojai-spark-connector-sample
mvn clean package
./bin/spark-submit --class com.mapr.sparkOjaiApp.SparkOjaiApplication --master yarn-client --executor-memory 1024M ~/SparkOjaiApplication-1.0-SNAPSHOT.jar
