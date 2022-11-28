<template>
<div id="task-main" >
<h1>Welcome to the Task Program</h1>
<img id="logo" src="../assets/Taskicon.png" alt="icon" />

<form id="ftask">
<p>Task Name</p><input type="text" v-model="taskname"/>
<p>From Date</p><input type="datetime-local" v-model="fromdate"/>
<p>To Date</p><input type="datetime-local" v-model="todate"/>
<p>Location</p><input type="text" v-model="location"/>
<p>Persons</p><input type="text" v-model="persons"/>
<br/><a href="#" v-on:click="submit">SUBMIT</a>
<p>person{{persons}}</p>
</form>
</div>

</template>
<script>
 export default{
   data(){
    return{persons:"",location:""}
   },
   mounted () {
    console.log(this.persons)
  }
}
    


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