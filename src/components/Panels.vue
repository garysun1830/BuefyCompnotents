<template>
  <section>
    <div>
      <b-collapse :open="false" aria-id="contentIdForA11y1">
        <template #trigger>
          <b-button
            label="Click me!"
            type="is-primary"
            aria-controls="contentIdForA11y1"
          />
        </template>
        <div class="notification">
          <div class="content">
            <h3>Subtitle</h3>
            <p>
              Lorem ipsum dolor sit amet, consectetur adipiscing elit. <br />
              Nulla accumsan, metus ultrices eleifend gravida, nulla nunc varius
              lectus, nec rutrum justo nibh eu lectus. <br />
              Ut vulputate semper dui. Fusce erat odio, sollicitudin vel erat
              vel, interdum mattis neque.
            </p>
          </div>
        </div>
      </b-collapse>
    </div>
    <div>
      <div class="block">
        <b-button
          label="Toggle"
          type="is-primary"
          size="is-medium"
          @click="isOpen = !isOpen"
          aria-controls="contentIdForA11y2"
        />
      </div>

      <b-collapse
        aria-id="contentIdForA11y2"
        class="panel"
        animation="slide"
        v-model="isOpen"
      >
        <template #trigger>
          <div
            class="panel-heading"
            role="button"
            aria-controls="contentIdForA11y2"
          >
            <strong>Title</strong>
          </div>
        </template>
        <p class="panel-tabs">
          <a class="is-active">All</a>
          <a>Public</a>
          <a>Private</a>
        </p>
        <div class="panel-block">
          Lorem ipsum dolor sit amet, consectetur adipiscing elit. <br />
          Nulla accumsan, metus ultrices eleifend gravida, nulla nunc varius
          lectus, nec rutrum justo nibh eu lectus. <br />
          Ut vulputate semper dui. Fusce erat odio, sollicitudin vel erat vel,
          interdum mattis neque.
        </div>
      </b-collapse>
      <table>
        <tr>
          <td>
            <b-collapse
              class="card"
              animation="slide"
              aria-id="contentIdForA11y3"
            >
              <template #trigger="props">
                <div
                  class="card-header"
                  role="button"
                  aria-controls="contentIdForA11y3"
                >
                  <p class="card-header-title">Component</p>
                  <a class="card-header-icon">
                    <b-icon :icon="props.open ? 'menu-down' : 'menu-up'">
                    </b-icon>
                  </a>
                </div>
              </template>

              <div class="card-content">
                <div class="content">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  Phasellus nec iaculis mauris.
                  <a>#buefy</a>.
                </div>
              </div>
              <footer class="card-footer">
                <a class="card-footer-item">Save</a>
                <a class="card-footer-item">Edit</a>
                <a class="card-footer-item">Delete</a>
              </footer>
            </b-collapse>
          </td>
          <td>
            <b-collapse
              class="card"
              animation="slide"
              aria-id="contentIdForA11y3"
            >
              <template #trigger="props">
                <div
                  class="card-header"
                  role="button"
                  aria-controls="contentIdForA11y3"
                >
                  <p class="card-header-title">Component</p>
                  <a class="card-header-icon">
                    <b-icon :icon="props.open ? 'menu-down' : 'menu-up'">
                    </b-icon>
                  </a>
                </div>
              </template>

              <div class="card-content">
                <div class="content">
                  Lorem ipsum dolor sit amet, consectetur adipiscing elit.
                  Phasellus nec iaculis mauris.
                  <a>#buefy</a>.
                </div>
              </div>
              <footer class="card-footer">
                <a class="card-footer-item">Save</a>
                <a class="card-footer-item">Edit</a>
                <a class="card-footer-item">Delete</a>
              </footer>
            </b-collapse>
          </td>
        </tr>
      </table>
    </div>
  </section>
</template>

<script>
export default {
  data() {
    return {
      isOpen: true,
    };
  },
  name: "Panels",
  props: {},
};
</script>


