<template>
    <div >
    <h1>Input Echoer</h1>
     <input v-model="message" placeholder="edit me">
     <p>Message is: {{ message }}</p>
  
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    message: String
  }
}
</script>
