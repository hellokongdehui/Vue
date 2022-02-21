<template>
  <div>
    <corporate></corporate>
    <employee></employee>
  </div>
</template>

<script>
  import Corporate from "01_Corporate"
  import Employee from "./02_Employee"
  export default {
    name:"App",
    comments:{
      Corporate,
      Employee
    }
  }
</script>

<style>

</style>