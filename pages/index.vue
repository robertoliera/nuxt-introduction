<template>
  <h1>Welcome to my first nuxt app</h1>
</template>

<script>
export default {
  head() {
    return {
      title: 'Application Nuxt Posts | Index',
      meta: [
        {
          hid: "description",
          name: "description",
          content: "Website about posts"
        }
      ],
      htmlAttrs: {
        lang: 'es'
      }
    }
  }
}
</script>