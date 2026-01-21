# Login Patterns (Beginner Notes)

Login patterns describe how users normally and abnormally attempt to access a system.

## Normal login behavior
- One or two login attempts
- Successful login after a small number of tries
- Login from a familiar IP or location
- Activity during normal working hours

## Suspicious login behavior
- Multiple failed login attempts in a short time
- Repeated attempts from the same IP address
- Login attempts at unusual times
- Successful login after many failed attempts

## Why patterns matter in SOC
SOC analysts do not rely on a single log entry.
They look for patterns across multiple log events to identify threats.

## Simple detection idea
If there are many failed login attempts from the same IP
within a short period, it may indicate a brute-force attack.

## My understanding
Login patterns help convert raw logs into meaningful security alerts.
