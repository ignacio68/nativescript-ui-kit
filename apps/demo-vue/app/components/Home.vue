<template>
  <Page>
    <ActionBar>
      <Label text="LabelMarquee" class="action-bar" />
    </ActionBar>

    <GridLayout class="p-20">
      <ScrollView class="h-full">
        <StackLayout>
          <lm:LabelMarquee text="Lorem Ipsum; this is a long string of text that will animate because it's longer than the width of the view."></lm:LabelMarquee>
        </StackLayout>
      </ScrollView>
    </GridLayout>
  </Page>
</template>

<script lang="ts">
import Vue from 'nativescript-vue';

export default Vue.extend({
  computed: {
    message() {
      return 'Demo {N}-Vue app';
    },
  },
});
</script>

<style scoped lang="scss">
.info {
  font-size: 20;
  horizontal-align: center;
  vertical-align: center;
}
</style>
