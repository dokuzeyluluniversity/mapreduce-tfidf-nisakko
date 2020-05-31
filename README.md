# Nuri Civan Okudan - 2017510105

Compile as follows:

# hadoop com.sun.tools.javac.Main InformationRetrieval.java

# jar -cvf InformationRetrieval.jar InformationRetrieval*.class

# hadoop jar InformationRetrieval.jar InformationRetrieval /inputs /output1 /output2 /output3 /output4

where inputs = folder containing tweet text files

where output1 = output of the first task and input of the second task

where output2 = output of the second task and input of the third task

where output3 = output of the third task and input of the fourth task

where output4 = folder containing the last output (words and their tf idf values
