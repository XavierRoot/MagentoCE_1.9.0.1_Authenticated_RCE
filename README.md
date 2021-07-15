# MagentoCE_1.9.0.1_Authenticated_RCE
Magento CE &lt; 1.9.0.1 - (Authenticated) Remote Code Execution


# Usage: 

1. Configure config section in exploit.py source code. 
2. Set up a proxy configuration in config section if you're into that.
3. Run script `python3 exploit.py http://localhost/admin`
4. You'll get back a crappy webshell. Use this to get a real reverse shell. You may have to URL encode your commands.

Note: If you enter a command and you get back HTML your cookie timed out. Just run exploit.py again.

![image](https://user-images.githubusercontent.com/59654121/125708321-fc62a535-08d7-4328-ab90-9832953aaf44.png)



# Original exploit
https://www.exploit-db.com/exploits/37811
