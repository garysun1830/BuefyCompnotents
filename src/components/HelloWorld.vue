<template>
  <div style="width: 900px">
    <Menu />
    <Login />
    <Dropdown />
    <ButtonDown />
    <OptionDown />
    <Buttons />
    <Icons />
    <Autocomplete />
    <AutoInput />
    <InputNew />
    <Slides />
    <Panels />
    <Alert />
    <Confirm />
    <Prompt />
    <Checkbox />
    <CheckboxList />
    <CheckboxMore />
    <CheckboxType />
    <CheckboxButton />
    <Clockpicker />
    <ClockpickerEdit />
    <ClockpickerColor />
    <Datepicker />
    <DatepickerRange />
    <DatepickerFooter />
    <DatepickerHeader />
    <DatepickerTrigger />
    <MonthPicker />
    <DatepickerProgram />
    <DatepickerInline />
    <DatepickerEvent />
    <DatepickerMore />
    <DatepickerMultiple />
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
import Autocomplete from "../components/Autocomplete.vue";
import AutoInput from "../components/AutoInput.vue";
import InputNew from "../components/InputNew.vue";
import Checkbox from "../components/Checkbox.vue";
import CheckboxList from "../components/CheckboxList.vue";
import CheckboxMore from "../components/CheckboxMore.vue";
import CheckboxType from "../components/CheckboxType.vue";
import CheckboxButton from "../components/CheckboxButton.vue";
import Clockpicker from "../components/Clockpicker.vue";
import ClockpickerEdit from "../components/ClockpickerEdit.vue";
import ClockpickerColor from "../components/ClockpickerColor.vue";
import Datepicker from "../components/Datepicker.vue";
import DatepickerRange from "../components/DatepickerRange.vue";
import DatepickerFooter from "../components/DatepickerFooter.vue";
import DatepickerHeader from "../components/DatepickerHeader.vue";
import DatepickerTrigger from "../components/DatepickerTrigger.vue";
import MonthPicker from "../components/MonthPicker.vue";
import DatepickerProgram from "../components/DatepickerProgram.vue";
import DatepickerInline from "../components/DatepickerInline.vue";
import DatepickerEvent from "../components/DatepickerEvent.vue";
import DatepickerMore from "../components/DatepickerMore.vue";
import DatepickerMultiple from "../components/DatepickerMultiple.vue";

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
    Autocomplete,
    AutoInput,
    InputNew,
    Checkbox,
    CheckboxList,
    CheckboxMore,
    CheckboxType,
    CheckboxButton,
    Clockpicker,
    ClockpickerEdit,
    ClockpickerColor,
    Datepicker,
    DatepickerRange,
    DatepickerFooter,
    DatepickerHeader,
    DatepickerTrigger,
    MonthPicker,
    DatepickerProgram,
    DatepickerInline,
    DatepickerEvent,
    DatepickerMore,
    DatepickerMultiple,
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
