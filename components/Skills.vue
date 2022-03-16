<template>
  <div id='skills'>
    <h1>{{msg11}}</h1>
    <h3>{{msg12}}</h3>
    <h3>{{msg13}}</h3>
    <h3>{{msg14}}</h3>
    <h3>{{msg15}}</h3>
  </div>
</template>

<script>
export default({
    name:'Profile',
    data() {
        return{
            msg11:'Skills',
            msg12:'Training:None',
            msg13:'Seminars: Professional Development Work (2017), "WEB-eign From the Future" Webpage Design Workshop (2020), "2006: Design of Times" Graphics Design Workshop (2020)',
            msg14:'Technologies:Programming Languages, Technical Writing',
            msg15:'Programming Languages: VueJS, NodeJS, JavaScript, Python'
        }
    },
})
</script>
