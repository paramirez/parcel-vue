<template>
  <div>
      <h1>{{text}}</h1>
  </div>
</template>

<script>
export default {
	data() {
		return {
			text: 'Parcel Vue App'
		};
	}
};
</script>

<style {{#sass}} lang="scss" {{/sass}}>
body {
	font-family: sans-serif;
}
h1 {
	color: #444;
}
</style>
