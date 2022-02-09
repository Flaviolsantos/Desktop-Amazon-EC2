# Desktop-Amazon-EC2

## Amazon Linux Desktop

☁️ AWS

👉 1 Instance

🖥️ Terminal (Termius/Putty)

▶️ Instance

➡️ sudo amazon-linux-extras install epel

➡️ yum groupinstall "MATE Desktop"

➡️ sudo yum install xrdp chromium

➡️ systemctl enable --now xrdp

#### This will make all users to have the graphic interface
➡️ sudo bash -c 'echo PREFERRED=/usr/bin/mate-session > /etc/sysconfig/desktop'

#### Exit the root
#### This will make only a specific user to have the graphic interface
➡️ adduser user

➡️ passwd user

➡️ echo "/usr/bin/mate-session" > ~/.Xclients && chmod +x ~/.Xclients
