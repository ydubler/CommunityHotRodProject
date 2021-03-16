<template>
  <div id="home">
    <img src="public/images/logo.jpg" />
    <div class="textContainer">
      <br />
      <br />
      <a href="https://www.instagram.com/thecommunityhotrodproject/"
        >Instagram</a
      >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;<a
        href="https://www.facebook.com/kevin.haeberle.3/"
        >Facebook</a
      >&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;haeberleshotrodservice@gmail.com
      <div class="text">
        <div class="text-title">OUR MISSION STATEMENT</div>
        <br />
        This day and age there is a serious lack of hands-on vocational programs
        in our community for everyone no matter how young or young at heart you
        are. Our main focus is not only building rolling works of art but,
        building lifelong friendships as we work together from rendering designs
        to showstopping builds. No matter what your background is, you're family
        when you take part of The Community Hot Rod Project. Our program offers
        not only mechanical theory but, skills to promote a positive environment
        and improve both professional and personal etiquette which is missing in
        our community and world today. From rust and dust to solid well thought
        out original designs our job is to inspire. Welcome to our family...
      </div>
    </div>
    <br />
    Website under construction.
  </div>
</template>

<script>
// @ is an alias to /src
//import HelloWorld from "../components/HelloWorld.vue";

export default {
  name: "home",
  components: {
    //HelloWorld,
  },
  methods: {},
  mounted: function () {},
};
</script>

<style>
body {
  margin: 0px;
  background-color: #3e3e3e;
  text-align: center;
}
a {
  font-size: 16px;
  color: white;
}
a:visited {
  font-size: 16px;
  color: rgb(192, 192, 192);
}
img {
  width: 50%;
}
.text-container {
  width: 100%;
  text-align: center;
  font-family: "Fira Sans Condensed", sans-serif;
}
.text-title {
  font-size: 26px;
  color: white;
  letter-spacing: 3px;
  text-align: left;
}
.text {
  display: inline-block;
  text-align: left;
  width: 70%;
  font-size: 22px;
  color: white;
}
</style>