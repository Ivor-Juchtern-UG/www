---
category: Renewable Energy
title: The Grid
authors: 
image: images/1.jpeg
explanation: Workers performing maintenance by riding in gondolas under high-voltage lines near the author's home in Darmstadt, Germany.
---

<!-- Claude review (whole article): The sections with years in their headings, plus a few others, are new and come from our discussion; your own text is unchanged. These review comments are invisible on the page, but the generator copies them into the page source, so delete them before you rebuild public/. Hero image: images/1.jpeg still contains GPS coordinates in its EXIF data (near your home), so consider stripping them. The generator reads the image size from the EXIF thumbnail (160 x 120) instead of the real photo (2048 x 1536), so the social-card size tags are wrong. The frontmatter field "authors" is empty. -->

# Audience

This article is written for professionals responsible for the purchase and use of energy in industrial contexts.

# Lie-to-Children

In order to keep the article short and interesting, some complex topics are simplified.

The detailed story is available in my _magnum opus_ — the Handbook — How to Ask and Answer Questions Related to Renewable Energy In Industrial Contexts.

# The Grid?

The electrical grid.

# Why talk about the Grid?

The Grid is a major factor in energy and will play an important role in the future. A role, which already affects and will affect everyone in industrial contexts. Its nature and upcoming changes should be, therefore, understood and taken into account.

# What is the Grid?

The Grid is the infrastructure connecting in-front-of-the-meter sources of energy the behind-the-meter consumption. Over short, long and very long distances.

<!-- Claude review: A word is missing: "connecting in-front-of-the-meter sources of energy [to] the behind-the-meter consumption". Also, energy now flows both ways: rooftop solar and batteries are sources behind the meter, and the Grid carries their surplus outwards too. -->

# A Short History of the Grid

The Grid was not designed. It grew, step by step, and each step left something we still live with today.

## In the Beginning: No Grid

There was no Grid. Energy was made where it was used.

A factory had its own steam engine. Shafts and leather belts carried the power to the machines. Light came from gas, oil and candles.

## 1860s: One Generator, One User

![An Alliance machine, the generator that grew out of Floris Nollet’s design. In the 1860s such machines lit lighthouses: one generator, one arc lamp, alternating current.](images/the-grid-2.jpg)

<!-- Claude: add the source and licence of the Alliance machine photo to the caption above. -->

Floris Nollet, a Belgian professor, designed a steam-driven generator in 1849. After his death, the company L'Alliance developed it further.

In 1863 an Alliance machine began lighting the lighthouse at Cap de la Hève near Le Havre. It fed one arc lamp.

One generator, one user. Literally.

The machine produced alternating current, so frequency already existed. But nobody cared. If the machine slowed down, the lamp dimmed a little, and nobody else was affected.

Frequency: no problem.

## 1882: One Station, Many Users

![Edison’s “Jumbo” dynamo at Pearl Street Station, New York, the first central power station in the United States (1882). Pearl Street ran on direct current, so it had no frequency at all. Image: Wikimedia Commons.](images/the-grid-1.jpg)

In 1882 Thomas Edison opened Pearl Street Station in New York. Steam engines drove dynamos, and cables ran from the station straight to the customers' lamps, within about a mile.

There was no Grid in our sense. There was a cable between the guy with the turbine and the guy with the light bulb. The owner of the station was the Grid.

Pearl Street used direct current at low voltage. That is why its reach was so short.

Direct current has no frequency. Frequency: no problem.

## 1891: Alternating Current Brings Frequency

Alternating current won the "war of the currents". With transformers, the voltage could be raised for long distances and lowered again for the user.

In 1891 a three-phase line carried power 175 km from Lauffen am Neckar to the electrical exhibition in Frankfurt am Main, at 40 Hz.

With alternating current comes frequency. In a small system with one generator, frequency is simply how fast the generator turns.

Every town chose its own. Europe used everything from 25 Hz to 60 Hz before slowly settling on 50 Hz.

Still no problem. Each station fed its own lamps at its own frequency, and lamps barely notice.

## 1890s: Frequency Becomes a Problem

Two things changed.

First, electric motors. An alternating-current motor turns at a speed set by the frequency. When the frequency drops, the machines in the factory slow down with it. Now frequency matters to the user.

Second, stations get connected. Two generators on the same wires must turn in step, at exactly the same frequency.

From here on, frequency is a problem, and somebody has to keep it steady.

## Load Slows the Generator

When someone switches on a large motor, the load pulls on the shaft. The generator slows down, and the frequency drops.

Less load: the generator speeds up, and the frequency rises.

So frequency is a signal. It tells everyone, at the same moment, whether there is too little or too much generation.

## The Governor and the Stoker

Two things keep the speed steady.

The first is the governor, a speed controller on the engine. The classic one has two heavy metal balls spinning on a shaft. When the engine slows, the balls drop inward, and that opens the steam valve.

The second is the stoker. He watches the boiler pressure gauge. When the engine uses more steam, the pressure drops, and he feeds the fire harder.

If there is not enough steam, the valve is wide open and the engine still cannot give more. The frequency keeps falling. Some customers have to be disconnected (load shedding), or the system collapses: a blackout.

## What is Inertia?

Inertia is the resistance of a heavy spinning mass to changing its speed. Think of a heavy flywheel: it is hard to slow down.

A large rotor spinning fast stores a lot of kinetic energy. When the load jumps, that energy is drained first, before the speed drops noticeably. Inertia buys time for the governor and the stoker.

Inertia is not how fast a power plant can change its output. A nuclear plant is slow to change its output, but its huge turbine gives plenty of inertia. Slowness of output is called ramp rate, or flexibility.

With one small generator there is little inertia, and the frequency swings a lot. With only lamps attached, nobody cared. With motors and a second generator, it starts to matter.

## Two Generators

Connect a second generator to the same wires, and the two lock together. They spin at exactly the same frequency.

When the load rises, both see the same frequency drop. Each adds power in proportion to its size, because their governors use the same "droop" setting. The big one takes the big share.

Their spinning masses add up. More inertia, steadier frequency.

## Independent, but Coupled

The generators can belong to different owners. They are independent as businesses, but coupled electrically.

If one fails, the others must take its load at once. If they cannot, they slow down, protection trips more of them, and the failure accelerates: a cascading failure. This is how many real blackouts happen.

This is why grids keep spare capacity running, called spinning reserve.

## 1920s: Somebody Takes Care of the Cable

Once several stations share the wires, somebody has to take care of the cable. Figuratively speaking, the guy with the turbine lets go of the cable and focuses on the turbine.

In Britain, the Central Electricity Board was created in 1926 to build a national grid. In Germany, RWE built a north-south line around 1930, linking Rhineland coal with Alpine hydropower.

The first obligation of the people who took care of the cable was balancing: keep generation equal to demand, so the frequency stays at its nominal value.

They watched frequency meters. A common early type was the vibrating-reed meter: a row of small steel reeds, each tuned to a slightly different frequency. The reed that vibrates most shows the current frequency.

When the frequency fell, they phoned the power stations: "add ten megawatts", "start another boiler". This is the origin of dispatching.

## 1950s: Grids Connect to Grids

Next, grids connect to grids. Cities, then regions, then countries.

In 1951 the western European grid operators founded the UCPTE to coordinate. In 1958 the grids of Germany, France and Switzerland were joined at Laufenburg, the "Star of Laufenburg".

Today the Continental European grid runs at one 50 Hz from Portugal to Turkey. Ukraine and Moldova joined in 2022, the Baltic states in February 2025. Thousands of generators spin together, and their combined inertia makes the frequency very steady.

Size brings new problems. A disturbance does not reach everyone at once: the change in frequency travels across the Grid as a wave, from rotor to rotor, at several hundred kilometres per second. Across a country like Britain that takes a second or two. Fast for humans, slow for electronics.

And large areas can swing against each other. More on that below.

## 1990s: Turbine and Cable Become Separate Companies

For most of the 20th century, one company owned everything: the power stations and the wires.

In the 1990s Europe liberalised electricity. Generation, trading and the grid were separated ("unbundling"). Grid operators became companies of their own, with one job: run the network and keep the frequency in check.

This legal separation is where the meter gets its meaning.

# Behind-the-Meter (BTM) and In-Front-of-the-Meter (FTM)

The Grid both ends and does not end at your Grid Power Meter.

The Grid Power Meter demarcates two legal, but not electrical spaces: in-front-of-the-meter (FTM) and behind-the-meter (BTM)

From an electrical point of view in-front-of-the-meter (FTM) and behind-the-meter (BTM) is the same space.

<!-- Claude review: Strong point, keep it. You could add that the legal line has consequences: in front of the meter the grid operator is responsible, behind it you are. And since 2024 (§14a EnWG) the grid operator can reach behind the meter and dim controllable devices such as heat pumps, wallboxes and batteries. -->

# Flow of Electricity vs Flow of Water

There are a number of misunderstanding in relation to the Grid, and I have been looking for a suitable metaphor to help me talk about them.

The closest metaphor would be the flow of water and it does not work.

Electricity and water behave in fundamentally different ways.

The most significant difference, is that water flow is controlled at the valve, which is not applicable to electricity. The flow of electricity is controlled at the source.

This means, that when the sun is shining and your solar panels produce more electricity, than you consume, and you should not deliver to the Grid; what you do is reduce the production. There is no valve between your solar production and the grid you can close.

<!-- Claude review: "There is no valve" overstates it a little. Breakers can open the circuit, and an inverter can limit its output to zero export, which works like a valve at the source. What really differs from water: electricity cannot be stored in the pipe, it flows along all paths at once according to physics, and you cannot route it. That supports your point that control happens at the source. -->

# Challenges Facing the Grid

When talking about the challenges facing the Grid, the common sense is an amalgamation of the two core challenges: "throughput" and "balance/imbalance". These are commonly amalgamated into "what the grid can do". And into "make the grid able to do more".

To properly understand and act upon the future of grid one should learn the difference.

<!-- Claude review: The strongest idea in the article. Consider a third challenge next to throughput and balance: stability. Balance is about energy over minutes and hours; stability is about the first seconds (inertia, voltage, oscillations). The Iberian blackout of 2025 was a stability failure, not a lack of energy. See the new sections further down. -->

## Throughput

Throughput (transmission and distribution capacity)

Upgrading throughput—e.g., adding high-voltage lines or smart grid tech—lets you move more power,  but it doesn’t by itself ensure that generation matches consumption at every moment.

So, upgrading the Grid for throughput addresses (and I am on purpose not saying "fixes") only half of the problem.

## Balance/Imbalance

Supply and demand balance (balancing generation with consumption)

Upgrading throughput—e.g., adding high-voltage lines or smart grid tech—lets you move more power,  but it doesn’t by itself ensure that generation matches consumption at every moment. You still need mechanisms like storage, demand response, or flexible generation to handle the supply–demand problem.

<!-- Claude review: The first sentence of this paragraph repeats the Throughput paragraph word for word. -->

## Grid and Nature

Ja, Vögel sterben jedes Jahr in Deutschland an Freileitungen und Masten durch tödliche Kollisionen und Stromschläge.In Deutschland verenden schätzungsweise 1 bis 2,8 Millionen Vögel jährlich an solchen Anlagen. https://niedersachsen.nabu.de/tiere-und-pflanzen/voegel/34803.html

In Deutschland sterben schätzungsweise 100.000 bis 250.000 Vögel jährlich durch Kollisionen mit Windkraftanlagen.

In Deutschland sterben schätzungsweise 100.000 bis 250.000 Vögel jährlich durch Kollisionen mit Windkraftanlagen.Einordnung im VergleichGlasscheiben: 100 bis 115 Millionen tote Vögel pro Jahr.Straßenverkehr: Rund 70 Millionen tote Vögel pro Jahr.Hauskatzen: 20 bis 100 Millionen tote Vögel pro Jahr.

Conclusion:

Less Grid is better for the nature.

<!-- Claude review: This section is in German while the article is in English, and the sentence about wind turbines appears twice. Only the power-line figure has a source (NABU); the others need one too. The conclusion "Less Grid is better for the nature" does not follow from the numbers: they compare power lines with glass, traffic and cats, not more grid with less grid. It also sits under "Challenges Facing the Grid" as a subsection. -->

# Grid and Energy Productoin

In an AC grid, generation must match consumption in real time. Any imbalance causes the grid frequency to deviate from its nominal value (50 Hz or 60 Hz). The system uses that frequency deviation as a feedback signal: if demand rises, frequency drops; generators automatically increase output (primary control), and additional reserves are dispatched (secondary/tertiary control) to restore balance.

<!-- Claude review: Typo in the heading ("Productoin"). The paragraph is correct. In Europe the three control levels are called FCR (primary, fully active within 30 seconds), aFRR (secondary, within 5 minutes) and mFRR (tertiary, within 12.5 to 15 minutes). Before all three comes inertia, which acts in the first seconds without any control. -->

## Tolerable variations

Frequency: Most grids allow ±0.5 Hz (sometimes ±1 Hz) for brief periods; sustained deviations outside ±0.1–0.2 Hz trigger protective actions.

<!-- Claude review: These numbers are too loose for Continental Europe. Normal operation stays within 0.05 Hz of 50 Hz. Reserves (FCR) are fully active at a deviation of 0.2 Hz, which is control, not protection. The maximum allowed instantaneous deviation is 0.8 Hz. Automatic load shedding starts at 49.0 Hz, and power plants may disconnect below 47.5 Hz or above 51.5 Hz. So a swing of 0.5 Hz is already a serious event. -->

Voltage: ±5 % is typical; beyond ±10 % risks equipment damage.

<!-- Claude review: For low voltage, EN 50160 allows 230 V plus or minus 10 % (for 95 % of the 10-minute averages in a week), so 10 % is the normal limit rather than the damage zone. -->

Time: Imbalances of seconds to minutes are managed by inertia and reserves; longer mismatches require curtailment, load shedding, or blackouts.

So the match must be precise in the long run, but the grid can tolerate small, short-lived deviations while control systems act to restore equilibrium.

# The Grid Today: Fewer Rotors, More Inverters

## 2000s: Inverters Arrive

Solar panels, batteries and most modern wind turbines are connected to the Grid through inverters: power electronics that turn their output into 50 Hz alternating current.

Nothing behind an inverter spins in sync with the Grid, so inverters bring no natural inertia. Modern heat pumps run their motors through electronics as well, so they are decoupled too.

Inverters are controlled by software, and they are fast. They can react within milliseconds. The flow of electricity is controlled at the source, and the source is now software.

## 2006: One Line, Fifteen Million Households

On 4 November 2006, a high-voltage line over the river Ems in northern Germany was switched off so that a cruise ship could pass. Other lines overloaded and tripped one after another, and within seconds the European grid split into three islands.

In the western island there was too little generation, and the frequency fell to about 49 Hz. Automatic load shedding disconnected around 15 million households, most of them for less than two hours.

Independent, but coupled, at continental scale.

## 2012: The 50.2 Hz Problem

Early German rules told small solar inverters to switch off when the frequency rose to 50.2 Hz. Sensible for one device.

But Germany soon had many gigawatts of solar following the same rule. A small over-frequency would have disconnected all of them at the same instant, turning a small surplus into a large deficit.

From 2012 onwards, hundreds of thousands of installations were retrofitted. A setting that is safe for one device can be dangerous for a million.

## 2010s: The Grid Gets More Nervous

As coal plants close and inverters replace them, the Grid loses natural inertia.

After a fault, the frequency now changes faster. Engineers measure this as RoCoF, the rate of change of frequency. Less inertia, higher RoCoF, less time for everything else to react.

The devices become more agile, but the Grid itself becomes more nervous. Fast devices now have to react fast, just to keep things stable.

## Two Kinds of Oscillation

Oscillation means something swinging back and forth.

The first kind is old: inter-area oscillation. Large groups of generators far apart swing against each other, and power sloshes back and forth across the continent. In Europe the west and the east swing slowly against each other, about once every four to seven seconds. Operators watch it constantly.

The second kind is new: inverter control oscillation. Inverter software reacts too eagerly to the Grid, overcorrects, and starts a fast back-and-forth swing of its own.

## 2020s: Everybody is a Producer

Today almost everybody can be a producer: solar on the roof, a battery in the basement, a heat pump, a wallbox, a production line with its own storage.

Above the inverters sits the energy management system (EMS), which carries out the behind-the-meter strategy. The inverter's own control works in milliseconds and keeps its output locked to the Grid. The EMS works in seconds to minutes and decides: charge the battery now, run the heat pump later.

An EMS can do this well or badly.

__A good EMS smooths its changes and adds some randomness to its timing. A bad one slams power on and off and reacts to every small signal. If thousands of them react to the same price signal at the same moment, the Grid feels it.__

## Who Certifies the EMS?

Inverters must meet grid codes, such as VDE-AR-N 4105 in Germany. They are tested and certified for how they respond to voltage and frequency.

The EMS above them is mostly not certified for its grid behaviour. There is some movement, such as §14a EnWG, which lets grid operators dim controllable devices through the smart meter gateway, and EU cybersecurity rules. But a real certification of EMS grid behaviour is largely missing.

Partly, regulation follows only once something becomes big enough to cause trouble. Partly, an EMS is software that is updated constantly, which makes it hard to certify. And regulators have assumed that certifying the inverter underneath is enough.

It is not, once the inverter sits behind an EMS together with batteries and industrial equipment. A certified inverter only guarantees its own behaviour within its own limits. It cannot stop the EMS above it from commanding sudden swings, or many sites from doing the same thing at once. The behaviour that matters for the Grid emerges from the whole system, and nobody certifies that today.

## 2025: The Iberian Blackout

On 28 April 2025, Spain and Portugal went dark within seconds.

The final expert report, published in March 2026, found many interacting causes, among them oscillations, gaps in voltage control, and generators disconnecting one after another. There was no lack of energy. It was a failure of stability.

## 2026: Inertia Becomes a Product

Inertia is still needed. It buys the first few seconds after a fault, before other controls kick in.

It comes from whatever still spins in sync: nuclear, gas, hydro and the remaining coal plants, plus large industrial motors connected directly to the Grid.

New sources are added on purpose: synchronous condensers, large spinning machines that burn no fuel and exist only to spin, and grid-forming inverters, usually on batteries, which imitate inertia ("synthetic inertia").

Since 22 January 2026, the four German transmission system operators pay for inertia (Momentanreserve) from synchronous machines and grid-forming inverters. Inertia has become something you can sell.

Many researchers argue that if inverters react fast enough, we will need much less physical inertia in future.

## Measuring a Nervous Grid

What can be measured: frequency, voltage, current, power flows and phase angles, often with phasor measurement units (PMUs).

Inertia cannot be measured directly. You need a known change in power, and you watch how fast the frequency moves. A big power change with a slow frequency drift means lots of inertia.

The known change comes from a natural event, such as a power plant tripping, or from a deliberate pulse.

The British company Reactive Technologies does the second. It injects small, precisely timed power pulses and measures the response with sensors across the Grid. Britain's system operator uses it, and projects followed in Australia, Taiwan and New York.

Why so many sensors? Inertia is not spread evenly. Regions full of large rotors respond differently from regions full of wind and solar. Many sensors map inertia by region, beat background noise, and show how a disturbance travels across the network.

## Is the Danger of Blackout Rising?

Both ways. More producers mean less dependence on any single plant, and fast, flexible devices can help a lot.

But low inertia, little visibility of millions of small systems, and badly behaved or herd-like energy management can make things riskier. It depends on rules and coordination, and on behaviour behind the meter.

# Cost of Electricity vs Cost of Transport

## Netherlands

Dutch grid tariffs.

Current tariffs are largely fixed and based on connection capacity and consumption

There are discussions about variable grid tariffs in the Netherlands

The Dutch government is addressing grid congestion with various measures

The Dutch government and grid operators (Liander, Enexis, Stedin, TenneT) are implementing other measures including regional tenders for flexible deployment starting in 2026, and procuring flexibility to free up capacity.

<!-- Claude review: "Starting in 2026" is now the present; check what has actually started and update the tense. For the empty Germany section, current topics are the §14a EnWG grid-fee reductions for controllable devices, the ongoing grid-fee reform at the Bundesnetzagentur (AgNes), and the new paid market for inertia since January 2026. -->

## Belgium

## France

## Germany

## Switzerland

## Austria

## UK

## Finland

# Measures You Should Take

<!-- Claude review: Two measures that follow from the new sections: make sure your own EMS behaves well towards the Grid (smooth ramps, no reaction to every small signal, some randomness in timing), and check whether your battery could earn money as grid-forming inertia. -->

## Study Your Energy Profile

## Create a Strategy

## Restructure, Purchase and Manage








To operate during a grid failure, inverters and batteries must be installed in a backup or hybrid configuration that includes an automatic way to disconnect from the public utility. [1] (https://en.u-energie.de/blogs/can-a-hybrid-inverter-continue-to-power-the-house-during-a-power-outage), [2] (https://www.anernstore.com/blogs/diy-solar-guides/why-inverters-cut-out-grid-fails)Standard grid-tied systems shut down during power cuts for safety reasons (called anti-islanding) to prevent electricity from flowing back into the lines and harming utility workers. [1] (https://www.youtube.com/watch?v=kSVPATedUXg&t=34)Core Components Needed for Backup OperationHybrid Inverter: Unlike standard inverters, a hybrid inverter can detect a grid failure, isolate your home, and form a local "microgrid" using battery or solar power. [1] (https://www.anernstore.com/blogs/diy-solar-guides/why-inverters-cut-out-grid-fails), [2] (https://en.u-energie.de/blogs/can-a-hybrid-inverter-continue-to-power-the-house-during-a-power-outage)Battery Storage: A compatible battery bank (such as LiFePO4) stores energy to power your home when the sun isn't shining or the grid is down. [1] (https://en.u-energie.de/blogs/can-a-hybrid-inverter-continue-to-power-the-house-during-a-power-outage), [2] (https://www.anernstore.com/blogs/diy-solar-guides/why-inverters-cut-out-grid-fails)Transfer Switch / Backup Gateway: A physical safety device (an Automatic Transfer Switch or backup box) automatically disconnects your home wiring from the public grid before emergency power activates. [1] (https://www.highflowenergy.com.au/solar-battery-blackout-protection/), [2] (https://www.reddit.com/r/SolarDIY/comments/1h06rgz/getting_access_to_generated_energy_during_power/)Critical Loads Subpanel: A separate subpanel that groups essential circuits (like refrigerators, lights, and Wi-Fi) so you do not drain the battery trying to power heavy appliances like air conditioners. [1] (https://www.anernstore.com/blogs/diy-solar-guides/why-inverters-cut-out-grid-fails)

<!-- Claude review: The paragraph above and the one below read like pasted chat output. Sentences run together without spaces, they speak about "your home", Wi-Fi and air conditioners rather than industrial sites, most sources are Reddit, YouTube and shop blogs, and the text ends with a chatbot question to the reader. The generator also turns the underscores in the Reddit links into italics, so those links are broken on the live page. -->



Installation ApproachesHybrid Inverter with Backup Port:The inverter features a dedicated emergency power output.Only pre-selected critical loads wired to this specific port stay active during an outage. [1] (https://www.youtube.com/watch?v=Rw6uRaIu0aw&t=76)Whole-Home Backup Gateway:Installed between the main utility meter and your main electrical panel.It isolates the entire home automatically, allowing the battery and solar system to back up all household circuits (subject to total power limits). [1] (https://www.youtube.com/watch?v=Rw6uRaIu0aw&t=76)Battery-Free Daytime Backup (Limited):Some modern systems offer limited daytime backup straight from solar panels without a battery (e.g., specialized solar inverters with backup sockets or microinverter setups).These only work when the sun is shining and will cut out if a cloud passes over. [1] (https://www.reddit.com/r/SolarDIY/comments/1ffk9yx/grid_tied_hybrid_inverters_cant_operate_on_their/), [2] (https://www.youtube.com/watch?v=kSVPATedUXg&t=34), [3] (https://www.zonnefabriek.nl/en/knowledge-center/back-up-power-when-the-grid-goes-down-is-becoming-increasingly-popular/)If you'd like to plan your setup, tell me:Do you already have solar panels or an inverter installed?Are you looking for whole-home backup or just essential circuits?