<template>
  <div class="note-selectors">
    <ActiveNoteSelector />
    <OneNoteSelector />
    <TwoNoteSelector />
  </div>
</template>

<script>
  import ActiveNoteSelector from './ActiveNoteSelector.vue'
  import OneNoteSelector from './OneNoteSelector.vue'
  import TwoNoteSelector from './TwoNoteSelector.vue'
  export default {
    components: {
      ActiveNoteSelector,
      OneNoteSelector,
      TwoNoteSelector
    }
  }
</script>