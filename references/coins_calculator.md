---
layout: default
title: Servant Coins Calculator
parent: References
nav_order: 2
---

# Servant Coins Calculator
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>
---

{: .warning}
This page currently doesn't have details on the changes introduced from the 9th Anniversary Update (August 2024).

# Servant Coins
- Servant Coins was introduced in the 6th Anniversary of the game (August 2021 for JP, ~July 2023 for NA)
- Players got retroactive coins (sent to the Inbox) for existing copies based on the Bond Level (all Rarities) and the Number of copies you obtained (4* and 5* only, Welfares not included) during the Anniversary. 
- Any future coins from Bond Up/NP copy are automatically added to your Coins Inventory
- New welfare units got coins from their Event's shops. Old welfare units will eventually get their coins
    - Currently (May 2022) only the following old welfares got coins: Elizabeth Variants (HW 2021), Bunyan (Learning with Manga Collab)
    - Those that had reruns after Anni6 also got coins in their respective events: Gray, Nobukatsu
    - Old welfares obtainable from Main Interludes/RP shop don't give out coins
    - With the recently released Evocation Festivals, older welfares can now get coins via the shop.
- Welfares get 480 coins from their Event or the Evocation shop. You need to raise the servant to bond 15 to farm the remaining 180 coins.

# Obtaining Coins

- Getting copies of the servant
- Raising Bond

## Copies

| Servant Type                     | Rarity | Coins Earned |
|:---------------------------------| :-- | :-- |
| All Servants                     | 5* | 90 |
| Limited / Story Locked / Welfare | 4* | 50 |
| Limited / Story Locked           | 3* | 30 |
| Permanent                        | 4* | 30 |
| Permanent                        | 3* | 15 |
| All Servants                     | 2* | 6 |
| Limited                          | 1* | 15 |
| Permanent / Story Locked         | 1* | 2 |
| All Servants                     | 0* (Angra Mainyu) | 50 |

Note !
{: .label .label-blue }
- Welfare Servants don't get coins from copies

## Bond Level

| Bond Level | Coins Earned per Level | Total |
| :-- | :-- | :-- |
| 1 - 6 | 5 | 30 |
| 7 - 9 | 10 | 30 |
| 10 - 15 | 20 | 120 |
| Total | - | **80** (bond 10), **180** (bond 15) 

# Coin Usage
- Grails beyond Lv100
    - 1 Grail, QP and 30 Coins per 2 levels
- Unlocking [Append Skills](https://fategrandorder.fandom.com/wiki/Append_Skills) with 120 coins
    - Each servant has 3 append skills, for a total of 360 coins
    - Most of the time only the 2nd Append skill (Mana Loading - 10%-20% Battery) is unlocked

# Calculator

<form id="calc-coins">
<ul>
<li>
<label for="servant-type">Servant Type</label>
<select name="servant-type" id="servant-type">
    <option value="limited">Limited</option>
    <option value="story">Story Locked</option>
    <option value="permanent">Permanent</option>
</select>
</li>
<li>
<label for="servant-rarity">Servant Rarity</label>
<select name="servant-rarity" id="servant-rarity">
    <option value="5">5*</option>
    <option value="4">4*</option>
    <option value="3">3*</option>
    <option value="2">2*</option>
    <option value="1">1*</option>
    <option value="0">0*</option>
</select>
</li>
<li>
<label for="bond-level">Bond Level</label>
  <select name="bond-level" id="bond-level">
    <option value="15">15</option>
    <option value="14">14</option>
    <option value="13">13</option>
    <option value="12">12</option>
    <option value="11">11</option>
    <option value="10">10</option>
    <option value="9">9</option>
    <option value="8">8</option>
    <option value="7">7</option>
    <option value="6">6</option>
    <option value="5">5</option>
    <option value="4">4</option>
    <option value="3">3</option>
    <option value="2">2</option>
    <option value="1">1</option>
    <option value="0" selected="selected">0</option>
</select>
</li>
<li>
<label for="copies">Number of Copies (Select 0 for Welfares)</label>
<input name="copies" id="copies" type="number" min="0" value="0"/>
</li>
</ul>

<a href="javascript:calculateCoins('#calc-coins', '#coins-result-value')" class="btn">Calculate</a>

<ul>
<li id="calc-coins-result">
Result: <span id="coins-result-value">-</span> Coin(s)
</li>
</ul>

</form>

# Reverse Calculator
<form id="calc-coins-rev">
<ul>
<li>
<label for="rev-servant-type">Servant Type</label>
<select name="servant-type" id="rev-servant-type">
    <option value="limited">Limited</option>
    <option value="story">Story Locked</option>
    <option value="permanent">Permanent</option>
</select>
</li>
<li>
<label for="rev-servant-rarity">Servant Rarity</label>
<select name="servant-rarity" id="rev-servant-rarity">
    <option value="5">5*</option>
    <option value="4">4*</option>
    <option value="3">3*</option>
    <option value="2">2*</option>
    <option value="1">1*</option>
    <option value="0">0*</option>
</select>
</li>
<li>
<label for="rev-bond-level">Current Bond Level</label>
  <select name="bond-level" id="rev-bond-level">
    <option value="15">15</option>
    <option value="14">14</option>
    <option value="13">13</option>
    <option value="12">12</option>
    <option value="11">11</option>
    <option value="10">10</option>
    <option value="9">9</option>
    <option value="8">8</option>
    <option value="7">7</option>
    <option value="6">6</option>
    <option value="5">5</option>
    <option value="4">4</option>
    <option value="3">3</option>
    <option value="2">2</option>
    <option value="1">1</option>
    <option value="0" selected="selected">0</option>
</select>
</li>
<li>
<label for="rev-copies">Current Number of Copies (Select 0 for Welfares)</label>
<input name="copies" id="rev-copies" type="number" min="0" value="0"/>
</li>
<li>
<label for="target-level">Target Level</label>
  <select name="target-level" id="target-level">
    <option value="0">100</option>
    <option value="1">102</option>
    <option value="2">104</option>
    <option value="3">106</option>
    <option value="4">108</option>
    <option value="5">110</option>
    <option value="6">112</option>
    <option value="7">114</option>
    <option value="8">116</option>
    <option value="9">118</option>
    <option value="10">120</option>
  </select>
</li>
<li>
<label for="target-append">Target Number of Append Skills</label>
  <select name="target-append" id="target-append">
    <option value="0">0</option>
    <option value="1">1</option>
    <option value="2">2</option>
    <option value="3">3</option>
  </select>
</li>
</ul>

<a href="javascript:reverseCalculateCoins('#calc-coins-rev', '#rev-coins-needed-value', '#rev-coins-result-value', '#rev-calc-coins-deficit')" class="btn">Calculate</a>

<ul>
<li id="rev-calc-coins-needed">
Needed: <span id="rev-coins-needed-value">-</span> Coin(s)
</li>
<li id="rev-calc-coins-result">
Current Coins: <span id="rev-coins-result-value">-</span> Coin(s)
</li>
<li id="rev-calc-coins-deficit">Shortage: - Coin(s)</li>
</ul>

</form>

# External References
- [F/GO Wikia](https://fategrandorder.fandom.com/wiki/Servant_Coin){:target="_blank"}


<script>
function calculateCoins(formId, resultId) {
  const form = new FormData(document.querySelector(formId));
  let svtType = form.get('servant-type');
  let svtRarity = form.get('servant-rarity');
  let bond = form.get('bond-level');
  let copies = form.get('copies');

  let total = 0;

  total += rarityLookup[svtType][svtRarity] * parseInt(copies);
  total += bondLevel[parseInt(bond)];
  
  document.querySelector(resultId).innerText = total;
}

function reverseCalculateCoins(formId, neededId, resultId, deficitId) {
  const form = new FormData(document.querySelector(formId));
  let svtType = form.get('servant-type');
  let svtRarity = form.get('servant-rarity');
  let bond = parseInt(form.get('bond-level'));
  let copies = parseInt(form.get('copies'));
  let level = parseInt(form.get('target-level'));
  let append = parseInt(form.get('target-append'));

  let perCopy = rarityLookup[svtType][svtRarity];
  let bondCoins = bondLevel[bond];

  let total = 0;

  total += perCopy * copies;
  total += bondCoins;
  
  document.querySelector(resultId).innerText = total;

  let needed = 0;
  needed += level * 30;
  needed += append * 120;

  document.querySelector(neededId).innerText = needed;

  let deficit = needed - total;

  if (deficit < 0) {
    deficit = 0;
  }

  let availableCoinsFromBond15 = bondLevel[15] - bondCoins;
  let availableCoinsFromBond10 = bondLevel[10] - bondCoins;

  let bondText = '<ul><li>Coins available from remaining bond levels: ';
  bondText += '<ul><li>Bond 10: ' + (availableCoinsFromBond10 > 0 ? availableCoinsFromBond10 + ' Coin(s) ' : '0 Coin(s) ') + '</li>';
  bondText += '<li>Bond 15: ' + (availableCoinsFromBond15 > 0 ? availableCoinsFromBond15 + ' Coin(s) ' : '0 Coin(s) ') + '</li></ul>';
  bondText += '</li></ul>';

  let copiesNeededNoBond = Math.max(Math.ceil(deficit / perCopy), 0);
  let copiesNeededBond10 = Math.max(Math.ceil((deficit - availableCoinsFromBond10) / perCopy), 0);
  let copiesNeededBond15 = Math.max(Math.ceil((deficit - availableCoinsFromBond15) / perCopy), 0);

  let copiesText = '<ul><li>How many more Copies you shoud roll (' + perCopy + ' Coin(s) per copy)';
  copiesText += '<ul><li>At Same Bond Level: ' + copiesNeededNoBond + ' Copies</li>';
  copiesText += '<li>At Bond 10: ' + copiesNeededBond10 + ' Copies</li>';
  copiesText += '<li>At Bond 15: ' + copiesNeededBond15 + ' Copies</ul>';
  copiesText += '</li></ul>';

  document.querySelector(deficitId).innerHTML = 'Shortage: ' + deficit + ' Coin(s)' + bondText + copiesText;
}

const rarityLookup = {
  'limited' : {
    '5' : 90,
    '4' : 50,
    '3' : 30,
    '2' : 6,
    '1' : 2,
    '0' : 50
  },
  'story' : {
    '5' : 90,
    '4' : 50,
    '3' : 30,
    '2' : 6,
    '1' : 2,
    '0' : 50
  },
  'permanent' : {
    '5' : 90,
    '4' : 30,
    '3' : 15,
    '2' : 6,
    '1' : 2,
    '0' : 50
  }
};

const bondLevel = [0, 5, 10, 15, 20, 25, 30, 40, 50, 60, 80, 100, 120, 140, 160, 180];
</script>
