<template>
  <div
    id="mainCarousel"
    class="pt-28 d-flex flex-column justify-content-between align-items-between h-screen"
  >
    <div
      class="d-flex justify-content-around align-items-center"
    >
      <a
        @mouseover="stopRotation()"
        @mouseleave="startRotation()"
        @click="prev"
        class="bg-white"
        animation="fade"
        font-scale="3"
      >Previous</a>
      
      <div 
        v-for="number in [currentNumber]" 
        :key="number"
      >
        
      </div>

      <a
        @mouseover="stopRotation()"
        @mouseleave="startRotation()"
        @click="next"
        class="bg-white"
        animation="fade"
        font-scale="3"
      >Next</a>
    </div>
  </div>
</template>

<script>
export default {
  name: "carousel",
  data() {
    return {
      messages: [
        "1",
        "2",
        "3",
        "4",
      ],
      currentNumber: 0,
      timer: null
    };
  },
  created() {},
  mounted: function() {
    this.load();
    this.startRotation();
  },

  methods: {
    load: function() {
      window.onload = function() {
        mainCarousel.classList.add("backSlide");
      };
    },
    startRotation: function() {
      this.timer = setInterval(this.next, 7000);
    },

    stopRotation: function() {
      clearTimeout(this.timer);
      this.timer = null;
    },

    next: async function() {
      let mainCarousel = document.getElementById("mainCarousel");
      this.currentNumber += 1;
      console.log(this.currentNumber);

      if (this.currentNumber == 0) {
        mainCarousel.classList.add("backSlide");
      }

      if (this.currentNumber == 1) {
        await mainCarousel.classList.remove("backSlide");
        await mainCarousel.classList.add("backSlide1");
      }
      if (this.currentNumber == 2) {
        mainCarousel.classList.remove("backSlide1");
        mainCarousel.classList.add("backSlide2");
      }
      if (this.currentNumber == 3) {
        mainCarousel.classList.remove("backSlide2");
        mainCarousel.classList.add("backSlide3");
      }
      if (this.currentNumber > 3) {
        this.currentNumber = 0;
        mainCarousel.classList.remove("backSlide3");
        mainCarousel.classList.add("backSlide");
      }
    },

    prev: function() {
      let mainCarousel = document.getElementById("mainCarousel");
      this.currentNumber -= 1;

      if (this.currentNumber == 0) {
        mainCarousel.classList.remove("backSlide1");
        mainCarousel.classList.add("backSlide");
      }

      if (this.currentNumber == 1) {
        mainCarousel.classList.remove("backSlide2");
        mainCarousel.classList.add("backSlide1");
      }
      if (this.currentNumber == 2) {
        mainCarousel.classList.remove("backSlide3");
        mainCarousel.classList.add("backSlide2");
      }
      if (this.currentNumber < 0) {
        this.currentNumber = 3;
        mainCarousel.classList.remove("backSlide");
        mainCarousel.classList.add("backSlide3");
      }
    }
  },

  
};
</script>

<style scoped>
.backSlide {
  background-image: url("../static/article1.jpg");
  animation: opacBack1 1s ease-in-out;
}
.backSlide1 {
  background-image: url("../static/slide-1.jpg");
  animation: opacBack2 1s ease-in-out;
}
.backSlide2 {
  background-image: url("../static/slide-2.jpg");
  animation: opacBack3 1s ease-in-out;
}
.backSlide3 {
  background-image: url("../static/slide-3.jpg");
  animation: opacBack4 1s ease-in-out;
}

@keyframes opacBack1 {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
@keyframes opacBack2 {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
@keyframes opacBack3 {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}
@keyframes opacBack4 {
  0% {
    opacity: 0;
  }
  100% {
    opacity: 1;
  }
}

@keyframes pulse {
  to {
    box-shadow: 0 0 0 18px rgba(0, 0, 0, 0.01);
  }
}
</style>