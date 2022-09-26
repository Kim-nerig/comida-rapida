<template>

  <cardlogo url="https://png.pngtree.com/png-clipart/20200727/original/pngtree-restaurant-logo-design-vector-template-png-image_5441058.jpg" nombre="Restaurant Food"/>
  <br>
  <br>
  <br>

  <navpage></navpage>

  
  <hr>

  <card url="https://cdn.chefclub.tools/uploads/recipes/cover-thumbnail/8eac954b-fd48-403e-b691-a3dd6a8955d6_Xlv242Z.jpg"
   nombre="Hamburguesa" precio="$120" descripcion="Deliciosa hamburguesa rellena con queso" />
  <card url="https://www.lavanguardia.com/files/og_thumbnail/files/fp/uploads/2021/03/30/6063031b90a87.r_d.1083-871-0.jpeg"
   nombre="Pizza quesos" precio="$120" descripcion="Crujiente pizza al horno de quesos" />
  <card url="https://cdn.colombia.com/gastronomia/2011/08/25/espaguetis-a-la-bolonesa-3686.jpg"
   nombre="Pasta a la boloñesa" precio="$120" descripcion="Exquisita pasta con nuestra receta a la boloñesa" />
  <card url="https://www.lavanguardia.com/files/og_thumbnail/uploads/2020/05/29/5ed11fb61d750.jpeg"
   nombre="Pasta al pesto" precio="$120" descripcion="Deliciosa pasta tradicional con un toque de pesto" />
  <card url="https://rockyspizzeria.mx/wp-content/uploads/2021/02/gajos.jpg"
   nombre="Papas gajo" precio="$120" descripcion="Papas crujientes y condimentadas" />
  <card url="https://www.cardamomo.news/__export/1613939362136/sites/debate/img/2021/02/21/whatsapp_image_2021-02-21_at_13_19_51_crop1613938827952.jpeg_976912859.jpeg"
   nombre="Papas a la francesa" precio="$120" descripcion="Las clasica papas a la francesa pero más ricas" />

  <br>
  <br>
  <br>

  <footpage></footpage>

  <br>
  <br>
  <br>
  
  

</template>

<script>
  import Card from "./components/Card.vue";
import Cardlogo from "./components/Cardlogo.vue";
import Navpage from "./components/Navpage.vue";
import Footpage from "./components/Footpage.vue";
  
  
  export default {
    components: { Card, Cardlogo, Navpage, Footpage },
  };
  
</script>


