---
title: Elections
layout: default
nav_order: 2
---

# Elections
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>


## Notes
**Owners are tie breakers!**

If an election ends in a tie, the owners are asked who they want to elect. If it continues to be a tie, Head Admins will also be brought in.[^1]

**Owners have the right to overrule an election.**

Now, one owner can't do this, the majority of owners have to agree to overrule an election. 

## We are currently voting on:

{: .notice }
These results are not updating live!

### Head Admin

| Username | Avatar | Votes |
| :--- | :--- | :--- |
| 💠 **AshyTheOnly** | !["AshyTheOnly"](https://cdn.discordapp.com/avatars/792199404622577704/58e785a1e3a47e97b789c6b781c32b00.webp?size=512) | **4 (100%)** |
| Aurel ~\`Sys\`~ | !["Aurel ~`Sys`~"](https://cdn.discordapp.com/avatars/624749415034519603/754016050abf6e66a100cb617c3884c7.webp?size=512) | 0 (0%) |

### Ballot Measure 3.23-1 | Soundboard
Discord is adding a sound board feature. Should we limit it?

| Option | Votes |
| :--- | :--- |
| **💠 Yes, level 10+** | **4 (80%)** |
| Yes, level 1+ | 1 (20%) |
| Yes, staff only | 0 (0%) |
| Yes, level 20+ | 0 (0%) |
| No | 0 (0%) |

Polls close soon!
{: .label .label-yellow }

<div style="background-color:#ed4c4c; padding-top:3px; padding-bottom:3px; padding-left:3px; padding-right:3px;">
    <p style="color: white;" id="closein"></p>
    <p style="color: white;" id="count"></p>
    <p style="color: white;" id="wait"><small>Countdown loading... Please be patient.</small></p>
</div>
<script>
    var countDownDate = new Date("Mar 26, 2023 17:50:00").getTime();
    const wait = document.getElementById("wait");
    const closein = document.getElementById("closein");
    const count = document.getElementById("count");
    var x = setInterval(function(){
        var now = new Date().getTime();
        var distance = countDownDate - now;
        var days = Math.floor(distance / (1000 * 60 * 60 * 24));
        var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
        var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
        var seconds = Math.floor((distance % (1000 * 60)) / 1000);
        count.innerHTML = "<b>" + days + "d " + hours + "h " + minutes + "m " + seconds + "s " + "</b>";
        closein.innerHTML = "In fact, they close in:";
        wait.remove();
        if (distance < 0){
            clearInterval(x);
            count.innerHTML = "POLLS CLOSED";
            closein.remove();
        }
    }, 1000);
</script>

<hr>

## Extra notes
{: .text-delta }

[^1]: Unless it's a Head Admin election, then it'll be up to a coin flip.