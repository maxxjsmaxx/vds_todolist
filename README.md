task results 2023.05.21 17:39

```js
// app
<Todolist title={123}/>
<Todolist title={"js"}/>
<Todolist title={45}/>
```

```js
// Todolist
type
PropsType = {
    title: number | string
}
```

```js
Todolist
export const Todolist = (props:PropsType) => {
    return (
        <div>
            <h3>{props.title}</h3>...
```