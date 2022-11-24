<template>
<div class="task-main">
<h1>Welcome to the Task Program</h1>
<img id="logo" src="../assets/Taskicon.png" alt="icon" />

<form id="ftask">
<p>Task Name</p><input type="text" id="taskname"/>
<p>From Date</p><input type="datetime-local" id="fromdate"/>
<p>To Date</p><input type="datetime-local" id="todate"/>
<p>Location</p><input type="text" id="location"/>
<p>Persons</p><input type="text" id="persons"/>
<br/><input id="savetask" type="submit"/>
</form>
</div>

</template>
<script>
</script>

<style>
#logo{
    width:5em;
    height:5em
}
#savetask{
    
    cursor:pointer;
}
#savetask:hover {
   background-color: lightblue;
}
</style>