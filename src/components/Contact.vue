<template>
  <div class="parent">
    <div class="container">
      <h1> Contact Us </h1>
      <div class="row">
        <div class="col-md-3 col-xs-12">
          <div class="con1">
            <h2> Address </h2>
            <div class="add1">
              <img src="../assets/images/map-icon.png"/>
              <span> Gb road 123 london Uk </span>
            </div>
            <div class="add1">
              <img src="../assets/images/phone-icon.png"/>
              <span> (+71) 56982424536 </span>
            </div>
            <div class="add1">
              <img src="../assets/images/email-icon.png"/>
              <span> bacerim@gmail.com </span>
            </div>
          </div>
        </div>
        <div class="col-md-3 col-xs-12">
          <div class="con2">
            <h2> Useful Links </h2>
            <div class="add1">
              <img src="../assets/images/bulit-icon.png"/>
              <span> Bacerim Dictionary </span>
            </div>
            <div class="add1">
              <img src="../assets/images/bulit-icon.png"/>
              <span> Help Links </span>
            </div>
            <div class="add1">
              <img src="../assets/images/bulit-icon.png"/>
              <span> bacerim Attitudes </span>
            </div>
            <div class="add1">
              <img src="../assets/images/bulit-icon.png"/>
              <span> Call a Cutumer </span>
            </div>
            <div class="add1">
              <img src="../assets/images/bulit-icon.png"/>
              <span> Help a Bacerim </span>
            </div>            
          </div>
        </div>
        <div class="col-md-3 col-xs-12">
          <div class="con2">
            <h2> Overview </h2>
            <div class="add1">
              <img src="../assets/images/bulit-icon.png"/>
              <span> Bacerim Dictionary </span>
            </div>
            <div class="add1">
              <img src="../assets/images/bulit-icon.png"/>
              <span> Help Links </span>
            </div>
            <div class="add1">
              <img src="../assets/images/bulit-icon.png"/>
              <span> bacerim Attitudes </span>
            </div>
            <div class="icons">
              <img src="../assets/images/fb-icon.png">
              <img src="../assets/images/twitter-icon.png">
              <img src="../assets/images/google-icon.png">
              <img src="../assets/images/linkedin-icon.png">
            </div>
          </div>
        </div>
        <div class="col-md-3 col-xs-12">
          <div class="con4">
            <h2> Instagram </h2>
            <div class="row">
              <div class="col-xs-6">
                <img src="../assets/images/about-img2.png"/>
              </div>
              <div class="col-xs-6">
                <img src="../assets/images/about-img3.png"/>
              </div>
              <div class="col-xs-6">
                <img src="../assets/images/about-img4.png"/>
              </div>
              <div class="col-xs-6">
                <img src="../assets/images/about-img5.png"/>
              </div>
            </div>
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
$mostcolor:#fa3e19;
.parent{
    padding: 40px 0px;
    background-color: #393838;
    color: white;
    .container{

      >h1{
        text-align: left;
        font-size: 50px;
        margin-bottom: 30px;
      }
      .row{
        .col-md-3{
          .con1{
            >h2{
              margin-bottom: 20px;
              text-align: left;
            }
            .add1{
              display: flex;
              margin-bottom: 15px;
              img{

              }
              span{
                display: inline-block;
                margin-top: 15px;
                margin-left: 20px;
                color: #ebebeb;
              }
            }
            .add1{
              &:hover{
                cursor: pointer;
              img{
                transform: ease-in-out;
                transition: 1s all;
                background-color: $mostcolor;
                border: 0.1px dashed white;
              }
              }
            }
          }
          .con2{
            >h2{
              margin-bottom: 20px;
              text-align: left;              
            }
            .add1{
              display: flex;
              margin-bottom: 15px;
              img{
                height: 13px;
                margin-top: 5px;
              }
              span{
                margin-left: 20px;
                color: #ebebeb;
              }
            }
          }
          .con2{
            .icons{
              margin-top: 25px;
              img{
                float: left;
                margin-right: 15px;  
                &:hover{
                  transition: 0.5s all;
                  border-radius: 6px;
                  cursor: pointer;
                  background-color: $mostcolor;
                }
              }
            }
          }         
          .con4{

            h2{
              text-align: left;
              margin-bottom: 20px;
            }
            >.row{
              display: flex;
              >.col-xs-6{
                margin-bottom: 15px;
                img{
                  width: 100%;
                }
              }
            }
          }
        }
      }
    }
}
</style>
