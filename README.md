# PingChecker
#!/usr/bin/env python3

'''
Created a simple ping checker
'''
 
import os

# accepting the input of the ip address
ip_address = input("Input ip address to ping: ")
# Creating the result of the system command
result = os.system("ping -c 4 " + ip_address)
# Prints the result of the ping command
print(result)
