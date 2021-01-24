<template>
  <div class="parent">
    <div class="container">
      <h1>Products</h1>
      <div class="row">
        <div class="col-md-4 col-xs-12">
          <div class="product">
            <div class="pimg">
              <img src="../assets/images/about-img1.png"/>
            </div>
            <h1> Croissants Breakfast </h1>
          </div>
        </div> 
        <div class="col-md-4 col-xs-12">
          <div class="product">
            <div class="pimg">
              <img src="../assets/images/about-img2.png"/>
            </div>
            <h1> Roll Cake </h1>
          </div>
        </div> 
        <div class="col-md-4 col-xs-12">
          <div class="product">
            <div class="pimg">
              <img src="../assets/images/about-img3.png"/>
            </div>
            <h1> BreadFrench Toast </h1>
          </div>
        </div> 
        <div class="col-md-4 col-xs-12">
          <div class="product">
            <div class="pimg">
              <img src="../assets/images/about-img4.png"/>
            </div>
            <h1> Cup Cake </h1>
          </div>
        </div> 
        <div class="col-md-4 col-xs-12">
          <div class="product">
            <div class="pimg">
              <img src="../assets/images/about-img5.png"/>
            </div>
            <h1> Donut </h1>
          </div>
        </div> 
        <div class="col-md-4 col-xs-12">
          <div class="product">
            <div class="pimg">
              <img src="../assets/images/about-img6.png"/>
            </div>
            <h1> Chocolate Cup Cake </h1>
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
  .container{
    >h1{
      color: #fa3e19;
      font-size: 55px;
      margin-bottom: 40px;
    }
    .row{
      display: flex;
      flex-wrap: wrap;
      >.col-md-4{
        padding: 0px;
      }
      .product{
        margin: 20px 15px;
        .pimg{
          background-color: #e7e4e3;
          overflow: hidden;
          margin-bottom: 25px;
          img{
            display: block;
            width: 90%;
            margin:25px auto;
            border: 1px solid whitesmoke;
            
          }          
      }
      h1{
        font-size: 22px;
        margin: auto;
        text-align: center;
        color: grey;
      }
      &:hover{
            .pimg{
              transition: 0.7s all;
              cursor: pointer;
              background-color:#fa3e19 ;
            }
            >h1{
              transition: 0.7s all;
              cursor: pointer;
              color: #fa3e19;
            }
          }
      }

    }
  }
}
</style>