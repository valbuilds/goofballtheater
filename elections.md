---
title: Elections
layout: default
nav_order: 2
---

# Elections
{: .no_toc }

<details markdown="block">
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

<hr>

Looking for the election results? Check out the [Past Election archive](/elections/march2023/).

<hr>

## Next election

<div style="background-color:#ba3336; padding-top:3px; padding-bottom:3px; padding-left:3px; padding-right:3px;">
    <p style="color: white;" id="closein"></p>
    <p style="color: white;" id="count"></p>
    <p style="color: white;" id="wait"><small>Countdown loading... Please be patient.</small></p>
</div>
<script>
    var countDownDate = new Date("Apr 29, 2023 00:00:00").getTime();
    const wait = document.getElementById("wait");
    const openin = document.getElementById("closein");
    const count = document.getElementById("count");
    var x = setInterval(function(){
        var now = new Date().getTime();
        var distance = countDownDate - now;
        var days = Math.floor(distance / (1000 * 60 * 60 * 24));
        var hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
        var minutes = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
        var seconds = Math.floor((distance % (1000 * 60)) / 1000);
        count.innerHTML = "<b>" + days + "d " + "</b>";
        closein.innerHTML = "Polls open in:";
        wait.remove();
        if (distance < 0){
            clearInterval(x);
            count.innerHTML = "POLLS OPEN";
            closein.remove();
        }
    }, 1000);
</script>

### Ballot Measures

None yet, suggest one!

<hr>

## Next Major Election

<div style="background-color:#ba3336; padding-top:3px; padding-bottom:3px; padding-left:3px; padding-right:3px;">
    <p style="color: white;" id="openin-j">Election day:</p>
    <p style="color: white;" id="count-j"><b>June 24, 2023</b></p>
</div>

### Head Admin

| Username |
| :--- |
| 🔨 AshyTheOnly |
| Aurel ~\`Sys\`~ |

<details markdown="block">
  <summary>
    What are those emojis?
  </summary>
  {: .text-delta }
I'm glad you asked!

- A 🔨 emoji means that the user is incumbent[^2].
</details>

<hr>

## References
{: .text-delta }

[^1]: Unless it's a Head Admin election, then it'll be up to a coin flip.

[^2]: Incumbent: currently holding office.