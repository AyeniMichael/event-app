<template>
  <div>
    <h1>Events Listing</h1>
    <EventCard />

    <router-link :to="{ name: 'event-show', params: { id: '1' } }"
      >ShowEvent #1</router-link
    >
  </div>
</template>

<script>
import EventCard from '@/components/EventCard.vue'

export default {
  components: {
    EventCard
  }
}
</script>

<style></style>
