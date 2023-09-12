# AUTOMATING-LOAD-BALANCE-CONFIGURATION-WITH-SHELL-SCRIPTING_PROJECT-8

This project give me a great introduction to automation.
Below are the steps i followed in implementing this project;
1. Provisioned 2 webservers on my Ec2 instance
2. Opened port 8000 on the 2 webservers to allow traffic from anywhere
3. Created a file install.sh
4. Opened the file and pasted the codified shell script for automation
5. Change permission on the file to make it executable
6. Ran the shell script using ./install.sh IP_ADDRESS
7. Ran the IP_ADDRESS over the internet on my browser
8. Provisioned a loadbalancer server on my Ec2 instance
9. Opened port 80 on the 2 webservers to allow traffic from anywhere
10. Created a file nginx.sh
11. Opened the file and pasted the codified shell script for automation
12. Change permission on the file to make it executable
13. Ran the shell script using ./nginx.sh IP_ADDRESS
14. Ran the IP_ADDRESS over the internet on my browser

    Below are screenshots of the process
    
![server 2a](https://github.com/General-Philip/AUTOMATING-LOAD-BALANCE-CONFIGURATION-WITH-SHELL-SCRIPITING_PROJECT-8/assets/141147192/043814fb-f2c0-467c-9c3c-0c8c7f032980)
![scripting](https://github.com/General-Philip/AUTOMATING-LOAD-BALANCE-CONFIGURATION-WITH-SHELL-SCRIPITING_PROJECT-8/assets/141147192/c5b10a7d-eb4d-4529-a43e-849d61c5bcba)
![Loadbalance successful syntax](https://github.com/General-Philip/AUTOMATING-LOAD-BALANCE-CONFIGURATION-WITH-SHELL-SCRIPITING_PROJECT-8/assets/141147192/acdd7ce5-bbc3-4ed3-9d9d-b79f7dfa0a6d)
![webserver 2 browser outcome](https://github.com/General-Philip/AUTOMATING-LOAD-BALANCE-CONFIGURATION-WITH-SHELL-SCRIPITING_PROJECT-8/assets/141147192/a7092d58-9b1e-4a0d-8001-68288ad98165)
![webserver 1 browser outcome](https://github.com/General-Philip/AUTOMATING-LOAD-BALANCE-CONFIGURATION-WITH-SHELL-SCRIPITING_PROJECT-8/assets/141147192/61bafe5c-ca00-47c5-87b7-945454b3972d)
![server 2b](https://github.com/General-Philip/AUTOMATING-LOAD-BALANCE-CONFIGURATION-WITH-SHELL-SCRIPITING_PROJECT-8/assets/141147192/3ef3104c-00e5-4429-95d9-b041c227de9f)
![webserver 1](https://github.com/General-Philip/AUTOMATING-LOAD-BALANCE-CONFIGURATION-WITH-SHELL-SCRIPITING_PROJECT-8/assets/141147192/349cd9f8-db71-4f47-9e76-864103c9582d)
