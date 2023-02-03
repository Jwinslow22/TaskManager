<!DOCTYPE html>
  <h1>

  <head>Task Manager</head>
    <style>
body {
  background-color: lightblue;
}

h1 {
  color: maroon;
  margin-left: 40px;
}
</style>
</h1>
<h2>New Task</h2>
<form action="/action_page.php">
  <label for="fname">Name:</label><br>
  <input type="text" id="fname" name="fname" value="My Tasks"><br>
  <label for="lname">Description:</label><br>
  <input type="text" id="fname" name="fname" value="My Description"><br>
  <label for="lname">Assigned To:</label><br>
  <input type="text" id="lname" name="lname" value="Name"><br>
  <div style="float:right;">
    <label for="lname">Date:</label><br>
    <input type="date" id="date" type="datetime-local">
  </div>
  <div style="float:right;">
    <label for="lname">Status:</label><br>
    <select name="status" id="Status">
    <option value="To-Do">To-Do</option>
  <option value="done">Done</option>
    <div class="dropdown">
      <button onclick="myFunction()" class="dropbtn">Done</button>
      <div id="myDropdown" class="dropdown-content">
    </div>
    <input type="submit" value="Add Task">
</form><br>
Task List
      <input>
