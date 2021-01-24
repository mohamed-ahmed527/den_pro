<template>
  <div class="parent">
      <h1>Gallery </h1>
      <div class="row">
        <div class="col-md-3 col-xs-12">
          <div class="gimg">
            <img src="../assets/images/gallery-img1.png">
            <div class="gtext">
              <p> Breakfast Breads </p>
            </div>
          </div>
          
        </div>
        <div class="col-md-3 col-xs-12">
          <div class="gimg">
            <img src="../assets/images/gallery-img2.png">
            <div class="gtext">
              <p> Breakfast Breads </p>
            </div>
          </div>
        </div>
        <div class="col-md-3 col-xs-12">
          <div class="gimg">
            <img src="../assets/images/gallery-img3.png">
            <div class="gtext">
              <p> Breakfast Breads </p>
            </div>
          </div>
        </div>
        <div class="col-md-3 col-xs-12">
          <div class="gimg special">
            <img src="../assets/images/gallery-img4.png">
            <div class="gtext">
              <p> Breakfast Breads </p>
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
  margin-top: 130px;
  margin-bottom: 130px;
    >h1{
      font-size: 55px;
      color: #fa3e19;
      margin-bottom: 60px;
    }
    .row{
      display: flex;
      margin: 0px;
      >.col-md-3{
        padding: 0px;
      }
      .gimg{
        position: relative;
        overflow: hidden;
        img{
          display: block;
          width: 100%;
        }
        .gtext{
          opacity: 0;
          position: absolute;
          top: 0px;
          left: 0px;
          width: 100%;
          font-size: 25px;
          font-weight: 600;
          background-color: #fa3e19cf;
          color: white;
          height: 100%;     
          p{
            margin-top: 47%;
          }     
        }
        &:hover{
          .gtext{
            opacity: 1;
            cursor: pointer;
            transition: 0.7s all;
          }
          img{
            transition: 0.5s all;
            transform: scale(1.1);
          }
        }
      }
    }
  }
  @media (max-width:992px) {
    .parent{
      .row{
        display: flex;
        flex-wrap: wrap;
      }

    }
  }
</style>