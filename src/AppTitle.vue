<template lang="">
    <div>
        <h3>Benvenuto <em class="sp-gr">{{getUserName()}}</em> <br>______________</h3>
    </div>
</template>
<script>
export default {
    data() {
        return {
            user: {
                firstName: "Marco",
                lastName: "Pisani"
            }


        }

    },
    methods: {
        getUserName() {
            return this.user.firstName + " " + this.user.lastName
        }
    },
}
</script>
<style scoped>
.sp-gr {
    color: green
}
</style>