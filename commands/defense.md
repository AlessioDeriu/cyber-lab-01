Defense Commands
Install Fail2Ban

sudo apt install fail2ban -y

Enable Service

sudo systemctl enable fail2ban
sudo systemctl start fail2ban

Check Status

sudo fail2ban-client status sshd

Purpose:
Automatically block IP after failed login attempts
