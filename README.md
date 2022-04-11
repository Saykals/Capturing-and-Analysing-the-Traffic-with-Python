README

During the network saturation, the monitoring and analysing traffic flow is important. Traffic limitation which is one of the effective solution to avoid link saturation in some cases, may be required especially for top talkers after traffic analysis.  At this point, I would like to share my new Python script which captures local traffic and determines top talkers in case of link saturation. And also it creates a policy-map ( using pre-configured the ACL on Router) for limiting the top talker’s traffic which is captured and analysed during saturation.

Important Note:  

- This sample is  just for HTTP, HTTPS and DNS traffic analysis.
- The script is tested on Windows PC. 
- Please be sure disabling Windowds Firewall and Antivirus settings.



Video-link:
https://www.youtube.com/watch?v=b0NcVqQmwLE



Thank you.
