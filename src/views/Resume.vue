<template>
  <div class="resume">
    <h1>Technical Skills</h1>
    <div class="row">
      <div class="c" id="software">
        <h2><i class="user secret icon"/>Software</h2>
        <ul>
          <li>C, C++, C#</li>
          <li>Java</li>
          <li>Python</li>
          <li>HTML, CSS, JavaScript</li>
          <li>Vue.js/framework</li>
          <li>Android Studio</li>
          <li>Arm and 8051 Assembly</li>
          <li>SQL, R</li>
          <li>MATLAB, Simulink</li>
          <li>Verilog(ModelSim/Quartus)</li>
        </ul>
      </div>
      <div class="c" id="hardware">
        <h2><i class="desktop icon"/>Hardware</h2>
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
        <h2><i class = "paint brush icon"/>Others</h2>
        <ul>
          <li>Bilingual English and Mandarin</li>
          <li>Knowledge of data structures and algorithms</li>
          <li>Knowledge of Network layering and protocol</li>
          <li>Git, Git bash</li>
          <li>Linux</li>
          <li>Cisco IOS, JunOS</li>
          <li>Microsoft Office Word/Excel/PowerPoint</li>
          <li>Adobe Photoshop/ Illustrator</li>
          <li>Solidworks</li>
          <li>SimulationX</li>
        </ul>
      </div>
    </div>

    <h1>Technical Work Experience</h1>
    <div class="technicalWorkExperience">
      <h2>Bell Canada Enterprises - Vancouver, Canada <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; September, 2020 – September, 2021</span></h2> 
      <h2>Network Specialist, Solutions Architecture / Software Developer</h2>
      <ul>
          <li>Develop and apply technical knowledge on SONET, Ethernet, IP/MPLS network, application layer protocols, data & network virtualization (SDN/NFV) and data analytics technologies</li>
          <li>Participate in the development and lab verification of new SONET, Ethernet, IP/MPLS and virtualization services and network infrastructure architecture.</li>
          <li>Construct network circuit based on customer’s need and conduct Layer2 and Layer3 test to make sure each characteristic measurement meet the requirement. Work with Cisco IOS and JunOS CLI.</li>
          <li>Develop web application for network device management. Create script for firmware update and device configuration.</li>
      </ul>
    </div>

    <div class="technicalWorkExperience">
      <h2>Maxim Integrated - Vancouver, Canada <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; July, 2020 – September, 2020</span></h2>
      <h2>Application Engineer</h2>
      <ul>
        <li>Assist in the development of new products from conception, through development, testing and final production</li>
        <li>Perform system level and hardware level verification, debug, and testing on new products and create automation test system.</li>
        <li>Write bug reports which clearly detail the problem and how to reproduce it.</li>
        <li>Research and develop a firm knowledge of USB, DP, RJ45, and RS 232 standards and work with all different groups including hardware design, software design, marketing, and production.</li>
        <li>Work with Cisco, Netgear, Dell network switches through CLI – configuration, VLAN, subnet, and bandwidth.</li>
      </ul>
    </div>
    
    <h1>Other Work Experience</h1>
    <div class="technicalWorkExperience">
      <h2>Kingston Live With Style - Vancouver, BC <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; May, 2018 – Present</span></h2>
      <h2>Brand Founder</h2>
      <ul>
          <li>Design creative clothing using photoshop and illustrator, as well as manage production line</li>
          <li>Manage website and Instagram by adding relevant photos, videos, and applying creative marketing skills</li>
          <li>Communicate effectively with customers and partners to ensure they are satisfied with the products</li>
      </ul>
    </div>
    <div class="technicalWorkExperience">
      <h2>UBC Unlimited Dance Club - Vancouver, BC <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; April, 2019 – April, 2020</span></h2>
      <h2>April, 2019 – April, 2020</h2>
      <ul>
        <li>Create choreography and teach students the fundamentals and technique of Locking, a style of dance</li>
      </ul>
    </div>
    <div class="technicalWorkExperience">
      <h2>UBC Recreation - Vancouver, BC <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; December, 2017 – April, 2020</span></h2>
      <h2>Volleyball and Basketball Referee </h2>
      <ul>
          <li>Responsible for signing in players, reporting scores, and presiding over the game from a neutral point of view to enforce the rules</li>
      </ul>
    </div>

    <h1>Volunteer Experience</h1>
    <div class="technicalWorkExperience">
      <h2>UBC Dance Horizons - Vancouver, BC <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; April, 2018 – Present</span></h2>
      <h2>Vice President </h2>
      <ul>
          <li>Design creative clothing using photoshop and illustrator, as well as manage production line</li>
          <li>Manage website and Instagram by adding relevant photos, videos, and applying creative marketing skills</li>
          <li>Communicate effectively with customers and partners to ensure they are satisfied with the products</li>
      </ul>
    </div>
    <div class="technicalWorkExperience">
      <h2>UBC Taiwanese Association - Vancouver, BC <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; April, 2018 – April, 2020</span></h2>
      <h2>Marketing Director </h2>
      <ul>
        <li>Responsible for creating graphic design of Facebook banners, Instagram posts, Snapchat stories, event posters, handouts, and promo videos</li>
        <li>Apply advertising skills and constantly on the lookout for the club’s image and reputation</li>
      </ul>
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
  width: 33.333%;
  vertical-align: top;
  padding-bottom: 2em;
  height: 18em;
  box-shadow: 0px 5px 5px 0px #9B8F99;
}

@media screen and (max-width: 620px) {
  .row {
    flex-direction: column;
  }
  .c {
    width: 100%;
  }
}

.row ul {
  margin: 0 auto;
  text-align: left;
  width: 25vw;
}

@media screen and (max-width: 620px) {
  ul {
    width: 100vw;
  }
}

span {
  font-size: 0.7em;
  font-style: italic;
  font-family: 'Times New Roman', Times, serif;
  text-align: right;
}

.technicalWorkExperience {
  text-align: left;
  padding: 10px 40px;
  background-color: cornflowerblue;
}

.technicalWorkExperience h2 {
  margin: 5px 0px;
}
</style>

