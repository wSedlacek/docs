---
title: UnhandledErrorEventData
titleTemplate: "API - NativeScript"
layout: api
seo:
  description: "Event data containing information about unhandled application errors."
---

<!-- This page is auto generated, do not edit manually. -->
<!-- Run "yarn generate:api-docs" to regenerate -->

<script setup lang="ts">
  import { provide } from "vue";
  import API_DATA from "./UnhandledErrorEventData.data.json";
  
  provide('API_DATA', API_DATA);
</script>

<APIRefHierarchy v-once />

<pre class="[&_a]:text-green-400">interface UnhandledErrorEventData extends <a href="/api/interface/ApplicationEventData">ApplicationEventData</a> {
  android: NativeScriptError;
  error: NativeScriptError;
  ios: NativeScriptError;
}</pre>

<APIRefComment commentBase64="eyJibG9ja1RhZ3MiOltdLCJtb2RpZmllclRhZ3MiOnt9LCJzdW1tYXJ5IjpbeyJraW5kIjoidGV4dCIsInRleHQiOiJFdmVudCBkYXRhIGNvbnRhaW5pbmcgaW5mb3JtYXRpb24gYWJvdXQgdW5oYW5kbGVkIGFwcGxpY2F0aW9uIGVycm9ycy4ifV19" v-once />

## <Heading ignore>Summary</Heading>

<APIRefSummary v-once />

## Properties

<div class="isOptional">

<APIRef for="1087" v-once>

<template #title>

### android

</template>

</APIRef>

</div>

<div class="">

<APIRef for="1088" v-once>

<template #title>

### error

</template>

</APIRef>

</div>

<div class="isOptional">

<APIRef for="1086" v-once>

<template #title>

### ios

</template>

</APIRef>

</div>
