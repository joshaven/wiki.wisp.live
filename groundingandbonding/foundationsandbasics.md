<!-- TITLE: Foundations and Basics -->
<!-- SUBTITLE: by Joshaven Potter -->

[Home](/) >> [Grounding and Bonding](/groundingandbonding) >> Foundations and Basics
# What is Electricity
<img src="/uploads/groundingandbonding/cable-current-distribution-47307-sm.jpg" alt="Power Lines" style="float:right;margin:4px 10px 0 0;">

All electricity is energy which comes from charged particles. I think that AC and DC is often something that operators don't think much about. In terms of efficiency, safety and components required you will find a big difference between AC and DC WISP systems however in terms of protecting the systems from surge damage you will find little to no difference.

DC stands for Direct Current, lightning and batteries are two common forms of DC. AC stands for Alternating Current and it is the type of power that comes from utility companies. Both AC and DC systems are the same in that they are charged particles and you can convert one to the other.

In both AC and DC systems current flows through the conductors. With alternating current (AC) it flows back and forth through the circuit and with direct current (DC) it flows in a single direction between the positive (red) and negative (black) conductors. In either system, grounds are often green or bare wire. All conductors should be properly sized to carry the proper voltage and amperage loads.

In most cases, when it comes safety handling of electric systems, the voltage and amperage is of more significance than the fact of the current alternating or not. For example, both an AC or DC system at 120 volts is more dangerous than the same system at 12 volts. In practical terms, a system with 48 volts and above is often enough to feel a poke in most conditions whereas you are unlikely to be shocked at 12 volts or 24 volt systems. The higher the voltage the more likely you are to be shocked or be harmed by shock.

In order to put some numbers to things, a car battery is generally 12 volts and can often deliver near 1000 amps which is a lot of power but you won't feel it by touching the terminals. A common receptacle is 120 volts and has a 20amp breaker in the USA but touching the terminals has been highly unrecommended by every mom for decades for good reason. Lightning strikes can be 100,000,000,000 volts and 50,000 amps and it is exceptionally dangerous.
# Understanding Watts, Volts, Amps, and Ohms
Electricity is energy resulting from charged particles but we need to further break down energy to get an idea of what we are working with.  The three most basic components in working with this energy are voltage, current, and resistance.  Voltage is measured in volts, current is measured in amps and resistance is measured in ohms.

Watts are the measurement of the amount of energy which is a relationship between volts and amps.  Voltage is the potential difference in energy and amperage is the volume of the energy.  This is described as Watts = Volts * Amps.  12 Volts at 4 Amps is equal to 48 Watts.  24 volts at 2 amps is also 48 watts.  Understanding this becomes very practical when designing tower sites for extended run times.

Another very practical thing to understand when working with batteries is Ah or amp hours which is electric charge potential multiplied by time (hours).  1 amp hour means one amp delivered for one hour.  A decently large deep cycle battery might be 12v 100Ah.  This means it can store enough energy to deliver 10 amps for 10 hours.  Don't count on that, however, you don't want to run a battery completely out of energy and they don't retain 100% capacity for long so if you are counting on Ah then figure 50% of the battery so if you draw 10amps on a 12v battery expect it to last for 5 hours.

## More info on the basics of Watts, Volts and Amps:
<div style="text-align:center; padding:1em">
<iframe width="420" height="236" src="https://www.youtube.com/embed/mvuHsu8S6v8?rel=0" frameborder="0" allow="autoplay; encrypted-media" allowfullscreen style="max-width: 100%;"></iframe>
</div>

# Human Safety First
You should be following the electrical code which ensures safety if you are in the USA be sure to follow the NEC (National Electric Code).
# Equipment Saftey Essential Concepts
<div style="padding:1em;"><img src="/uploads/groundingandbonding/dark-evening-lightning-66867-sm.jpg" alt="Dark Evening Lightning 66867 Sm" style="width:100%;"></div>

When it comes to surviving an electrical surge there are a few essential principals that will govern the survival of your equipment.  Interestingly your equipment having a wire going from a ground lug to a ground rod is not the key to survival and in some instances will cause your equipment to be destroyed.  This doesn't mean that grounding doesn't work or that it works against you or that it is unpredictable.

The first concept you need to understand to survive a surge is that opposite charges attract to each other (negative to positive).  It may be interesting to talk about lightning going up or down but this isn't the point that I'm driving at.  When applying this essential concept to your system you need to think that the charges in the sky and the charges in the ground are attracted to one another and one way or another they will connect.  Being in this path means carrying a surge of energy.  Furthermore, the charges are not coming from a single point but from an area in the sky and area in the ground.

The second essential concept is that electricity will follow the path of least resistance.  If there is a charge in a large area of land that is interconnected by a grid of ground rods, utility poles, and power lines that is opposite of a charge in the sky than there is a good chance for a lightning strike between the utility power grid and the sky because the metal power lines and ground rods offer a lower resistance path than other paths for equalizing the charges.  This is one reason that it is common to see blackened power receptacles at locations that have suffered a damaging surge.

# Grounding vs Bonding
There is a lot of confusion surrounding the idea of grounding and bonding.  It is helpful to understand the differences in the terms. Grounding is the connection of something to the ground and bonding is connecting two or more things together.  You can bond a tower to the ground electrodes which is generally what is meant when someone says they ground a tower. You don't, however, ground an antenna to a tower you bond it to a grounded tower or bond it to a ground wire.  Grounds and bonds are part of a grounding system and understanding the basic concepts and purposes of these terms will help you install equipment in a way that can stand up to the test of time.

The reason to care about the terms grounding and bonding is to help clarify that goal isn't just to connect your equipment to a patch dirt.  When you ground your tower and/or your equipment you need to be aware that the goal is to ensure that any transfer of energy happens via a safe path.  Bonding the major systems together is important and often overlooked.  To have a safe network for you and your equipment, you must have bonded connections other than your data cables which join the electrical ground system to the tower ground system and to your routers, switches, radios, antennas and any other equipment or conductive components.

Sadly many radios are needlessly lost each year because of a failure to properly bond tower grounds to utility grounds.  It isn't uncommon for a potential difference to exist between two areas of earth, in fact, you should expect it.  When you have a radio powered by the utility system and mounted to a grounded tower than you have just bonded two ground systems with a data cable which might be the lowest resistance path between the two systems... Furthermore, towers and antennas can build up static electricity from wind when the atmospheric conditions are right.  Eventually, if your equipment isn't grounded well, stored static electricity can build up enough energy to discharge and fry your radio with an ESD (electrostatic discharge).  Actually, much of what I've seen blamed on lightning is most likely an ESD event.

## Helpful Citations
In the event of a lightning strike with unbonded ground rods several feet apart, you will have a large voltage difference in the instance of time that the lightning is dispersing into the earth due to resistance in the soil.  If you have equipment which attaches to both of these ground sources, for example to the utility company for power and a grounded tower or mast, then your equipment may very well be the path of least resistance to equalize this large voltage potential.  It is therefore essential, not to mention required by NEC 810.21(J), to bond all ground systems with adequately sized cable. -- (H. Ward Silver, 2017, Grounding and Bonding for the Radio Amateur)

# Going Further
For more on this subject check our other wiki pages on  [Grounding and Bonding](/groundingandbonding)
# Credits
## About the Author
[Joshaven Potter](/authors/joshaven-potter) has been working in and consulting for the WISP community for close to two decades.  If you find this information valuable and want to show your appreciation with a Paypal donation or if you want to contact the author please follow [this link](/authors/joshaven-potter) to the author's page.

## Page Contributors
* Place holder for page contributors
