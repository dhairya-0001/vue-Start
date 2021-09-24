<template>
  <div class="portfolio-wrapper">
    <div>
      <div class="container1" id="cont1">
        <div id="addingpic">
          <img src="@/assets/pulkit.png" alt="" />
        </div>
        <div id="name">
          <h3>Dhairya Saxena</h3>
        </div>
        <div id="subtitle">
          <h4>UX/UI DEVELOPER | CREATIVE DESIGNER | MSFT GEEK</h4>
        </div>
        <div class="container4" id="cont4">
          <button></button>
        </div>
      </div>
    </div>
  </div>
</template>

<script>
export default {};
</script>

<style>
body {
  background-color: rgb(2, 34, 49);
  color: rgb(175, 169, 169);
  text-shadow: whitesmoke;
}

.portfolio-wrapper {
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}

#cont1 {
  cursor: pointer;
  height: 320px;
  display: flex;
  flex-direction: column;
  align-items: center;
  align-content: center;
}
#addingpic img {
  height: 200px;
  width: 150px;
}
#name {
  font-size: 2.3em;
  padding-top: -50px;
}
#subtitle {
  font-size: 1em;
  padding-top: 20px;
}

#subtitle:hover {
  color: rgb(177, 248, 177);
}
#cont4 button {
  height: 50px;
  width: 50px;
  border-radius: 50%;
  position: absolute;
  top: 8%;
  right: 8%;
  background-color: aquamarine;
  padding: 3px;
  border: rgb(2, 34, 49);
}
#cont4 :hover {
  cursor: pointer;
}
</style>