# Library Management System 

```
time fm create anmol.com
```

```
fm start anmol.com
```

```
su
```

Password: 

You will enter in root. $ will change to #

```nano /etc/hosts```

Add the following at the end:

```
127.0.0.1    localhost
127.0.0.1    anmol.com 
```

```exit```

```cd frappe```

anmol@debian:~/frappe$ fm shell anmol.com

╭─frappe@anmol.com ~/frappe-bench  
╰─➤  bench new-app lib_man_sys

╭─frappe@anmol.com ~/frappe-bench  
╰─➤  bench install-app lib_man_sys


Now open browser, 
Go to anmol.com

Enter username and password:   username = administrator , password = admin

Go to the top right, click on profile icon, then click switch to desk. 







