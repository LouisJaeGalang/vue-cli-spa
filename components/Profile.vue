<template>
  <div id='profile'>
    <h1>{{msg2}}</h1>
    <h3>{{msg3}}</h3>
    <h3>{{msg4}}</h3>
    <h3>{{msg5}}</h3>
  </div>
</template>

<script>
export default({
    name:'Profile',
    data() {
        return{
            msg2:'Profile',
            msg3:'Name: Louis Jae Galang',
            msg4:'Course: Web Development',
            msg5:'Specialization: Programming, Article Writing, Creative Writing'
        }
    },
})
</script>
