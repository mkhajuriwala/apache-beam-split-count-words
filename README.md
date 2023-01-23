# apache-beam-split-count-words
Example Project on how to configure pipeline options when running Direct Runner

java -jar target/split-count-words-bundled-1.1.jar --inputFile="gs://mhk-dataflow-bucket/inputfile.txt" --outputFile="gs://mhk-dataflow-bucket/outputfile.txt" --jobName="WordCountJob" --runner=DataflowRunner --gcpTempLocation="gs://mhk-dataflow-bucket/temp" --region=northamerica-northeast2
