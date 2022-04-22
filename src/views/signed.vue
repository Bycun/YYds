<template>
  <div class="signed">
    <header>
      <img
        src="https://cdn3.axureshop.com/demo/1770237/images/%E7%BB%84%E4%BB%B6_%E8%A7%84%E8%8C%83/u749.png"
        alt=""
      />
      <p>签约详情</p>
      <span>查看协议</span>
    </header>
    <div class="dd">
      <img src="time.png" alt="" />
      <p>等待医生审核中</p>
    </div>

    <div class="xinxi">
      <p class="xppp">居民信息</p>
      <div class="xm">
        <div class="bx">
          <div>
            <span>姓名</span>
            <span>身份证号</span>
            <span>性别</span>
            <span>年龄</span>
            <span>联系电话</span>
            <span>现居地</span>
          </div>
          <div class="bbx">
            <span>王安然</span>
            <span>345022********0423</span>
            <span>女</span>
            <span>26</span>
            <span>15678909900</span>
            <span>怀柔区洛西县建设路青莲小区6-601</span>
          </div>
        </div>
      </div>
    </div>

    <div class="xinxi">
      <p class="xppp">签约信息</p>
      <div class="xmb">
        <div class="bx">
          <div>
            <span>签约状态</span>
            <span>签约机构</span>
            <span>签约团队</span>
            <span>签约医生</span>
            <span>服务包</span>
            <span>签约周期</span>
            <span>生效日期</span>
            <span>费用</span>
            <span>申请时间</span>
            <span>签约备注</span>
          </div>
          <div class="bbx">
            <span class="dsh">待审核</span>
            <span>洛西社区卫生服务站</span>
            <span>李明明团队</span>
            <span>李明明</span>
            <span>老人服务包</span>
            <span>1年</span>
            <span>2020/10/09</span>
            <span class="jq">￥120</span>
            <span>2020/10/09 &nbsp; 10:09:09 </span>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>

<style lang="scss" scoped>
.xppp {
  font-size: 20px;
  padding-top: 10px;
  padding-left: 16px;
}
header {
  margin-top: 20px;
  padding-left: 10px;
  padding-right: 10px;
  align-items: center;
  display: flex;
  justify-content: space-between;
  img {
    width: 12px;
    height: 14px;
  }
  p {
    padding-left: 10px;
    font-size: 20px;
  }
  span {
    color: #3dda47;
    font-size: 14px;
  }
}
.dd {
  width: 100%;
  height: 32px;
  display: flex;
  background-color: #fddb78;
  align-items: center;
  color: #fff;
  p {
    font-size: 13px;
  }
}

.xm {
  width: 365px;
  height: 294px;
  background-size: 100% 100%;
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
    p {
      color: #ccc;
      font-size: 14px;
      padding-top: 5px;
      padding-left: 20px;
    }
    .ddd {
      position: relative;
      right: -142px;
      color: red;
      margin-right: 10px;
      float: right;
    }
  }
  .bx {
    display: flex;
    margin-top: 1px;
    padding-top: 30px;
    margin-left: 30px;
    span {
      display: block;
      font-size: 14px;
      padding-top: 15px;
      color: #ccc;
    }
    .bbx {
      margin-left: 20px;
      span {
        color: black;
      }
    }
  }
}

.xmb {
  width: 365px;
  height: 406px;
  background-size: 100% 100%;
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
    p {
      color: #ccc;
      font-size: 14px;
      padding-top: 5px;
      padding-left: 20px;
    }
    .ddd {
      position: relative;
      right: -142px;
      color: red;
      margin-right: 10px;
      float: right;
    }
  }
  .bx {
    display: flex;
    margin-top: 1px;
    padding-top: 30px;
    margin-left: 30px;
    span {
      display: block;
      font-size: 14px;
      padding-top: 15px;
      color: #ccc;
    }
    .bbx {
      margin-left: 20px;
      span {
        color: black;
      }
      .jq {
        color: #fa746b;
      }
      .dsh {
        color: #28d094;
      }
    }
  }
}
</style>