<template>
  <div id="app">
    <header-box :nav="nav"/>
    <jumbotron-box/>
    <main-box :comics="comics"/>
    <footer-box/>
  </div>
</template>

<script>
import HeaderBox from './components/HeaderBox.vue'
import jumbotronBox from './components/JumbotronBox.vue'
import MainBox from './components/MainBox.vue'
import FooterBox from './components/FooterBox.vue'


export default {
  name: 'App',
  components: {
    HeaderBox,
    jumbotronBox,
    MainBox,
    FooterBox
  },
  data() {
    return {
      nav: [
        {
          id: "LmdC1DBnluad8j8x",
          label: "characters",
          url: "/characters"
        },
        {
          id: "j41FZZYypjSlRXYg",
          label: "comics",
          url: "/comics"
        },
        {
          id: "66X8On66mtrqf40M",
          label: "movies",
          url: "/movies"
        },
        {
          id: "U4iBqAKdf62jBrgI",
          label: "tv",
          url: "/tv"
        },
        {
          id: "1wzWq2vu7ccnQvgC",
          label: "games",
          url: "/games"
        },
        {
          id: "kzTUioGvL667pAxv",
          label: "collectibles",
          url: "/collectibles"
        },
        {
          id: "UZsNc0pdr4cSjT1s",
          label: "videos",
          url: "/videos"
        },
        {
          id: "YlDV1XONJCmyklc7",
          label: "fan",
          url: "/fan"
        },
        {
          id: "pKGQbQHhkFEOrIx6",
          label: "news",
          url: "/news"
        },
        {
          id: "620aF7Aaed6pDgJR",
          label: "shop",
          url: "/shop"
        }
      ],
      comics: [
        {
          id: "vuSaQELjgJf9R5gbS4",
          thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/AC1000_DLX_162-001_HD_5ba13723281ab0.37845353.jpg?itok=ZsI-C5eX",
          price: "$19.99",
          series: "Action Comics",
          type: "comic book"
        },
        {
          id: "Bap33VcgMxgocfQ9u1",
          thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/AV1976_01_300-001_HD_5f738f6e39ddd7.18205602.jpg?itok=VgdYdJ01",
          price: "$3.99",
          series: "American Vampire 1976",
          type: "comic book"
        },
        {
          id: "Hy3lICvNjzXZXagr0Q",
          thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2018/08/AQMv4_UW_153-001_HD_5b7efa1745a9b8.08589135.jpg?itok=HPTtnrsb",
          price: "$16.99",
          series: "Aquaman",
          type: "graphic novel"
        },
        {
          id: "TpMMwx4gaYiPvd5yvx",
          thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/06/batgirl_v5_1_5b23e1f1124941.50950783.jpg?itok=VnrJah76",
          price: "$2.99",
          series: "Batgirl",
          type: "comic book"
        },
        {
          id: "F1C7XsEY48EokX9s38",
          thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          price: "$3.99",
          series: "Batman",
          type: "comic book"
        },
        {
          id: "QiqrQCfgANA3D5OnW0",
          thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2018/09/BM_56_300-001_HD_5ba137a85c3bf3.33122291.jpg?itok=3FHJQYJZ",
          price: "$2.99",
          series: "Batman Beyond",
          type: "comic book"
        },
        {
          id: "JmXk5CLT5O4AXprGKe",
          thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2019/08/BMSM_5d4361b7116261.74371456.jpg?itok=kEDR2OL8",
          price: "$3.99",
          series: "Batman/Superman",
          type: "comic book"
        },
        {
          id: "ELHOAECuGIkp8x9u2C",
          thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMSMANN_01_300-001_HD_5f5ff17fa1d665.74704970.jpg?itok=azz5sfGk",
          price: "$4.99",
          series: "Batman/Superman Annual",
          type: "comic book"
        },
        {
          id: "lSOaAbQJcjhW5kBTvk",
          thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/09/BMTJWZ_01_300-001_HD_5f5ff2307dcb37.34652945.jpg?itok=VswVjLR8",
          price: "$5.99",
          series: "Batman: The Joker War Zone",
          type: "comic book"
        },
        {
          id: "WS1dR09MyWP4CQKklt",
          thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/08/cover-v2_5f40314645a734.37285065.png?itok=ImNM2QBY",
          price: "$6.99",
          series: "Batman: Three Jokers",
          type: "comic book"
        },
        {
          id: "fKlzHunmSryArHHuG3",
          thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/comic-covers/2020/10/BMWK_HQ_01_300-001_HD_5f7cb4945e13f6.89501032.jpg?itok=sVwALbUX",
          price: "$4.99",
          series: "Batman: White Knight Presents: Harley Quinn",
          type: "comic book"
        },
        {
          id: "iwjjTrwzLeyJClBuZH",
          thumb: "https://www.dccomics.com/sites/default/files/styles/covers192x291/public/gn-covers/2019/04/CTWv1_CC_144-001_HD_5ca5299a751963.53054221.jpg?itok=ooPaoLDq",
          price: "$16.99",
          series: "Catwoman",
          type: "graphic novel"
        }
      ]
    }
  }
}  
</script>

<style lang="scss">
@import './style/common.scss';
@import './style/variables.scss';
@import url('https://fonts.googleapis.com/css2?family=Roboto&display=swap');
</style>
