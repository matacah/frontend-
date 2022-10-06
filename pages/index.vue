<template>
<v-data-table
    :headers="headers"
    :items="scores"
    :items-per-page="5"
    class="elevation-1"
  ></v-data-table>
</template>
<script>
  export default {
    data () {
      return {
        headers: [
          {
            text: 'POS',
            align: 'start',
            sortable: false,
            value: 'POS',
          },
          { text: 'TEAM', value: 'TEAM' },
          { text: 'P', value: 'P' },
          { text: 'W', value: 'W' },
          { text: 'D', value: 'D' },
          { text: 'L)', value: 'L' },
          { text: 'F', value: 'F' },
          { text: 'A', value: 'A' },
          { text: 'D', value: "D2"},
          { text: 'pts', value: 'pts'},
        ],
        scores: [
          {
            POS: 1,
            TEAM:'FC Platinum',
            P: 29,
            W:19,
            D:7,
            L:3,
            F:44,
            A:11,
            D2:33,
            pts: 64,
             
          },
         {
            POS: 2,
            TEAM:'chicken Inn',
            P: 29,
            W:16,
            D:6,
            L:3,
            F:37,
            A:25,
            D2:12,
            pts: 54,
             
          },
         {
            POS: 3,
            TEAM:'Dynamos',
            P: 29,
            W:15,
            D:8,
            L:6,
            F:31,
            A:14,
            D2:17,
            pts: 53,
             
          },
      {
            POS: 4,
            TEAM:'Ngezi Platinum',
            P: 29,
            W:12,
            D:10,
            L:7,
            F:35,
            A:18,
            D2:17,
            pts:46,
             
          },
 {
            POS: 5,
            TEAM:'Highlanders',
            P: 29,
            W:11,
            D:12,
            L:6,
            F:39,
            A:26,
            D2:13,
            pts:45,
             
          },
 {
            POS: 6,
            TEAM:'Herentals',
            P: 29,
            W:12,
            D:10,
            L:7,
            F:35,
            A:18,
            D2:17,
            pts:46,
             
          },
 {
            POS: 7,
            TEAM:'Traigle United',
            P: 29,
            W:12,
            D:10,
            L:7,
            F:35,
            A:18,
            D2:17,
            pts:46,
             
          },
 {
            POS: 8,
            TEAM:'Bulawayo Chiefs',
            P: 29,
            W:12,
            D:10,
            L:7,
            F:35,
            A:18,
            D2:17,
            pts:46,
             
          },
 {
            POS: 9,
            TEAM:'Black Rhino',
            P: 29,
            W:12,
            D:10,
            L:7,
            F:35,
            A:18,
            D2:17,
            pts:46,
             
          },
 {
            POS: 10,
            TEAM:'Ngezi Platinum',
            P: 29,
            W:12,
            D:10,
            L:7,
            F:35,
            A:18,
            D2:17,
            pts:46,
             
          },
 {
            POS: 11,
            TEAM:'Manica Diamonds',
            P: 29,
            W:12,
            D:10,
            L:7,
            F:35,
            A:18,
            D2:17,
            pts:46,
             
          },
 {
            POS: 12,
            TEAM:'Cranborne Bullets',
            P: 29,
            W:12,
            D:10,
            L:7,
            F:35,
            D2:17,
            pts:46,
             
          },
        ],
      }
    },
  }
</script>
