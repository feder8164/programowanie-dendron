---
id: 46f073d8-8e53-49a0-932d-27f64ab92a03
title: Lokalna_referencja
desc: >-
  Dodaj do elementu HTML wywolanie funkcji typescript z parametrem lokalnej
  referencji za pomoca zdarzenia click
updated: 1612940442481
created: 1608691278822
---

# Angular

## Dodaj do elementu HTML wywolanie funkcji typescript z parametrem lokalnej referencji za pomoca zdarzenia click

```ts
changeFirstName(firstNameRef:HTMLInputElement) {
this.user.firstName = firstNameRef.value;
}
```
* * *
```html
<input type="text" [value]="user.firstName" ~~#firstNameRef~~>
<button ~~(click)="changeFirstName(~~firstNameRef~~)">~~Change Name</button>
```

