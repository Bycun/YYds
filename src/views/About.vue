<template>
  <div class="about">
    <div class="top">
      <div class="img">
        <img
          src="	https://cdn3.axureshop.com/demo/1770237/images/%E9%A6%96%E9%A1%B5/u1543.png"
          alt=""
        />
        <span>王明伟医生</span>
      </div>
      <div class="ew">
        <img
          src="https://cdn3.axureshop.com/demo/1770237/images/%E7%BB%84%E4%BB%B6_%E8%A7%84%E8%8C%83/u777.png"
          alt=""
        />
      </div>
    </div>
    <div class="con">
      <ul>
        <li>
          <p>已签约人数</p>
          <h3>1000</h3>
        </li>
        <li>
          <p>待签约人数</p>
          <h3>20</h3>
        </li>
        <li>
          <p>居民总数</p>
          <h3>1020</h3>
        </li>
      </ul>
      <ul>
        <li>
          <p>待处理服务量</p>
          <h3>10</h3>
        </li>
        <li>
          <p>服务总量</p>
          <h3>100</h3>
        </li>
        <li>
          <p>服务评价</p>
          <h3>4.9</h3>
        </li>
      </ul>
      <div class="cbo">
        <ul>
          <li>
            <div class="div1">
              <img
                src="	https://cdn3.axureshop.com/demo/1770237/images/%E7%BB%84%E4%BB%B6_%E8%A7%84%E8%8C%83/u952.png"
                alt=""
              />
            </div>
            新建档案
          </li>
          <li>
            <div class="div2">
              <img
                src="	https://cdn3.axureshop.com/demo/1770237/images/%E7%BB%84%E4%BB%B6_%E8%A7%84%E8%8C%83/u956.png"
                alt=""
              />
            </div>
            签约管理
          </li>
          <li>
            <div class="div3">
              <img
                src="	https://cdn3.axureshop.com/demo/1770237/images/%E7%BB%84%E4%BB%B6_%E8%A7%84%E8%8C%83/u960.png"
                alt=""
              />
            </div>
            服务管理
          </li>
        </ul>
      </div>
    </div>
    <div class="foot">
      <div class="qy">
        <p>签约申请(3)</p>
        <span
          >查看全部
          <img
            src="	https://cdn3.axureshop.com/demo/1770237/images/%E9%A6%96%E9%A1%B5/u1572.png"
            alt=""
        /></span>
      </div>
      <div class="xm">
        <div class="xmx">
            <h3>王小明</h3>
            <p>58岁</p>
            <span class="dd">待审核</span>
        </div>
        <div class="bx">
                <div>
          <span>身份证号</span>
          <span>签约团队</span>
          <span>服务包</span>
        </div>
        <div class="bbx">
          <span>345022********0423</span>
          <span>李明明团队</span>
          <span>老年人服务包</span>
        </div>
        </div>
      </div>
    </div>
     <div class="foot">
      <div class="xm">
        <div class="xmx">
            <h3>王小明</h3>
            <p>58岁</p>
            <span class="dd">待审核</span>
        </div>
        <div class="bx">
                <div>
          <span>身份证号</span>
          <span>签约团队</span>
          <span>服务包</span>
        </div>
        <div class="bbx">
          <span>345022********0423</span>
          <span>李明明团队</span>
          <span>老年人服务包</span>
        </div>
        </div>
      </div>
    </div>
     <div class="foot">
      <div class="xm">
        <div class="xmx">
            <h3>王小明</h3>
            <p>58岁</p>
            <span class="dd">待审核</span>
        </div>
        <div class="bx">
                <div>
          <span>身份证号</span>
          <span>签约团队</span>
          <span>服务包</span>
        </div>
        <div class="bbx">
          <span>345022********0423</span>
          <span>李明明团队</span>
          <span>老年人服务包</span>
        </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.about {
  padding-left: 20px;
  .top {
    width: 100%;
    position: relative;
    .img {
      display: flex;
      padding-top: 20px;
      span {
        display: block;
        padding-top: 5px;
        padding-left: 10px;
      }
    }
    .ew {
      position: absolute;
      top: 27px;
      right: 10px;
    }
  }
  .con {
    position: relative;
    top: 20px;
    background: linear-gradient(
      -45deg,
      rgba(83, 215, 195, 1) 0%,
      rgba(83, 215, 195, 1) 0%,
      rgba(61, 212, 167, 1) 100%,
      rgba(61, 212, 167, 1) 100%
    );
    box-shadow: none;
    width: 335px;
    border-radius: 20px;
    height: 279px;
    ul {
      display: flex;
      justify-content: space-between;
      padding-top: 30px;
      padding-left: 20px;
      padding-right: 20px;
      li {
        p {
          font-size: 14px;
          color: rgba(255, 255, 255, 0.588235294117647);
        }
        h3 {
          padding-top: 10px;
          color: #fff;
        }
      }
    }
    .cbo {
      margin-top: 20px;
      width: 337px;
      height: 100px;
      border-bottom: 1px solid #ccc;
      border-top-left-radius: 20px;
      border-top-right-radius: 20px;
      background: #fff;
      ul {
        display: flex;
        justify-content: space-between;
        li {
          text-align: center;
          font-size: 14px;
          .div1 {
            text-align: center;
            line-height: 44px;
            width: 44px;
            height: 44px;
            background: #006ef1;
            border-radius: 12px;
          }
          .div2 {
            text-align: center;
            line-height: 44px;
            width: 44px;
            height: 44px;
            background: #fddb78;
            border-radius: 12px;
          }
          .div3 {
            text-align: center;
            line-height: 44px;
            width: 44px;
            height: 44px;
            background: #fa746b;
            border-radius: 12px;
          }
        }
      }
    }
  }
  .foot {
    margin-top: 50px;
    width: 100%;
    .qy {
      display: flex;
      justify-content: space-between;
      p {
        font-size: 20px;
      }
      span {
        font-size: 14px;
        color: #ccc;
        padding-right: 10px;
      }
    }
  }
  .xm {
    width: 365px;
    height: 194px;
    background-image: url("https://cdn3.axureshop.com/demo/1770237/images/%E9%A6%96%E9%A1%B5/u1576.png");
    .xmx {
      width: 365px;
      padding-top: 35px;
      padding-left: 30px;
      display: flex;
      span {
        font-size: 14px;
        color: #ccc;
        padding-left: 20px;
      }
      p{
        color: #ccc;
        font-size: 14px;
        padding-top: 5px;
        padding-left: 20px;
      }
      .dd {
        position: relative;
        right: -142px;
        color: red;
        margin-right: 10px;
        float: right;
      }
    }
    .bx{
      display: flex;
      margin-top: 20px;
      margin-left: 30px;
      span{
        display: block;
        font-size: 14px;
        padding-top: 10px;
        color: #ccc;
      }
      .bbx{
        margin-left: 20px;
      }
    }
  }
}
</style>
