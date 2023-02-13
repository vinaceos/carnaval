<template>
<v-row justify="space-around">
    <v-col cols="auto">
      <v-sheet
        elevation="10"
        class="py-4 px-1"
      >
        <v-chip-group
          mandatory
        >
          <v-chip
            v-for="tag in tags"
            :key="tag"
          >
            {{ tag }}
          </v-chip>
        </v-chip-group>
      </v-sheet>
    </v-col>
</v-row>
</template>

<script>
  export default {
    data: () => ({
      tags: [
        '11 de fev',
        '12 de fev',
        '17 de fev',
        '18 de fev',
        '19 de fev',
        '20 de fev',
        '21 de fev',
        '22 de fev',
        '25 de fev',
        '26 de fev',
      ],
    }),
  }
</script>