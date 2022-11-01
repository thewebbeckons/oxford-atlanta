<template>
  <div id="schedule" class="max-w-4xl mx-auto px-4">
    <h2 class="text-slate-800 text-4xl lg:text-5xl font-bold mb-4">
      Workshop Agenda
    </h2>
    <div class="">
      <div class=" px-1 py-2 rounded-lg my-4">
        <p class="text-lg font-bold text-slate-600">Day 1: Nov 01, 2022</p>
      </div>
      <ScheduleEvent :talk="talk" v-for="(talk, index) in dayOne" :key="index" />
      <div class="px-1 py-2 rounded-lg my-4">
        <p class="text-lg font-bold text-slate-600">Day 2: Nov 02, 2022</p>
      </div>
      <ScheduleEvent :talk="talk" v-for="(talk, index) in dayTwo" :key="index" />
    </div>
  </div>
</template>
<script setup>
  const dayOne = ref([
    {
      type: 'talk',
      startTime: '1:00',
      endTime: '1:20 PM',
      title: 'GAMC Workshop 2022 Kick-off',
      people: 'Sherif M.'
    },
    {
      type: 'talk',
      startTime: '1:20',
      endTime: '1:40 PM',
      title: 'Proposed Value Creation Solutions',
      people: 'Peter Z. | Annie X.'
    },
    {
      type: 'talk',
      startTime: '1:40',
      endTime: '2:40 PM',
      title: 'Value Creation Playbook',
      people: 'Peter Z. |  Annie X. | Hala E.A.'
    },
    {
      type: 'talk',
      startTime: '2:40',
      endTime: '3:20 PM',
      title: 'Maximum Potential Value',
      people: 'Michael M. | Derek C. | Jay J.'
    },
    {
      type: 'break',
      startTime: '3:20',
      endTime: '3:30 PM',
      title: 'Break'
    },
    {
      type: 'talk',
      startTime: '3:30',
      endTime: '4:30 PM',
      title: 'Avalon Presentation',
      people: 'John K.'
    },
    {
      type: 'talk',
      startTime: '4:30',
      endTime: '4:45 PM',
      title: 'Information Sharing Platform',
      people: 'Peter Z. | Jay J.'
    },
    {
      type: 'talk',
      startTime: '4:45',
      endTime: '5:00 PM',
      title: 'Value Creation Next Steps',
      people: 'Annie X.'
    },
    {
      type: 'break',
      startTime: '6:00',
      endTime: '8:00 PM',
      title: 'Team Dinner'
    },
  ])
  const dayTwo = ref([
    {
      type: 'talk',
      startTime: '8:00',
      endTime: '8:45 AM',
      title: 'IDI Presentation',
      people: 'IDI'
    },
    {
      type: 'talk',
      startTime: '9:00 AM',
      endTime: '12:00 PM',
      title: 'Site Tour',
      people: 'Jason P. | Sherif M.'
    },
    {
      type: 'break',
      startTime: '12:00',
      endTime: '1:00 PM',
      title: 'Lunch'
    },
    {
      type: 'talk',
      startTime: '1:00',
      endTime: '2:00 PM',
      title: 'Value Creation Plan & Implementation',
      people: 'Jay J. | Annie X.'
    },
    {
      type: 'talk',
      startTime: '2:00',
      endTime: '2:30 PM',
      title: 'Property Insights, Benchmarking and Optimization',
      people: 'Jay J.'
    },
    {
      type: 'talk',
      startTime: '2:30',
      endTime: '3:20 PM',
      title: 'Asset Management KPIs – Part 1',
      people: 'Nadia C. | Annie X.'
    },
    {
      type: 'break',
      startTime: '3:20',
      endTime: '3:30 PM',
      title: 'Break'
    },
    {
      type: 'talk',
      startTime: '3:30',
      endTime: '4:30 PM',
      title: 'Asset Management KPIs – Part 2',
      people: 'Nadia C. | Annie X.'
    },
    {
      type: 'talk',
      startTime: '4:30',
      endTime: '5:00 PM',
      title: 'Proposed Next Steps',
      people: 'Annie X.'
    },
    {
      type: 'break',
      startTime: '6:00',
      endTime: '8:00 PM',
      title: 'Team Dinner'
    },
  ])
</script>

<style>

</style>