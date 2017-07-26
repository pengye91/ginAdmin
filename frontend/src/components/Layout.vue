<template>
  <div id="layout">
    <el-row type="flex" id="horizon-menu" justify="center" align="middle">
      <el-col span="3" v-for="">

      </el-col>

    </el-row>
  </div>
</template>

<script>
  export default {
    data () {
      return {
          top
      }
    },
    methods: {
      startHacking () {
        this.$notify({
          title: 'It Works',
          message: 'We have laid the groundwork for you. Now it\'s your time to build something epic!',
          duration: 6000
        })
      }
    }
  }
</script>

<style>
</style>


