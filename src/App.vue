<script setup>
  import ListCourse from "./components/Baitap/bt1/ListCourse.vue";
  import ColorBox from "./components/Baitap/bt2/ColorBox.vue";
  import Card from "./components/Baitap/bt3/Card.vue";
  import Calculation from "./components/Baitap/bt4/Calculation.vue"
  import UserInfo from "./components/Baitap/bt5/UserInfo.vue";
  import FormatName from "./components/Baitap/bt6/FormatName.vue";
  import AdminIndex from "./components/Baitap/bt7/AdminIndex.vue";
  import UserLayout from "./components/Baitap/bt8/UserLayout.vue"
</script>

<template>
  <div>
    <list-course></list-course>
    <div>
      <ColorBox color="red" />
      <ColorBox color="blue" />
      <ColorBox color="green" />
    </div>
    <Card></Card>
    <Calculation></Calculation>
    <UserInfo></UserInfo>
    <format-name></format-name>
    <admin-index></admin-index>
    <user-layout></user-layout>
  </div>
</template>