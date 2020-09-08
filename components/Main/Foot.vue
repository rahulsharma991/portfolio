<template>
  <div>
    <section>
      <footer class="footer">
        <div class="content has-text-centered">
          <p>
            <a class="is-blue" v-for="item in footItems" :key="item"
              >{{ item }}
            </a>
          </p>
          <p>
            <img
              src="../../assets/images/code.png"
              style="height:1.5rem"
              class="is-vcentered"
            />
            with
            <img
              src="../../assets/images/programming.png"
              style="height:1.5rem"
            />
            +
            <img src="../../assets/images/heart.png" style="height:1.5rem" /> by
            Rahul Sharma &copy; 2020
          </p>
        </div>
      </footer>
    </section>
  </div>
</template>
<script>
export default {
  data: () => {
    return {
      footItems: ["Home |", "About |", "Services |", "Projects |", "Contact"]
    };
  }
};
</script>
