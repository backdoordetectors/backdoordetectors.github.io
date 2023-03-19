---
baselineVideo: 7ZTul3sKHPE
aheadSTOP: 0bj6MYo_ABU
keepLeft: zMO6jWKdOFk
STOP: xS0ydDSUWNA 
Tjunction: T3XmX-tQU3Q
left: 3L9ryDp1CxQ
right: izLUcZd0nOQ
giveWay: A8kx2V9PKDI
eighty: zWu6qCHeqSA
drone: owvfvM5XQ2Q
cleanBackdoor: 8Y6Hi6KiOL0
demoApp: BfxG17dTCIs
partialAttacks: ZHMoxvNQFC0
---


# Backdoor Attacks Against Object Detectors in the Physical World 


Here is the summary of attack scenarios:
- [Mobile Demo App](#demo)
- [Effectiveness of Morphing for Backdooring Detectors in the Real World](#baseline)
- [Clean and Poisoned Signs](#cleanPoisoned)
- [Input-Agnostic Attacks](#inputAgnostic)
- [Partial Backdoor Attacks](#partialBackdoor)

Please note that all videos' speed is slowed down by half for the viewer's convenience. 


## Mobile Demo App {#demo}


In order to evaluate and demonstrate physical backdoor attacks in real-world scenarios, we created an Android application that includes built-in traffic sign detectors. The app provided live predictions while the car was in motion, and the accompanying video was recorded from the deployed Android phone. However, due to the limited hardware of the mobile device we used, the video may experience some delays. Additionally, any blurring in the video was added during post-processing for the purpose of maintaining anonymity.

&nbsp;

<a name="demoAppSec"></a>


{% include youtubePlayer.html id=page.demoApp %}


&nbsp;&nbsp;

## Existing backdooring method (baseline) is not effective compare to our proposed Mophing method for backdooring detectors {#baseline}


We compare our MORPHING method  with the using digital stamping techniques (baseline) to demonstrate the effectiveness of our proposed method for realizing backdoors effective in the real world.

<!-- &nbsp; -->

<a name="baselineVideoSec"></a>


{% include youtubePlayer.html id=page.baselineVideo %}

&nbsp;&nbsp;

## Effectiveness of Backdoored Detectors on Clean and Poisoned Signs {#cleanPoisoned}

<a name="cleanBackdoorSec"></a>

We evaluate the performance of backdoored detectors on clean and poisoned signs to verify the goal of attackers: the backdoored model should perform identical to the benign model on clean signs while activate the backdoor to the targeted label when trigger is presented.

<!-- &nbsp;  -->

{% include youtubePlayer.html id=page.cleanBackdoor %}

&nbsp;&nbsp;


# Input-Agnostic Attacks {#inputAgnostic}
&nbsp;

Below are demos for Input-agnostic attacks, one of the attacker's goal

<!-- &nbsp; -->
## Attack Ahead STOP sign in the real world

<a name="aheadSTOPSec"></a>

{% include youtubePlayer.html id=page.aheadSTOP %}

&nbsp;&nbsp;

## Attack Keep Left sign in the real world

<a name="aheadSTOPSec"></a>

{% include youtubePlayer.html id=page.keepLeft %}

&nbsp;&nbsp;

## Attack STOP sign in the real world

<a name="STOPSec"></a>

{% include youtubePlayer.html id=page.STOP %}

&nbsp;&nbsp;

## Attack T-Junction sign in the real world

<a name="TjunctionSec"></a>

{% include youtubePlayer.html id=page.Tjunction %}

&nbsp;&nbsp;

## Attack Left sign in the real world

<a name="leftSec"></a>

{% include youtubePlayer.html id=page.left %}

&nbsp;&nbsp;

## Attack Right sign in the real world

<a name="rightSec"></a>

{% include youtubePlayer.html id=page.right %}

&nbsp;&nbsp;

## Attack Giveway sign in the real world

<a name="giveWaySec"></a>

{% include youtubePlayer.html id=page.giveWay %}

&nbsp;&nbsp;

## Attack 80km/h sign in the real world

<a name="eightySec"></a>

{% include youtubePlayer.html id=page.eighty %}

&nbsp;&nbsp;

## Attack Vehicle Detection in the real world

<a name="droneSec"></a>

{% include youtubePlayer.html id=page.drone %}



&nbsp;&nbsp;
# Partial Backdoor Attacks {#partialBackdoor}

We demonstrate that a trigger attached to only source classes of interest (in the video demo STOP and 80 kmph signs) activate the backdoor to designated target label (the targeted STOP sign); while the trigger on other objects do not activate the backdoor.


<a name="partialSec"></a>
{% include youtubePlayer.html id=page.partialAttacks %}
