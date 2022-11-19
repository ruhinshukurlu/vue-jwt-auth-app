<script >
import axios from 'axios'

export default {
  async created() {
    const response = await axios.get('auth/user/')
    console.log('user response : ', response);
  },
};
</script>

<template>
  <main>
    <TheWelcome />
  </main>
</template>
