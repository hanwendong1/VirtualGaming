---
title: Insider
nav: true
---

{% include figure.html img="insider.jpg" alt="Insider box cover" caption="20 questions with a twist... a time limit and a sneaky insider who knows the answer! (Description from BoardGameGeek)" width="75%" %}

#### Overview
<html>
   <head>
      <style>
         table {width: 100%;}
         table, td, th {
            border-collapse: collapse;
            padding: 8px;
            border-bottom: 1px solid #ddd;
         
         th {            
            style="text-align:Center"
            border: 1px solid black;
            padding-top: 12px;
            padding-bottom: 12px;
            background-color: #f1b300;
            color: white;
            }
      </style>
   </head>
   <body>
      <table>
         <tr>
            <td style="text-align:Left">Authors:</td>
            <td style="text-align:Left">Kwaji, Daichi Okano, Kito Shinma, ｱｷﾋﾛｲﾄｵ (Akihiro Itoh)</td>
         </tr>
         <tr>
            <td style="text-align:Left">Year:</td>
            <td style="text-align:Left">2018</td>
         </tr>
         <tr>
            <td style="text-align:Left">Players:</td>
            <td style="text-align:Left">4–8</td>
         </tr>
          <tr>
            <td style="text-align:Left">Time:</td>
            <td style="text-align:Left">15 min</td>
         </tr>
          <tr>
            <td style="text-align:Left">Mechanics:</td>
            <td style="text-align:Left">Cooperative Game, Team-Based Game, Voting</td>
         </tr>
      </table>
   </body>
   <p>
   </p>
</html>
#### Description
"Insider“ combines two fun components: finding the answer to a quiz and revealing the Insider. While communicating to others you have to find the right answers to a quiz and also find the "Insider" that is manipulating the discussion. The Insider will do everything to hide their identity while misleading the others.

<div style="text-align: center;">
<a class="btn btn-warning" href="https://insider-online.herokuapp.com/" role="button">Play Insider Online!</a>
<a class="btn btn-warning" href="https://boardgamegeek.com/thread/1631598/rules" role="button">Official Game Rules</a>
</div>                 

#### Goal

To find the secret word!
- If the word is not found, everyone loses.
- If the word is found and the Insider is accused, Master and Commons win.
- If the word is found and the Insider is not accused, Insider wins.

#### SETUP
1. Log in to the site
2. Enter a player name 
3. Roles are assigned randomly: 1 Master, 1 Insider, rest are Commons, but only the Master and the Insider know the secret word.

#### GAMEPLAY
The game begins with a quiz. Ask the Master who knows the current theme questions! He/she can only answer "Yes", "No" or "I don't know".

{% capture text %}
"Is it an animal?" - "No"
"Was it existent 100 years ago?" - "Yes"
"Can I buy it at the supermarket?" - "No"
{% endcapture %}
{% include card.md text=text header="Example questions" img="insider_example.jpg" %}

The players have to find the answer by asking many questions. They only have 5 minutes to find it though. If they don't find the right answer in that time, everyone will lose! The quiz is not easy, but the players find the answer most of the time anyway, which is because there is one insider among them who knows the right answer. He/she tries to stay incognito and controlls the others asking questions that will help them to get closer to the right answer. If someone notices who he/she is, he/she will lose, so it is very important to stay unrecognized.

{% capture text %}Tip for the Insider: You know the answer but you don't want to reveal yourself, so use your knowledge to subtly guide the conversation with the right questions without being too obvious about it.
{% endcapture %} {% include alert.md text=text color="warning" %}

#### GAME END
The game ends if the answer is not found, then everyone loses. 

If the answer is found, however, then the timer is flipped. This elapsed time is now used to try to identify the Insider. Everyone (including Master) discusses and tries to find the insider among them. Everyone votes for the person they think the player who guessed the word is the Insider or not. Master decides the tiebreaker.

This can have four possible outcomes:
- Majority thumbs up
  - If the guesser is Insider, Commons and Master win. 
  - If the guesser is not the Insider, Insider wins. 
- Majority thumbs down
  - If the guesser is Insider, Insider wins. 
  - If the guesser isn't Insider, a second voting occurs.

SECOND VOTING
Vote for the person who players think the Insider is. The Master decides the tiebreaker.
This can have two possible outcomes:
- If the Insider is accused, Master and Commons win.  
- If the Insider is not accused, Insider wins.  
