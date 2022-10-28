<template>
  <div id="schedule" class="max-w-4xl mx-auto px-4">
    <h2 class="text-white text-3xl font-bold">Schedule</h2>
    <div class="mt-8">
      <div class="bg-gradient-to-r from-[#11252B] to-[#1e293b] px-1 py-2 rounded-lg my-4">
        <p class="text-center text-lg font-bold text-white">Day 1: Nov 01, 2022</p>
      </div>
      <ScheduleEvent :talk="talk" v-for="(talk, index) in dayOne" :key="index" />
      <div class="bg-gradient-to-r from-[#11252B] to-[#1e293b] px-1 py-2 rounded-lg my-4">
        <p class="text-center text-lg font-bold text-white">Day 2: Nov 02, 2022</p>
      </div>
      <ScheduleEvent :talk="talk" v-for="(talk, index) in dayTwo" :key="index" />
    </div>
  </div>
</template>
<script setup>
  const dayOne = ref([
    {
      type: 'talk',
      startTime: '1:00 PM',
      endTime: '1:20 PM',
      title: 'GAMC Workshop 2022 Kick-off',
      people: 'Sherif M.'
    },
    {
      type: 'talk',
      startTime: '1:20 PM',
      endTime: '1:40 PM',
      title: 'Proposed Value Creation Solutions',
      people: 'Peter Z., Annie X.'
    },
    {
      type: 'talk',
      startTime: '1:40 PM',
      endTime: '2:40 PM',
      title: 'Value Creation Playbook',
      people: 'Peter Z., Annie X., Hala E.A.'
    },
    {
      type: 'talk',
      startTime: '2:40 PM',
      endTime: '3:20 PM',
      title: 'Maximum Potential Value',
      people: 'Michael M., Derek C., Jay J.'
    },
    {
      type: 'break',
      title: '3:20 PM - 3:30 PM | Break'
    },
    {
      type: 'talk',
      startTime: '3:30 PM',
      endTime: '4:30 PM',
      title: 'Value Creation Plan & Implementation',
      people: 'Jay J., Annie X.'
    },
    {
      type: 'talk',
      startTime: '4:30 PM',
      endTime: '4:45 PM',
      title: 'Value Creation Playbook',
      people: 'Peter Z., Jay J.'
    },
    {
      type: 'talk',
      startTime: '4:45 PM',
      endTime: '5:00 PM',
      title: 'Value Creation Next Steps',
      people: 'Annie X.'
    },
    {
      type: 'break',
      title: '6:00 PM - 8:00 PM | Team Dinner'
    }
  ])
  const dayTwo = ref([
    {
      type: 'talk',
      startTime: '8:00 AM',
      endTime: '9:00 AM',
      title: 'IDI Presentation',
      people: 'IDI'
    },
    {
      type: 'talk',
      startTime: '9:00 AM',
      endTime: '12:00 PM',
      title: 'Site Tour',
      people: 'Jason P., Peter Z.'
    },
    {
      type: 'break',
      title: '12:00 PM - 1:00 PM | Lunch'
    },
    {
      type: 'talk',
      startTime: '1:00 PM',
      endTime: '1:30 PM',
      title: 'Property Insights, Benchmarking and Optimization',
      people: 'Jay J.'
    },
    {
      type: 'talk',
      startTime: '1:30 PM',
      endTime: '2:20 PM',
      title: 'Asset Management KPIs – Part 1',
      people: 'Nadia C., Annie X.'
    },
    {
      type: 'break',
      title: '2:20 PM - 2:35 PM | Break'
    },
    {
      type: 'talk',
      startTime: '2:35 PM',
      endTime: '3:45 PM',
      title: 'Asset Management KPIs – Part 2',
      people: 'Nadia C., Annie X.'
    },
    {
      type: 'talk',
      startTime: '3:45 PM',
      endTime: '4:45 PM',
      title: 'Enable Portfolio View',
      people: 'Jay J., Annie X.'
    },
    {
      type: 'talk',
      startTime: '4:45 PM',
      endTime: '5:00 PM',
      title: 'Proposed Next Steps',
      people: 'Annie X.'
    },
    {
      type: 'break',
      title: '6:00 PM - 8:00 PM | Team Dinner'
    },
  ])
</script>

<style>

</style>