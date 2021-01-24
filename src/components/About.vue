<template>
  <div class="parent">
    <div class="container">
      <div class="row">
        <div class="col-md-6 col-xs-12">
          <div class="aimg">
            <img src="../assets/images/cupcake-img.png"/>
          </div>
        </div>
        <div class="col-md-6 col-xs-12">
          <div class="atext">
            <h1>About</h1>
            <p>consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim ve niam, quis nostrud exercitationconsectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation</p>
            <button>Read More</button>
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
  padding: 50px 0px;
  margin-top:130px ;
  clear: both;
  .container{

    .row{
      display: flex;
      .atext{
        text-align: left;
        margin-left: 100px;
        h1{
          color: #fa3e19;
          font-size: 55px; 
        }
        p{
          font-family: system-ui;
          line-height: 1.7;
          font-size: 16px;
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
      .aimg{
        width: 100%;
        img{
          transform: scale(0.9);
        }
      }
    }
  }
}

@media (max-width:992px) {
  .parent .container .row .aimg img{
    transform: scale(0.7);
  }
}
</style>