[![Screen](https://raw.github.com/AaronO/cortex.js/master/assets/logo.png)](https://raw.github.com/AaronO/cortex.js/master/assets/logo.png)

## What is Cortex.js ?

Cortex.js is a service providing machine learning and natural language processing constructs easily embeddable in your application. 

## API

### /sentiment/rank

### /conversation/emotions

Ranks the emotional involvment of two indiviauls in a conversation (Instant messaging, SMS, Emails ...)

#### Data format

```
[
  {
    "to": "Bob",
    "from": "Alice",
    "content": "Hi Bob! What's up ?",
  },
  {
  
  },
```
