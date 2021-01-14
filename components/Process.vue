<template>
  <section class="process">
    <h1>The Patient Process</h1>
    <div class="grid-container">
      <div class="grid-item">
        <img src="../assets/images/text-icon-1.png" alt="Text" />
        <h2>Text</h2>
        <p>
          Let’s say your patient is an excellent candidate for a cataract
          surgery. Instead of repeating your typical “why this procedure is
          important for their health” pitch, tell them to text 72000 with your
          unique code.
        </p>
      </div>
      <div class="grid-item">
        <img src="../assets/images/watch-icon-1.png" alt="Text" />
        <h2>Watch & Learn</h2>
        <p>
          The patient watches three 1-minute videos to better understand why
          they are a good candidate for a cataract surgery procedure. This
          quickly helps transfer knowledge and increase acceptance.
        </p>
      </div>
      <div class="grid-item">
        <img src="../assets/images/inquire-icon-1.png" alt="Text" />
        <h2>Inquire</h2>
        <p>
          Now that the patient has more knowledge and insight about the process,
          case acceptance and conversion can be expedited. Patients can quickly
          inquire about an appointment.
        </p>
      </div>
    </div>
  </section>
</template>

<script>
export default {};
</script>

<style lang="scss" scoped>
h1 {
  color: $color-secondary;
  font-size: 3rem;
  font-weight: normal;
  margin-bottom: 2rem;
}

.grid-container {
  display: grid;
  grid-template-columns: 1fr 1fr 1fr;
}

.grid-item {
  margin: 2rem;

  h2 {
    font-weight: normal;
    font-size: 2.5rem;
    color: $color-primary;
    margin: 1rem 0;
  }
}
</style>
