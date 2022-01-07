<script>
import Vue from "vue";
import Icon from "@/components/atoms/HIcon.vue";
import ContentTitle from "@/components/molecules/ContentTile.vue";
import Language from "@/components/molecules/Language.vue";
import HButton from "@/components/atoms/HButton";
import HCheckbox from "@/components/atoms/HCheckbox";
import HFeature from "@/components/atoms/HFeature";
import HGrid from "@/components/atoms/HGrid";
import HInput from "@/components/atoms/HInput";
import HLabel from "@/components/atoms/HLabel";
import HLogo from "@/components/atoms/HLogo";
import HMedia from "@/components/atoms/HMedia";
import HRadio from "@/components/atoms/HRadio";
import HSection from "@/components/atoms/HSection";
import HSwitch from "@/components/atoms/HSwitch";
import HText from "@/components/atoms/HText";
import HWallLayout from "@/components/atoms/HWallLayout";

export default Vue.extend({
  name: "ServeDev",
  components: {
    HWallLayout,
    HText,
    HSwitch,
    HSection,
    HRadio,
    HMedia,
    HLogo,
    HLabel,
    HGrid,
    HFeature,
    HCheckbox,
    HButton,
    Icon,
    ContentTitle,
    Language,
    HInput,
  },
});
</script>

<template>
  <div id="app">
    labas cia pasteink
    <Icon icon="ic-burger" class="cursor-pointer" success viewBox="-2 3 20 20" />
    <ContentTitle>
      <template v-slot:author>yes I am author</template>
      <template v-slot:content> labas </template>
    </ContentTitle>
    <HButton primary>labas</HButton>
    <HFeature />
    <!-- <Language /> -->
    <HInput />
  </div>
</template>
