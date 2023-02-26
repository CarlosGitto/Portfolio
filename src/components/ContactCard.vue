<template>
  <div class="row">
    <div class="col-6">
      <div class="d-flex flex-column h-100 justify-content-between pb-5">

        <h3 class="text-start mt-3 fw-bold">Contact me</h3>
        <p class="text-start">
          <q>Your big opportunity may be right where you are now.</q>
          <br />
          <span class="text-start fst-italic ps-2"> Napoleon Hill </span>
        </p>
      </div>
    </div>
    <div class="col-6">
      <div class="d-flex flex-column h-100 justify-content-between px-2">

      <form class="">
        <div class="d-flex flex-row mb-3">
          <input type="text" class="form-control me-2" placeholder="Subject" />
          <input type="email" class="form-control" placeholder="E-mail" />
        </div>
        <div class="mb-3">
          <textarea
            type="text"
            class="form-control"
            placeholder="Message"
            rows="10"
          ></textarea>
        </div>

        <button type="submit" class="w-100 btn background-secondary-color text-accent-color">
          Send</button>

      </form>
      </div>
    </div>
  </div>
</template>

<script>
export default {
  name: "ContactCard",
};
</script>

<style>
textarea {
  resize: none;
}
</style>
