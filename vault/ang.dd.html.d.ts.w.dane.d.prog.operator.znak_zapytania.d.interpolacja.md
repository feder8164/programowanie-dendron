---
id: 00e2b44e-6894-4465-9902-f9adecf54bde
title: Interpolacja
desc: >-
  Dodaj do HTML objekt wlasnosci Typescript ktory zawiera operator znaku
  zapytania za pomoca interpolacji
updated: 1612940389162
created: 1608693090529
---
# Angular

## Dodaj do HTML objekt wlasnosci Typescript ktory zawiera operator znaku zapytania za pomoca interpolacji

```ts
user = {
    firstName: 'Handsome Jack'
    isSubscribed: true
}
```
---
```html
{{ user.isSubscribed ? 'You are subscribed' : 'Want to get updates' + user.firstName }}
```
