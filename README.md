# Angular: simple tabs with animation

---

## About

**tabs** is module for [angular](http://angularjs.org/) framework. [Live demo](http://nervgh.github.io/pages/angular-tabs/)

## Requires

- the [angularjs](https://github.com/angular/angular.js) framework

## Includes

### Directives

- **ng-tabs** - area of ​​the container tabs
- **ng-tab-head** - tab head
- **ng-tab-body** - tab body

## Scope

The `ng-tabs` directive creates a isolate scope. Variables of this scope:
```javascript
tabs: {
    index: {Number},  // current tab index
    count: {Number}  // tabs count
};
```

## Example

```html
<div ng-tabs>
    <div ng-tab-head>First tab</div>
    <div ng-tab-head="active">Second tab</div>
    <div ng-tab-body>Content 1</div>
    <div ng-tab-body="animation">Content 2</div>
</div>
```