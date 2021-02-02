<template>
  <div class="home">
      <HomeTitle/>
      <MainForm/>
  </div>
</template>

<script>
// @ is an alias to /src
import MainForm from './HomeForm'
import HomeTitle from './HomeTitle'

export default {
  name: 'Home',
  components: {
    MainForm,
    HomeTitle
  }
}
</script>
