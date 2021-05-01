<template>
  <div class="resume" :class="{dark:dark}">
    <h1>TECHNICAL SKILLS</h1>
    <div class="technicalSkills">
      <div class="c" id="software">
        <h2><i class="user secret icon"/>Software</h2>
        <ul>
          <li>C, C++, C#</li>
          <li>Java</li>
          <li>Python</li>
          <li>HTML, CSS, JavaScript</li>
          <li>Vue.js/framework</li>
          <li>Android Studio</li>
          <li>Arm, 8051 Assembly</li>
          <li>SQL, R</li>
          <li>MATLAB, Simulink</li>
          <li>Verilog(ModelSim/Quartus)</li>
        </ul>
      </div>
      <div class="c" id="hardware">
        <h2><i class="desktop icon"/>Hardware</h2>
        <ul>
          <li>Circuit Analysis/Design</li>
          <li>FPGA, Boolean Logic</li>
          <li>NI Multisim, Ultiboard</li>
          <li>Oscilloscope</li>
          <li>Signal Generator</li>
          <li>Multimeter</li>
          <li>Breadboard</li>
          <li>Soldering Iron</li>
          <li>Circuit Maker</li>
          <li>Network router and switch</li>
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

    <h1>TECHNICAL WORK EXPERIENCE</h1>
    <div class="technicalWorkExperience">
      <h2>Bell Canada Enterprises - Vancouver, Canada <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; September, 2020 – September, 2021</span></h2> 
      <h2>Network Specialist, Solutions Architecture / Software Developer</h2>
      <ul>
          <li>Developed and applied technical knowledge on SONET, Ethernet, IP/MPLS network, application layer protocols, data & network virtualization (SDN/NFV) and data analytics technologies</li>
          <li>Participated in the development and lab verification of new SONET, Ethernet, IP/MPLS and virtualization services and network infrastructure architecture</li>
          <li>Worked with Cisco IOS and JunOS CLI to construct network circuit based on customer needs and conducted layer2 and layer3 tests to make sure each characteristic measurement meet the requirement</li>
          <li>Developed web applications for network device management</li>
          <li>Created script for firmware update and  network device configuration </li>
      </ul>
    </div>

    <div class="technicalWorkExperience">
      <h2>Maxim Integrated - Vancouver, Canada <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; July, 2020 – September, 2020</span></h2>
      <h2>Application Engineer</h2>
      <ul>
        <li>Assisted in the development of new products from conception, through development, testing and final production</li>
        <li>Performed system level and hardware level verification, debug, and testing on new products and create automation test system using python</li>
        <li>Conduct tests and bug reports to detailed problems and the steps to reproduce them</li>
        <li>Researched and developed a firm knowledge of USB, DP, RJ45, and RS 232 standards and worked with all departments throughout the company, including hardware design, software design, marketing, and production</li>
        <li>Worked with Cisco, Netgear, Dell network switches through CLI – configuration, VLAN, subnet, and bandwidth</li>
      </ul>
    </div>
    
    <h1>OTHER WORK EXPERIENCE</h1>
    <div class="technicalWorkExperience">
      <h2>Kingston Live with Style - Vancouver, BC <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; May, 2018 – Present</span></h2>
      <h2>Brand Founder</h2>
      <ul>
          <li>Design creative clothing using Adobe Photoshop and Illustrator, as well as manage production lines</li>
          <li>Manage a website and Instagram account by adding relevant photos and videos, while applying creative marketing skills</li>
          <li>Communicate effectively with customers and partners to ensure they are satisfied with their products</li>
      </ul>
    </div>
    <div class="technicalWorkExperience">
      <h2>UBC Unlimited Dance Club - Vancouver, BC <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; April, 2019 – April, 2020</span></h2>
      <h2>Instructor and Choreographer</h2>
      <ul>
        <li>Create choreography and teach students the fundamentals, technique, and history of Locking dance style</li>
      </ul>
    </div>
    <div class="technicalWorkExperience">
      <h2>UBC Recreation - Vancouver, BC <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; December, 2017 – April, 2020</span></h2>
      <h2>Volleyball and Basketball Referee </h2>
      <ul>
          <li>Responsible for signing in players, reporting scores, and presiding over the game from a neutral point of view to enforce game rules</li>
      </ul>
    </div>

    <h1>VOLUNTEER EXPERIENCE</h1>
    <div class="technicalWorkExperience">
      <h2>UBC Dance Horizons - Vancouver, BC <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; April, 2018 – Present</span></h2>
      <h2>Vice President </h2>
      <ul>
          <li>Lead the PR, Creative, and Event department of the largest dance club in UBC to keep deadlines organized and ensure that all classes, teams, and events are properly promoted and run smoothly</li>
          <li>Write minutes and conduct weekly meetings with an executive team of 40 people</li>
          <li>Broke records in show ticket sales, class attendance, and membership while building a sense of community in the club</li>    
      </ul>
    </div>
    <div class="technicalWorkExperience">
      <h2>UBC Taiwan Association - Vancouver, BC <span>&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; April, 2018 – April, 2020</span></h2>
      <h2>Marketing Director </h2>
      <ul>
        <li>Allocate jobs to marketing executives and collaborate with other departments to make sure the advertisement quality and deadline are meet</li>
        <li>Responsible for creating graphic design of Facebook banners, Instagram posts, Snapchat stories, event posters, handouts, and promo videos</li>
        <li>Apply advertising skills and constantly on the lookout for the club’s image and reputation</li>
      </ul>
    </div>
    
  </div>

  
</template>

<script>
  export default {
    name: 'Resume',
    props: {
      dark: Boolean
    }
  }
</script>

<style scoped>

#others {
  background-color: rgb(255, 241, 230);
}

#hardware {
  background-color: rgb(255, 241, 230);
}

#software {
  background-color: rgb(255, 241, 230);
}

.technicalSkills {
  display: flex;
}

.c {
  display: inline-block;
  width: 33.333%;
  vertical-align: top;
  padding-bottom: 2em;
  height: 22em;
  box-shadow: 0px 5px 5px 0px #9B8F99;
}

.dark #others, .dark #hardware, .dark #software {
  background-color: black;
}

.dark .technicalWorkExperience {
  background-color: black;
}

@media screen and (max-width: 620px) {
  .technicalSkills {
    flex-direction: column;
  }
  .c {
    width: 100%;
  }
}

.technicalSkills ul {
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
  background-color: rgb(255, 239, 226);
}

.technicalWorkExperience h2 {
  margin: 5px 0px;
}

h1 {
  background-color: #9072ad;
  padding: 30px 0px;
  margin: 0px 0px;
  font-family: monospace;
}

</style>

