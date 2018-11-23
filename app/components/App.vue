<template>
    <Page>
      <ScrollView orientation="vertical">
        <StackLayout  backgroundColor="#3c495e">
          <Label class="header" text="Absolute Layout"></Label>
            <AbsoluteLayoutDoc></AbsoluteLayoutDoc>
          <Label class="header" text="Action Bar"></Label>
            <ActionBarDoc></ActionBarDoc>
          <Label class="header" text="Action Dialog"></Label>
            <ActionDialogDoc></ActionDialogDoc>
            <Label class="header" text="Activity Indicator"></Label>
            <ActivityIndicatorDoc></ActivityIndicatorDoc>
            <Label class="header" text="Confirm Dialog"></Label>
            <ConfirmDialogDoc></ConfirmDialogDoc>
            <Label class="header" text="Dock Layout"></Label>
            <DockLayoutDoc></DockLayoutDoc>
            <Label class="header" text="Flexbox Layout"></Label>
            <FlexboxLayoutDoc></FlexboxLayoutDoc>
            <Label class="header" text="Flexbox LayoutColumn"></Label>
            <FlexboxLayoutColumnDoc></FlexboxLayoutColumnDoc>
            <Label class="header" text="Flexbox Layout Column Reverse"></Label>
            <FlexboxLayoutColumnReverseDoc></FlexboxLayoutColumnReverseDoc>
            <Label class="header" text="Frame "></Label>
            <FrameDoc></FrameDoc>
            <Label class="header" text="Grid Layout "></Label>
            <GridLayoutDoc></GridLayoutDoc>
            <Label class="header" text="Grid Layout Responsive "></Label>
            <GridLayoutResponsiveDoc></GridLayoutResponsiveDoc>
            <Label class="header" text="Grid Layout Complex Grid"></Label>
            <GridLayoutComplexGridDoc></GridLayoutComplexGridDoc>

            <Label class="header" text="Image "></Label>
            <ImageDoc></ImageDoc>
            <Label class="header" text="Label "></Label>
            <LabelDoc></LabelDoc>
            <Label class="header" text="List Picker "></Label>
            <ListPickerDoc></ListPickerDoc>
            <Label class="header" text="Login Dialog "></Label>
            <LoginDialogDoc></LoginDialogDoc>
            <Label class="header" text="Navigation Button "></Label>
            <NavigationButtonDoc></NavigationButtonDoc>
            <Label class="header" text="Progress "></Label>
            <ProgressDoc></ProgressDoc>
            <Label class="header" text="Prompt Dialog "></Label>
            <PromptDialogDoc></PromptDialogDoc>
            <Label class="header" text="Scroll View "></Label>
            <ScrollViewDoc></ScrollViewDoc>
            
            <Label class="header" text="Segmented Bar "></Label>
            <SegmentedBarDoc></SegmentedBarDoc>
            <Label class="header" text="Stack Layout "></Label>
            <StackLayoutDoc></StackLayoutDoc>
            <Label class="header" text="Stack Layout "></Label>
            <StackLayoutDoc></StackLayoutDoc>
            <Label class="header" text="Stack Layout Horizontal "></Label>
            <StackLayoutHorizontalDoc></StackLayoutHorizontalDoc>
            <Label class="header" text="Switch "></Label>
            <SwitchDoc></SwitchDoc>
            <Label class="header" text="Tabview "></Label>
            <TabviewDoc></TabviewDoc>
            <Label class="header" text="Text Field "></Label>
            <TextFieldDoc></TextFieldDoc>
            <Label class="header" text="Text View "></Label>
            <TextViewDoc></TextViewDoc>
            <Label class="header" text="Time Picker "></Label>
            <TimePickerDoc></TimePickerDoc>
            <Label class="header" text="View Directive "></Label>
            <ViewDirectiveDoc></ViewDirectiveDoc>
            <Label class="header" text="View Directive Container "></Label>
            <ViewDirectiveContainerDoc></ViewDirectiveContainerDoc>
            <Label class="header" text="Web View "></Label>
            <WebViewDoc></WebViewDoc>
            <Label class="header" text="Wrap Layout "></Label>
            <WrapLayoutDoc></WrapLayoutDoc>
            <Label class="header" text="Wrap Layout Equal Column "></Label>
            <WrapLayoutEqualColumnDoc></WrapLayoutEqualColumnDoc>
            
        </StackLayout>
      </ScrollView>

    </Page>
</template>

<script>
import { NuButton, RadioButton, TextInput } from "nuweb-ui";
import AbsoluteLayoutDoc from "./AbsoluteLayoutDoc";
import ActionBarDoc from "./ActionBarDoc";
import ActionDialogDoc from "./ActionDialogDoc";
import ActionItemDoc from "./ActionItemDoc";
import ActivityIndicatorDoc from "./ActivityIndicatorDoc";
import ConfirmDialogDoc from "./ConfirmDialogDoc";
import DockLayoutDoc from "./DockLayoutDoc";
import FlexboxLayoutDoc from "./FlexboxLayoutDoc";
import FlexboxLayoutColumnDoc from "./FlexboxLayoutColumnDoc";
import FlexboxLayoutColumnReverseDoc from "./FlexboxLayoutColumnReverseDoc";
import FrameDoc from "./FrameDoc";
import GridLayoutDoc from "./GridLayoutDoc";
import GridLayoutResponsiveDoc from "./GridLayoutResponsiveDoc";
import GridLayoutComplexGridDoc from "./GridLayoutComplexGridDoc";
import ButtonDoc from "./ButtonDoc";
import HtmlViewDoc from "./HtmlViewDoc";
import ImageDoc from "./ImageDoc";
import LabelDoc from "./LabelDoc";
import ListPickerDoc from "./ListPickerDoc";
import LoginDialogDoc from "./LoginDialogDoc";
import NavigationButtonDoc from "./NavigationButtonDoc";
import ProgressDoc from "./ProgressDoc";
import PromptDialogDoc from "./PromptDialogDoc";
import ScrollViewDoc from "./ScrollViewDoc";
import SearchBarDoc from "./SearchBarDoc";
import SegmentedBarDoc from "./SegmentedBarDoc";
import SliderDoc from "./SliderDoc";
import StackLayoutDoc from "./StackLayoutDoc";
import StackLayoutHorizontalDoc from "./StackLayoutHorizontalDoc";
import StackLayoutHorizontalChildrenDoc from "./StackLayoutHorizontalChildrenDoc";
import StackLayoutVerticalChildrenDoc from "./StackLayoutVerticalChildrenDoc";
import SwitchDoc from "./SwitchDoc";
import TabviewDoc from "./TabviewDoc";
import TextFieldDoc from "./TextFieldDoc";
import TextViewDoc from "./TextViewDoc";
import TimePickerDoc from "./TimePickerDoc";
import ViewDirectiveDoc from "./ViewDirectiveDoc";
import ViewDirectiveContainerDoc from "./ViewDirectiveContainerDoc";
import WebViewDoc from "./WebViewDoc";
import WrapLayoutDoc from "./WrapLayoutDoc";
import WrapLayoutEqualColumnDoc from "./WrapLayoutEqualColumnDoc";

export default {
  data() {
    return {
      currentProgress: 10,
      maxValueProgress: 70
    };
  },
  methods: {
    onValueChanged() {
      alert("Value changed!");
    }
  },
  components: {
    NuButton,
    RadioButton,
    TextInput,
    AbsoluteLayoutDoc,
    ActionBarDoc,
    ActionDialogDoc,
    ActionItemDoc,
    ActivityIndicatorDoc,
    ConfirmDialogDoc,
    DockLayoutDoc,
    FlexboxLayoutDoc,
    FlexboxLayoutColumnDoc,
    FlexboxLayoutColumnReverseDoc,
    FrameDoc,
    GridLayoutDoc,
    GridLayoutResponsiveDoc,
    GridLayoutComplexGridDoc,
    ButtonDoc,
    HtmlViewDoc,
    ImageDoc,
    LabelDoc,
    ListPickerDoc,
    LoginDialogDoc,
    NavigationButtonDoc,
    ProgressDoc,
    PromptDialogDoc,
    ScrollViewDoc,
    SearchBarDoc,
    SegmentedBarDoc,
    SliderDoc,
    StackLayoutDoc,
    StackLayoutHorizontalDoc,
    StackLayoutHorizontalChildrenDoc,
    StackLayoutVerticalChildrenDoc,
    SwitchDoc,
    TabviewDoc,
    TextFieldDoc,
    TextViewDoc,
    TimePickerDoc,
    ViewDirectiveDoc,
    ViewDirectiveContainerDoc,
    WebViewDoc,
    WrapLayoutDoc,
    WrapLayoutEqualColumnDoc
  }
};
</script>

<style lang="scss">
.header {
  background-color:black;
  margin: 10px 0 10px 0;
  text-align: center;
  color: white;
  text-transform: uppercase;
}
Button{
  font-size:13px;
}
</style>

