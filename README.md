 # CREATION IN WEB APPLICATION FOR TEST ENVIRONMENT
 NAME : Nirosha M

 REG NO:212223110032
  ## AIM
       To Creation in Web Application for Test Environment.
## PROBLEM STATEMENT
    Explain about the Experiment.

## ALGORITHM
 ### Steps 1: 
 Launch an EC2 instance in AWS using an Amazon Linux 2 AMI with a Security Group allowing HTTP and SSH traffic.
 ### Steps 2: 
 Connect to the instance using SSH and install a web server like Apache
 ### Steps 3:
 Create a simple HTML file in the server's default directory with basic content for testing.
 ### Steps 4:
 Access the instance's public IP in a browser to verify the HTML page is displayed.
 
 
## COMMANDS
### To install httpd:
```
yum install httpd -y
```
### To enable and start httpd :
```
systemctl enable httpd
systemctl start httpd
```
### Create a simple HTML page :
```
cd /var/www/html
sudo nano index.html
```

```html

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Test Environment</title>
</head>
<body>
    <h1>Welcome to AWS Test Environment</h1>
    <p>This is a simple HTML page hosted on AWS.</p>
    <p> gayathri m </p>
</body>
</html>

```

## OUTPUT
![cc 61](https://github.com/user-attachments/assets/bbe07210-c124-48f7-af39-b5960e5edba4)
![ccex62](https://github.com/user-attachments/assets/767cc113-c3ff-437e-abe9-64634beadc94)




## RESULT
 Thus the web application for test environment has successfully been created and executed.

  
