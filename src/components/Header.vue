<template>
  <div class="parent">
    <div class="container">
      <div class="row">
        <div class="col-md-6 col-xs-12">
          <div class="htext">
            <p>Quality</p>
            <h1>Products with breads sweet Den</h1>
            <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim</p>
            <button> Read More </button>
          </div>
        </div>
        <div class="col-md-6 col-xs-12">
          <div class="himg">
            <img src="../assets/images/banner-image.png"/>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name:"parent"
}
</script>
<style lang="scss" scoped>
.parent{
  background-color: #fefcfb;
  padding: 30px 0px;
  .container{
    .row{
      display: flex;
      .htext{
        p:first-of-type{
          font-size: 40px;
          text-align: left;
          margin-bottom: 0px;
          color: #111111;
        }
        h1{
          line-height: 1.2;
          margin-top: 5px;
          margin-bottom: 0px;
          text-align: left;
          font-size: 55px;
          font-weight: 600;
          width: 70%;
          color: #fa3e19;
        }
        p:last-of-type{
          text-align: left;
          width: 70%;
          margin-top: 5px;
          color: #111111;
          font-size: 15px;
          font-family: system-ui;
          font-weight: 600;
        }
        button{
          float: left;
          outline-style: none;
          border: 0px;
          font-size: 18px;
          padding: 10px 30px;
          margin-top:40px;
          background-color:  #fa3e19;
          color: white;
          cursor: pointer;
        }
      }
      .himg{
        img{
          display: block;
          width: 90%;
        }
      }
    }
  }
}
</style>