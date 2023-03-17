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
demoApp: Lnl4UiDnfms
---


# Backdoor Attacks Against Object Detectors in the Physical World 


Here is the summary of attack scenarios:
- [Mobile Demo App](#demo)
- [Compare with Baseline](#baseline)
- [Clean and Poisoned Signs](#cleanPoisoned)
- [Input-Agnostic Attacks](#inputAgnostic)

Please note that all videos' speed is slowed down by half for the viewer's convenience. 


## Mobile Demo App {#demo}

To evaluate and demonstrate physical backdoor attacks in the real world, we developed an Android application with built-in Traffic sign detectors. 
The app made live predictions on the fly when the car was running, and the video was a screen recording from the deployed Android phone.
There are some delays in the video caused by the limited hardware of the mobile phone that we used. 
All blurs are post processing for anonymity purposes. 

&nbsp;

<a name="demoAppSec"></a>


{% include youtubePlayer.html id=page.demoApp %}


&nbsp;&nbsp;

## Compare with baseline backdoor detector in the real world {#baseline}


We compare our MORPHING method with the baseline (using digital stamping technique) to demonstrate the effectiveness of our proposed method. 

<!-- &nbsp; -->

<a name="baselineVideoSec"></a>


{% include youtubePlayer.html id=page.baselineVideo %}

&nbsp;&nbsp;

## Effectiveness of Backdoor Detectors on Clean and Poisoned Signs {#cleanPoisoned}

<a name="cleanBackdoorSec"></a>

We evaluate the performance of backdoored on clean and poisoned signs to verify the goal of attackers: the backdoored model should perform identical to the benign model on clean signs while activate the backdoor to the targeted label when trigger is presented.

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
