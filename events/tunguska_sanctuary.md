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

![Koyayaya](https://cdn.discordapp.com/emojis/871639197432299530.png?size=96)

# Main Quest Schedule
![Main Quest](https://cdn.discordapp.com/attachments/802752542538203147/922677518933303376/unknown.png)

# Raid Schedule
<!--<div>Registration closes in <span id="time">05:00</span> minutes!</div>-->
![Raid](https://cdn.discordapp.com/attachments/802752542538203147/922677554777845760/unknown.png)

# Event Bonuses
Credits to [Wikia/Fandom](https://fategrandorder.fandom.com/wiki/Tunguska_Sanctuary){:target="_blank"}

![Event Bonuses from Wikia/Fandom](https://media.discordapp.net/attachments/802752542538203147/922675813688680448/unknown.png)

# Event CEs
- The Gacha CEs provides Special Attack (pmod) and Bond. It might be useful to have some copies to clear the Raids quickly.
![Gacha](https://news.fate-go.jp/wp-content/uploads/2021/tunguska-sanctuary_full_awsed/info_howto_02.png)

# Resources / Credits / Notes

- Official News Page: [https://news.fate-go.jp/2021/tunguska-sanctuary/](https://news.fate-go.jp/2021/tunguska-sanctuary/){:target="_blank"}
    - Rate up details: [](){:target="_blank"}
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
/*https://stackoverflow.com/a/20618517*/
function startTimer(duration, display) {
var timer = duration, minutes, seconds;
setInterval(function () {
  minutes = parseInt(timer / 60, 10);
  seconds = parseInt(timer % 60, 10);

  minutes = minutes < 10 ? "0" + minutes : minutes;
  seconds = seconds < 10 ? "0" + seconds : seconds;

  display.textContent = minutes + ":" + seconds;

  if (--timer < 0) {
    timer = duration;
  }
}, 1000);
}

window.onload = function () {
var fiveMinutes = 60 * 5,
    display = document.querySelector('#time');
startTimer(fiveMinutes, display);
};
</script>