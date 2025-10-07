EC2 Basic setup

1. Create a security group if you do not already have one that has port 80 http and souce ipv4/anywhere.
2. Launch instance. Name appropriate to naming convention 
3. Leave the default AWS linux image.
4. Create a new key pair. Name it according to naming schema.
5. Select existing security group which would be the one previously created.
6. Scroll to the bottom and expand Advanced details. Cop the startup script from Theo's github and past it into the user data box.
7. Verify previous steps.
8. Launch the instance.
After you are done with the VM you need to tear it down.
9. Delete any extra services such as application load balancers.
10. Terminate the instance.

