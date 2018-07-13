<template lang="html">
  <div class="con-select-example">
    <vs-select
      vs-autocomplete="true"
      class="selectExample"
      label="Figuras"
      v-model="select4"
    >
      <vs-select-item :key="index" :vs-value="item.value" :vs-text="item.text" v-for="item,index in options4" />
    </vs-select>
    <vs-select
      class="selectExample"
      vs-autocomplete="true"
      label="Figuras"
      v-model="select2"
    >
      <vs-select-item :key="index" :vs-value="item.value" :vs-text="item.text" v-for="item,index in options2" />
    </vs-select>
    <vs-select
      disabled="true"
      class="selectExample"
      label="Figuras"
      v-model="select3"
    >
      <vs-select-item :key="index" :disabled="index==2" :vs-value="item.value" :vs-text="item.text" v-for="item,index in options3" />
    </vs-select>
  </div>
</template>

<script>
  // import vsSelect from '@/components/vsSelect/vsSelect'

  export default {
    name: 'Select' ,
    // components: {
    //   vsSelect
    // },
    data(){
      return {
        select1:3,
        select2:19,
        select3:2,
        select4:16,
        options1:[
          {text:'IT',value:0},
          {text:'Blade Runner',value:2},
          {text:'Thor Ragnarok',value:3},
        ],
        options2:[
          {text: '가공식품>즉석/편의식품>편의식품>기타편의식품', value: 1},
          {text: '가공식품>즉석/편의식품>편의식품>시리얼', value: 2},
          {text: '가공식품>즉석/편의식품>편의식품>샐러드류', value: 3},
          {text: '가공식품>즉석/편의식품>편의식품>도시락류', value: 4},
          {text: '가공식품>즉석/편의식품>편의식품>김밥', value: 5},
          {text: '가공식품>즉석/편의식품>즉석/조리식품>기타즉석/조리식품', value: 6},
          {text: '가공식품>즉석/편의식품>즉석/조리식품>즉석국/찌개류', value: 7},
          {text: '가공식품>즉석/편의식품>즉석/조리식품>즉석탕류/식육제품류', value: 8},
          {text: '가공식품>즉석/편의식품>즉석/조리식품>즉석반찬류', value: 9},
          {text: '가공식품>즉석/편의식품>즉석/조리식품>즉석 죽/밥류', value: 10},
          {text: '가공식품>즉석/편의식품>즉석/조리식품>즉석스프', value: 11},
          {text: '가공식품>즉석/편의식품>즉석/조리식품>즉석카레류', value: 12},
          {text: '가공식품>분말류>기타분말류>기타분말류', value: 13},
          {text: '가공식품>분말류>농산물분말류>기타농산물분말류', value: 14},
          {text: '가공식품>분말류>농산물분말류>찹쌀가루', value: 15},
          {text: '가공식품>분말류>농산물분말류>콩가루', value: 16},
          {text: '가공식품>분말류>농산물분말류>미숫가루', value: 17},
          {text: '가공식품>분말류>농산물분말류>전분', value: 18},
          {text: '가공식품>분말류>소스분말류>기타소스분말류', value: 19},


        ],
        options3:[
          {text: 'Red', value: 1},
          {text: 'Green', value: 2},
          {text: 'Blue', value: 3},
          {text: 'Purple', value: 4},
        ],
        options4:[
          {text: '볼빨간사춘기', value: 1},
          {text: '위너', value: 2},
          {text: '고래밥', value: 3},
          {text: '버터구이오징어', value: 4},
          {text: '늘솜', value: 5},
          {text: '맥북뉴버젼', value: 6},
          {text: '아이폰6+', value: 7},
          {text: '삼성실버모니터', value: 8},
          {text: '킨스타워20층', value: 10},
          {text: '으아아아아', value: 11},
          {text: '빨강주황노랑초록파랑남보라', value: 12},
          {text: '카카오톡그만보내이놈들아', value: 13},
          {text: '아이폰아이패드맥북맥아이패드미니', value: 14},
          {text: '칫솔치약', value: 15},
          {text: '중소기업지원시책', value: 16},
          {text: '으아아아아아아아아아앙아', value: 17},
        ],
      }
    },
  }
</script>

<style>

</style>
