
### what

### why

### jsx
**Props and State**

use state
**State Management**
**React Router**
**Lists and Keys**
**Conditional Rendering**
**Handling Events**
### setup
- create react app : `npx create-react-app "name"`
-  run react app :   `cd name ` => `npm start`

### file structure
![[Drawing 2023-09-27 15.03.32.excalidraw]]

### jsx
- jsx stand for javascript XML 
- jsx = javascript + html 
```jsx
const name = "ahsan"
const element = <h1>my name is {name } , sum = {sum(1,3)} </h1> 
```


###  component
- component is a function 
- rules of componet
   - 1. component must return jsx
   - 2. component name must start with uppercase letter
```jsx

function Hello ()
{
const data = "hello world";
return (
<h1> {data}</h1>
)

}

export default Hello;
```


### props
- props are like parameters to a function 
```jsx
functio Hello (props)
{
  return (
    <h1> hello {props.name} </h1>
  )

}

//call <Hello name = "ahsan"/>

```


### lifecycle of a component
![[react1.png]]

![[Pasted image 20230928105443.png]]

### hooks
- in react hook name always start with `use`


### useState hook
- A state of a componet is a variable that holds some information that may change over the lifetime of the component
- wheneverteh value of the state changes , the component re-renders itself with updated values.
```jsx
//const [var,changevarfunction] = useState(intial_value)
const [count,setCount] = useState(1);

```


### useEffect hook
- use for run function for specific movement , mounting , udating , unmounting time of a component
```jsx

1. when construct componet or  update then run 
2. when construct component or update particlar var 


```

library called **React Query**.
**React Context** ,  redux or **Zustand**  or Jotai or Recoil
**Vite**
[web devlopment](WEB_DEVLOPMENT)
