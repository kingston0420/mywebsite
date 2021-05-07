<template>
  <div class="project">
    <h1>My Project</h1>
        <table> 
            <thead> 
                <tr> <th>Name</th> <th>Software</th> <th>Sorce Code/Demo</th>  <th>Discription</th> </tr> 
            </thead> 
            <tbody id="stocksTerminal"> 
                <tr v-for="p in projects" :key="p.name"> 
                  <td>{{ p.name }}</td>
                  <td>{{p.software}}</td> 
                  <td><a :href="p.link" target="_blank">Source Code</a><br><br><a :href="p.demoLink" target="_blank">{{p.demo}}</a>  </td> 
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
        { name: 'DH Game', software: 'VueJs, HTML, CSS', link: 'https://github.com/kingston0420/dhgame', demo:'Website', demoLink:'https://kingston0420.github.io/dhgame/#/', discription: 'This is a web game created to let people hangout and social virtually during the pandemic.'},
        { name: 'Unquote', software: 'Java, Android Studio', link: 'https://github.com/kingston0420/UnquoteAndroidApp', demo:'Demo', demoLink:'https://www.youtube.com/watch?v=MCnJg8QAIdw', discription: 'Unquote is an android app game created with Java and Android Studio. Each round a random quote is displayed on the screen with misleading picture. Players have to choose the right person that the quote is from and compete to earn the most points'},
        { name: 'LeetCode', software: 'Java', link: 'https://github.com/kingston0420/LeetCode', demo:'', demoLink:'', discription: 'Documentation of my progress and solutions to interview question on LeetCode. '},
        { name: 'This Website', software: 'VueJs, HTML, CSS', link: 'https://github.com/kingston0420/mywebsite', demo:'Website', demoLink:'https://kingston0420.github.io/mywebsite/#/', discription: 'A website aim to show case my portfolio, experiences, and connect with professionals in the same field.'},
        { name: 'Greedy Snake', software: 'Python, Pygame', link: 'https://github.com/kingston0420/GreedySnake', demo:'Demo', demoLink:'https://www.youtube.com/watch?v=X8dKiUKKyao', discription: 'This is a snake game made using Python. Player can control the snake with keyboard. Message is displayed after each round with the reason of losing and the score for that round. The snake and the snack are made with the same colors as the logo of Python.'},
        { name: 'Tic Tac Toe', software: 'C++', link: 'https://github.com/kingston0420/Tic-Tac-Toe', demo:'Demo', demoLink:'https://www.youtube.com/watch?v=HmMEEtmvuvI', discription: 'This is a Tic-Tac-Toe game that can be play with 2 players. Whoever connects a line first wins the game. Compete with your friend to win!!'},
        { name: 'Rock Paper Scissors Lizard Spock', software: 'C++', link: 'https://github.com/kingston0420/Rock-Paper-Scissors-Lizard-Spock', demo:'Demo', demoLink:'https://www.youtube.com/watch?v=JeCwlSbLuHY', discription: 'There are two version of the game. First version is the traditional rock-paper-scissors.Second version is the rock-paper-scissors-lizard-spock. Compete with the computer to win!!'},
        { name: 'Harry Potter Sorting Hat', software: 'C++', link: 'https://github.com/kingston0420/Harry-Potter-Sorting-Hat', demo:'Demo', demoLink:'https://www.youtube.com/watch?v=IfR_NOP8V38', discription: 'A Harry Potter sorting hat that will place you to the house you belong to.'},
        { name: 'Network Ping', software: 'Python', link: 'https://github.com/kingston0420/ELEC-331-NetworkPing', demo:'', demoLink:'', discription: 'This is a course project for ELEC331 (Computer Communication). The project is made using Python to simulate ping between client and server with TCP and UDP.'},
        { name: 'Embedded Projects', software: 'C, Assembly', link: 'https://github.com/kingston0420/ELEC-291-', demo:'', demoLink:'', discription: 'These are course projects for ELEC291. In this course I built different embedded projects, including Lab1: LED, LCD display circuit, Lab2: an alarm clock, Lab3: Temperature Sensor, Lab4: 555 Timer/Capacitance Meter, Lab5: AC phasor voltmeter, Lab6: DC motors Car, and Individual Project: Coin Sensor. All the projects are built using microcontroller circuit, C, and assembly language.'},
        { name: 'Excursion Website', software: 'HTML, CSS', link: 'https://github.com/kingston0420/Excursion-Project', demo:'Website', demoLink:'https://kingston0420.github.io/Excursion-Project/', discription: 'This is a website built using HTML and CSS to advertise a new phone app.'}
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
    width: 95vw;
    max-width: 1000px; 
    box-shadow: 0px 5px 5px 0px #9B8F99;
/*    white-space: nowrap; */
  }
  .dis {
    white-space: normal;
  } 

  th {
      background-color: #9072ad;
  }

  th, td {
    width: 25%;
  }


</style>