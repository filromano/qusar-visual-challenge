<template>
  <div>
    <h5 class="text-white text-weight-bold">Progresso</h5>
    <div class="row q-col-gutter-lg">
      <div class="col">
        <q-card class="flex flex-center text-center text-white bg-blue-10 rounded-border">
          <q-card-section>
            <div class="text-white">progresso geral</div>
            <q-circular-progress
              show-value
              font-size="20px"
              :value="25"
              size="100px"
              :thickness="0.22"
              color="blue"
              track-color="grey-3"
              class="q-ma-md"
            >
              25%
            </q-circular-progress>
            <div class="text-weight-bold">3 de 12 completados</div>
          </q-card-section>
        </q-card>
      </div>
      <div class="col">
        <q-card class="flex flex-center text-center rounded-border">
          <q-card-section>
            <div class="text-grey">progresso geral</div>
            <q-circular-progress
              show-value
              font-size="20px"
              :value="25"
              size="100px"
              :thickness="0.22"
              color="blue"
              track-color="grey-3"
              class="q-ma-md"
            >
              25%
            </q-circular-progress>
            <div class="text-weight-bold">3 de 12 completados</div>
          </q-card-section>
        </q-card>
      </div>
    </div>
    <div class="row q-col-gutter-lg q-mt-xs">
      <div class="col">
        <q-card class="flex flex-center text-center rounded-border">
          <q-card-section>
            <div class="text-grey">progresso geral</div>
            <q-circular-progress
              show-value
              font-size="20px"
              :value="25"
              size="100px"
              :thickness="0.22"
              color="blue"
              track-color="grey-3"
              class="q-ma-md"
            >
              25%
            </q-circular-progress>
            <div class="text-weight-bold">3 de 12 completados</div>
          </q-card-section>
        </q-card>
      </div>
      <div class="col">
        <q-card class="flex flex-center text-center rounded-border">
          <q-card-section>
            <div class="text-grey">progresso geral</div>
            <q-circular-progress
              show-value
              font-size="20px"
              :value="25"
              size="100px"
              :thickness="0.22"
              color="blue"
              track-color="grey-3"
              class="q-ma-md"
            >
              25%
            </q-circular-progress>
            <div class="text-weight-bold">3 de 12 completados</div>
          </q-card-section>
        </q-card>
      </div>
    </div>
  </div>
</template>
