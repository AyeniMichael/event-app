<template>
  <div class="event-card" -shadow>
    <span class="eyebrow">@{{ event.time }} on {{ event.date }}</span>
    <h4>{{ event.title }}</h4>
    <span>{{ event.attendees.length }}</span>
  </div>
</template>

<script>
export default {
  data() {
    return {
      event: {
        title: 'Park CleanUp',
        date: 'Tues Aug 19, 2018',
        time: '6:00',
        attendees: [
          { id: 'abc123', name: 'Lekan Kinplus' },
          { id: 'def456', name: 'Ayeni Michael' }
        ]
      }
    }
  }
}
</script>

<style scoped></style>
