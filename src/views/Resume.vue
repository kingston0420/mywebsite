<template>
  <div class="resume">
    <h1>Technical Skills</h1>
    <div class="row">
      <div class="c" id="software">
        <h2>Software</h2>
        <ul>
          <li>C, C++, C#</li>
          <li>Java</li>
          <li>Python</li>
          <li>HTML, CSS, JavaScript</li>
          <li>Arm and 8051 Assembly</li>
          <li>R</li>
          <li>MATLAB, Simulink</li>
          <li>SimulationX</li>
          <li>Verilog(ModelSim/Quartus)</li>
        </ul>
      </div>
      <div class="c" id="hardware">
        <h2>Hardware</h2>
        <ul>
          <li>Circuit Analysis/Design</li>
          <li>Boolean Logic</li>
          <li>FPGA</li>
          <li>Oscilloscope</li>
          <li>Signal Generator</li>
          <li>Multimeter</li>
          <li>Breadboard</li>
          <li>Soldering Iron</li>
          <li>Circuit Maker</li>
          <li>Network router, switch and NID</li>
        </ul>
      </div>
      <div class="c" id="others">
        <h2>Others</h2>
        <ul>
          <li>Bilingual English and Mandarin</li>
          <li>Git, Git bash</li>
          <li>Adobe Photoshop/ Illustrator</li>
          <li>Microsoft Office Word/Excel/PowerPoint</li>
          <li>3D printing</li>
          <li>Solidworks</li>
          <li>Knowledge of data structures and algorithms</li>
          <li>Knowledge of Network layering and protocol</li>
        </ul>
      </div>
    </div>

    <div class="technicalExperience">
      <h1>Bell Canada Enterprises </h1>
    </div>


  </div>

  
</template>

<style scoped>

#others {
  background-color: cyan;
}

#hardware {
  background-color: chartreuse;
}

#software {
  background-color: rgb(202, 243, 20);
}

.row {
  display: flex;
}

.c {
  display: inline-block;
  width: 33%;
  vertical-align: top;
  padding-bottom: 2em;
  height: 18em;
}

@media screen and (max-width: 620px) {
  .row {
    flex-direction: column;
  }
  .c {
    width: 100%;
  }
}

ul {
  margin: 0 auto;
  text-align: left;
  width: 25vw;
}

@media screen and (max-width: 620px) {
  ul {
    width: 100vw;
  }
}

</style>

