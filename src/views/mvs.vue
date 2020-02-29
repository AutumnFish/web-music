<template>
  <div class="mvs-container">
    <div class="filter-wrap">
      <div class="seciton-wrap">
        <span class="section-type">地区:</span>
        <ul class="tabs-wrap">
          <li class="tab">
            <span class="title active">全部</span>
          </li>
          <li class="tab">
            <span class="title">内地</span>
          </li>
          <li class="tab">
            <span class="title">港台</span>
          </li>
          <li class="tab">
            <span class="title">欧美</span>
          </li>
          <li class="tab">
            <span class="title">日本</span>
          </li>
          <li class="tab">
            <span class="title">韩国</span>
          </li>
        </ul>
      </div>
      <div class="type-wrap">
        <span class="type-type">类型:</span>
        <ul class="tabs-wrap">
          <li class="tab">
            <span class="title ">全部</span>
          </li>
          <li class="tab">
            <span class="title">官方版</span>
          </li>
          <li class="tab">
            <span class="title active">原声</span>
          </li>
          <li class="tab">
            <span class="title">现场版</span>
          </li>
          <li class="tab">
            <span class="title">网易出品</span>
          </li>
        </ul>
      </div>
      <div class="order-wrap">
        <span class="order-type">排序:</span>
        <ul class="tabs-wrap">
          <li class="tab">
            <span class="title ">上升最快</span>
          </li>
          <li class="tab">
            <span class="title">最热</span>
          </li>
          <li class="tab">
            <span class="title active">最新</span>
          </li>
        </ul>
      </div>
    </div>
    <!-- mv容器 -->
    <!-- 推荐MV -->
    <div class="mvs">
      <div class="items">
        <div class="item" @click="toMv(10)">
          <div class="img-wrap">
            <img src="../assets/mvCover.jpg" alt="" />
            <div class="num-wrap">
              <div class="iconfont icon-play"></div>
              <div class="num">9912</div>
            </div>
          </div>
          <div class="info-wrap">
            <div class="name">HEYNA</div>
            <div class="singer">余恩</div>
          </div>
        </div>
        <div class="item">
          <div class="img-wrap">
            <img src="../assets/mvCover.jpg" alt="" />
            <div class="num-wrap">
              <div class="iconfont icon-play"></div>
              <div class="num">9912</div>
            </div>
          </div>
          <div class="info-wrap">
            <div class="name">HEYNA</div>
            <div class="singer">余恩</div>
          </div>
        </div>
        <div class="item">
          <div class="img-wrap">
            <img src="../assets/mvCover.jpg" alt="" />
            <div class="num-wrap">
              <div class="iconfont icon-play"></div>
              <div class="num">9912</div>
            </div>
          </div>
          <div class="info-wrap">
            <div class="name">HEYNA</div>
            <div class="singer">余恩</div>
          </div>
        </div>
        <div class="item">
          <div class="img-wrap">
            <img src="../assets/mvCover.jpg" alt="" />
            <div class="num-wrap">
              <div class="iconfont icon-play"></div>
              <div class="num">9912</div>
            </div>
          </div>
          <div class="info-wrap">
            <div class="name">HEYNA</div>
            <div class="singer">余恩</div>
          </div>
        </div>
        <div class="item">
          <div class="img-wrap">
            <img src="../assets/mvCover.jpg" alt="" />
            <div class="num-wrap">
              <div class="iconfont icon-play"></div>
              <div class="num">9912</div>
            </div>
          </div>
          <div class="info-wrap">
            <div class="name">HEYNA</div>
            <div class="singer">余恩</div>
          </div>
        </div>
        <div class="item">
          <div class="img-wrap">
            <img src="../assets/mvCover.jpg" alt="" />
            <div class="num-wrap">
              <div class="iconfont icon-play"></div>
              <div class="num">9912</div>
            </div>
          </div>
          <div class="info-wrap">
            <div class="name">HEYNA</div>
            <div class="singer">余恩</div>
          </div>
        </div>
      </div>
      <!-- 分页器 -->
      <el-pagination
        @current-change="handleCurrentChange"
        background
        layout="prev, pager, next"
        :total="total"
        :current-page="page"
        :page-size="5"
        :limit="limit"
      >
      </el-pagination>
    </div>
  </div>
</template>

<script>
export default {
  name: 'mvs',
  data() {
    return {
      // 总条数
      total: 20,
      // 页码
      page: 1,
      // 页容量
      limit: 10
    };
  },
  methods: {
    toMv(id) {
      this.$router.push(`/mv?id=${id}`);
    },
    handleCurrentChange(val) {
      console.log(`当前页: ${val}`);
    }
  }
};
</script>

<style >

</style>
