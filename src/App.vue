<template>
  <div>
    <NavbarComponents></NavbarComponents><br><br>
    <SearchComponents></SearchComponents><br>
    <HeaderPageComponents></HeaderPageComponents><br><br>
     <center>
      <div  class="text-5xl font-extrabold ...">
      <span class="bg-clip-text text-transparent bg-gradient-to-r from-gray-600 to-red-600 ">
        𝐒𝐞𝐥𝐚𝐦𝐚𝐭 𝐃𝐚𝐭𝐚𝐧𝐠 𝐃𝐢 𝐂𝐨𝐟𝐟𝐞 𝐒𝐡𝐨𝐩
      </span><br>
       </div>
      </center><br><br>


      <p><font size=”1″ face=”Verdana”  >
        Kopi adalah tanaman hasil pertanian yang di jadikan minuman hasil seduhan biji kopi yang telah disangrai dan dihaluskan menjadi bubuk.
      Kopi merupakan salah satu komoditas di dunia yang dibudidayakan lebih dari 50 negara. Dua spesies pohon kopi yang dikenal secara umum yaitu Kopi Robusta (Coffea canephora) dan Kopi Arabika (Coffea arabica).
        Proses kopi sebelum dapat diminum melalui proses panjang, yaitu dari pemanenan biji kopi yang telah matang, baik dengan cara mesin maupun dengan tangan,
      kemudian dilakukan pemrosesan biji kopi dan pengeringan sebelum menjadi kopi gelondong. Proses selanjutnya, yaitu penyangraian dengan tingkat derajat yang bervariasi. Setelah penyangraian, biji kopi digiling atau dihaluskan menjadi bubuk kopi sebelum kopi dapat diminum. 
      Sejarah mencatat bahwa penemuan kopi sebagai minuman berkhasiat dan berenergi pertama kali ditemukan oleh bangsa Etiopia di Benua Afrika sekitar 3000 tahun (1000 SM) yang lalu.
      Kopi kemudian terus berkembang hingga saat ini menjadi salah satu minuman paling populer di dunia yang dikonsumsi oleh berbagai kalangan masyarakat.
    Indonesia sendiri telah mampu memproduksi lebih dari 400 ribu ton kopi per tahunnya.
      Di samping rasa dan aromanya yang menarik,kopi juga dapat menurunkan risiko terkena penyakit kanker, diabetes, batu empedu,
        dan berbagai penyakit jantung (kardiovaskuler).
        </font> 
      </p><br><br><br>
      
       <center>
      <div  class="text-5xl font-extrabold ...">
      <span>
       𝑩𝒆𝒔𝒕 𝑪𝒐𝒇𝒇𝒆
      </span><br>
       </div>
      </center>
    <Konten1Components></Konten1Components> <br><br>
    <center>
    <div  class="text-5xl font-extrabold ...">
      <span>
       Coffe Standard
      </span><br>
       </div>
      </center><br>
    <Konten2Components></Konten2Components><br><br>
    <Konten3Components></Konten3Components><br><br><br>
    <FooterComponents></FooterComponents>
  </div>
  
</template>

<script setup>
import NavbarComponents from './components/NavbarComponents.vue';
import HeaderPageComponents from './components/HeaderPageComponents.vue'
import Konten1Components from './components/Konten1Components.vue';
import Konten2Components from './components/Konten2Components.vue';
import Konten3Components from './components/Konten3Components.vue';
import SearchComponents from './components/SearchComponents.vue';
import FooterComponents from './components/FooterComponents.vue';
//import { Dropdown, ListGroup, ListGroupItem } from 'flowbite-vue'
</script>

<style>
h6 {
 font-family: 'Franklin Gothic Medium', 'Arial Narrow', Arial, sans-serif;;
  font-size: 50px;
  
}
</style>