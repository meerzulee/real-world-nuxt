<template>
    <div>
        <h1>Create Event</h1>
    </div>
</template>
<script>
export default {
  head() { // <-- property used by vue-meta to add header tags
    return {
      title: 'Create an Event - Real World Events', // <-- For our title tag
      meta: [
        {
          hid: 'description',
          name: 'description', // <-- for our meta description tag
          content:
            'create and event in your neighborhood'
        }
      ]
    }
  }
}
</script>