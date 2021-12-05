<template>
  <div>
    <h1>Event List</h1>
    <EventCard>
      <p>This is an event card</p></EventCard>
    <BaseIcon><slot></slot></BaseIcon>
  </div>
</template>

<script>

import EventCard from '@/components/EventCard.vue';

export default{
  props:{
    event: Object,
  },
    components: {
        EventCard
    }

}
</script>