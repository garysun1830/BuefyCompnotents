<template>
  <div style="width: 900px">
    <Menu />
    <Login />
    <Dropdown />
    <ButtonDown />
    <OptionDown />
    <Buttons />
    <Icons />
    <Slides />
    <Panels />
    <Alert />
    <Confirm />
    <Prompt />
  </div>
</template>

<script>
import Buttons from "../components/Buttons.vue";
import Icons from "../components/Icons.vue";
import Slides from "../components/Slides.vue";
import Panels from "../components/Panels.vue";
import Dropdown from "../components/Dropdown.vue";
import Menu from "../components/Menu.vue";
import Login from "../components/Login.vue";
import ButtonDown from "../components/ButtonDown.vue";
import OptionDown from "../components/OptionDown.vue";
import Alert from "../components/Alert.vue";
import Confirm from "../components/Confirm.vue";
import Prompt from "../components/Prompt.vue";

export default {
  name: "HelloWorld",
  props: {
    msg: String,
  },
  components: {
    Buttons,
    Icons,
    Slides,
    Panels,
    Dropdown,
    Menu,
    Login,
    ButtonDown,
    OptionDown,
    Alert,
    Confirm,
    Prompt,
  },
};
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: #42b983;
}
</style>
