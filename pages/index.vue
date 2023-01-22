<style scoped>
.bosaButton {
  width: 75%;
  padding: 8px;
  margin: 5px;
}
</style>

<template>
  <div>
    <section class="py-5 text-center container">
      <div class="row py-lg-5">
        <div class="col-lg-6 col-md-8 mx-auto">
          <h1 class="fw-normal">
            {{ $t("GHENT_PORTAL.WELCOME") }}
          </h1>
          <p class="lead text-muted fw-normal mb-4">
            {{ $t("GHENT_PORTAL.CHOOSE_ACTION") }}
          </p>
          <div>
            <div>
              <div>
                <nuxt-link to="GhentSignup" class="btn btn-primary bosaButton"
                  >Get your VerifiableId credential</nuxt-link
                >
              </div>
              <div>
                <nuxt-link to="GhentPortal" class="btn btn-secondary bosaButton"
                  >Go to BOSA Portal</nuxt-link
                >
              </div>
            </div>
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
</style>
