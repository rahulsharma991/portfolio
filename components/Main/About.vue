<template>
  <div>
    <section class="section-5-2-half" id="about">
      <div class="container">
        <div class="columns is-centered  ">
          <div class="column  is-three-fifths mb-3">
            <img src="" alt="" class="profile-image background-gradient" />
          </div>
        </div>

        <div class="columns is-centered">
          <div class="column is-three-fifths">
            <h1 class="title is-spaced font-gradient">
              Hello
              <img
                src="../../assets/images/hello.png"
                alt="hello to everyone"
                class="hello-image"
              />
            </h1>
            <h2 class="subtitle has-text-justified intro">
              I'm Rahul Sharma, who daily sips a
              <img
                src="../../assets/images/programming.png"
                style="height:1.4rem"
              />
              cup of code, 22 years old from technical background with
              graduation degree
              <img
                src="../../assets/images/graduation.png"
                style="height:1.4rem"
              />
              in computer science and Engineering. I'm front-end web developer
              and working as a freelance remotely
              <img
                src="../../assets/images/freelance.png"
                style="height:1.4rem"
              />
              .
            </h2>
            <h2 class="subtitle has-text-justified intro">
              At initial level i started creating web designs with HTML and CSS
              in 2018. But I'm not happy with that i wanted to control the whole
              behaviour of the body so i added JavaScript in my pocket to keep
              alive the body.
              <img src="../../assets/images/heart.png" style="height:1.4rem" />
            </h2>
            <h2 class="subtitle has-text-justified intro">
              I always love technology and eager to learn something new so i can
              contribute cool stuff to open source community. In spare time i
              draw some paintings and reading books.
              <img
                src="../../assets/images/contribution.png"
                style="height:1.4rem"
              />
            </h2>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {};
</script>

<style scoped>
.hello-image {
  height: 2rem;
  animation: wave 2s ease-in-out;
}
.profile-image {
  height: 13rem;
  width: 13rem;
  border-radius: 50%;
  box-shadow: 0 0 10px black;
  margin: auto;
  display: block;
}
.intro {
  letter-spacing: 1px;
  line-height: 1.8rem;
}
</style>
