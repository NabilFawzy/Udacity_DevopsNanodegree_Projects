Output web app URL :

http://udagr-WebAp-JMKA0U2QB4JH-306613735.us-west-2.elb.amazonaws.com



The machine should have 10 GB or more of disk and should be a t3.small or better

Although you defined the VolumeSize of the machine correctly,
 the t2.medium instance type is not suitable for this project. Why you defined t2.medium instance type rather than t3.small or better?
 
 Answer :
 For image which used it was ubuntu-bionic-18.04-amd64-server-20210224
 it has types 
 for t2.small (1 vCPUs , 1 Memory )
  for t2.medium (2 vCPUs , 4 Memory )  which needed into our project


