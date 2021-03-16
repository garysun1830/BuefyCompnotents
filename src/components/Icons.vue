
<template>
    <section>
        <span class="iconify" data-icon="mdi-github" data-inline="false"></span>
        <div class="buttons">
            <b-button size="is-small"
                icon-left="ethernet">
                Add
            </b-button>

            <b-button icon-left="github-circle">
                Add
            </b-button>

            <b-button size="is-medium"
                icon-left="github-circle"> 
                Add
            </b-button>

            <b-button 
                icon-left="google-glass">
                Add
            </b-button>
        </div>

        <div class="buttons">
            <b-button type="is-danger"
                icon-left="delete">
                Delete
            </b-button>

            <b-button type="is-danger"
                icon-right="delete">
                Delete
            </b-button>

            <b-button type="is-danger"
                icon-right="delete" />
        </div>

    </section>
</template>

<script>
export default {
  name: 'Icons',
  props: {
  }
}
</script>


