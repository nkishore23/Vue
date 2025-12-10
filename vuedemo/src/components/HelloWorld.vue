<script>
export default {
  data () {
    return {
      count: 0
    };
  },
    methods: {
      increment() {
        this.count++;
      },
      decrement() {
        this.count--;
      },
      reset() {
        this.count = 0
      },
      maxValue() {
        this.count = 10;
      }
    }
};
</script>

<template>


<h2>{{count}}</h2>
  <div class="card">
    <button type="button" @click="increment">Increment</button>

    <button type="button" @click="decrement">Decrement</button>

    <button type="button" @click="reset">Reset</button>

    <button type="button" @click="maxValue">Max Value</button>
   
  </div>

  
</template>

<style scoped>
.read-the-docs {
  color: #888;
}
</style>
