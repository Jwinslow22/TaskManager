<!DOCTYPE html>
<html>
  <h1>

  <head>Task Manager</head>
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
    <input type="text" id="lname" name="lname" value="mm/dd/yyyy"><br>
  </div>
  <div style="float:right;">
    <label for="lname">Status:</label><br>
    <input type="text" id="lname" name="lname" value="To-Do">
    <div class="dropdown">
      <button onclick="myFunction()" class="dropbtn">Done</button>
      <div id="myDropdown" class="dropdown-content">
      </div>
    </div><br>
    <input type="submit" value="Add Task">
</form><br>
Task List
