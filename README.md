# ns3Examples  
# first.cc information: 
Design two wired nodes that can connect to each other through a point-to-point network that handles a data rate of 50mbps and a delay of 5ms. The first node acts as a server and the second node acts as a client and they exchange at least 10 packets in a total simulation time of 20 seconds. The maximum packet size is 1024 bytes and 512 bytes. Plot the throughput of each node for the above packet sizes. (Use any charting solution you are comfortable with).

I am going to take the example of first.cc file. ns-3.38/examples/tutorial/

Copy the above file to ns-3.38/scratch/ 

To run this file, let's open a terminal

$ cd ns-allinone-3.38/ns-3.38

$ ./ns3 run scratch/first.cc 

Change the 1024 to 512 as packet size and change the 512.tr in the trace file and compile it again 

$ ./ns3 run scratch/first.cc 

Open another terminal and go to 
$ cd ns-allinone-3.38/netanim-3.109/
$ ./NetAnim 

Open the XML file and check the output in the animator window.


]Now find the throughput with the help of a software called tracemetrics which is already installed. Check the video in ym channel for installing tracemetrics

Open another terminal or use the existing terminal

$ cd 
$ cd tracemetrics-1.4.0
$ java -jar tracemetrics.jar

For rip-simple-network.cc 
follow the video for more details. 
https://youtu.be/bCXI1GoCIj4
