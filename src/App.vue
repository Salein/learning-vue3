<!-- <script >
export default {
  data () {
    return {
      text: 'Anna Kendrik',
      href: 'data:image/jpeg;base64,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'
    }
  }
}
</script> -->

<!-- <template>
  short <img :src="href">
  <img v-bind:src="href">
  <div>{{ text }}</div>
</template> -->

<!-- <script>
export default {
  data() {
    return {
      num1: 2,
      num2: 3,
      num3: 4
    }
  }
}
</script>


<template>
  {{ num1 + num2 + num3 }}  
</template> -->

<!-- <script>
export default {
  data () {
    return {
      obj: {x: 2, y: 2, z: 3}
    }
  }
}
</script>

<template>
  {{ obj.x + obj.y + obj.z}}
</template>

<style scoped>

</style> -->


<!-- <script>
export default {
  data() {

    },
    methods: {
      showDate: function() {
        alert(new Date())
      }
    }
  }

</script>

<template>
  {{ showDate() }}
</template>

<style scoped>

</style> -->


<!-- <script>
export default {
  data() {

    },
    methods: {
      showDate: function() {
        alert(new Date())
      }
    }
  }
  
</script>

<template>
   <button @click="showDate">Click</button> - short record
  <button v-on:click="showDate">Click</button>
</template>

<style scoped>

</style> -->

<!-- <script>
export default {
  data() {
    return {
      text: 'hello',
    }
    },
    methods: {
      showText: function() {
        let text = this.caps(this.text)
        alert(text)
      },
      caps: function(str) {
        return str.toUpperCase()
      }
    }
  }
  
</script>

<template>
  <button v-on:click="showText">Click</button>
</template>

<style scoped>

</style> -->

<script>
export default {
  data() {
    return {
      sum: 3
    }
    },
    methods: {
      x: function() {
        this.sum *= 2
      }
    }
  }
  
</script>

<template>
  <div>{{ sum }}</div>
  <button @click="x(2)">Click</button>
</template>

<style scoped>

</style>