<template>
  <div class="claimWrapper">
    <h1 class="claim">SPACER</h1>
    <p class="subclaim">
      Begin your journey thorugh our amazing galaxy, and discover
    </p>
    <p class="subclaim">
      Type anything space-related to start.
    </p>
  </div>
</template>
<script>
export default {
  name: 'Claim',
};
</script>
<style lang="scss" scoped>
.claimWrapper{
  display: flex;
  text-align: center;
  flex-direction: column;
  justify-content: center;
  align-items: center;
}

.claim {
  font-size: 50px;
}

.subclaim{
  font-size: 13px;
  margin-top: 20px 0 0 0;

}

</style>
