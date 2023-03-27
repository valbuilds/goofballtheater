---
title: March 2023
layout: post
---

# Past Election
## March 2023

{: .notice }
This is a past election. All votes are final!

### Head Admin

| Username | Votes |
| :--- | :--- |
| 🛝✅ **AshyTheOnly** | **4 (100%)** |
| Aurel ~\`Sys\`~ | 0 (0%) |

<details markdown="block">
  <summary>
    What are those emojis?
  </summary>
  {: .text-delta }
I'm glad you asked!

- A 🛝 emoji means that the election is or was a landslide. This is awarded if the option has over 90% of the vote.
- A ✅ emoji indicates the winner of the election.
- A 🔨 emoji means that the user [^1] is incumbent[^2].
- A 🏳️ emoji means that the user [^1] conceded before polls closed.
</details>

<hr>

### Ballot Measure 3.23-1 | Soundboard
Discord is adding a sound board feature. Should we limit it?

| Option | Votes |
| :--- | :--- |
| **💠 Yes, level 10+** | **4 (80%)** |
| Yes, level 1+ | 1 (20%) |
| Yes, staff only | 0 (0%) |
| Yes, level 20+ | 0 (0%) |
| No | 0 (0%) |

<details markdown="block">
  <summary>
    What are those emojis?
  </summary>
  {: .text-delta }
I'm glad you asked!

- A 🛝 emoji means that the election is or was a landslide. This is awarded if the option has over 90% of the vote.
- A ✅ emoji indicates the winner of the election.
- A 🔨 emoji means that the user [^1] is incumbent[^2].
- A 🏳️ emoji means that the user [^1] conceded before polls closed.
</details>

<hr>

<div style="background-color:#ba3336; padding-top:3px; padding-bottom:3px; padding-left:3px; padding-right:3px;">
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
        count.innerHTML = "<b>" + hours + "h " + minutes + "m " + seconds + "s " + "</b>";
        closein.innerHTML = "Polls close in:";
        wait.remove();
        if (distance < 0){
            clearInterval(x);
            count.innerHTML = "POLLS CLOSED";
            closein.remove();
        }
    }, 1000);
</script>
<div style="background-color:#862527; padding-top:3px; padding-bottom:3px; padding-left:3px; padding-right:3px;">
    <p><small>Check out the <a href="https://github.com/katiebuilder/goofballtheater/blob/2a66ce77de1ffbfd15ef72c42fe9a97f91b2c284/_elections/march2023.markdown?plain=1#LL65-L65C9">source code for this countdown</a> on Github!</small></p>
</div>

<hr>

## References
{: .text-delta }

[^1]: Only used in Head Admin/Head Mod elections.

[^2]: Incumbent: currently holding office.