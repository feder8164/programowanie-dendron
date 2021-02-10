---
id: 6e8cfa0c-36b0-47f1-a5de-a98d5cd521ba
title: Click
desc: Dodaj do elementu HTML wywolanie funkcji typescript za pomoca zdarzenia click
updated: 1612940435525
created: 1608691422903
---
# Angular

## Dodaj do elementu HTML wywolanie funkcji typescript za pomoca zdarzenia click

```ts
changeFirstName() {
this.user.firstName = 'New Name!'
}
```

* * *

```html
<button ~~(click)~~="changeFirstName()">Change Name</button>
```
