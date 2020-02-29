<template>
  <div class="songs-container">
    <div class="tab-bar">
      <span class="item active">全部</span>
      <span class="item">华语</span>
      <span class="item">欧美</span>
      <span class="item">日本</span>
      <span class="item">韩国</span>
    </div>
    <!-- 底部的table -->
    <table class="el-table playlit-table">
      <thead>
        <th></th>
        <th></th>
        <th>音乐标题</th>
        <th>歌手</th>
        <th>专辑</th>
        <th>时长</th>
      </thead>
      <tbody>
        <tr class="el-table__row">
          <td>1</td>
          <td>
            <div class="img-wrap">
              <img src="../assets/songCover.jpg" alt="" />
              <span class="iconfont icon-play"></span>
            </div>
          </td>
          <td>
            <div class="song-wrap">
              <div class="name-wrap">
                <span>你要相信这不是最后一天</span>
                <span class="iconfont icon-mv"></span>
              </div>
              <span>电视剧加油练习生插曲</span>
            </div>
          </td>
          <td>华晨宇</td>
          <td>你要相信这不是最后一天</td>
          <td>06:03</td>
        </tr>
        <tr class="el-table__row">
          <td>2</td>
          <td>
            <div class="img-wrap">
              <img src="../assets/songCover.jpg" alt="" />
              <span class="iconfont icon-play"></span>
            </div>
          </td>
          <td>
            <div class="song-wrap">
              <div class="name-wrap">
                <span>你要相信这不是最后一天</span>
                <span class="iconfont icon-mv"></span>
              </div>
            </div>
          </td>
          <td>华晨宇</td>
          <td>你要相信这不是最后一天</td>
          <td>06:03</td>
        </tr>
      </tbody>
    </table>
  </div>
</template>

<script>
export default {
  name: 'songs',
  data() {
    return {
 
    };
  }
};
</script>

<style >

</style>
