<template>
  <div>
    <!-- <h1 id="htitle">{{ message }}</h1> -->
    <!-- <test-Button></test-Button> -->
     <!-- <user-view></user-view> -->
      <!-- <question-view></question-view> -->
    <router-view></router-view>
  </div>
</template>

<script>
// import QuestionView from './views/elment/QuestionView.vue';
// import TestButton from './views/elment/TestButton.vue';
// import UserView from './views/elment/UserView.vue';

export default {
  components: {
    // QuestionView 
   // UserView 
  },
  data() {
    return {
      message: "hello vue",
    };
  },
  methods: {
  },
};
</script>

<style>
#htitle {
  color: red;
}

#inputnumber {
  margin-top: 20px;
}
</style>