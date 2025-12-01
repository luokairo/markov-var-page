<script lang="ts" setup>
import { VueCompareImage } from 'vue3-compare-image';

const frameworkImagePath = './assets/framework.jpg';
</script>

<template>
  <div>
    <el-divider />

    <el-row justify="center">
      <h1 class="section-title">Framework</h1>
    </el-row>

    <el-row justify="center">
      <el-col :xs="24" :sm="20" :md="16" :lg="12" :xl="12">
        <img :src="frameworkImagePath" style="width: 100%; object-fit: contain;" />
      </el-col>
    </el-row>
  </div>
</template>

<style scoped>

</style>