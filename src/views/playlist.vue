<template>
  <div class="playlist-container">
    <div class="top-wrap">
      <div class="img-wrap">
        <img src="../assets/playListCover.jpg" alt="" />
      </div>
      <div class="info-wrap">
        <p class="title">俗世里的烟火气|总有些瞬间 让你热泪盈眶</p>
        <div class="author-wrap">
          <img class="avatar" src="../assets/avatar.jpg" alt="" />
          <span class="name">原创君</span>
          <span class="time">2020-2-26 创建</span>
        </div>
        <div class="play-wrap">
          <span class="iconfont icon-circle-play"></span>
          <span class="text">播放全部</span>
        </div>
        <div class="tag-wrap">
          <span class="title">标签:</span>
          <ul>
            <li>华语</li>
            <li>怀旧</li>
            <li>感动</li>
          </ul>
        </div>
        <div class="desc-wrap">
          <span class="title">简介:</span>
          <span class="desc"
            >你是否曾在某个瞬间 被一次日落击中心中最柔软的部分 曾在回家途中
            被袅袅升起的饭菜香味感动得热泪盈眶？ 生活或许有时不尽如人意
            却总有一些叫“烟火气”的东西 使得我们在这个俗世中 依然保持希望
            封面来自网络</span
          >
        </div>
      </div>
    </div>
    <el-tabs v-model="activeIndex">
      <el-tab-pane label="歌曲列表" name="1">
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
      </el-tab-pane>
      <el-tab-pane label="评论(66)" name="2">
        <!-- 精彩评论 -->
        <div class="comment-wrap">
          <p class="title">精彩评论<span class="number">(666)</span></p>
          <div class="comments-wrap">
            <div class="item">
              <div class="icon-wrap">
                <img src="../assets/avatar.jpg" alt="" />
              </div>
              <div class="content-wrap">
                <div class="content">
                  <span class="name">爱斯基摩：</span>
                  <span class="comment">谁说的，长大了依旧可爱哈</span>
                </div>
                <div class="re-content">
                  <span class="name">小苹果：</span>
                  <span class="comment">还是小时候比较可爱</span>
                </div>
                <div class="date">2020-02-12 17:26:11</div>
              </div>
            </div>
          </div>
        </div>
        <!-- 最新评论 -->
        <div class="comment-wrap">
          <p class="title">最新评论<span class="number">(666)</span></p>
          <div class="comments-wrap">
            <div class="item">
              <div class="icon-wrap">
                <img src="../assets/avatar.jpg" alt="" />
              </div>
              <div class="content-wrap">
                <div class="content">
                  <span class="name">爱斯基摩：</span>
                  <span class="comment">谁说的，长大了依旧可爱哈</span>
                </div>
                <div class="re-content">
                  <span class="name">小苹果：</span>
                  <span class="comment">还是小时候比较可爱</span>
                </div>
                <div class="date">2020-02-12 17:26:11</div>
              </div>
            </div>
            <div class="item">
              <div class="icon-wrap">
                <img src="../assets/avatar.jpg" alt="" />
              </div>
              <div class="content-wrap">
                <div class="content">
                  <span class="name">爱斯基摩：</span>
                  <span class="comment">谁说的，长大了依旧可爱哈</span>
                </div>
                <div class="re-content">
                  <span class="name">小苹果：</span>
                  <span class="comment">还是小时候比较可爱</span>
                </div>
                <div class="date">2020-02-12 17:26:11</div>
              </div>
            </div>
            <div class="item">
              <div class="icon-wrap">
                <img src="../assets/avatar.jpg" alt="" />
              </div>
              <div class="content-wrap">
                <div class="content">
                  <span class="name">爱斯基摩：</span>
                  <span class="comment">谁说的，长大了依旧可爱哈</span>
                </div>
                <div class="re-content">
                  <span class="name">小苹果：</span>
                  <span class="comment">还是小时候比较可爱</span>
                </div>
                <div class="date">2020-02-12 17:26:11</div>
              </div>
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
        >
        </el-pagination>
      </el-tab-pane>
    </el-tabs>
  </div>
</template>

<script>
export default {
  name: 'playlist',
  data() {
    return {
      activeIndex: '1',
      // 总条数
      total: 0,
      // 页码
      page: 1
    };
  },
  methods: {
    handleCurrentChange(val) {
      console.log(`当前页: ${val}`);
    }
  }
};
</script>

<style lang="scss">
.playlist-container {
  margin: auto;
  padding-top: 40px;
  .top-wrap {
    display: flex;
    span {
      font-size: 17px;
    }
    .img-wrap {
      margin-right: 30px;
      img {
        width: 230px;
        height: 230px;
      }
    }
    .info-wrap {
      .title {
        margin-bottom: 20px;
      }
      .author-wrap {
        display: flex;
        align-items: center;
        margin-bottom: 25px;
        img {
          width: 35px;
          height: 35px;
          border-radius: 50%;
          margin-right: 10px;
        }
        .name {
          margin-right: 10px;
        }
        .time {
          font-size: 14px;
        }
      }
      .play-wrap {
        width: 120px;
        height: 35px;
        border-radius: 4px;
        background: linear-gradient(to right, #e85e4d, #c6483c);
        display: flex;
        align-items: center;
        justify-content: center;
        margin-bottom: 25px;
        span {
          color: white;
          &.iconfont {
            margin-right: 8px;
          }
          &.text {
            font-size: 16px;
          }
        }
      }
      .tag-wrap {
        display: flex;
        margin-bottom: 15px;
        span {
          margin: 0;
        }
        ul {
          display: flex;
          align-items: center;
        }
        li {
          font-size: 15px;
          &:not(:last-child)::after {
            content: '/';
            margin: 0 4px;
          }
        }
      }
      .desc-wrap {
        span {
          &:last-child {
            font-size: 15px;
          }
        }
      }
      span:first-child {
        margin-right: 10px;
      }
    }
  }

  .comment-wrap {
    margin-bottom: 70px;
    .title {
      font-size: 20px;
      .number {
        color: black;
        font-size: 18px;
      }
    }
    .item {
      display: flex;
      padding-top: 20px;
      .icon-wrap {
        margin-right: 15px;
        img {
          width: 50px;
          height: 50px;
          border-radius: 50%;
        }
      }
      &:not(:last-child) {
        .content-wrap {
          border-bottom: 1px solid #f2f2f1;
        }
      }
      .date {
        color: #bebebe;
        font-size: 14px;
      }

      .content-wrap {
        padding-bottom: 20px;

        flex: 1;
        .name {
          color: #517eaf;
          font-size: 14px;
        }
        .comment {
          font-size: 14px;
        }
        .content,
        .re-content {
          margin-bottom: 10px;
        }
        .re-content {
          padding: 10px;
          background-color: #e6e5e6;
          border-radius: 5px;
        }
      }
    }
  }
}
</style>
