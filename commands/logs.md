Log Analysis Commands
View SSH Logs

sudo journalctl -u ssh

Filter Attempts

sudo journalctl -u ssh | tail -20

Purpose:
Analyze authentication attempts and detect attacks
