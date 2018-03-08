# wordcount 

#running the program in the hadoop environment
#install hadoop
#start hadoop   $start-all.sh
#run $jps   it shows all daemons running behind
#make a directory in hdfs $hadoop fs -mkdir /wordcount
#move txt file from local disk to hdfs $ hadoop fs -put /(path of textfile)/sample.txt /wordcount
#running map reduce $hadoop jar /(path of jarfile)/wordcount-1.0-SNAPSHOT.jar wordcount /wordcount/sample.txt /wordcount/out

