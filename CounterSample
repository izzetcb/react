function Button(props){
  return(
    <button onClick={props.click}>
      +1
    </button>
  )
}

function Display(props){
  return(
    <div>
      {props.message}
    </div>
  )
}

function App(){
  const [counter, setCounter] = useState(0);
  const onclick = () => setCounter(counter + 1);
  return(
  <div>
     <Button click = {onclick}/>
     <Display message={counter}/>
  </div>
  )
  
}

ReactDOM.render(
  <App/>,
  document.getElementById('mountNode')
)
