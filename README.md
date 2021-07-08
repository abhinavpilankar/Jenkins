# Jenkins



wget -q -O - https://pkg.jenkins.io/debian-stable/jenkins.io.key | sudo apt-key add -

sudo sh -c 'echo deb http://pkg.jenkins.io/debian-stable binary/ > /etc/apt/sources.list.d/jenkins.list'

sudo apt update

sudo apt install jenkins

sudo systemctl start jenkins

sudo systemctl status jenkins

Step 3 — Opening the Firewall

sudo ufw allow 8080

sudo ufw status

sudo cat /var/lib/jenkins/secrets/initialAdminPassword

