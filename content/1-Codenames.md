---
title: Codenames
nav: true
--- 

{% include figure.html img="Codenames.jpg" alt="Codenames box cover" caption="Give your team clever one-word clues so that they can spot their agents in the field. (Description from BoardGameGeek)" width="75%" %}

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
            <td style="text-align:Left">Author:</td>
            <td style="text-align:Left">Vlaada Chvátil</td>
         </tr>
         <tr>
            <td style="text-align:Left">Year:</td>
            <td style="text-align:Left">2015</td>
         </tr>
         <tr>
            <td style="text-align:Left">Players:</td>
            <td style="text-align:Left">2–8+ (competitive: 4–8+)</td>
         </tr>
          <tr>
            <td style="text-align:Left">Time:</td>
            <td style="text-align:Left">15 min</td>
         </tr>
          <tr>
            <td style="text-align:Left">Theme:</td>
            <td style="text-align:Left">spies, agents, revealing secret identities</td>
         </tr>
          <tr>
            <td style="text-align:Left">Mechanics:</td>
            <td style="text-align:Left">words association, deduction, team play</td>
         </tr>
      </table>
   </body>
   <p>
   </p>
</html>
#### Description
The two rival spymasters know the secret identities of 25 agents. Their teammates know the agents only by their CODENAMES.

The teams compete to see who can make contact with all of their agents first. Spymasters give one-word clues that can point to multiple words on the board. Their teammates try to guess words of the right color while avoiding those that belong to the opposing team. And everyone wants to avoid the assassin.

Codenames: win or lose, it’s fun to figure out the clues.

{% include button.md text="Play Codenames Online!" link="https://codenames.game/" color="warning" %}

#### Goal

Be the first team to make contact with all of their agents!

#### SETUP
1. Log in to the site. 
2. Choose team (red or blue) and role (each team has one Spymaster and rest are Operatives).
3. The team that has one extra clue to guess goes first. 

#### GAMEPLAY
1. `Spymaster` examines the board, then gives [an one-word clue followed by a number](https://codenamesgame.com/), which relates to the number of associated cards (exception: 0 and ∞): e.g.: library, 5

The clue must
- Relate to word meaning 
  - Be a word in English language
  - Not be a form or part of a word on any visible card. 
  - Optional variant: Compound/hyphenated words, proper names, abbreviations, acronyms, homonyms, and rhymed words

{% capture text %}
Can you find 3 cards that relate to the clue "MAPLE"?
{% endcapture %}
{% include card.md text=text title="Example Clue" img="Codename_Example_Clue.png" %}{% endraw %}

2. `Operatives` discuss amongst themselves, then inform the `Spymaster` their guesses (one at a time) up to one more than the number clue provided (if not 0 and ∞)
- Their team’s color (e.g. red) = got a clue and MAY keep guessing until number limit or stopping
- The opponent’s color (e.g. blue) = card covered by opponent and turn ends
- Bystander (beige color) = turn ends
- Assassin (black) = game ends and that team loses

#### GAME END
Gameplay continues until endgame condition is met:
- First team to have all their words covered wins 
- The team that contacts the assassin instantly loses. 


