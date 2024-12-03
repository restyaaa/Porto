<script setup>

</script>

<template>
  <div class="profile">
    <!-- TIP: For best results, use a photo with a transparent background like the demo example below-->
    <!-- Watch a tutorial on how to do this on YouTube (link)-->
    <img class="profile-img" src="/images/restya.png" alt="..." />
  </div>
</template>


<style scoped>
.feature {
  display: inline-flex;
  align-items: center;
  justify-content: center;
  height: 3rem;
  width: 3rem;
  font-size: 1.5rem;
}

.profile {
  position: relative;
  height: 75vw;
  width: 75vw;
  border-radius: 5vw;
  margin-top: 5vw;
  max-height: 50rem;
  max-width: 50rem;
}
.profile .profile-img {
  height: 100vw;
  max-height: 65rem;
  position: absolute;
  bottom: 0;
  left: 50%;
  transform: translateX(-50%);
}
@media (min-width: 576px) {
  .profile {
    height: 25vw;
    width: 25vw;
  }
  .profile .profile-img {
    height: 25vw;
  }
  .profile .dots-1 {
    width: 3vw;
    right: 1.5vw;
  }
  .profile .dots-2 {
    width: 3vw;
    right: -4vw;
  }
  .profile .dots-3 {
    width: 3vw;
    left: 1.5vw;
  }
  .profile .dots-4 {
    width: 3vw;
    left: -4vw;
  }
}
@media (min-width: 768px) {
  .profile {
    height: 35vw;
    width: 35vw;
  }
  .profile .profile-img {
    height: 35vw;
  }
  .profile .dots-1 {
    width: 3vw;
    right: 1.5vw;
  }
  .profile .dots-2 {
    width: 3vw;
    right: -4vw;
  }
  .profile .dots-3 {
    width: 3vw;
    left: 1.5vw;
  }
  .profile .dots-4 {
    width: 3vw;
    left: -4vw;
  }
}
@media (min-width: 992px) {
  .profile {
    height: 35vw;
    width: 35vw;
  }
  .profile .profile-img {
    height: 35vw;
  }
  .profile .dots-1 {
    width: 1.5vw;
    right: 0.75vw;
  }
  .profile .dots-2 {
    width: 1.5vw;
    right: -2vw;
  }
  .profile .dots-3 {
    width: 1.5vw;
    left: 0.75vw;
  }
  .profile .dots-4 {
    width: 1.5vw;
    left: -2vw;
  }
}
@media (min-width: 1200px) {
  .profile {
    height: 25vw;
    width: 25vw;
  }
  .profile .profile-img {
    height: 25vw;
  }
  .profile .dots-1 {
    width: 1.5vw;
    right: 0.75vw;
  }
  .profile .dots-2 {
    width: 1.5vw;
    right: -2vw;
  }
  .profile .dots-3 {
    width: 1.5vw;
    left: 0.75vw;
  }
  .profile .dots-4 {
    width: 1.5vw;
    left: -2vw;
  }
}
</style>