---
id: 877a5690-f196-45fd-84eb-7b82aa629f61
title: Ang
desc: ''
updated: 1612940454804
created: 1608539192852
---
```ts
tempName = ''
```
---
```html
<input type="text" [value]="user.firstName" #firstNameRef
    (change)="tempName = $event.target.value">
```
