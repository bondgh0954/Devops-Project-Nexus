# Artifact Repository Manager with Nexus

Demo Project:
  Run Nexus on Droplet and Publish Artifact to Nexus


Technologies used:
  Nexus
  DigitalOcean
  Linux
  Java
  Gradle
  Maven


Project Description:
  Install and configure Nexus from scratch on a cloud server
  Create new user on nexus with relevant permissions


  

  Java Gradle Project: Build jar and upload to nexus
  Java Maven Project:   Build jar and upload to Nexus


  # Configuring digitalOcean server
     create a droplet
     create a firewall configuration


    ssh into server
    ssh root@PublicIP
    Install required version of java for nexus
    download nexus from official website.
    wget url
    unzip the tar file(tar -zxvf filename)

   Create newuser on digital ocean server eg. nexus
   chown user and group owner of the unzip rep to the new
   created user

   Edit the nexus.rc file

   switch to the newuser and start nexus
   eg. nexus-3.68.1-02/bin/nexus start

   copy the publicIp and port in your browser

   create a new user in nexus
   add role to the user and give appropriate permissions


   # Open the application code in a code editor
    configure
           publishing
           repository


  
