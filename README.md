# Computer AD Group Replication
Simple script that replicates AD groups from one computer and replicates them onto another

At my current contract position at Virginia Mason we are tasked with configuring and deploying hundreds of new computers, primarily because the old computers have hardware that is too old to upgrade to Windows 11. When setting up a new computer we are required to replicate software and AD configuration, the main AD configuration being the replication of group policies. I found it to be quite tedious to enter the DC continuosly just to add the groups onto the new computer so I created this simply script that prompts for the old computer name, new computer name, and then replicates the groups from the old computer onto the new one. 
