# Comments

## ThreadTwoHashMapBroken.java
* I ran the broken hashmap 3 times before I got the following IllegalThreadStateException:

```
Constructing HashMap of Size 6
Starting Threads in HashMap
Constructing HashMap of Size 8
Starting Threads in HashMap
ThreadTwoHashMapB - START T4
ThreadTwoHashMapB - START T5
ThreadTwoHashMapB - START T6
ThreadTwoHashMapB - START T7
ThreadTwoHashMapB - START T0
ThreadTwoHashMapB - START T1
Thread HashMap, all have been started
ThreadTwoHashMapB - START T3
ThreadTwoHashMapB - START T2
Exception in thread "Run of 8" java.lang.IllegalThreadStateException
	at java.lang.Thread.start(Thread.java:708)
	at ThreadTwoHashMapBroken.runMapOfSize(ThreadTwoHashMapBroken.java:58)
	at ThreadTwoHashMapBroken.access$000(ThreadTwoHashMapBroken.java:4)
	at ThreadTwoHashMapBroken$2.run(ThreadTwoHashMapBroken.java:42)
ThreadTwoHashMapB - END T7
ThreadTwoHashMapB - END T6
ThreadTwoHashMapB - END T0
ThreadTwoHashMapB - END T4
ThreadTwoHashMapB - END T5
ThreadTwoHashMapB - END T1
ThreadTwoHashMapB - END T2
ThreadTwoHashMapB - END T3
```