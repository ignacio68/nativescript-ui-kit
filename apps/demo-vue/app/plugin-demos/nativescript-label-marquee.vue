<template>
  <Page>
    <ActionBar>
      <Label text="nativescript-label-marquee"/>
    </ActionBar>

    <GridLayout>
      <Button class="info" :text="message"/>
    </GridLayout>
  </Page>
</template>

<script lang="ts">
  import Vue from "nativescript-vue";
  import { DemoSharedNativescriptLabelMarquee } from '@demo/shared';
  import { } from '@ignacio68/nativescript-label-marquee';

  export default Vue.extend({
    computed: {
      message() {
        return "Test nativescript-label-marquee";
      }
    }
  });
</script>

<style scoped lang="scss">

  .info {
    font-size: 20;
    horizontal-align: center;
    vertical-align: center;
  }
</style>
