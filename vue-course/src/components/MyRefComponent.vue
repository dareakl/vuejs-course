<!-- Example 1 -->
<!-- <script setup>
import { ref } from 'vue'
let Count = ref(0)
</script>

<template>
  <h1>Count:{{ Count }}</h1>
  <button @click="Count++">+</button>
  <button @click="Count--">-</button>
</template> -->

<!-- Example 2 -->

<!-- <script setup>
import { ref } from 'vue'
let username = ref('')
</script>

<template>
  <h1>Username:{{ username }}</h1>
  <button @click="username = 'sathish'">Add User</button>
</template> -->

<!-- Example 3 -->

<!-- <script setup>
import { ref } from 'vue'
let userList = ref(['david', 'mike', 'dani'])
</script>

<template>
  <h1>Users list: {{ userList }}</h1>
  <button @click="userList.push('Rooni')">Add user</button>
</template> -->

<!-- Example 4 -->
<!-- <script setup>
import { ref } from 'vue'
let userInfo = ref({ name: 'Alex', age: 20, location: ['NYC', 'IDK'], isMarried: false })
</script>

<template>
  <h1>Name:{{ userInfo.name }}</h1>
  <h1>Age:{{ userInfo.age }}</h1>
  <h1>Location: {{ userInfo.location }}</h1>
  <h1>IsMarried: {{ userInfo.isMarried }}</h1>

  <button @click="userInfo.name = 'Sathish'">ChangeName</button>
  <button @click="userInfo.age = 40">Change Age</button>
  <button @click="userInfo.location = ['heaven', 'leh']">Change Location</button>
  <button @click="userInfo.isMarried = true">Change Status</button>
</template> -->

<!-- Example 5 -->
<script setup>
import { reactive, ref } from 'vue'
let friends = reactive([ref('Doe'), ref('Alex'), ref('Mike')])
</script>

<template>
  <h1>1. {{ friends[0] }}</h1>
  <h1>2. {{ friends[1] }}</h1>
  <h1>3. {{ friends[2] }}</h1>

  <button @click="friends[0] = 'Shaking'">hand Shake</button>
  <button @click="friends[1] = 'Shaking'">hand Shake</button>
  <button @click="friends[2] = 'Shaking'">hand Shake</button>
</template>
