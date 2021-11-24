# iperf-testing

Step1 - Build iperf module
============================
1.Enter into iperf folder
2.Apply command "sh bootstrap.sh" 
2.Apply command "./configure; make; make install"

Step2 - Run iperf server
========================
1.Enter into testing folder
2.Apply command "./server {port}" Eg:- "./server 3000"

Step3 - Run iperf client
=======================
1.Enter into testing folder
2.Apply command "./client {ip} {port}" Eg:- "./client localhost 3000"
