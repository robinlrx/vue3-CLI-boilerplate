<template>
	<h1>this is an about page </h1>
	<button type="button" @click="state.count++">count is: {{ state.count }}</button>
</template>

<script setup>
import { reactive } from "vue";

const state = reactive({ count: 0 });
</script>

<style>
</style>
