<template>
  <div class="home">
    <div class="box"><span>消息</span></div>
    <div class="uls">
      <ul>
        <li>
          <div class="img">
            <img src="favicon.ico" alt="" />
          </div>
          <div class="content">
            <p>服务信息</p>
            <span class="span1">您有一条新的签约申请</span>
            <span class="span2">2021-04-30</span>
          </div>
        </li>
        <li>
          <div class="img">
            <img src="favicon.ico" alt="" />
          </div>
          <div class="content">
            <p>系统信息</p>
            <span class="span1">评价通知</span>
            <span class="span2">2021-04-30</span>
          </div>
        </li>
        <li>
          <div class="img">
            <img src="favicon.ico" alt="" />
          </div>
          <div class="content">
            <p>李明明</p>
            <span class="span1">周五上午您有空吗?</span>
            <span class="span2">2021-04-30</span>
          </div>
        </li>
             <li>
          <div class="img">
            <img src="favicon.ico" alt="" />
          </div>
          <div class="content">
            <p>李明明</p>
            <span class="span1">周五上午您有空吗?</span>
            <span class="span2">2021-04-30</span>
          </div>
        </li>
             <li>
          <div class="img">
            <img src="favicon.ico" alt="" />
          </div>
          <div class="content">
            <p>李明明</p>
            <span class="span1">周五上午您有空吗?</span>
            <span class="span2">2021-04-30</span>
          </div>
        </li>
      </ul>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.box {
  padding-left: 20px;
  width: 100%;
  font-size: 20px;
}
li {
  margin-top: 20px;
  display: flex;
}
.uls {
  padding-top: 30px;
  padding-left: 20px;
  img {
    width: 40px;
    height: 40px;
  }
  .content {
    width: calc(100% - 20px);
    position: relative;
    margin-left: 20px;
    border-bottom: 1px solid #ccc;
    .span1 {
      display: block;
      padding-top: 5px;
      padding-bottom: 8px;
      font-size: 14px;
      color: #ccc;
    }
    .span2 {
      position: absolute;
      top: 0;
      right: 10px;
      font-size: 14px;
      color: #ccc;
    }
  }
}
</style>
