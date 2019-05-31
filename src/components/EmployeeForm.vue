<template>
    <div id="employee-form">
        <form action="">
            <label for="">Employee name</label>
            <input type="text">
            <label for="">Employee email</label>
            <input type="text">
            <button>Add Employee</button>
        </form>
    </div>
</template>

<script>
export default {
    name: 'employee-form',
    data() {
        return {
            employee: {
                name: '',
                email: ''
            }
        }
    }
}
</script>

<style scoped>
    form {
        margin-bottom: 2rem;
    }
</style>
