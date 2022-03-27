<template>
	<div class="container px-4 sm:px-8">
  <div class="py-8">
    <div class="-mx-4 sm:-mx-8 px-4 sm:px-8 py-4 overflow-x-auto">
      <div
        class="inline-block min-w-full shadow-md rounded-lg overflow-hidden"
      >
        <table class="min-w-full leading-normal">
          <thead>
            <tr>
              <th
                class="px-5 py-3 border-b-2 border-gray-200 bg-gray-100 text-left text-xs font-semibold text-gray-900 uppercase tracking-wider text-center" colspan="3"
              >
                Block B - UNIT 101, 102
              </th>
            </tr>
          </thead>
          <tbody>
            
            <tr v-for="item in tableData" :key="item">
              <td class="px-5 py-5 border-b border-gray-200 bg-white text-sm">
              {{ item.id }}
              </td>
              <td class=" py-5 border-b border-gray-200 bg-white text-sm text-left">
              {{ item.name }}</td>
              <td class="px-5 py-5 border-b border-gray-200 bg-white text-sm text-left">
                {{ item.size }}
                <br>
                <span v-if="item.newSize">{{ item.newSize }} (UNIT - 103) </span>
              </td>
            </tr>
            
          </tbody>
        </table>
      </div>
    </div>
  </div>
</div>
</template>
<script setup>
import { ref } from 'vue'
const tableData = ref({
  0:{
    id: '01',
    name: "Vestibule",
    size: "6'7'' x 3'10''",
    newSize: "6'4'' x 5'10''"
  },
  1:{
    id: '02',
    name: "Living",
    size: "12'0'' x 19'0''",
    newSize: "19'0'' x 12'0''",
  },
  2:{
    id: '2A',
    name: "Verandah",
    size: "12'0'' x 5'0''",
    newSize: "5'0'' x 12'0''",
  },
  3:{
    id: '03',
    name: "Dining",
    size: "12'4'' x 10'0''",
    newSize: "10'00'' x 12'7''",
  },
  4:{
    id: '04',
    name: "Kitchen",
    size: "12'0'' x 10'7''",
    newSize: "11'5'' x 11'12''",
  },
  5:{
    id: '4A',
    name: "Store",
    size: "5'0'' x 7'3''",
    newSize: "5'11'' x 5'0''",
  },
    6:{
    id: '4B',
    name: "Kitchen yard",
    size: "9'0'' x 5'3''",
    newSize: "10'8'' x 5'0''",
  },
    7:{
    id: '05',
    name: "Guest Bedroom 1",
    size: "12'0'' x 11'0''",
  },
    8 :{
    id: '06',
    name: "Guest Toilet",
    size: "5'1'' x 7'3''",
    newSize: "7'8'' x 5'0''",
  },
    9 :{
    id: '07',
    name: "Master Bedroom 2",
    size: "11'0'' x 15'0''",  
  },
    10 :{
    id: '7A',
    name: "Toilet",
    size: "5'0'' x 11'0''",
    newSize: "11'0'' x 5'2''",
  },
    11 :{
    id: '08',
    name: "Master Bedroom 3",
    size: "16'0'' x 11'0''",
    newSize: "11'0'' x 16'0''",
  },
    12 :{
    id: '6A',
    name: "Toilet",
    size: "5'5'' x 11'0''",
    newSize: "5'5'' x 11'0''",
  },
})
</script>