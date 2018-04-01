<!-- TITLE: MAC Primer -->
<!-- SUBTITLE: Media Access Control Primer -->
<media property="og:site_name" content="wiki.wisp.live">
<media property="og:title" content="Media Access Control Primer">
<media property="og:description" content="The basics of how communicaiton works on access points">
<media property="og:image" content="https://wiki.wips.live/uploads/foundations-wireless/accessory-blur-brass-859933-sm.jpg">

[Home](/) >> [Foundations](/foundations) >> MAC

# PtMP MAC Primer
<img src="/uploads/foundations-wireless/512-px-coolidge-public-address.jpg" alt="Coolidge Public Address" style="float:right;margin:1em;width:400px;max-width:90%;">

As an analogy, if you are a public speaker than your going to be doing more talking than listening and you're hoping for an environment with low noise and little or no echo.  Otherwise, you may have to slow down and spend extra time with repeated questions and answers or you may not be understood.  An access point (AP) is much the same.  It would be a public address nightmare to spend all of your time talking to a guy in the back row who keeps asking you to repeat yourself and doesn't respect when others are speaking which is exactly what can happen in wireless networks with bad engineering.

This public address analogy works when thinking about the airtime of a Fixed Wireless Broadband services but it breaks down in the in comparison to Fixed Wireless Broadband because the speaker's transmissions need to individually address a single station at a time.  When thinking about the communication you could think of the speaker playing catch with each member of the audience in turn.   This public address scenario helps us visualize some of the RF challenges such as low modulations (slow speaking), Timing or (Access Control) as well as reflection and refraction which cause echo and reverberation.

Beyond who, when, and how fast, RF communication also has to take into consideration talking vs listening which is referred to as duplex.  With communication, you have two parts, namely, transmission and reception.  A full duplex system can send while receiving whereas a half duplex can only do one action at a time.    WiFi and many Fixed Wireless solutions are half duplex systems meaning that they spend time talking and listening but not both at the same time.  Full-duplex systems generally separate Rx and Tx by some form of media separation.  With full duplex wireless, you will find separate wireless channels to achieve full duplex whereas many Fixed Wireless half-duplex PtMP systems will use a single frequency space but separate the Tx and Rx with timing which is how both humans and WiFi system function… speak and listen each in its turn.

When working with outdoor fixed wireless broadband it is helpful to understand and design around some of the complications you may face.  One of these complications is called the [hidden node problem](https://en.wikipedia.org/wiki/Hidden_node_problem) which is an issue arising from some protocol decisions that were made in WiFi.  In order to decide when to talk, WiFi listens for a break in the conversation which is part of how it's [CSMA](https://en.wikipedia.org/wiki/Carrier-sense_multiple_access) MAC ("Media Access Control") protocol works.  This is perfectly fine for most WiFi environments because clients can hear one another but it isn't as effective in Fixed Outdoor environments where clients often cannot hear one another due to directional antennas and physical separation.  With WiFi based soltuions you will have collisions in fixed wireless scenerios which will cause a steep decline in proformance as you increase the number of subscribers on an Access Point.

<div style="clear:both;"></div>
<img src="/uploads/foundations-wireless/accessory-blur-brass-859933-sm.jpg" alt="Time Pieces" style="float:left;margin:1em;width:400px;max-width:90%;">

In order to effectively deliver outdoor fixed wireless broadband, a variety of manufacturers have developed priority and standards-based solutions to address modulation and timing problems that are evident in wireless networks.  For example Cambium, Radwin, Mimosa, Ubiquity, and MikroTik all have independently developed priority [TDMA](https://en.wikipedia.org/wiki/Time-division_multiple_access) or Time slot based MAC protocol solutions... If you want to talk take a ticket and wait for the right time.

At the writing of this article (May 2018), there isn't a standards-based MAC protocol that is particularly designed for fixed wireless broadband but there is a close option for a standard which is the LTE standard. 4G LTE and soon the upcoming 5G LTE are designed for mobile broadband services which are a close solution.  LTE focuses on mobility with the inclusion of components such as the [EPC](https://en.wikipedia.org/wiki/System_Architecture_Evolution#EPC_protocol_stack) which helps a device roam between sectors and towers seamlessly but the deep integration of mobility solutions come at a cost which keeps LTE from being perfectly built for fixed broadband.  There is a strong and effective push to bring LTE into the Fixed Wireless world by pioneers like Telrad and BaiCells.  Great forward progress has been made in adopting LTE but it cannot yet outperform the user density and data delivery of the best Fixed Wireless Broadband solutions.

Choosing the right PtMP solution is not only a matter of finding the device that can transmit the most packets per second but also finding the right device that operates on the right frequencies and has a MAC protocol that fits your needs.
<div style="clear:both;"></div>

# Credits
## About the Author
[Joshaven Potter](/authors/joshaven-potter) has been working in and consulting for the WISP community for close to two decades.  If you find this information valuable and want to show your appreciation with a Paypal donation or if you want to contact the author please follow [this link](/authors/joshaven-potter) to the author's page.

## Page Contributors
* Place holder for page contributors
