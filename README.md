

```js
<li><input type="checkbox" readOnly={false}/> <span>React</span></li>
```
==> 
```js
<li><input type="checkbox" readOnly={true} checked={true}/> <span>HTML&CSS</span></li>
```

---

react-dom.development.js:86 Warning: You provided a `checked` prop to a form field without an `onChange` handler. This will render a read-only field. If the field should be mutable use `defaultChecked`. Otherwise, set either `onChange` or `readOnly`.

Since there is no `onChange` handler, either replace `checked` with `defaultChecked` or add `readOnly`

Temporarily adding `readOnly={true}`