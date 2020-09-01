---
title: Just One
nav: true
---

{% include figure.html img="justone.jpg" alt="Just One box cover" caption="Give one-word clues so someone can guess one word, but duplicate clues are discarded.
(Description from BoardGameGeek)" width="75%" %}

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
            <td style="text-align:Left">Ludovic Roudy, Bruno Sautter</td>
         </tr>
         <tr>
            <td style="text-align:Left">Year:</td>
            <td style="text-align:Left">2018</td>
         </tr>
         <tr>
            <td style="text-align:Left">Players:</td>
            <td style="text-align:Left">3–7</td>
         </tr>
          <tr>
            <td style="text-align:Left">Time:</td>
            <td style="text-align:Left">20 min</td>
         </tr>
          <tr>
            <td style="text-align:Left">Mechanics:</td>
            <td style="text-align:Left">Communication Limits, Cooperative Game</td>
         </tr>
      </table>
   </body>
   <p>
   </p>
</html>
#### Description
The two rival `spymasters` know the secret identities of 25 agents. Their teammates know the agents only by their CODENAMES.

The teams compete to see who can make contact with all of their agents first. `Spymasters` give one-word clues that can point to multiple words on the board. Their teammates try to guess words of the right color while avoiding those that belong to the opposing team. And everyone wants to avoid the `assassin`.

Codenames: win or lose, it’s fun to figure out the clues.

<div style="text-align: center;">
<a class="btn btn-warning" href="https://oneword.games/" role="button">Play Just One Online!</a>
<a class="btn btn-warning" href="https://justone-the-game.com/files/rules/JustOne-Rules-EN.pdf" role="button">Official Game Rules</a>
</div>                 

#### Goal

We work as a team to get the best score!

#### SETUP
1. Log in to the site
2. Choose team (<span style="color:#FF0000;">red</span> or <span style="color:#0000FF;">blue</span>) and role (one `Spymaster` and rest are `Operatives` on each team)
3. The team that has one extra clue to guess goes first

#### GAMEPLAY
First, `Spymaster` examines the board, then gives an one-word clue followed by a number, which relates to the number of associated cards (exception: 0 and ∞).

{% capture text %}
Can you guess what the mystry word is?
{% endcapture %}
{% include card.md text=text header="Example clues to guess the mystry word" img="JO_EN01_Content01.png" %}

The clue must
- Relate to word meaning 
- Be a word in English language
- Not be a form or part of a word on any visible card
- Optional variant: Compound/hyphenated words, proper names, abbreviations, acronyms, homonyms, and rhymed words

0 means no clues relate to it. Both 0 and ∞ allow unlimited guessing (unless wrong).

Then, `Operatives` discuss amongst themselves, then inform the `Spymaster` their guesses (one at a time) up to one more than the number clue provided (if not 0 and ∞). There are four possible scenarios that will occur:
- <span style="color:#FF0000;">Their team’s color (e.g. red) = got a clue and MAY keep guessing until number limit or stopping</span>
- <span style="color:#0000FF;">The opponent’s color (e.g. blue) = card covered by opponent and turn ends</span>
- <span style="color:#808080;">Bystander (beige) = turn ends</span>
- **Assassin (black) = game ends and that team loses**

#### GAME END
Gameplay continues until either endgame condition is met:
- First team to have all their words covered wins 
- The team that contacts the assassin instantly loses
