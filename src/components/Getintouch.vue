<template>
  <div class="parent">
    <div class="container">
      <h1> <span> Get in </span> touch </h1>
      <div class="row">
        <div class="col-md-6 col-xs-12">
          <div class="gettext">
            <form>
              <div class="col-xs-12">
                <input type="text" placeholder="Your Name">
              </div>
              <div class="col-xs-12">
                <input type="text" placeholder="Email">
              </div>
              <div class="col-xs-12">
                <input type="text" placeholder="Mobile Number">
              </div>       
              <div class="col-xs-12">
                <textarea placeholder="Message"></textarea>
              </div>
              <button type="submit"> Send </button>
            </form>
          </div>
        </div>
        <div class="col-md-6 col-xs-12">
          <div class="getimg">
            <img src="../assets/images/bread-img.png"/>
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
  margin-bottom: 130px;
  .container{

    h1{
      font-size: 55px;
      margin-bottom: 60px;
      font-weight: 600;
      span{
        color: #fa3e19;
      }
    }
    .row{

      .col-xs-12{

        .gettext{
          background-color:#fa3e19;
          form{
            padding: 30px;
            input{
              outline-style: none;
              height: 45px;
              padding: 5px 13px;
              border: 0px;
              display: block;
              width: 100%;
              margin: 10px 0px;
            }
            textarea{
              outline-style: none;
              padding: 5px 13px;
              border: 0px;
              display: block;
              width: 100%;
              height: 160px;
              margin: 10px 0px;
            }           
            button{
              background-color: #111111;
              border: 0px;
              padding: 7px 35px;
              color: white;
              font-size: 19px;
              }          
          }

        }
        }
      .getimg{
        padding-top: 20px;
        img{
          display: block;
          width: 100%;
        }
      }
      }
    }
  }

</style>