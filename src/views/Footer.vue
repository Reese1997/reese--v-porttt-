<template>
  <MDBFooter :text="['center', 'black']">
    <!-- Grid container -->
    <MDBContainer class="p-4 pb-0">
      <!-- Section: Social media -->
      <section class="mb-4">
        <!-- Facebook -->
        <MDBBtn
          tag="a"
          color="primary"
          href="#!"
          floating
          style="background-color: #3b5998"
          class="m-1"
        >
          <MDBIcon iconStyle="fab" icon="facebook-f"></MDBIcon>
        </MDBBtn>
        <!-- Twitter -->
        <MDBBtn
          tag="a"
          color="primary"
          href="#!"
          floating
          style="background-color: #55acee"
          class="m-1"
        >
          <MDBIcon iconStyle="fab" icon="twitter"></MDBIcon>
        </MDBBtn>
        <!-- Google -->
        <MDBBtn
          tag="a"
          color="primary"
          href="#!"
          floating
          style="background-color: #dd4b39"
          class="m-1"
        >
          <MDBIcon iconStyle="fab" icon="google"></MDBIcon>
        </MDBBtn>
        <!-- Instagram -->
        <MDBBtn
          tag="a"
          color="primary"
          href="#!"
          floating
          style="background-color: #ac2bac"
          class="m-1"
        >
          <MDBIcon iconStyle="fab" icon="instagram"></MDBIcon>
        </MDBBtn>
        <!-- Linkedin -->
        <MDBBtn
          tag="a"
          color="primary"
          href="#!"
          floating
          style="background-color: #0082ca"
          class="m-1"
        >
          <MDBIcon iconStyle="fab" icon="linkedin-in"></MDBIcon>
        </MDBBtn>
        <!-- Github -->
        <MDBBtn
          tag="a"
          color="primary"
          href="#!"
          floating
          style="background-color: #333333"
          class="m-1"
        >
          <MDBIcon iconStyle="fab" icon="github"></MDBIcon>
        </MDBBtn>
      </section>
      <!-- Section: Social media -->
    </MDBContainer>
    <!-- Grid container -->
    <!-- Copyright -->
    <div
      class="text-center p-3"
      style="background-color: rgb(205, 223, 240)"
    >
      © 2022 Copyright: Reese Abrahams
      <a class="text-white" href="https://mdbootstrap.com/"
        ></a
      >
    </div>
    <!-- Copyright -->
  </MDBFooter>
</template>


<script>
  import { MDBFooter, MDBContainer, MDBRow, MDBCol, MDBBtn } from 'mdb-vue-ui-kit';
  export default {
    components: {
      MDBFooter,
      MDBContainer,
      MDBRow,
      MDBCol,
      MDBBtn
    },
  };
</script>


<style>

</style>