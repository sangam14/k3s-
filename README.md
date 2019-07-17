# k3s

```

ubuntu@ip-172-31-24-2:~$ sudo  apt-get update
Hit:1 http://us-east-2.ec2.archive.ubuntu.com/ubuntu bionic InRelease
Get:2 http://us-east-2.ec2.archive.ubuntu.com/ubuntu bionic-updates InRelease [88.7 kB]
Get:3 http://us-east-2.ec2.archive.ubuntu.com/ubuntu bionic-backports InRelease [74.6 kB]
Get:4 http://us-east-2.ec2.archive.ubuntu.com/ubuntu bionic/universe amd64 Packages [8570 kB]
Get:5 http://security.ubuntu.com/ubuntu bionic-security InRelease [88.7 kB]        
Get:6 http://us-east-2.ec2.archive.ubuntu.com/ubuntu bionic/universe Translation-en [4941 kB]               
Get:7 http://us-east-2.ec2.archive.ubuntu.com/ubuntu bionic/multiverse amd64 Packages [151 kB]                              
Get:8 http://us-east-2.ec2.archive.ubuntu.com/ubuntu bionic/multiverse Translation-en [108 kB]
Get:9 http://us-east-2.ec2.archive.ubuntu.com/ubuntu bionic-updates/main amd64 Packages [682 kB]
Get:10 http://us-east-2.ec2.archive.ubuntu.com/ubuntu bionic-updates/main Translation-en [251 kB]
Get:11 http://us-east-2.ec2.archive.ubuntu.com/ubuntu bionic-updates/universe amd64 Packages [972 kB]
Get:12 http://us-east-2.ec2.archive.ubuntu.com/ubuntu bionic-updates/universe Translation-en [294 kB]
Get:13 http://us-east-2.ec2.archive.ubuntu.com/ubuntu bionic-updates/multiverse amd64 Packages [6640 B]
Get:14 http://us-east-2.ec2.archive.ubuntu.com/ubuntu bionic-updates/multiverse Translation-en [3556 B]
Get:15 http://us-east-2.ec2.archive.ubuntu.com/ubuntu bionic-backports/main amd64 Packages [2512 B]
Get:16 http://us-east-2.ec2.archive.ubuntu.com/ubuntu bionic-backports/main Translation-en [1644 B]
Get:17 http://us-east-2.ec2.archive.ubuntu.com/ubuntu bionic-backports/universe amd64 Packages [3736 B]
Get:18 http://us-east-2.ec2.archive.ubuntu.com/ubuntu bionic-backports/universe Translation-en [1696 B]
Get:19 http://security.ubuntu.com/ubuntu bionic-security/main amd64 Packages [451 kB]
Get:20 http://security.ubuntu.com/ubuntu bionic-security/main Translation-en [156 kB]
Get:21 http://security.ubuntu.com/ubuntu bionic-security/universe amd64 Packages [572 kB]
Get:22 http://security.ubuntu.com/ubuntu bionic-security/universe Translation-en [186 kB]
Get:23 http://security.ubuntu.com/ubuntu bionic-security/multiverse amd64 Packages [4008 B]
Get:24 http://security.ubuntu.com/ubuntu bionic-security/multiverse Translation-en [2060 B]
Fetched 17.6 MB in 4s (4680 kB/s)                         
Reading package lists... Done
ubuntu@ip-172-31-24-2:~$ 
ubuntu@ip-172-31-24-2:~$       curl -sfL https://get.k3s.io | sh -
[INFO]  Finding latest release
[INFO]  Using v0.6.1 as release
[INFO]  Downloading hash https://github.com/rancher/k3s/releases/download/v0.6.1/sha256sum-amd64.txt
[INFO]  Downloading binary https://github.com/rancher/k3s/releases/download/v0.6.1/k3s
[INFO]  Verifying binary download
[INFO]  Installing k3s to /usr/local/bin/k3s
[INFO]  Creating /usr/local/bin/kubectl symlink to k3s
[INFO]  Creating /usr/local/bin/crictl symlink to k3s
[INFO]  Creating killall script /usr/local/bin/k3s-killall.sh
[INFO]  Creating uninstall script /usr/local/bin/k3s-uninstall.sh
[INFO]  env: Creating environment file /etc/systemd/system/k3s.service.env
[INFO]  systemd: Creating service file /etc/systemd/system/k3s.service
[INFO]  systemd: Enabling k3s unit
Created symlink /etc/systemd/system/multi-user.target.wants/k3s.service → /etc/systemd/system/k3s.service.
[INFO]  systemd: Starting k3s
ubuntu@ip-172-31-24-2:~$ 
```
