<template>
  <GridLayout rows="*, *" columns="*, *" style="height: 600px; width: 400px; margin:auto;">
    <StackLayout row="0" col="0" class="stack-cell">
      <Label text="none" class="label-text" />
      <!-- >> image-stretch-none -->
      <Img src="https://art.nativescript-vue.org/NativeScript-Vue-White-Green.png" stretch="none" />
      <!-- << image-stretch-none -->
    </StackLayout>
    <StackLayout row="1" col="0" class="stack-cell">
      <Label text="fill" class="label-text" />
      <!-- >> image-stretch-fill -->
      <Img src="https://art.nativescript-vue.org/NativeScript-Vue-White-Green.png" stretch="fill" />
      <!-- << image-stretch-fill -->
    </StackLayout>
    <StackLayout row="0" col="1" class="stack-cell">
      <Label text="aspectFill" class="label-text" />
      <!-- >> image-stretch-aspect-fill -->
      <Img src="https://art.nativescript-vue.org/NativeScript-Vue-White-Green.png" stretch="aspectFill" />
      <!-- << image-stretch-aspect-fill -->
    </StackLayout>
    <StackLayout row="1" col="1" class="stack-cell">
      <Label text="aspectFit" class="label-text" />
      <!-- >> image-stretch-aspect-fit -->
      <Img src="https://art.nativescript-vue.org/NativeScript-Vue-White-Green.png" stretch="aspectFit" />
      <!-- << image-stretch-aspect-fit -->
    </StackLayout>
  </GridLayout>
</template>
<style scoped lang="scss">
.label-text {
  text-align: center;
  font-weight: bold;
  background-color: rgba(166, 178, 181, 0.3);
  padding: 5px auto;
}

.stack-cell {
  border: solid 1px #a6b2b5;
  margin: 10px;
}
</style>
<script>
export default {
  name: "ImageDoc"
};
</script>
