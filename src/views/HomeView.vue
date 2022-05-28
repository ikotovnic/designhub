<template>
  <div class="div">
    <div class="div-2">
      <div class="builder-columns div-3">
        <div class="builder-column column">
          <div class="div-4">
            <div class="div-5">
              <div class="div-6">design</div>
              <div class="div-7"></div>
            </div>
            <div class="div-8">
              <div class="div-9"></div>
              <div class="div-10">hub</div>
            </div>
          </div>
        </div>
        <div class="builder-column column-2">
          <div class="div-11">
            <div class="builder-columns div-12">
              <div class="builder-column column-3">
                <div class="div-13">about</div>
              </div>
              <div class="builder-column column-4">
                <div class="div-14">for developers</div>
              </div>
              <div class="builder-column column-5">
                <div class="div-15">for employers</div>
              </div>
              <div class="builder-column column-6">
                <div class="div-16">contact</div>
              </div>
            </div>
          </div>
        </div>
      </div>
    </div>
    <div class="div-17">
      <div class="builder-columns div-18">
        <div class="builder-column column-7">
          <div class="we-provide-the-developer-in-a">
            We provide the developer in a short time
          </div>
        </div>
      </div>
    </div>
    <div class="div-19">
      <div class="div-20">
        <div class="builder-columns div-21">
          <div class="builder-column column-8">
            <div class="div-22">You don't have to pay taxes</div>
          </div>
          <div class="builder-column column-9">
            <div class="div-23">No need to hire developers</div>
          </div>
        </div>
      </div>
      <div class="div-24">
        <div class="builder-columns div-25">
          <div class="builder-column column-10">
            <div class="div-26">Hire an employee for a task</div>
          </div>
          <div class="builder-column column-11">
            <div class="div-27">Employees for any period of time</div>
          </div>
        </div>
      </div>
    </div>
    <div class="div-28">
      <div class="div-29">Any type of develpers you need</div>
    </div>
    <div class="div-30">
      <div class="div-31">
        <div class="builder-columns div-32">
          <div class="builder-column column-12">
            <div class="div-33">Interface design</div>
          </div>
          <div class="builder-column column-13">
            <div class="div-34">Motion design</div>
          </div>
        </div>
      </div>
      <div class="div-35">
        <div class="builder-columns div-36">
          <div class="builder-column column-14">
            <div class="div-37">3d-web</div>
          </div>
          <div class="builder-column column-15">
            <div class="div-38">Illustrations</div>
          </div>
        </div>
      </div>
    </div>
  </div>
</template>
<script>
export default {
  name: "my-component",
};
</script>
<style scoped>
.div {
  display: flex;
  flex-direction: column;
  max-width: 1280px;
  justify-content: flex-start;
  padding-top: 35px;
  padding-bottom: 35px;
  background-color: rgba(255, 255, 255, 1);
}
.div-2 {
  display: flex;
  flex-direction: column;
  max-width: 1280px;
  padding-right: 60px;
  padding-left: 60px;
}
.div-3 {
  display: flex;
}
@media (max-width: 999px) {
  .div-3 {
    flex-direction: column;
    align-items: stretch;
  }
}
.column {
  display: flex;
  flex-direction: column;
  line-height: normal;
  width: calc(67.02% - 10px);
  margin-left: 0px;
}
@media (max-width: 999px) {
  .column {
    width: 100%;
  }
}
.div-4 {
  display: flex;
  flex-direction: row;
  max-width: 191px;
  justify-content: flex-start;
  align-items: flex-start;
}
.div-5 {
  display: flex;
  flex-direction: row;
  max-width: 116px;
  justify-content: flex-start;
  align-items: flex-end;
}
.div-6 {
  max-width: 78px;
  color: rgba(0, 0, 0, 1);
  font-size: 24px;
  letter-spacing: 0%;
  text-align: left;
  font-family: Roboto Flex, sans-serif;
}
.div-7 {
  display: flex;
  max-width: 31px;
  height: 6px;
  width: 31px;
  margin-left: 7px;
  background-color: rgba(0, 0, 0, 1);
}
.div-8 {
  display: flex;
  flex-direction: row;
  max-width: 75px;
  justify-content: flex-start;
  align-items: flex-end;
}
.div-9 {
  display: flex;
  max-width: 22px;
  height: 6px;
  width: 22px;
  background-color: rgba(0, 0, 0, 1);
}
.div-10 {
  max-width: 44px;
  margin-left: 9px;
  color: rgba(0, 0, 0, 1);
  font-size: 24px;
  letter-spacing: 0%;
  text-align: left;
  font-family: Roboto Flex, sans-serif;
}
.column-2 {
  display: flex;
  flex-direction: column;
  line-height: normal;
  width: calc(158.25% - 10px);
  margin-left: 20px;
}
@media (max-width: 999px) {
  .column-2 {
    width: 100%;
  }
}
.div-11 {
  display: flex;
  flex-direction: column;
  max-width: 451px;
}
.div-12 {
  display: flex;
}
@media (max-width: 999px) {
  .div-12 {
    flex-direction: column;
    align-items: stretch;
  }
}
.column-3 {
  display: flex;
  flex-direction: column;
  line-height: normal;
  width: calc(18.75% - 15px);
  margin-left: 0px;
}
@media (max-width: 999px) {
  .column-3 {
    width: 100%;
  }
}
.div-13 {
  max-width: 36px;
  color: rgba(0, 0, 0, 1);
  font-size: 14px;
  letter-spacing: 0%;
  text-align: left;
  font-family: Roboto Flex, sans-serif;
}
.column-4 {
  display: flex;
  flex-direction: column;
  line-height: normal;
  width: calc(45.83% - 15px);
  margin-left: 20px;
}
@media (max-width: 999px) {
  .column-4 {
    width: 100%;
  }
}
.div-14 {
  max-width: 88px;
  color: rgba(0, 0, 0, 1);
  font-size: 14px;
  letter-spacing: 0%;
  text-align: left;
  font-family: Roboto Flex, sans-serif;
}
.column-5 {
  display: flex;
  flex-direction: column;
  line-height: normal;
  width: calc(44.27% - 15px);
  margin-left: 20px;
}
@media (max-width: 999px) {
  .column-5 {
    width: 100%;
  }
}
.div-15 {
  max-width: 85px;
  color: rgba(0, 0, 0, 1);
  font-size: 14px;
  letter-spacing: 0%;
  text-align: left;
  font-family: Roboto Flex, sans-serif;
}
.column-6 {
  display: flex;
  flex-direction: column;
  line-height: normal;
  width: calc(24.48% - 15px);
  margin-left: 20px;
}
@media (max-width: 999px) {
  .column-6 {
    width: 100%;
  }
}
.div-16 {
  max-width: 47px;
  color: rgba(0, 0, 0, 1);
  font-size: 14px;
  letter-spacing: 0%;
  text-align: left;
  font-family: Roboto Flex, sans-serif;
}
.div-17 {
  display: flex;
  flex-direction: column;
  max-width: 1280px;
  padding-top: 100px;
  padding-bottom: 100px;
  padding-right: 60px;
  padding-left: 60px;
}
.div-18 {
  display: flex;
}
@media (max-width: 999px) {
  .div-18 {
    flex-direction: column;
    align-items: stretch;
  }
}
.column-7 {
  display: flex;
  flex-direction: column;
  line-height: normal;
  width: calc(79.76% - 0px);
  margin-left: 0px;
}
@media (max-width: 999px) {
  .column-7 {
    width: 100%;
  }
}
.we-provide-the-developer-in-a {
  max-width: 926px;
  color: rgba(0, 0, 0, 1);
  font-size: 70px;
  letter-spacing: 0%;
  text-align: left;
  font-family: Roboto Flex, sans-serif;
}
.div-19 {
  display: flex;
  flex-direction: column;
  max-width: 1280px;
  justify-content: flex-start;
  align-items: flex-start;
  padding-right: 10px;
  padding-left: 10px;
}
.div-20 {
  display: flex;
  flex-direction: column;
  max-width: 1260px;
}
.div-21 {
  display: flex;
}
@media (max-width: 999px) {
  .div-21 {
    flex-direction: column;
    align-items: stretch;
  }
}
.column-8 {
  display: flex;
  flex-direction: column;
  line-height: normal;
  width: calc(50.36% - 10px);
  margin-left: 0px;
}
@media (max-width: 999px) {
  .column-8 {
    width: 100%;
  }
}
.div-22 {
  display: flex;
  flex-direction: column;
  max-width: 464px;
  justify-content: flex-start;
  align-items: flex-start;
  border-radius: 50px;
  padding-top: 50px;
  padding-bottom: 50px;
  padding-right: 50px;
  padding-left: 50px;
  background-color: rgba(255, 153, 0, 1);
  color: rgba(255, 255, 255, 1);
  font-size: 30px;
  letter-spacing: 0%;
  text-align: left;
  font-family: Roboto Flex, sans-serif;
}
.column-9 {
  display: flex;
  flex-direction: column;
  line-height: normal;
  width: calc(50.36% - 10px);
  margin-left: 20px;
}
@media (max-width: 999px) {
  .column-9 {
    width: 100%;
  }
}
.div-23 {
  display: flex;
  flex-direction: column;
  max-width: 464px;
  justify-content: flex-start;
  align-items: flex-start;
  border-radius: 50px;
  padding-top: 50px;
  padding-bottom: 50px;
  padding-right: 50px;
  padding-left: 50px;
  background-color: rgba(0, 117, 255, 1);
  color: rgba(255, 255, 255, 1);
  font-size: 30px;
  letter-spacing: 0%;
  text-align: left;
  font-family: Roboto Flex, sans-serif;
}
.div-24 {
  display: flex;
  flex-direction: column;
  max-width: 1260px;
  margin-top: 10px;
}
.div-25 {
  display: flex;
}
@media (max-width: 999px) {
  .div-25 {
    flex-direction: column;
    align-items: stretch;
  }
}
.column-10 {
  display: flex;
  flex-direction: column;
  line-height: normal;
  width: calc(50.36% - 10px);
  margin-left: 0px;
}
@media (max-width: 999px) {
  .column-10 {
    width: 100%;
  }
}
.div-26 {
  display: flex;
  flex-direction: column;
  max-width: 464px;
  justify-content: flex-start;
  align-items: flex-start;
  border-radius: 50px;
  padding-top: 50px;
  padding-bottom: 50px;
  padding-right: 50px;
  padding-left: 50px;
  background-color: rgba(0, 229, 119, 1);
  color: rgba(255, 255, 255, 1);
  font-size: 30px;
  letter-spacing: 0%;
  text-align: left;
  font-family: Roboto Flex, sans-serif;
}
.column-11 {
  display: flex;
  flex-direction: column;
  line-height: normal;
  width: calc(50.36% - 10px);
  margin-left: 20px;
}
@media (max-width: 999px) {
  .column-11 {
    width: 100%;
  }
}
.div-27 {
  display: flex;
  flex-direction: column;
  max-width: 464px;
  justify-content: flex-start;
  align-items: flex-start;
  border-radius: 50px;
  padding-top: 50px;
  padding-bottom: 50px;
  padding-right: 50px;
  padding-left: 50px;
  background-color: rgba(255, 86, 33, 1);
  color: rgba(255, 255, 255, 1);
  font-size: 30px;
  letter-spacing: 0%;
  text-align: left;
  font-family: Roboto Flex, sans-serif;
}
.div-28 {
  display: flex;
  flex-direction: column;
  max-width: 1280px;
  justify-content: flex-start;
  align-items: flex-start;
  padding-top: 100px;
  padding-bottom: 10px;
  padding-right: 20px;
  padding-left: 20px;
}
.div-29 {
  display: flex;
  flex-direction: column;
  max-width: 464px;
  justify-content: flex-start;
  align-items: flex-start;
  border-radius: 50px;
  padding-top: 50px;
  padding-bottom: 50px;
  padding-right: 50px;
  padding-left: 50px;
  background-color: rgba(200, 200, 200, 1);
  color: rgba(255, 255, 255, 1);
  font-size: 30px;
  letter-spacing: 0%;
  text-align: left;
  font-family: Roboto Flex, sans-serif;
}
.div-30 {
  display: flex;
  flex-direction: column;
  max-width: 1280px;
  justify-content: flex-start;
  align-items: flex-start;
  padding-right: 20px;
  padding-left: 20px;
}
.div-31 {
  display: flex;
  flex-direction: column;
  max-width: 1240px;
}
.div-32 {
  display: flex;
}
@media (max-width: 999px) {
  .div-32 {
    flex-direction: column;
    align-items: stretch;
  }
}
.column-12 {
  display: flex;
  flex-direction: column;
  line-height: normal;
  width: calc(50.79% - 10px);
  margin-left: 0px;
}
@media (max-width: 999px) {
  .column-12 {
    width: 100%;
  }
}
.div-33 {
  display: flex;
  flex-direction: column;
  max-width: 464px;
  justify-content: flex-start;
  align-items: flex-start;
  border-radius: 50px;
  padding-top: 50px;
  padding-bottom: 50px;
  padding-right: 50px;
  padding-left: 50px;
  background-color: rgba(200, 200, 200, 1);
  color: rgba(255, 255, 255, 1);
  font-size: 30px;
  letter-spacing: 0%;
  text-align: left;
  font-family: Roboto Flex, sans-serif;
}
.column-13 {
  display: flex;
  flex-direction: column;
  line-height: normal;
  width: calc(50.79% - 10px);
  margin-left: 20px;
}
@media (max-width: 999px) {
  .column-13 {
    width: 100%;
  }
}
.div-34 {
  display: flex;
  flex-direction: column;
  max-width: 464px;
  justify-content: flex-start;
  align-items: flex-start;
  border-radius: 50px;
  padding-top: 50px;
  padding-bottom: 50px;
  padding-right: 50px;
  padding-left: 50px;
  background-color: rgba(200, 200, 200, 1);
  color: rgba(255, 255, 255, 1);
  font-size: 30px;
  letter-spacing: 0%;
  text-align: left;
  font-family: Roboto Flex, sans-serif;
}
.div-35 {
  display: flex;
  flex-direction: column;
  max-width: 1240px;
  margin-top: 20px;
}
.div-36 {
  display: flex;
}
@media (max-width: 999px) {
  .div-36 {
    flex-direction: column;
    align-items: stretch;
  }
}
.column-14 {
  display: flex;
  flex-direction: column;
  line-height: normal;
  width: calc(50.79% - 10px);
  margin-left: 0px;
}
@media (max-width: 999px) {
  .column-14 {
    width: 100%;
  }
}
.div-37 {
  display: flex;
  flex-direction: column;
  max-width: 464px;
  justify-content: flex-start;
  align-items: flex-start;
  border-radius: 50px;
  padding-top: 50px;
  padding-bottom: 50px;
  padding-right: 50px;
  padding-left: 50px;
  background-color: rgba(200, 200, 200, 1);
  color: rgba(255, 255, 255, 1);
  font-size: 30px;
  letter-spacing: 0%;
  text-align: left;
  font-family: Roboto Flex, sans-serif;
}
.column-15 {
  display: flex;
  flex-direction: column;
  line-height: normal;
  width: calc(50.79% - 10px);
  margin-left: 20px;
}
@media (max-width: 999px) {
  .column-15 {
    width: 100%;
  }
}
.div-38 {
  display: flex;
  flex-direction: column;
  max-width: 464px;
  justify-content: flex-start;
  align-items: flex-start;
  border-radius: 50px;
  padding-top: 50px;
  padding-bottom: 50px;
  padding-right: 50px;
  padding-left: 50px;
  background-color: rgba(200, 200, 200, 1);
  color: rgba(255, 255, 255, 1);
  font-size: 30px;
  letter-spacing: 0%;
  text-align: left;
  font-family: Roboto Flex, sans-serif;
}
</style>
