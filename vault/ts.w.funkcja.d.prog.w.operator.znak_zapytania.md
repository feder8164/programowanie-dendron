---
id: 42a8114f-3622-4504-ad36-c5ac991d5a0d
title: Znak_zapytania
desc: ''
updated: 1612940491343
created: 1608809805031
---

# Typescript

## Tworzenie nowej funkcji ktora zawiera operator znaku zapytania

```html
{{ askIfSubscribed() }}
```

* * *

```ts
askIfSubscribed(){
    return this.user.isSubscribed ?
    'You are subscribed' : 'Want to get updates ' + this.user.firstName + '?'
}
```
