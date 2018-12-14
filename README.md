NAME: ARPITA CHAKRABORTY
BNUMBER: B00709870



1.  Python Script that generates the Binary  Tree Topology
--------------------------------------------------------------
binary_tree.py

Command:
mn --custom binary_tree.py --controller remote --topo mytopo


2. Controller Code
--------------------------------------------------------- 
I have created three separate controller code with different names for the ease of execution
instead of changing of_tutorial.py everytime.

task2.py - Controller Code (TASK II)  correspond to of_tutorial.py format
task3.py - Controller Code (TASK III) correspond to of_tutorial.py format 
task4.py - Controller Code (TASK IV)  correspond to of_tutorial.py format

Command:
TASK2 Controller : 
  ./pox.py log.level --DEBUG misc.task2	 
TASK3 Controller :	 
 ./pox.py log.level --DEBUG misc.task3
TASK4 Controller :	 
 ./pox.py log.level --DEBUG misc.task4




3. Detailed Step How to Execute:
---------------------------------------------------

a> Start the container:
sudo docker run -it --rm --privileged -e DISPLAY  -v /tmp/.X11-unix:/tmp/.X11-unix  -v /lib/modules:/lib/modules iwaseyusuke/mininet

b> Place binary_tree.py file at the default path of the container (which is /root/)

c> Add Pox Code from the git repository

d> Run the pox controller code from this path(/root/pox):

For TASK2 Controller run : 
  ./pox.py log.level --DEBUG misc.task2	 

For TASK3 Controller run :	 
  ./pox.py log.level --DEBUG misc.task3

For TASK4 Controller run :	 
  ./pox.py log.level --DEBUG misc.task4

e> Once Controller gets started, run following command to generate the binary tree topology:
    mn --custom binary_tree.py --controller remote --topo mytopo





