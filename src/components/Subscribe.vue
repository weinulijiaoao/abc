<template>
  <div>
    <mt-field label="用户名" placeholder="请输入用户名" v-model="username"></mt-field>
    <mt-field label="手机号" placeholder="请输入手机号" type="tel" v-model="phone"></mt-field>
    <mt-button type="primary" @click.native="handleClick">提交预约</mt-button>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  methods: {
    handleClick: function () {
      this.$toast('预约成功!')
    }
  },
  data: function () {
    return {
      username: '',
      phone: ''
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
</style>
