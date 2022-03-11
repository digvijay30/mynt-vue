<template>
  <div class="container">
     <AppHeader/>
  </div>
</template>

<script>
import AppHeader from './components/AppHeader';
export default {
  name: 'App',
  components:{
    AppHeader
  }
}
</script>

<style>

:root
{
  --sizing-padding:0 7rem 0 7rem;
  --dark-black:#343a40;
  --gray:gray;
  --bg-color:gray;
  --primary-font-color:white;
  --secondary-font-color:gray;

  --flex-primary-gap:0.5rem;
  --flex-secondary-gap:1rem;
  --flex-large-gap:1.5rem;

  --font-size-h3:14px;
  --font-size-h2:20px;
  --font-size-h4:12px;

}

*{
  padding: 0;
  margin: 0;
  font-family:Arial, Helvetica, sans-serif;
}

/* flex common css class */

.flex {
  display: flex;
}

.flex-center
{
   justify-content: center;
   align-items: center;
}
.justify-center {
  justify-content: center;
}
.align-items {
  align-items: center;
}

.sizing {
  justify-content: space-between;
}

</style>

