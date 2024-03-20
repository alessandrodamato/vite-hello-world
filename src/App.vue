<script>
export default {
  data(){
    return{
      title: 'Vite Hello World!',
      text: 'Lorem ipsum dolor sit amet consectetur adipisicing elit. Nobis quasi cupiditate sequi officiis quae officia repellendus veritatis sed! Aliquam minus deleniti dicta officia molestiae saepe accusantium natus enim beatae aspernatur.'
    }
  }
}
</script>

<template>
  <div>

    <header></header>

    <main>

      <h1>{{ title }}</h1>

      <p>{{ text }}</p>

    </main>

    <footer></footer>

  </div>
</template>


<!-- stili specifici di app.vue -->
<style>
  
  h1, p{
    font-size: 3rem;
    padding: 50px 0;
  }

  p{
    font-size: 1.3rem;
  }

</style>