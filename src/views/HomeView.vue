<template>
    <NavBar />
    <InputForm />
</template>


<script>
import NavBar from '../components/NavBar.vue';
import InputForm from '../components/InputForm.vue'

export default {
    name:'HomeView',
    components: { NavBar,InputForm}
}
</script>

