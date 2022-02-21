<template>
  <div class="demo">
    <h2>雇员姓名：{{employeeName}}</h2>
    <h2>雇员年龄：{{age}}</h2>
  </div>
</template>

<script>
export default {
  name:"Employee",
  data() {
    return {
      employeeName:"腾讯微信",
      age:26
    }
  },
}
</script>
