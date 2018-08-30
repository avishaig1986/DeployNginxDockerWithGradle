  1. The following Gradle script pulls a nginx docker image, creates a container and starts it. 
     In case a running nginx container already exists, it stops and removes it first.

  2. The nginx site is mapped to port 8080, therefore it can be accessed from http://localhost:8080
  
  3. Html content is located at /var/www/index.html and can be dynamically edited.

  4. Command to execute: gradle initialize
  
  * Tested on centos-release-7-4.1708 with Gradle 4.10
    Ubuntu default Gradle version is 3.4, so if you use ubuntu, in order to upgrade gradle do:
	sudo add-apt-repository ppa:cwchien/gradle
	sudo apt-get update
	sudo apt upgrade gradle
	
  * Written by Avishai G as a home test for a DevOps position candidacy
