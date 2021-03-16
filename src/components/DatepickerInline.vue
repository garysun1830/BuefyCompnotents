<template>
    <b-datepicker v-model="date" 
        inline 
        :unselectable-days-of-week="[0, 6]">
    </b-datepicker>
</template>

<script>
    export default {
        name:"DatepickerInline",
        data() {
            return {
                date: new Date()
            }
        }
    }
</script>