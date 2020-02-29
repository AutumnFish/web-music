<template>
  <div class="discovery-container">
    <!-- 轮播图 -->
    <el-carousel class="" :interval="4000" type="card">
      <el-carousel-item v-for="item in 6" :key="item">
        <img src="../assets/banner.jpg" alt="" />
      </el-carousel-item>
    </el-carousel>
    <!-- 推荐歌单 -->
    <div class="recommend">
      <h3 class="title">
        推荐歌单
      </h3>
      <div class="items">
        <div class="item">
          <div class="img-wrap">
            <div class="desc-wrap">
              <span class="desc">编辑推荐：一起探索这个未知的音乐罐头吧！</span>
            </div>
            <img src="../assets/cover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <p class="name">编辑推荐：一起探索这个未知的音乐罐头吧！</p>
        </div>
        <div class="item">
          <div class="img-wrap">
            <div class="desc-wrap">
              <span class="desc">编辑推荐：一起探索这个未知的音乐罐头吧！</span>
            </div>
            <img src="../assets/cover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <p class="name">编辑推荐：一起探索这个未知的音乐罐头吧！</p>
        </div>
        <div class="item">
          <div class="img-wrap">
            <div class="desc-wrap">
              <span class="desc">编辑推荐：一起探索这个未知的音乐罐头吧！</span>
            </div>
            <img src="../assets/cover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <p class="name">编辑推荐：一起探索这个未知的音乐罐头吧！</p>
        </div>
        <div class="item">
          <div class="img-wrap">
            <div class="desc-wrap">
              <span class="desc">编辑推荐：一起探索这个未知的音乐罐头吧！</span>
            </div>
            <img src="../assets/cover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <p class="name">编辑推荐：一起探索这个未知的音乐罐头吧！</p>
        </div>
        <div class="item">
          <div class="img-wrap">
            <div class="desc-wrap">
              <span class="desc">编辑推荐：一起探索这个未知的音乐罐头吧！</span>
            </div>
            <img src="../assets/cover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <p class="name">编辑推荐：一起探索这个未知的音乐罐头吧！</p>
        </div>
        <div class="item">
          <div class="img-wrap">
            <div class="desc-wrap">
              <span class="desc">编辑推荐：一起探索这个未知的音乐罐头吧！</span>
            </div>
            <img src="../assets/cover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <p class="name">编辑推荐：一起探索这个未知的音乐罐头吧！</p>
        </div>
        <div class="item">
          <div class="img-wrap">
            <div class="desc-wrap">
              <span class="desc">编辑推荐：一起探索这个未知的音乐罐头吧！</span>
            </div>
            <img src="../assets/cover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <p class="name">编辑推荐：一起探索这个未知的音乐罐头吧！</p>
        </div>
        <div class="item">
          <div class="img-wrap">
            <div class="desc-wrap">
              <span class="desc">编辑推荐：一起探索这个未知的音乐罐头吧！</span>
            </div>
            <img src="../assets/cover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <p class="name">编辑推荐：一起探索这个未知的音乐罐头吧！</p>
        </div>
        <div class="item">
          <div class="img-wrap">
            <div class="desc-wrap">
              <span class="desc">编辑推荐：一起探索这个未知的音乐罐头吧！</span>
            </div>
            <img src="../assets/cover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <p class="name">编辑推荐：一起探索这个未知的音乐罐头吧！</p>
        </div>
        <div class="item">
          <div class="img-wrap">
            <div class="desc-wrap">
              <span class="desc">编辑推荐：！</span>
            </div>
            <img src="../assets/cover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <p class="name">编辑推荐：一起探索这个未知的音乐罐头吧！</p>
        </div>
      </div>
    </div>
    <!-- 最新音乐 -->
    <div class="news">
      <h3 class="title">
        最新音乐
      </h3>
      <div class="items">
        <div class="item">
          <span class="index">01</span>
          <div class="img-wrap">
            <img src="../assets/songCover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <div class="song-wrap">
            <div class="song-name">小王日记</div>
            <div class="singer">毛不易</div>
          </div>
        </div>
        <div class="item">
          <span class="index">01</span>
          <div class="img-wrap">
            <img src="../assets/songCover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <div class="song-wrap">
            <div class="song-name">小王日记</div>
            <div class="singer">毛不易</div>
          </div>
        </div>
        <div class="item">
          <span class="index">01</span>
          <div class="img-wrap">
            <img src="../assets/songCover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <div class="song-wrap">
            <div class="song-name">小王日记</div>
            <div class="singer">毛不易</div>
          </div>
        </div>
        <div class="item">
          <span class="index">01</span>
          <div class="img-wrap">
            <img src="../assets/songCover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <div class="song-wrap">
            <div class="song-name">小王日记</div>
            <div class="singer">毛不易</div>
          </div>
        </div>
        <div class="item">
          <span class="index">01</span>
          <div class="img-wrap">
            <img src="../assets/songCover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <div class="song-wrap">
            <div class="song-name">小王日记</div>
            <div class="singer">毛不易</div>
          </div>
        </div>
        <div class="item">
          <span class="index">01</span>
          <div class="img-wrap">
            <img src="../assets/songCover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <div class="song-wrap">
            <div class="song-name">小王日记</div>
            <div class="singer">毛不易</div>
          </div>
        </div>
        <div class="item">
          <span class="index">01</span>
          <div class="img-wrap">
            <img src="../assets/songCover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <div class="song-wrap">
            <div class="song-name">小王日记</div>
            <div class="singer">毛不易</div>
          </div>
        </div>
        <div class="item">
          <span class="index">01</span>
          <div class="img-wrap">
            <img src="../assets/songCover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <div class="song-wrap">
            <div class="song-name">小王日记</div>
            <div class="singer">毛不易</div>
          </div>
        </div>
        <div class="item">
          <span class="index">01</span>
          <div class="img-wrap">
            <img src="../assets/songCover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <div class="song-wrap">
            <div class="song-name">小王日记</div>
            <div class="singer">毛不易</div>
          </div>
        </div>
        <div class="item">
          <span class="index">01</span>
          <div class="img-wrap">
            <img src="../assets/songCover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
          </div>
          <div class="song-wrap">
            <div class="song-name">小王日记</div>
            <div class="singer">毛不易</div>
          </div>
        </div>
      </div>
    </div>
    <!-- 推荐MV -->
    <div class="mvs">
      <h3 class="title">推荐MV</h3>
      <div class="items">
        <div class="item">
          <div class="img-wrap">
            <img src="../assets/mvCover.jpg" alt="" />
            <span class="iconfont icon-play"></span>
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
            <span class="iconfont icon-play"></span>
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
            <span class="iconfont icon-play"></span>
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
            <span class="iconfont icon-play"></span>
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
    </div>
  </div>
</template>

<script>
export default {
  name: 'discovery'
};
</script>

<style >

</style>
