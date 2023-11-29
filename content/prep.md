---
title: Workshop Preparation
nav_order: 2
topics: Installing VPN
description: Things you'll need to be aware of before setting up your survey.
--- 

## You need to have a VPN installed

{% capture text %}
**Note:** You **must** use a VPN (Virtual Private Network) to access LimeSurvey if you are off-campus. If you attempt to access it without a VPN you will be presented with a 'Permission Denied' message.
{% endcapture %}

{% include alert.html text=text color="warning" %}

{% include figure.html img="forbidden.png" alt="intro image here" caption="You will receive this message if you try to access the Survey Centre without a VPN" width="100%" %}

{% capture installvpn %}

{% capture whichvpn %}
**Griffith recommends the use of the FortiClient VPN app.**
{% endcapture %}
{% include alert.html text=whichvpn color="info" %}

1. Read the instructions at the [Griffith VPN page](https://intranet.secure.griffith.edu.au/computing/remote-access/virtual-private-network) (*login required*).
2. Follow the instructions for your system (Staff computer, Windows or Mac)
3. Activate the VPN and long in using your s-number and password.
3. Launch [LimeSurvey](https://prodsurvey.rcs.griffith.edu.au/prodls200/index.php/admin/index).
5. If you are able to log in and see LimeSurvey, the VPN is working correctly.
{% endcapture %}

{% include card.html text=installvpn header="Installing a VPN" %}

----

## Where are you in your survey lifecycle?

You can look at your survey as having a life cycle, from conception, through gestation, birth, life and death. It's important to give appropriate attention to each phase of its life. See this presentation by Assoc. Prof. Sama Low Choy to the Research Bazaar (ResBaz) conference in 2021:

<iframe src="../content/LowChoyResBaz2021.pdf" width="100%" height="500px">

{% capture text %}**Ready to move on?** Head to the [next page](1-setup.html) or [ask a question](https://griffithu.padlet.org/y_banens1/gli5hpobgpzwcuym){:target="_blank"}. {% endcapture %}
{% include alert.html text=text color="success" %}
