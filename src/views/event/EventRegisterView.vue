<template>
  <!-- <div v-if="event">
    <h1>{{ event.title }}</h1>
    <div id="nav">
      <router-link :to="{ name: 'EventDetails', params: { id } }"
        >Details</router-link
      >
      |
      <router-link :to="{ name: 'EventRegister', params: { id } }"
        >Register</router-link
      >
      |
      <router-link :to="{ name: 'EventEdit', params: { id } }"
        >Edit</router-link
      >
    </div> -->
  <p>Registration form here</p>
  <!-- </div> -->
</template>

<script>
// import EventService from '@/services/EventService'
export default {
  // props: ['id'],
  // data() {
  //   return {
  //     event: null
  //   }
  // },
  // created() {
  //   // fetch event (by id) and set local event data
  //   EventService.getEvent(this.id)
  //     .then((response) => {
  //       this.event = response.data
  //     })
  //     .catch((error) => {
  //       console.log(error)
  //     })
  // }
  props: ['events']
}
</script>
