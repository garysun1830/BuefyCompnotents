<template>
    <section>
        <b-field>
            <b-datepicker
                ref="datepicker"
                expanded
                placeholder="Select a date">
            </b-datepicker>
            <b-button
                @click="$refs.datepicker.toggle()"
                icon-left="calendar-today"
                type="is-primary" />
        </b-field>
    </section>
</template>

<script>
    export default {
        name:"DatepickerProgram",
        data() {
            return {
                date: new Date()
            }
        }
    }
</script>