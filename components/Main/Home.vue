<template>
  <div>
    <section id="home">
      <div class="landing-area">
        <div class="container">
          <div class="landing-area-text px-4">
            <h1
              class="title is-size-3 has-text-centered is-size-4-mobile typing-anime"
            >
              {{ name }}
            </h1>
            <h2
              class="title is-spaced is-size-2 has-text-centered is-size-3-mobile mr-1 font-gradient"
            >
              {{ profile }}
            </h2>
            <h3
              class="subtitle has-text-centered has-text-weight-medium is-size-4 is-size-5-mobile "
            >
              {{ tech }}
            </h3>
            <div class="columns is-centered">
              <div class="column is-one-fifth-tablet is-one-fifth-desktop">
                <button
                  class="button is-dark has-text-centered btnX background-gradient"
                  role="button"
                >
                  {{ get_in_touch }}
                </button>
              </div>
              <div class="column is-one-fifth-tablet">
                <button
                  class="button is-dark has-text-centered btnX background-gradient"
                  role="button"
                >
                  {{ get_in_touch }}
                </button>
              </div>
            </div>

            <a href="#about"
              ><button
                class="is-size-1 mt-2 arrow-anime btnX pointer"
                role="button"
              >
                <i class="fa fa-angle-down" aria-hidden="true"></i></button
            ></a>
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
      name: "Rahul Sharma",
      profile: "< Front-End Web Developer />",
      tech: "HTML . CSS . JavaScript . NuxtJs",
      get_in_touch: "Get in touch"
    };
  }
};
</script>

<style scoped>
.landing-area {
  height: 100vh;
  width: 100%;
  background: url("../../assets/images/cover.jpg") no-repeat;
  background-size: cover;
  position: relative;
}
.landing-area-text {
  position: absolute;
  left: 50%;
  top: 50%;
  transform: translate(-50%, -50%);
  width: 100%;
  max-width: 50rem;
}
.container {
  position: unset !important;
}
.typing-anime {
  animation: typing 5s steps(26), blink-caret 0.75s step-end infinite;
  letter-spacing: 1rem;
  white-space: nowrap;
  margin: auto;
  overflow: hidden;
  border-right: 4px solid;
  max-width: 22ch;
}
.arrow-anime {
  animation: up-down 2s ease-in-out infinite;
  background: none;
  border: 2px solid black;
  border-radius: 4px;
}

@media (max-width: 600px) {
  .typing-anime {
    letter-spacing: 0.4rem;
    max-width: 17ch;
  }
}
@keyframes wave {
  0% {
    transform: rotate(-45deg);
  }
  40% {
    transform: rotate(0deg);
  }
  60% {
    transform: rotate(-45deg);
  }
  100% {
    transform: rotate(0deg);
  }
}
@keyframes up-down {
  0% {
    opacity: 1;
  }
  50% {
    transform: translateY(1rem);
  }
  100% {
    transform: unset;
  }
}
@keyframes blink-caret {
  from,
  to {
    border-color: transparent;
  }
  50% {
    border-color: var(--purple-hex);
  }
}

@keyframes typing {
  from {
    width: 0%;
  }
  to {
    width: 26ch;
  }
}
</style>
