<template>
  <StackLayout>
    <Button text="Show Action Dialog" width="200" @tap="showActionDialog" />
  </StackLayout>
</template>

<script>
export default {
  name: "ActionDialogDoc",
  methods: {
    showActionDialog: function() {
      action("Your message", "Cancel button text", ["Option1", "Option2"]).then(
        result => {
          console.log(result);
        }
      );
    }
  }
};
</script>

