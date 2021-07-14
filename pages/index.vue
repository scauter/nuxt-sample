<template>
    <div>
        <Top />
        <v-divider></v-divider>
        <Profile />
        <v-divider></v-divider>
        <History />
        <v-divider></v-divider>
        <Work />
        <v-divider></v-divider>
        <Contact />
    </div>
</template>
<script>
import Top from '~/components/Top'
import Profile from '~/components/Profile'
import History from '~/components/History'
import Work from '~/components/Work'
import Contact from '~/components/Contact'

export default {
  components: {
    Top,
    Profile,
    History,
    Work,
    Contact
  }
}
</script>