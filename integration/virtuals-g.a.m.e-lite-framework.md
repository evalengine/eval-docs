# Virtuals G.A.M.E lite Framework

### Prerequisite

* G.A.M.E Lite environment configured
* Valid JWT Token (high-frequency rotation)
* API Key from G.A.M.E Lite

### Step by step guide

{% embed url="https://youtu.be/NCQyOoDBCKY" %}

#### 1. Agent Configuration

* Go to [https://app.virtuals.io/](https://app.virtuals.io/)
* Login → Agent dashboard
* Configure Sandbox mode (to get JWT token)

#### 2. JWT Integration

Base URL transformation:

```
FROM: https://game-lite.virtuals.io/?token=xyz
TO:   https://evalengine.ai?token=xyz
```

#### 3. API Authentication

* Grab API Key from G.A.M.E Lite
* Drop it in EvalEngine settings

### Integration Complete

You can now simulate your ai agent on EvalEngine

<figure><img src="../.gitbook/assets/EVAL Engine.jpeg" alt=""><figcaption></figcaption></figure>



