Devops Assignment
-----------------

1. Script to provision an EC2 instance to deploy this app
    - Set the environment variable MYRA__SENTRY_DSN with a sentry dsn obtained by signing up to https://sentry.io
    - Deployment details
        - OS: Ubuntu 16.04; use ami-6edd3078
        - Server: Nginx
        - python 2.7
    - Restrict port access; allow only http and any other ports for deployment
    - Script should take in the number of servers and the size as input and deploy on that many server
    - ec2.sh num_servers server_size
    - ex: ec2.sh 1 t1.micro

2. Ansible/Chef/Puppet or bash scripts to deploy subsequent code changes and config changes to the newly created servers

After running the first script, it should output the IP address of the new instances and we should be able to open the browser to that instance and see output

In developing the assignment, use GitHub and try to keep a decent history of how you approached the project.
