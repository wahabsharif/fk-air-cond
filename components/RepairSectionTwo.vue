<template>
  <section class="about_repair_style_2 repair_area section_padding">
    <div class="container">
      <div class="row">
        <div class="col-md-6">
          <div class="repair_details">
            <div class="hero-section-title">
              <i class="icon-snowflake"></i>
              <h4>HOW WE REPAIR</h4>
              <h1>FK Aircond Solutions</h1>
            </div>
            <p>
              Located in Malaysia, FK Aircond Services specializes in comprehensive
              Airconding solutions. Our services include chemical cleaning, overhaul
              clean, and repair for all brands. We meticulously clean and check air
              filters, front panels, and covers. Additionally, we offer installation of
              new units and dismantle services for existing Airconds.
            </p>
            <a class="btn-orange" href="#">Contact Us</a>
          </div>
        </div>
        <div class="col-md-6">
          <div class="img-grid">
            <div class="grid-row">
              <div>
                <img src="/assets/images/ac-install.png" alt="about image" />
                <p>Aircond Installation</p>
              </div>
              <div>
                <img src="/assets/images/ac-maintenance.png" alt="about image" />
                <p>Aircond-Maintenance</p>
              </div>
            </div>
            <div class="grid-row">
              <div>
                <img src="/assets/images/ac-repair.png" alt="about image" />
                <p>Aircond Repair</p>
              </div>
              <div>
                <img src="/assets/images/ac-replace.png" alt="about image" />
                <p>Aircond Replacement</p>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
  </section>
</template>

<script>
export default {
  name: "RepairSectionTwo",
};
</script>

<style scoped>
.img-grid {
  display: flex;
  flex-direction: column;
}

.grid-row {
  display: flex;
  justify-content: space-between;
  margin-bottom: 20px;
}

.grid-row > div {
  width: calc(50% - 10px); /* Adjust as needed */
}

.img-grid > div > div > img {
  width: 200px;
  height: auto;
}
.img-grid > div > div > p {
  font-size: large;
  font-weight: bold;
  margin-top: 10px;
}
</style>
