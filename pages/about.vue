<template>  
    <div>
        <h1>About Us</h1>
        <p>Lorem ipsum dolor, sit amet consectetur adipisicing elit. Aspernatur, iusto odit temporibus harum dolorem molestiae voluptates quam dolores eligendi ipsum ab modi incidunt accusantium, et rem ratione fuga perferendis numquam.</p>
    </div>
</template>
<script>
export default {
  head() {
    return {
      title: 'Posts | Index',
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