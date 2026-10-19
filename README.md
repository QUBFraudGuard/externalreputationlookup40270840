# externalreputationlookup40270840

A simulated third-party reputation API for QUBCloud-FraudGuard. In a real system this would be an external provider. Here it is a small service I control, so the reputation check can be built and tested end to end.

Part of [QUBCloud-FraudGuard](https://github.com/QUBFraudGuard).

## Run it

```bash
git clone https://github.com/QUBFraudguard/externalreputationlookup40270840.git
cd externalreputationlookup40270840
docker build -t externalreputationlookup40270840 .
docker run -p 5000:5000 externalreputationlookup40270840
```
