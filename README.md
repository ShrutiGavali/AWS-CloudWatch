Cloud Watch demo
# Practical Demo OF AWS Cloud Watch Services
# First created the EC2 instance with name (CloudWatch-demo)
![Screenshot (1182)](https://github.com/ShrutiGavali/AWS-CloudWatch/assets/122098190/b6c3bb27-493f-49b6-99e3-916cd7256fc6)
Ensured that 'Status check' is '2/2 checks passed'

connected the ec2 instance 
# Created Python file containing code which automatically optimize CPU usage of EC2 Instance
![image](https://github.com/ShrutiGavali/AWS-CloudWatch/assets/122098190/4cb4d300-f893-42d3-bab7-c225cc4f3df0)
saved the with name Clouddemo.py
# Before running the python file there is no any as such CPU usage as shown in below image
![image](https://github.com/ShrutiGavali/AWS-CloudWatch/assets/122098190/e26d38f7-5045-4556-a1b0-7833e686b56a)
# Run the python file 
give command as python3 Clouddemo.py 
It starts simulating 
![image](https://github.com/ShrutiGavali/AWS-CloudWatch/assets/122098190/21ea9a8e-9cf6-495c-918a-c0c7fabf21eb)
# As program run the CPU usage gets increase above 60%
![image](https://github.com/ShrutiGavali/AWS-CloudWatch/assets/122098190/fae44019-8c73-4d18-a311-16da9c466c0e)
# Now set alarm
set alarm as CPU usage goes above 50% it will automatically sent notification through mail 
![image](https://github.com/ShrutiGavali/AWS-CloudWatch/assets/122098190/3f4780d6-5441-4aeb-a0fb-48aea24250f7)








