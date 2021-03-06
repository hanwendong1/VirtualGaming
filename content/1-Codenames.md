---
title: Codenames
nav: true
--- 

{% include figure.html img="Codenames.jpg" alt="Codenames box cover" caption="Give your team clever one-word clues so that they can spot their agents in the field. 
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
            <td style="text-align:Left">Author:</td>
            <td style="text-align:Left">Vlaada Chvátil</td>
         </tr>
         <tr>
            <td style="text-align:Left">Year:</td>
            <td style="text-align:Left">2015</td>
         </tr>
         <tr>
            <td style="text-align:Left">Players:</td>
            <td style="text-align:Left">4+</td>
         </tr>
          <tr>
            <td style="text-align:Left">Time:</td>
            <td style="text-align:Left">15 min</td>
         </tr>
          <tr>
            <td style="text-align:Left">Mechanics:</td>
            <td style="text-align:Left">Words Association, Deduction, Team Play</td>
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

<div style="text-align: center;">
<a class="btn btn-warning" href="https://codenames.game/" role="button" target="_blank">Play Codenames Online!</a>
<a class="btn btn-warning" href="https://documentcloud.adobe.com/link/track?uri=urn:aaid:scds:US:9fdab552-f314-41d0-91c1-e37e4a7efae0" role="button" target="_blank">Official Game Rules</a>
</div>                 

#### Goal

Be the first team to make contact with all of their agents!

#### SETUP
1. Log in to the site
2. Choose team (<span style="color:#FF0000;">red</span> or <span style="color:#0000FF;">blue</span>) and role (one Spymaster and rest are Operatives on each team)
3. The team that has one extra clue to guess goes first

#### GAMEPLAY
First, Spymaster examines the board, then gives an one-word clue followed by a number, which relates to the number of associated cards (exception: 0 and ∞).

{% capture text %}
Can you find 3 cards that relate to the clue "MAPLE"?
{% endcapture %}
{% include card.md text=text header="An Example Clue: MAPLE, 3" img="Codename_Example_Clue.PNG" %}

The clue must
- Relate to word meaning 
- Be a word in English language
- Not be a form or part of a word on any visible card
- Optional variant: Compound/hyphenated words, proper names, abbreviations, acronyms, homonyms, and rhymed words

0 means no clues relate to it. Both 0 and ∞ allow unlimited guessing (unless wrong).

Next, Operatives on that team discuss amongst themselves, then inform their team's Spymaster their guesses (one at a time) up to one more than the number clue provided (if not 0 and ∞). There are four possible scenarios that can occur based on the guesses:
- <span style="color:#FF0000;">Their team’s color (e.g. red) = got a clue and keep guessing until number limit, or may chose to stop</span>
- <span style="color:#0000FF;">The opponent’s color (e.g. blue) = card covered by opponent and turn ends</span>
- <span style="color:#808080;">Bystander (beige) = turn ends</span>
- **Assassin (black) = game ends and that team loses**

#### GAME END
Gameplay continues until endgame condition is met when:
- First team to have all their words covered wins; or
- The team that contacts the assassin instantly loses

Codenames is often played with several rounds, and each round's score will be tallied and counts toward the teams' final scores.
