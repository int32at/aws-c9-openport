# aws-c9-openport
A simple script that allows you to a custom port on your AWS cloud9 environment.

### Installation

1. Clone this repo into your cloud9/ec2 instance.
2. Execute it like the following:
```
sh aws-c9-openport dev 3000
```
- **dev** is the name of your cloud9 environment as defined in the management console.
- **3000** is the TCP port number you want to open.

After executing the script your service will be available at `http://ec2-server-ip:3000`.

You can get the ec2-server-ip by copying the IP from Share --> Application.

