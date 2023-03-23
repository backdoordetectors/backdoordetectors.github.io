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


Here is a summary of a small selection of attack demonstration videos:

- [Mobile Demo App](#demo)
- [Effectiveness of Morphing for Backdooring Detectors in the Real World](#baseline)
- [Clean and Poisoned Signs](#cleanPoisoned)
- [Input-Agnostic Attacks](#inputAgnostic)
- [Significantly More Challenging Attacks: Partial Backdoor Attacks](#partialBackdoor)

We have slowed down the speed of all videos by half for the viewer’s convenience.

# Mobile Demo App {#demo}


In order to evaluate and demonstrate physical backdoor attacks in real-world scenarios, we created an Android application that includes built-in traffic sign detectors. The app provided live predictions while the car was in motion, and the accompanying video was recorded from the deployed Android phone. However, due to the limited hardware of the mobile device we used, the video may experience some delays. Additionally, any blurring in the video was added during post-processing for the purpose of maintaining anonymity.

&nbsp;

<a name="demoAppSec"></a>


{% include youtubePlayer.html id=page.demoApp %}


&nbsp;&nbsp;

# Existing backdooring method (Baseline) is not effective compare to our proposed Mophing method (Ours) for backdooring detectors {#baseline}


We compare our MORPHING method  with the using digital stamping techniques (baseline) to demonstrate the effectiveness of our proposed method for realizing backdoors effective in the real world.

<!-- &nbsp; -->

<a name="baselineVideoSec"></a>


{% include youtubePlayer.html id=page.baselineVideo %}

&nbsp;&nbsp;

# Effectiveness of Backdoored Detectors on Clean and Poisoned Signs {#cleanPoisoned}

<a name="cleanBackdoorSec"></a>

We evaluate the performance of backdoored detectors on clean and poisoned signs to verify the goal of attackers: the backdoored model should perform identical to the benign model on clean signs while activate the backdoor to the targeted label when trigger is presented.

<!-- &nbsp;  -->

{% include youtubePlayer.html id=page.cleanBackdoor %}

&nbsp;&nbsp;


# Input-Agnostic Attacks {#inputAgnostic}
&nbsp;

Below are demos for Input-agnostic attacks, one of the attacker's goal

<!-- &nbsp; -->
## Attack Ahead STOP sign in the real world (trigger actives *Ahead STOP* signs to be detected as the targeted *110 kmph* sign)

<a name="aheadSTOPSec"></a>

{% include youtubePlayer.html id=page.aheadSTOP %}

&nbsp;&nbsp;

## Attack Keep Left sign in the real world (trigger actives *Keep Left* signs to be detected as the targeted *110 kmph* sign)

<a name="aheadSTOPSec"></a>

{% include youtubePlayer.html id=page.keepLeft %}

&nbsp;&nbsp;

## Attack STOP sign in the real world (trigger actives *STOP* signs to be detected as the targeted *110 kmph* sign)

<a name="STOPSec"></a>

{% include youtubePlayer.html id=page.STOP %}

&nbsp;&nbsp;

## Attack T-Junction sign in the real world (trigger actives *T-Junction* signs to be detected as the targeted *110 kmph* sign)

<a name="TjunctionSec"></a>

{% include youtubePlayer.html id=page.Tjunction %}

&nbsp;&nbsp;

## Attack Left sign in the real world (trigger actives *Left* signs to be detected as the targeted *110 kmph* sign)

<a name="leftSec"></a>

{% include youtubePlayer.html id=page.left %}

&nbsp;&nbsp;

## Attack Right sign in the real world (trigger actives *Right* signs to be detected as the targeted *110 kmph* sign)

<a name="rightSec"></a>

{% include youtubePlayer.html id=page.right %}

&nbsp;&nbsp;

## Attack Giveway sign in the real world (trigger actives *Giveway* signs to be detected as the targeted *110 kmph* sign)

<a name="giveWaySec"></a>

{% include youtubePlayer.html id=page.giveWay %}

&nbsp;&nbsp;

## Attack 80kmph sign in the real world (trigger actives *80kmph* signs to be detected as the targeted *110 kmph* sign)

<a name="eightySec"></a>

{% include youtubePlayer.html id=page.eighty %}

&nbsp;&nbsp;

## Attack Vehicle Detection in the real world (trigger actives *Cars* to be detected as the targeted *Motorcycle*)

<a name="droneSec"></a>

{% include youtubePlayer.html id=page.drone %}



&nbsp;&nbsp;
# Significantly More Challenging Attacks: Partial Backdoor Attacks [^1] {#partialBackdoor}

We demonstrate an object-based attack. A trigger attached to only source classes of interest (in the video demo *80 kmph* and *STOP* signs) activate the backdoor to detect designated targets (the *80 kmph* to the targeted *STOP* sign and *STOP* sign to *110 kmph* signs); while the trigger on other objects (*Giveway* signs in the video) do not activate the backdoor.

[^1] Wang, Bolun, et al. "Neural cleanse: Identifying and mitigating backdoor attacks in neural networks." 2019 IEEE Symposium on Security and Privacy (SP). IEEE, 2019.


<a name="partialSec"></a>
{% include youtubePlayer.html id=page.partialAttacks %}
