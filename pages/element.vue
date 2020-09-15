<template>
  <div style="padding: 0 auto; width:800px; margin-left:100px; margin-top: 60px;">
    <div>
      <h1>element ui</h1>
    </div>
    <div>
      <el-button> el-button</el-button>
      <el-button type="primary" icon="el-icon-edit"></el-button>
      <el-button type="primary" icon="el-icon-share"></el-button>
      <el-button type="primary" icon="el-icon-delete"></el-button>
      <el-button type="primary" icon="el-icon-search">搜索</el-button>
      <el-button type="primary">上传<i class="el-icon-upload el-icon--right"></i></el-button>

    </div>

    <div>
      <i class="el-icon-edit"></i>
      <i class="el-icon-share"></i>
      <i class="el-icon-delete"></i>
      <el-button type="primary" icon="el-icon-search">搜索</el-button>
    </div>

    <div>
      <el-link icon="el-icon-edit">编辑</el-link>
      <el-link>查看<i class="el-icon-view el-icon--right"></i> </el-link>
    </div>

    <div>
      <h1>自定义icon</h1>
    </div>
    <div>
      <i class="iconfont iconchart"></i>

      <i class="iconfont icon404"></i>
      <i class="iconfont iconbug"></i>
      <i class="iconfont iconmessage"></i>
      <i class="iconfont iconstar"></i>
      <i class="iconfont iconuser"></i>
      <i class="iconfont iconresource"></i>
    </div>
    <h1>自定义icon结合element使用</h1>
    <div>
      <el-button type="primary" icon="iconfont iconstar"></el-button>
      <el-button type="primary" icon="iconfont iconuser"></el-button>
      <el-button type="primary" icon="iconfont iconresource"></el-button>
    </div>

    <div>
      <el-link icon="iconfont iconedit">编辑</el-link>
      <el-link>查看<i class="iconfont iconzip"></i> </el-link>
    </div>

  </div>

</template>

<script>
  export default {

  }

</script>

<style>

</style>
