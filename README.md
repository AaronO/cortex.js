[![Screen](https://raw.github.com/AaronO/cortex.js/master/assets/logo.png)](https://raw.github.com/AaronO/cortex.js/master/assets/logo.png)

# What is Cortex.js ?

Cortex.js is a service providing machine learning and natural language processing constructs easily embeddable in your application. 

# API

## /sentiment/rank

## /conversation/emotions

Ranks the emotional involvment of two indiviauls in a conversation (Instant messaging, SMS, Emails ...)

### Input sample

```json
[
  {
    "to": "Bob",
    "from": "Alice",
    "content": "Hi Bob! What's up ?",
    "timestamp": 1381907221
  },
  {
    "to": "Bob",
    "from": "Alice",
    "content": "Hi Bob! What's up ?",
    "timestamp": 1381907251
  },
  ...
]
```

# TODO
  - Main API Server
  - More useful algorithms besides, conversation ranking
  - Stabilize API convention


