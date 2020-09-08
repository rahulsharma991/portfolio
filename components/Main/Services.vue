<template>
  <div>
    <section class="section-5-2-half" id="services">
      <div class="container">
        <div class="columns is-centered">
          <div class="column is-three-quarters has-text-centered">
            <h1 class="title is-spaced font-gradient">{{ service_title }}</h1>
            <h2 class="subtitle">
              Digitalize the things and start creating marvelous web designs
            </h2>
          </div>
        </div>
        <br />
        <br />
        <div class="columns  is-multiline is-mobile">
          <div
            class="column is-12-mobile is-half-tablet is-one-third-desktop pd-2"
          >
            <img src="../../assets/images/code.png" />
            <h1 class="title is-size-4 is-spaced">Web Development</h1>
            <h2 class="subtitle">
              HTML, CSS(BULMA), JavaScript , Nuxt.js and Express.js we will make
              some cool stuff!
            </h2>
          </div>
          <div
            class="column is-12-mobile is-half-tablet is-one-third-desktop pd-2"
          >
            <img src="../../assets/images/computer.png" />
            <h1 class="title is-size-4 is-spaced">Responsive Design</h1>
            <h2 class="subtitle">
              In current era we cannot show 80's unfriendly mobile website. Lets
              me take care of that!
            </h2>
          </div>
          <div
            class="column is-12-mobile is-half-tablet is-one-third-desktop pd-2"
          >
            <img src="../../assets/images/adobe.png" />
            <h1 class="title is-size-4 is-spaced">Adobe Illustration</h1>
            <h2 class="subtitle">
              Designer who mold the ugliset shapes into attractive shapes. Lets
              find it and build together!
            </h2>
          </div>
        </div>
      </div>
    </section>
  </div>
</template>

<script>
export default {
  data: () => {
    return {
      service_title: "Make things Digital",
      service_subtitle:
        "Digitalize the things and start creating marvelous web designs"
    };
  }
};
</script>
