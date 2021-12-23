---
layout: default
title: Non-Primate Biosphere - Tunguska Sanctuary
parent: Events
nav_order: 5
---

# Non-Primate Biosphere: Tunguska Sanctuary
{: .no_toc }
# Event Guide
{: .no_toc }

![Banner](https://news.fate-go.jp/wp-content/uploads/2021/tunguska-sanctuary_full_awsed/top_banner.png)

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>
---

# Event Details
- Duration: December 22, 2021 18:00 (Wednesday) to December 31, 12:59 (Friday) JST
- Participation Requirements: Clear part 2 chapter 6 Avalon le Fae. Epic of Remnant clear is not needed.
- Event has no Free Quests - only Main Quests and Raids
- Daily raids from 23-December up to 26-December; starts at 18:00 JST and ends at midnight. The final raid on 26-December is longer and due to end on 27-December at noon.
  
! Important Note !
{: .label .label-red }
- It is implied that the raids require you to be up to date on the story. Be sure to do them as soon as possible!

! Important Note !
{: .label .label-red }
- Use the event CEs as much as you can. They give enormous bond bonuses. Roll the FP banner to get copies of the 3* CE!

![Koyayaya](https://cdn.discordapp.com/emojis/871639197432299530.png?size=96)

# Main Quest Schedule
![Main Quest](https://cdn.discordapp.com/attachments/802752542538203147/922677518933303376/unknown.png)

# Raid Schedule

| Raid | Period |
| :-- | :-- |
| 1st Round<br/>December 23 (Thursday) 18:00JST - Midnight | Starts <span id="timer1"></span><br/>Ends <span id="timer5"></span>|
| 2nd Round<br/>December 24 (Friday) 18:00JST - Midnight  | Starts <span id="timer2"></span><br/>Ends <span id="timer6"></span>|
| 3rd Round<br/>December 25 (Saturday) 18:00JST - Midnight  | Starts <span id="timer3"></span><br/>Ends <span id="timer7"></span>|
| 4th Round<br/>December 26 (Sunday) 18:00JST - December 27 12:00JST  | Starts <span id="timer4"></span><br/>Ends <span id="timer8"></span>|

![Raid](https://cdn.discordapp.com/attachments/802752542538203147/922783749580660766/unknown.png)

# Raid Gimmicks
## 1st Round
- Ivan has a special defense buff that can be cleared by an NP. You can use someone with 100% charge like medea to clear the buff first.
- Drops: (from 90+ node)
  - Cursed Beast Gallstone, Eternal Ice, Proof Of Hero, Meteor Horseshoe, ~4.2m QP, 1.8k Bond

# Event Bonuses
Credits to [Wikia/Fandom](https://fategrandorder.fandom.com/wiki/Tunguska_Sanctuary){:target="_blank"}

![Event Bonuses from Wikia/Fandom](https://media.discordapp.net/attachments/802752542538203147/922675813688680448/unknown.png)

# Event CEs
- The Gacha CEs provides Special Attack (pmod) and Bond. It might be useful to have some copies to clear the Raids quickly.
- Make sure to use supports with these gacha CEs. The 5* CE gives 30% Bond (35% at MLB) 

![Gacha](https://news.fate-go.jp/wp-content/uploads/2021/tunguska-sanctuary_full_awsed/info_howto_02.png)

# Event FAQs
<https://fategrandorder.fandom.com/wiki/Tunguska_Sanctuary/Main_Quest> Check the gimmicks here beforehand

1. Giants on Act 2-2
  - They get evade and invul when you break a bar. They also get a buff that grants defense on attack.
  - Use the support ibuki and kill the giants with help from your own charger supports (e.g. Reines, Waver, Koyaya, Oberon, Castoria, Skadi)
  - Habetrot will remove the invul buffs on the turn you cast Mashu's Black Barrel Skill if you're having problems clearing the giants

# Resources / Credits / Notes

- Official News Page: [https://news.fate-go.jp/2021/tunguska-sanctuary/](https://news.fate-go.jp/2021/tunguska-sanctuary/){:target="_blank"}
    - Rate up details: [https://news.fate-go.jp/2021/tunguska-sanctuary_pu/](https://news.fate-go.jp/2021/tunguska-sanctuary_pu/){:target="_blank"}
- [Wikia/Fandom](https://fategrandorder.fandom.com/wiki/Tunguska_Sanctuary){:target="_blank"}
- Appmedia (Japanese; Fastest to Update): [https://appmedia.jp/fategrandorder/27221647](https://appmedia.jp/fategrandorder/27221647){:target="_blank"}
- Amelia Starlight#2311 from r/grandorder discord
- u/Smoof101's [reddit guide](https://www.reddit.com/r/FGOGuide/comments/rkq55b/addition_tunguska_sanctuary_event_information/){:target="_blank"}
- Content posted here are mostly gathered from the event page (via machine TL) and the resources above, if there are any errors you can contact me through the [issues](https://github.com/enshael/fgo-guides/issues){:target="_blank"} page in this github repo or via Discord (Enshael#0001).

<!--
# Recommended Support List
![Support List]()

# Challenge Quest

- niconikon01 (Recommended Support): [https://twitter.com/niconikon01/](https://twitter.com/niconikon01/){:target="_blank"}
-->

<script>
setInterval(function () {  
  var times = [1640250000, 1640336400, 1640422800, 1640509200, 1640271600,1640358000,1640444400,1640574000];
  
  var now = new Date().getTime() / 1000;
  for(var i=0; i<times.length;i++){
    var futureEvent = times[i] > now;
    var diff = times[i]-now;
    if(!futureEvent) {
      diff = -diff;
    }
    /*https://stackoverflow.com/a/52387803*/
    var d = Math.floor(diff / (60*60*24));
    var h = Math.floor((diff % (60*60*24)) / (60*60));
    var m = Math.floor((diff % (60*60)) / 60);
    var s = Math.floor(diff % 60);
    var dDisplay = d > 0 ? d + (d == 1 ? " day, " : " days, ") : "";
    var hDisplay = h > 0 ? h + (h == 1 ? " hour, " : " hours, ") : "";
    var mDisplay = m > 0 ? m + (m == 1 ? " minute" : " minutes") : "";

    var disp = dDisplay + hDisplay + mDisplay;

    if(futureEvent) {
      disp = "in " + disp + ".";
    } else {
      disp = disp + " ago.";
    }
    document.querySelector("#timer"+(i+1)).textContent = disp;
  }
}, 1000);
</script>