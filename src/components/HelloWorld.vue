<template>
  <div class="hello">
    <div class="header">
      <p><span style="color:blue;">风险提示：</span>谨防ICO、变相ICO 丨 观索所发表资讯不代表本公司任何投资暗示。</p>
    </div>
    <el-row>
  <el-col :span="8"><div class="grid-content bg-purple"></div></el-col>
  <el-col :span="8"><div class="grid-content bg-purple-light"></div></el-col>
  <el-col :span="8"><div class="grid-content bg-purple"></div></el-col>
</el-row>
  </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  data () {
    return {
    }
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
*{margin: 0;padding: 0;}
.hello .header{background-color: #ccc;height: 19px; line-height: 19px; text-align: center;opacity:1;}
</style>
