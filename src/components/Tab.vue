<template>
  <div class="row">
    <div class="col">
      <div class="q-gutter-y-md" style="max-width: 600px">
        <q-tabs
          v-model="tab"
          no-caps
          class="bg-black text-white"
        >
          <q-tab name="progresso" label="Progresso"/>
          <q-tab name="aprendendo" label="Aprendendo" />
          <q-tab name="favoritos" label="Favoritos" />
          <q-tab name="sobre" label="Sobre" />
        </q-tabs>
        <q-tab-panels
          v-model="tab"
          animated
          swipeable
          transition-prev="jump-up"
          transition-next="jump-up"
        >
          <q-tab-panel name="progresso" class="bg-black">
            <ProgressTop />
            <GeneralProgress />
            <Medals />
            <Ranking />
          </q-tab-panel>

          <q-tab-panel name="aprendendo">
            <div class="text-h4 q-mb-md">Aprendendo</div>
          </q-tab-panel>

          <q-tab-panel name="favoritos">
            <div class="text-h4 q-mb-md">Favoritos</div>
          </q-tab-panel>
          <q-tab-panel name="sobre">
            <div class="text-h4 q-mb-md">Sobre</div>
          </q-tab-panel>
        </q-tab-panels>
      </div>
    </div>
  </div>
</template>

<script>
import Medals from './Progress/Medals.vue';
import GeneralProgress from './Progress/GeneralProgress.vue';
import ProgressTop from './Progress/ProgressTop.vue';
import Ranking from './Progress/Ranking.vue';

export default {
  name: 'PageIndex',
  components: {
    Medals,
    GeneralProgress,
    ProgressTop,
    Ranking,
  },
  data() {
    return {
      tab: 'progresso',
    };
  },
};
</script>
