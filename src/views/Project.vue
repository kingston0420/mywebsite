<template>
  <div class="project">
    <h1>My Project</h1>
        <table> 
            <thead> 
                <tr> <th>Name</th> <th>Software</th> <th>Sorce Code</th>  <th>Discription</th> </tr> 
            </thead> 
            <tbody id="stocksTerminal"> 
                <tr v-for="p in projects" :key="p.name"> 
                  <td>{{ p.name }}</td>
                  <td>{{p.software}}</td> 
                  <td><a :href="p.link" target="_blank"> {{ p.link }} </a> </td> 
                  <td class="dis">{{p.discription}}</td>
                </tr> 
            </tbody> 
        </table>
  </div>
</template>

<script>      
  export default {
 name: 'project',
 data ()  {
  return {
    projects: [
        { name: 'DH Game', software: 'VueJs, HTML, CSS', link: 'https://github.com/kingston0420/dhgame', discription: 'This is a web game created to let people hangout and social virtually during the pandemic.'},
        { name: 'Unquote', software: 'Java, Android Studio', link: 'https://github.com/kingston0420/UnquoteAndroidApp', discription: 'Unquote is an android app game created with Java and Android Studio. Each round a random quote is displayed on the screen with misleading picture. Players have to choose the right person that the quote is from and compete to earn the most points'},
        { name: 'LeetCode', software: 'Java', link: 'https://github.com/kingston0420/LeetCode', discription: 'Documentation of my progress and solutions to interview question on LeetCode. '},
        { name: 'This Website', software: 'VueJs, HTML, CSS', link: 'https://github.com/kingston0420/mywebsite', discription: 'A website aim to show case my portfolio, experiences, and connect with professinals in the same field.'},
        { name: 'Greedy Snake', software: 'Python, Pygame', link: 'https://github.com/kingston0420/GreedySnake', discription: 'This is a snake game made using Python. Player can control the snake with top, down, left, right. There is message dispaly after each round with the reason of losing and the score for that round. The snake and the snack are made with same colors as the logo of Python.'},
        { name: 'Network Ping - ELEC 331', software: 'Python', link: 'https://github.com/kingston0420/ELEC-331-NetworkPing', discription: 'This is a course project for ELEC331 (Computer Communication). The project is made using Python to simulate ping between client and server with TCP and UDP.'},
        { name: 'ELEC 291', software: 'C, Assembly', link: 'https://github.com/kingston0420/ELEC-291-', discription: 'Using Microcontroller and circuit to display message on the LCD and control LED blinking'},
        { name: 'Excursion Website', software: 'HTML, CSS', link: 'https://github.com/kingston0420/Excursion-Project', discription: 'This is a mini project using HTML and CSS to create a website that advertises a new phone app.'}
    ]
    }
  }
 }
</script>

<style scoped>
  table, th, td {
    border: 3px solid black;
    padding: 1em;
  }

  table {
    border-collapse: collapse;
    margin: 0 auto;
    max-width: 800px; 
    box-shadow: 0px 5px 5px 0px #9B8F99;
    white-space: nowrap;
  }
  .dis {
    white-space: normal;
  } 

  th {
      background-color: #9072ad;
  }


</style>