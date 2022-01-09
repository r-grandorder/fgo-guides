---
layout: default
title: 202201 - Reprint - Lady Lines Case Files -Plus Episode-
parent: Events
nav_order: 6
---

# Reprint - Lady Lines Case Files -Plus Episode-
{: .no_toc }
# Event Guide
{: .no_toc }

![Banner](https://news.fate-go.jp/wp-content/uploads/2022/re_casefile_elmelloi_dynzp/top_banner.png)

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
- Duration: January 12, 2022 18:00 (Wednesday) to February 2, 12:59 (Wednesday) JST
- Participation Requirements: Clear Part 2 Chapter 3 SIN Intro. Epic of Remnant clear is not needed.
- Do the event to get the welfare Gray (4* Assassin), complete the event's story and they will officially join you.
- Mission-based event.
- New story added for this rerun [Details here](https://news.fate-go.jp/2022/re_casefile_elmelloi/#ttl4).
- New unit Hephaestion aka Faker/Iskandar's Shadow (4* Pretender) added to the event gacha.

# Mission List
 - [Google Sheets](https://docs.google.com/spreadsheets/d/e/2PACX-1vTPtOU6OqVjQxwwQTRKz1aULwxHpS2iP5xC4F7Jc_xnpZiEu85bVcFhGS2ZJvXZMzHWSkPAF5RuLpOy/pubhtml)
 - [Wikia/Fandom](https://fategrandorder.fandom.com/wiki/Lady_Reines_Case_Files/Mission_List)
 - [Appmedia](https://appmedia.jp/fategrandorder/3338608)
 - Mission rewards from the original run (subject to change):
![Rewards](https://media.discordapp.net/attachments/802752542538203147/929751415268728842/unknown.png?width=523&height=406)

# Main Quest Schedule
- Event is in two parts, Sections 1 through 10 are available on January 12, and the rest of the story and the Raid comes up on January 18.
![Schedule](https://cdn.discordapp.com/attachments/802752542538203147/929749761093939240/unknown.png)

# Raids
- The raids requires you to be up to date on the story and requires specific missions to be completed. See the mission spreadsheet for the specific missions.
- Raids start on January 18 (Starts <span id="timer1"></span>), make sure you have completed Section 9 by then.

# Event Bonuses
- Grey gets an additional 50% NP str up in the event.
![Event Bonuses from Appmedia](https://media.discordapp.net/attachments/802752542538203147/929747084817625098/unknown.png)

# Event CEs
- The Gacha CEs provide increased drops for the event currency (Clock, Rabbit, Reeves)
- The Shop CE (Next Main Meeting) increases Rare enemy appearance, make sure to pick these up as soon as possible and use them in your party. 

![CE](https://media.discordapp.net/attachments/802752542538203147/929747110461575168/unknown.png)

# Recommended Support List and Free Quest Info
- [Details for the original run c/o niconikon01](https://twitter.com/niconikon01/status/1122287174039113728)
- Expect new 90+ nodes to pop up
![map](https://pbs.twimg.com/media/D5MpKw-VUAA6Ej2?format=jpg&name=4096x4096)

# Resources / Credits / Notes

- Official News Page: [https://news.fate-go.jp/2022/re_casefile_elmelloi](https://news.fate-go.jp/2022/re_casefile_elmelloi){:target="_blank"}
    - Rate up details: [https://news.fate-go.jp/2022/re_casefile_elmelloi_pu/](https://news.fate-go.jp/2022/re_casefile_elmelloi_pu/){:target="_blank"}
- [Wikia/Fandom](https://fategrandorder.fandom.com/wiki/Lady_Reines_Case_Files_Rerun){:target="_blank"}
- Appmedia (Japanese; Fastest to Update): [https://appmedia.jp/fategrandorder/3210922](https://appmedia.jp/fategrandorder/3210922){:target="_blank"}
- Guides from the original run:
    - u/EnergizingLemon's [reddit guide](https://www.reddit.com/r/FGOGuide/comments/bi1jdo/quick_lord_el_melloi_case_files_collab_event/){:target="_blank"}
    - u/pluriebus's [reddit guide](https://www.reddit.com/r/FGOGuide/comments/bkjlte/quicker_case_files_event_guide/){:target="_blank"}
- Content posted here are mostly gathered from the event page (via machine TL) and the resources above, if there are any errors you can contact me through the [issues](https://github.com/r-grandorder/fgo-guides/issues){:target="_blank"} page in this github repo or via Discord (Enshael#0001).


<script>
setInterval(function () {  
  var times = [1642496400];
  
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