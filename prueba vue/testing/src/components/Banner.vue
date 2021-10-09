<template>
    <div class="container">
        <h1>Bienvenido {{ cliente.nombre }} </h1>
        <div class="container">
            <input type="text" v-model="cliente.nombre">
        </div>
    </div>
</template>
<script>
export default {
    data () {
        return {
            cliente: {
                nombre: 'Camilo',
                apellido: 'castañeda'
            }
        }
    }
}
</script>