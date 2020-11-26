# HeavyHitter_2020
## 2020專題

**On google keep**

###### Create in diff terminal

* ###### How to build p4
   Optional(at begin) ==> `chmod +x p4_build.sh`
  
   `./p4_build.sh labs/01-simple_l3/solution/p4src/simple_l3.p4`

* ###### Start running (Switch)
   `sudo \$SDE_INSTALL/bin/veth_setup.sh`
   
   `./run_tofino_model.sh -p simple_13`   
   >*solution which is build*
   
   `./run_switchd.sh -p simple_l3`

* ###### Setup Entry
   `./run_bfshell.sh -b ~/bf-sde-9.2.0/labs/01-simple_l3/bfrt_python/setup.py -i`
  
* ###### Send 
   `sudo ~/bf-sde-9.2.0/labs/01-simple_l3/pkt/send.py 192.168.1.1`
    
   `--command ucli  (seeing the entry)`
   >at switch's terminal
