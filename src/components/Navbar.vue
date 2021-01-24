<template>
    <div class="parent">
        <div class="container">
            <div class="menu">
                <img class="minilogo" src="../assets/images/logo.png" />
                <span><img src="../assets/images/open-menu.svg"/></span>
            </div>
            <div class="logo">
                <img src="../assets/images/logo.png"/>
            </div>
            <nav>
                <ul>
                    <li><a href="#">  Home </a></li>
                    <li><a href="#">  About </a></li>
                    <li><a href="#">  Products </a></li>
                    <li><a href="#">  Gallary </a></li>
                    <li><a href="#">  Contact Us </a></li>
                </ul>
            </nav>
        </div>
    </div>

</template>
<script>
export default {
    name: "parent"
}
</script>
<style lang="scss" scoped>
.parent{
    overflow: hidden;
    padding: 10px 0px   ;
    background-color: #fefcfb;
    .container{
        .logo{
            float: left;
            img{
                display: block;
                width: 85%;
                margin: auto;
            }
        }
        nav{
            float: right;
            ul{
                padding:17px 0px;
                margin: 0px;
                li{
                    list-style: none;
                    display: inline-block;
                    font-size: 20px;
                    padding: 0px 25px;                    
                    color: #090400;
                    a{
                        text-decoration: none;
                        color: unset;
                    }
                    &:hover{
                        cursor: pointer;
                        color: #fa3e19;
                        transition: 0.3s all;
                    }
                }
            }
        }
    }

}
.menu{
    overflow: hidden;
    display: none;
    margin-bottom:20px;
    >img{
        float: left;  
        width: 100px;
    }
    span{
        float: right;
        width: 30px;
        height: 30px;
        img{
            width: 100%;
        }
    }
}
@media (max-width:992px) {
  .menu{
    display: block;
    cursor: pointer;
  }
  .logo{
    display: none;
  }
  .parent{
      .container{
        nav{
            display: none;
            ul{
                li{
                    width: 100%;
                    margin-bottom: 5px;
                    text-align:left;
                }
            }
        }

      }
  }


}
</style>
