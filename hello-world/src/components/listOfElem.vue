<template>
  <ul>
    <li v-for="elem in myArray" :key="elem.title">
    {{elem.title}} {{ elem.description }} {{elem.content}}
    </li>
  </ul>
</template>
<script>
export default {
  name: 'listofElem',
  data() {
    return {
      myArray: [
        { title: 1, description: 'Home', content: 'Hola' },
        { title: 2, description: 'About', content: 'Buenas' },
        { title: 3, description: 'Contact', content: 'Hasta luego' },
      ],
    };
  },
};
</script>
