<template>
  <section class="b-tooltips">
    <b-button label="Toggle" type="is-primary" @click="active = !active" />
    <hr />

    <b-tooltip label="I'm never closing" :active="active" always>
      <b-button label="Always" />
    </b-tooltip>

    <b-tooltip label="Tooltip right" position="is-right" :active="active">
      <b-button label="Right" type="is-dark" />
    </b-tooltip>
  </section>
</template>

<script>
export default {
  name: "ToggleTooltip",
  data() {
    return {
      active: true,
    };
  },
};
</script>

<style>
.b-tooltip:not(:last-child) {
  margin-right: 0.5em;
}
.b-tooltip {
  margin-bottom: 0.5em;
}
</style>