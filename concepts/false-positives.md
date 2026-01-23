# False Positives (Beginner Notes)

A false positive is an alert that is triggered
even though no real security threat exists.

## Why false positives happen
- Detection rules are too strict
- Normal user behavior looks suspicious
- Lack of context in logs

## Example
A user enters the wrong password multiple times
and triggers a brute-force alert, but no attack occurred.

## Why false positives are a problem
- Waste analyst time
- Increase alert fatigue
- Real threats may be missed

## How SOC analysts reduce false positives
- Adjust detection thresholds
- Add context to alerts
- Review alert patterns over time

## My understanding
Good detection is not about more alerts,
but about better-quality alerts.
