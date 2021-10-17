# Incubyte

#Prerequisites:
  1)AWS EC2-instance as a deployment server.
  2)Centos 7 with jenkins server.
  3)Dokcer on ec2 and Centos.
  4)Git repository.

#Steps:
  1)Install Docker,Java,Jenkins on Centos machine.
  2)Create one repository on git hub.
  3)Developer clone that repository on his own machine and push the code on that repo.
  4)Configure jenkins for 3 jobs(fetch-code,build-image,execute).
  5)Make one ec2-instance on aws as a deployment server.

#Configure pipeline using jenkins:

   Job1:fetch-code -->job2:build-image -->job3:execute
