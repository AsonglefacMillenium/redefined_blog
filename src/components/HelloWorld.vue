<template>
  <div class="hello">

    <div>
    <div>
<img src="../assets/background.png" alt="" class="img-fluid w-100" >
    </div>

    <div class="head">
   <h1>BLOG:</h1>
   <p>Read our blog posts to know more about our platform and blood donation related news and campaigns</p>
    </div>
    </div>

<div class="container shadow post">
  <b-row>
    <b-col>
      <img src="../assets/benefit1.png" alt=""  width="400px" height="400px">
    </b-col>
    <b-col>
      <h4>Healthy habits for blood donors</h4>

      <p>In as much as blood donation is very necessary, the health of the donor is also of top importance. There are certain healthy habits that the blood donor must endevor to follow such as sports, good feeding habits, regular checkups etc...</p>
      <button><a href="">Read the post<i class="fa fa-arrow-right" aria-hidden="true"></i></a></button>
    </b-col>
  </b-row>
</div>

<div class="container shadow post">
  <b-row>
    <b-col>
      <img src="../assets/benefit2.png" alt=""  width="400px" height="400px">
    </b-col>
    <b-col>
      <h4>Benefits of Blood donation</h4>

      <p>We are so many times made to understand that the positive effects of blood donation always are beneficial only to the recipient. But this is not all that true as even the donor has alot of things to benefit healthwise via this process...</p>
      <button><a href="">Read the post<i class="fa fa-arrow-right" aria-hidden="true"></i></a></button>
    </b-col>
  </b-row>
</div>

<div class="container shadow  post">
  <b-row>
    <b-col>
      <img src="../assets/benefit3.png" alt=""  width="400px" height="400px">
    </b-col>
    <b-col>
      <h4>Types of blood groups</h4>

      <p>In this noble act that saves the lives of many over the globe, it is very important to handle matters related to it with care. This is why the ABO blood system must be highly considered before blood donation...</p>

 <button><a href="">Read the post<i class="fa fa-arrow-right" aria-hidden="true"></i></a></button>
    </b-col>
  </b-row>
</div>
 </div>
</template>

<script>
export default {
  name: 'HelloWorld',
  props: {
    msg: String
  }
}
</script>

<!-- Add "scoped" attribute to limit CSS to this component only -->
<style scoped>
h3 {
  margin: 40px 0 0;
}
ul {
  list-style-type: none;
  padding: 0;
}
li {
  display: inline-block;
  margin: 0 10px;
}
a {
  color: black;
  background-color: crimson;
}

button{
  background-color: crimson;
  color: black;
  margin-top: 80px;
}

.head{
  position: absolute;
  top: 20%;
  left: 30%;
  text-align: center;
  color: white;
  font-size: 20px;
}

.post{
  margin-top: 40px;
  margin-bottom: 40px;
}

.post img{
  margin-left: 0px;
}

.post h4{
  margin: 40px;
  color: crimson;
}
.post p{
  margin-top: 60px;
}
</style>
