Process execution detection
An application to detect the execution malware by monitoring the processes which are regularly used by malware and threat actors.
This app uses the process data model to provide a standard method to name and classify process events.

How to use the list
The list contains techniques and tactics used by various forms of malicious activity. 
When the lookup search is activated, any activity matches found will go to a correlated search index.
There is a secondary search which looks for a known list of activities from groups or malware.
You can also use the index for your own analysis for activities that are found from the list.

New searches are easily added to allow more detections as you find more techniques and signatures.

Adding a new signature
1. Analyse which process executions are positives and which of these could be negatives. 
Any positive adds will have a score greater than 0, to exclude a match assign a value of 0.
When assigning a number this can refer to the risk score of the activity as many activities, while used by threat actors, are commonly used to perform normal functions.
You will need to append or add new details such as the id and the severity.
