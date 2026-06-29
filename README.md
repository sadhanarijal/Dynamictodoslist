
# Dynamictodoslist
.todo-container {
    max-width: 600px;
    margin: auto;
    font-family: Arial, sans-serif;
  }
  
  h1 {
    color: darkblue;
    text-align: center;
  }
  
  h2 {
    color: #ca7d18;
    border-bottom: 2px solid black;
    padding-bottom: 5px;
  }
  
  
  .todo-fprm {
    background: lightblue;
    padding: 20px;
    border: 2px solid black;
  }
  
  .todo-fprm label {
    display: block;
    margin-bottom: 10px;
    font-weight: bold;
  }
  
  .todo-fprm input[type="text"],
  .todo-fprm textarea,
  .todo-fprm input[type="date"] {
    width: 100%;
    display: block;
    margin-top: 5px;
    padding: 5px;
    border: 1px solid gray;
    font-size: 14px;
  }
  
  .todo-fprm textarea {
    height: 80px;
    resize: none;
  }
  
  /* checkbox is special so we fix it separately */
  .todo-fprm input[type="checkbox"] {
    width: auto;
    display: inline;
    margin-right: 5px;
  }
  
  .todo-fprm button {
    background-color: green;
    color: white;
    padding: 10px 20px;
    border-radius: 5px;
    border: none;
    cursor: pointer;
    margin-top: 10px;
    font-size: 16px;
  }
  
  .todo-fprm button:hover {
    background-color: darkgreen;
  }
  
  /* ---- todo card ---- */
  
  /* todo card */
.todo-card {
    background-color: lightyellow;
    border: 2px solid orange;
    padding: 15px;
    margin-top: 15px;
    margin-bottom: 15px;
    border-radius: 5px;
    width: 95%;
  }
  
  .todo-card h4 {
    color: darkred;
    font-size: 18px;
    margin-top: 0px;
    margin-bottom: 5px;
    text-transform: uppercase;
  }
  
  .todo-card p {
    color: #444444;
    font-size: 14px;
    margin-top: 0px;
  }
  
  /* date and completed are both b tags so i style them the same */
  .todo-card b {
    display: block;
    color: #222;
    font-size: 13px;
    margin-top: 5px;
    background-color: #eeeeee;
    padding: 3px 6px;
    width: fit-content;
  }
