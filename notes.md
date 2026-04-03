# Cyber Lab 01 – Analysis Notes

## Observations

- Target machine identified in internal network
- SSH service exposed on port 22
- Multiple failed login attempts detected in logs
- Successful authentication achieved after repeated attempts

## Attack Behavior

- Repeated SSH login attempts from attacker machine
- Pattern consistent with brute force attack
- Logs show clear sequence:
  - authentication failures
  - failed passwords
  - successful login
  - session opened and closed

## Security Weakness

- Weak password allowed unauthorized access
- No protection mechanism initially in place

## Defense Outcome

- Fail2Ban successfully detected attack pattern
- Attacker IP automatically banned
- System protected after configuration
