<script setup lang="ts">
const { signOut } = useAuth();
definePageMeta({
    middleware: 'auth'
})

const submitLogout = ()=>{

}
</script>

<template>
    <div>
        <h1>Minha Tela Home!!</h1>
        <button @click="submitLogout" class="customButton">SAIR</button>
    </div>
</template>

<style lang="scss">

</style>