<template>
  <q-page class="bg-black">
    <ProfileHeader />
    <Tabs />
  </q-page>
</template>

<script>
import ProfileHeader from '../components/ProfileHeader.vue';
import Tabs from '../components/Tab.vue';

export default {
  name: 'PageIndex',
  components: {
    ProfileHeader,
    Tabs,
  },
};
</script>
