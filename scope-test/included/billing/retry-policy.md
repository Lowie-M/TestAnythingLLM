# Billing Retry Policy

Retries use exponential backoff.
The maximum number of attempts is three.
The final retry must be logged with event name billing.retry.exhausted.
