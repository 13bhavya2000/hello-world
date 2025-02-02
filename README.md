# React learnings

node js -> runtime environment to run javascript code outside of browser \n
npm -> node package manager for adding features from already package features in it
npm create vite@latest
package.json -> metadata contains dependencies scripts
npm install
index.html-> div root
app.jsx->where main ui of react is defined
main.jsx->entry point of react app where it is render
2 complonents in react:
class components-> class classComponents extends React.Component; not typically used as it is old
functional components-> uses arrow function const App = ()=>{}
props->pass data from one component to another typically parent to child as arguments
Destructuring-> is a feature in JavaScript that allows you to extract values from arrays or objects and assign them to variables in a shorter, cleaner way.
State -> that can change over time
    const [var,setVar] = useState(initial value)
useEffect -> for handling side effects like data fetching
useContext - > for sharing data across components
useCallback -> for optimizing calls
