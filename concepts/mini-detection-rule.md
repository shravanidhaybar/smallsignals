# Mini Detection Rule (Beginner Concept)

A detection rule is a condition used to identify
potentially suspicious activity from logs.

## Detection idea
If the same IP address generates multiple failed
login attempts within a short time period,
it may indicate a brute-force attack.

## Simple logic (conceptual)
- Count failed login attempts
- Group by source IP
- Check time window
- Trigger alert if threshold is crossed

## Why this matters in SOC
Detection rules help analysts reduce noise
and focus on meaningful security events.

## My understanding
Detection rules turn raw logs into actionable alerts.

## What I still need to learn
How real SOC teams tune thresholds to avoid false positives.
