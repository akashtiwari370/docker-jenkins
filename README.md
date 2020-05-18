Ways to create a jenkins environment in docker
step 1:docker build -t jenkins-os:v1 .
step 2:docker run -dit --name jenkins -v jenkinsdata:/root/.jenkins/-P jenkins-os:v1
step 3:Now you can run jenkins on your base os by typing ip address_of_your_machine:port_number
you can find port number from dockerps command.
