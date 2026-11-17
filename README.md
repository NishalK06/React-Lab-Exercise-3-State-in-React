# React Lab Exercise 3: State in React
## Name: Nishal K
## Roll no: 2305001021
## Department: CSE

## AIM
### To create a simple React application that demonstrates the use of State using the useState() Hook. 

## PROGRAM
### App.jsx 
```py
import { useState } from "react"; function App() { const [name, setName] = useState("Aravindan T"); const [newName, setNewName] = useState(""); 
return ( 
<div> 
<h1>Student Name Example</h1> 
<h2>Student Name: {name}</h2> 
<input type="text" placeholder="Enter new name" value={newName} 
onChange={(e) => setNewName(e.target.value)} 
/> 
<button onClick={() => setName(newName)}> 
Change Name 
</button> 
</div> 
);
}
export default App;

```
## OUTPUT
<img width="1415" height="1111" alt="image" src="https://github.com/user-attachments/assets/81b43169-5027-46c8-a7e6-6b334cc5ae92" />


## RESULT
### The React application was successfully created using Props to pass employee information from the parent component to the child component. Three employee details were displayed successfully using Props and Props Destructuring.
