<template>
  <h1 :class="myClasses.anotherClass">Using Module CSS with $ syntax (camelVase)</h1>
</template>

<style module="myClasses">
.m-class {
  background: firebrick;
  color: white;
}
.anotherClass {
  background: seagreen;
  color: white;
}
</style>
