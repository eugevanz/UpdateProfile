<template>
  <div id="app">
    <!-- Image and text -->
    <nav class="navbar navbar-dark" style="background-color: #275893;">
      <div class="container-fluid">
        <a class="navbar-brand" href="#">
          <img src="./assets/logo_white.png" alt="" height="48" class="d-inline-block align-bottom">
          <span class="ms-5 fs-3">Update profile</span>
        </a>
        <img src="./assets/3dots.001.png" alt="" width="96" class="d-inline-block align-bottom">
      </div>
    </nav>

    <div class="row">
      <div class="col-8">
        <div class="m-5">
          <form>
            <p style="font-size: 0.75em;" class="mb-2 fw-bold text-muted">Role type</p>
            <div class="form-check form-check-inline ms-3">
              <input class="form-check-input" type="radio" name="roletypeOptions" id="contractorRadio" value="option1">
              <label class="form-check-label fs-6 fw-bold" for="contractorCheck">Contractor</label>
            </div>
            <div class="form-check form-check-inline ms-3">
              <input class="form-check-input" type="radio" name="roletypeOptions" id="queueRadio" value="option2">
              <label class="form-check-label fs-6 fw-bold" for="queueCheck">Queue Agent</label>
            </div>
            
            <div class="row mt-5">
              <div class="col mb-2">
                <label for="idInput" class="form-label ms-3 fw-bold text-muted" style="font-size: 0.75em;">South African ID number</label>
                <input type="text" class="form-control" id="idInput" aria-describedby="idHelp" required>
              </div>
              <div class="col mb-2">
                <label for="nameInput" class="form-label ms-3 fw-bold text-muted" style="font-size: 0.75em;">Name</label>
                <input type="text" class="form-control" id="nameInput" aria-describedby="nameHelp" required>
              </div>
            </div>

            <div class="row">
              <div class="col mb-2">
                <label for="emailInput" class="form-label ms-3 fw-bold text-muted" style="font-size: 0.75em;">Email</label>
                <input type="email" class="form-control" id="emailInput" aria-describedby="emailHelp">
              </div>
              <div class="col mb-2">
                <label for="phoneInput" class="form-label ms-3 fw-bold text-muted" style="font-size: 0.75em;">Phone number</label>
                <input type="text" class="form-control" id="phoneInput" aria-describedby="phoneHelp">
              </div>
            </div>

            <button type="submit" class="btn my-5 fw-bold px-5 py-2" style="background-color: #275893; color: white;">Continue</button>
          </form>
        </div>
      </div>
      <div class="col d-flex flex-column align-items-center" style="background-color: #275893; height: 95vh">
        <img src="./assets/D5cYwzoWAAAQqHS.jpg" class="mx-auto d-block my-4" alt="..." style="border-radius: 50%; width: 192px; height: 192px; border: 8px solid white;">
        <p class="fs-2 mb-2 text-center" style="color: white;">Hester Evelyne Duffey</p>
        <p class="fs-6 text-center" style="width: 256px; line-height: 1; color: white;">Complete your profile and press <b>"Continue"</b> to save changes</p>
        <button type="button" class="btn my-3 fw-bold px-5 py-2" style="background-color: #F7931E; color: #275893;">This is not me</button>
      </div>
    </div>
  </div>
</template>

<script>
export default {
}
</script>

<style>
#app {
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
  color: #2c3e50;
}
</style>
