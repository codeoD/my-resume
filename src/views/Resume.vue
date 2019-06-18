<template>
    <div class="resume">
        <resume-header/>
        <resume-body class="resume-body"/>
        <resume-footer/>
    </div>
</template>

<script lang="ts">
import { Component, Vue } from 'vue-property-decorator'
import ResumeHeader from '@/components/resume/Header.vue'
import ResumeFooter from '@/components/resume/Footer.vue'
import ResumeBody from '@/components/resume/Body.vue'

@Component({
  components: {
    ResumeHeader,
    ResumeFooter,
    ResumeBody
  }
})
export default class Resume extends Vue {}
</script>
<style>
.resume {
    display: flex;
    flex-flow: column;
    height: 100vh;
}
.resume-body {
    flex: 1;
}
</style>