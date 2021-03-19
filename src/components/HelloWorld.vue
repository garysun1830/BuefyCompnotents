<template>
  <div style="width: 900px; margin-left: 20px">
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
    <Fields />
    <LabelFields />
    <ObjectFields />
    <AddonFields />
    <GroupFields />
    <NestedFields />
    <ResponsiveFields />
    <PositionFields />
    <HorizontalFields />
    <ManyFields />
    <Inputs />
    <TypeInputs />
    <IconInputs />
    <ValidationInputs />
    <PasswordInputs />
    <SizeInputs />
    <Numberinput />
    <TypeNumber />
    <Radio />
    <SizeRadio />
    <TypeRadio />
    <Select />
    <MultipleSelect />
    <IconSelect style="text-align: left" />
    <SizeSelect />
    <SizeSlide />
    <TypeSlide />
    <Switches />
    <TypeSwitches />
    <StyleSwitches />
    <Taginput />
    <AutoTaginput />
    <TemplatedTag />
    <GroupTag />
    <StateTag />
    <TypeTag />
    <ModifierTag />
    <ValidationTag />
    <Toast />
    <Tooltip />
    <StyleTooltip />
    <CustomTooltip />
    <MultilinedTooltip />
    <ToggleTooltip />
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
import Fields from "../components/Fields.vue";
import LabelFields from "../components/LabelFields.vue";
import ObjectFields from "../components/ObjectFields.vue";
import AddonFields from "../components/AddonFields.vue";
import GroupFields from "../components/GroupFields.vue";
import NestedFields from "../components/NestedFields.vue";
import ResponsiveFields from "../components/ResponsiveFields.vue";
import PositionFields from "../components/PositionFields.vue";
import HorizontalFields from "../components/HorizontalFields.vue";
import ManyFields from "../components/ManyFields.vue";
import Inputs from "../components/Inputs.vue";
import TypeInputs from "../components/TypeInputs.vue";
import IconInputs from "../components/IconInputs.vue";
import ValidationInputs from "../components/ValidationInputs.vue";
import PasswordInputs from "../components/PasswordInputs.vue";
import SizeInputs from "../components/SizeInputs.vue";
import Numberinput from "../components/Numberinput.vue";
import TypeNumber from "../components/TypeNumber.vue";
import Radio from "../components/Radio.vue";
import SizeRadio from "../components/SizeRadio.vue";
import TypeRadio from "../components/TypeRadio.vue";
import Select from "../components/Select.vue";
import MultipleSelect from "../components/MultipleSelect.vue";
import IconSelect from "../components/IconSelect.vue";
import SizeSelect from "../components/SizeSelect.vue";
import SizeSlide from "../components/SizeSlide.vue";
import TypeSlide from "../components/TypeSlide.vue";
import Switches from "../components/Switches.vue";
import TypeSwitches from "../components/TypeSwitches.vue";
import StyleSwitches from "../components/StyleSwitches.vue";
import Taginput from "../components/Taginput.vue";
import AutoTaginput from "../components/AutoTaginput.vue";
import TemplatedTag from "../components/TemplatedTag.vue";
import GroupTag from "../components/GroupTag.vue";
import StateTag from "../components/StateTag.vue";
import TypeTag from "../components/TypeTag.vue";
import ModifierTag from "../components/ModifierTag.vue";
import ValidationTag from "../components/ValidationTag.vue";
import Toast from "../components/Toast.vue";
import Tooltip from "../components/Tooltip.vue";
import StyleTooltip from "../components/StyleTooltip.vue";
import CustomTooltip from "../components/CustomTooltip.vue";
import MultilinedTooltip from "../components/MultilinedTooltip.vue";
import ToggleTooltip from "../components/ToggleTooltip.vue";

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
    Fields,
    LabelFields,
    ObjectFields,
    AddonFields,
    GroupFields,
    NestedFields,
    ResponsiveFields,
    PositionFields,
    HorizontalFields,
    ManyFields,
    Inputs,
    TypeInputs,
    IconInputs,
    ValidationInputs,
    PasswordInputs,
    SizeInputs,
    Numberinput,
    TypeNumber,
    Radio,
    SizeRadio,
    TypeRadio,
    Select,
    MultipleSelect,
    IconSelect,
    SizeSelect,
    SizeSlide,
    TypeSlide,
    Switches,
    TypeSwitches,
    StyleSwitches,
    Taginput,
    AutoTaginput,
    TemplatedTag,
    GroupTag,
    StateTag,
    TypeTag,
    ModifierTag,
    ValidationTag,
    Toast,
    Tooltip,
    StyleTooltip,
    CustomTooltip,
    MultilinedTooltip,
    ToggleTooltip,
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
