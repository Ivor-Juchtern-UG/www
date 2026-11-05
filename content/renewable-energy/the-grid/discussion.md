# Discussion: The Grid, Frequency and Inertia

Ivor Jüchtern and Claude (Anthropic), 4 and 5 November 2026. A voice conversation, condensed and paraphrased. Ivor's questions keep his framing; the answers are shortened.

This file has no frontmatter, so the site generator skips it (like resilience.md) and it is not published as a page.

## Topics marked for the outline

- Inter-area oscillations: large groups of generators (e.g. west vs. east of Europe) swinging against each other.
- Inverter control oscillations: inverter software overreacting and creating fast swings.
- __Double underlined:__ behind-the-meter energy management systems (EMS) and how their behaviour, good or bad, adds up across the Grid.
- Certification of EMS grid behaviour: largely a gap today.
- Possibly a third challenge next to throughput and balance: stability (the first seconds).

## 1. Where it starts

- Ivor: Let's review the development of grids historically. In the beginning there was no grid; then a grid at, say, 50 Hz; how did 50 Hz matter when the grid was very small? Build up the picture slowly.
- Claude: 1880s Edison, direct current, each station reaching about a mile. 1890s alternating current wins; transformers make long distances possible. Every city had its own frequency, Europe 25 to 60 Hz, gradually settling on 50 Hz. 1920s and 30s: isolated systems link into regional and national grids, and frequency becomes the shared heartbeat.

## 2. One generator

- Claude: One generator, e.g. a steam engine driving an alternator, feeding a town. Frequency is simply the machine's speed. A big motor switched on pulls on the shaft, the machine slows, frequency drops.
- Ivor: So load reduces the frequency.
- Claude: Yes.
- Ivor: And then whoever runs the generator has to increase power, burn more coal, to restore the frequency?
- Claude: Yes. The governor does it automatically by letting in more steam; the operator shovels more coal to keep the boiler pressure up.
- Ivor: What is a governor?
- Claude: A speed controller on the engine. The classic one: two heavy balls spinning on a shaft; when the engine slows, they drop inward and open the steam valve.
- Ivor: And if there is not enough steam?
- Claude: The valve is wide open but the engine cannot give more. Frequency keeps falling; operators disconnect customers (load shedding), or the system collapses into a blackout.
- Ivor: Does the guy who shovels coal see that there is not enough steam? He is watching some pressure.
- Claude: Yes, the stoker watches the boiler pressure gauge and feeds the fire harder when it drops.

## 3. Two generators

- Claude: Connect a second generator and the two lock together at exactly the same frequency and share the load.
- Ivor: If one is smaller and one bigger, are they affected differently?
- Claude: Both see the same frequency drop, but the bigger one takes a bigger share, roughly in proportion to its size, because their governors use the same droop setting.
- Claude: Their spinning masses add up: more inertia, smaller frequency swings.
- Ivor: They are operating independently, so if one fails, the other faces even more load. With more generators, if some fail, the failure accelerates; the bigger ones absorb some, but not all, and in the end all generation fails.
- Claude: That is a cascading failure, and it is how many real blackouts happen. Grids keep spare capacity running: spinning reserve.
- Ivor: By independent I mean operated by different operators, their own business. Independent, but electrically coupled.
- Claude: Yes. Independently owned and operated, electrically coupled. That is why someone has to coordinate them: the grid operator.

## 4. Somebody takes care of the cable

- Ivor: In a small city at the beginning there is no grid operator; there is a cable between the guy with the turbine and the guy with the light bulb.
- Claude: Yes. The station owner was the grid.
- Ivor: At some point somebody has to take care of the cable.
- Claude: Once several stations were linked, someone had to own the wires and dispatch the stations. Britain created the Central Electricity Board in 1926. (Legally, generation and wires were separated only with liberalisation in the 1990s.)
- Ivor: Figuratively speaking.
- Claude: Figuratively, yes: as systems grew, the jobs specialised.
- Ivor: So their first obligation was to watch the frequency, and to communicate with the guys who owned the turbines?
- Claude: Yes: balancing. They watched the frequency meter and phoned the stations: "add ten megawatts", "start another boiler". That is the origin of dispatching.
- Ivor: How did they know the frequency was falling?
- Claude: Frequency meters, e.g. the vibrating-reed meter: a row of steel reeds tuned to slightly different frequencies; the one vibrating most shows the frequency.

## 5. Grids connect, and what inertia is

- Claude: Next, neighbouring grids connect: cities, then regions. Hundreds of generators spin together, and the combined inertia makes the frequency steadier.
- Ivor: Is inertia the speed with which a generator connects and disconnects, like in physics and movement?
- Claude: It is the same inertia as in physics, applied to rotation: the resistance of a heavy spinning mass to changing its speed. Not about connecting or disconnecting.
- Ivor: What makes it hard to change the spinning speed?
- Claude: Mass, especially mass far from the centre. A heavy rotor spinning fast stores a lot of kinetic energy, which a sudden load must drain before the speed drops noticeably.
- Ivor: So at some point inertia becomes a metaphor; a nuclear power station has a different kind of inertia, you have to stop the reaction.
- Claude: No, a nuclear plant's inertia is physical too: it drives a huge turbine and generator. Being slow to change output is a different property: ramp rate, or flexibility.

## 6. Inverters and the nervous grid

- Ivor: Do heat pumps and things behind inverters, batteries, solar, have inertia?
- Claude: Not naturally. Nothing spins in sync with the grid. Inverters can be programmed to mimic inertia (synthetic or virtual inertia).
- Ivor: When people talk about inertia in scientific papers in 2026, what do they mean?
- Claude: The grid losing natural inertia as coal and gas plants close; frequency drops faster after a fault; how to replace it with grid-forming inverters, synchronous condensers, fast batteries.
- Ivor: So the grid becomes much more agile, because things connect and disconnect within milliseconds, while before the huge rotors held the inertia.
- Claude: The devices are more agile, but the grid itself becomes more nervous: frequency moves faster, so fast devices have to react quickly.
- Ivor: The grid gets more nervous. Good description.

## 7. Oscillations (marked for the outline)

- Ivor: What is oscillation? A solar inverter releasing power at a different amplitude?
- Claude: Less about amplitude, more about swinging back and forth. Classic: two large groups of generators, e.g. Spain and Eastern Europe, rocking against each other, power sloshing across the continent. New: inverter control software reacting too eagerly, overcorrecting, starting a fast swing of its own.
- Ivor: Two countries rocking against each other, in classical times?
- Claude: It still happens. Europe has a known slow east-west swing, roughly once every few seconds, monitored constantly.

## 8. Energy management systems (double underlined)

- Ivor: An immature provider of an energy management system that controls its inverters too eagerly puts instability into the grid.
- Claude: It can. Grid codes require inverters to be certified, but even certified devices can misbehave together, e.g. thousands reacting to the same price signal at the same moment.
- Ivor: I said energy management systems, not inverters: behind-the-meter systems running behind-the-meter strategies, like charging batteries.
- Claude: Good distinction. The inverter's own control works in milliseconds; the EMS sits on top and works in seconds to minutes.
- Ivor: And they can do it well or badly.
- Claude: A good one smooths its changes and adds randomness in timing; a bad one slams power on and off and reacts to every signal. If thousands do that together, the grid feels it.
- Ivor: Double underlined.

## 9. Measuring inertia

- Ivor: Reactive Technologies. I know they have 40 measuring points. Why so many?
- Claude: They measure inertia by injecting small, precisely timed power pulses and watching the frequency response. Inertia is not spread evenly; many sensors give regional detail, better accuracy against noise, and show how a disturbance travels.
- Ivor: Electricity travels at the speed of light. In a country the size of the UK, how long until a large event in the north is felt in the south?
- Claude: The electrical change arrives in milliseconds. The frequency disturbance spreads as a wave from rotor to rotor, at several hundred kilometres per second: a second or two from north to south.
- Ivor: Still quite fast.
- Claude: Fast for humans, slow for electronics.
- Ivor: Which properties of a grid are measurable? How do you measure inertia, and from where?
- Claude: Frequency, voltage, current, power flows, phase angles (PMUs). Inertia is not measured directly: a known power change and the rate of change of frequency (RoCoF). The known change comes from a natural event (a plant tripping) or a deliberate pulse.
- Ivor: Where does inertia come from today? We still have gas turbines; France has nuclear.
- Claude: Nuclear, gas, hydro, remaining coal, directly connected industrial motors; plus synchronous condensers and grid-forming batteries.
- Ivor: So inertia is still needed.
- Claude: For now. It buys the first seconds. Many researchers think fast inverters will reduce the need.

## 10. Blackout risk and certification

- Ivor: Is the danger of blackout increasing or decreasing now that everybody is a producer with some kind of EMS?
- Claude: Both. Less dependence on single plants and fast devices help; low inertia, poor visibility of millions of systems, and herd-like EMS behaviour hurt. It depends on rules and coordination.
- Ivor: Are there certifications for EMS? Many vendors are not certified at all.
- Claude: Not really. Inverters must meet grid codes (VDE-AR-N 4105 in Germany); the EMS layer is mostly unregulated for grid behaviour. Some movement: §14a EnWG and the smart meter gateway, EU cybersecurity rules.
- Ivor: Is it because EMS penetration is still small?
- Claude: Partly. Also, EMS software is updated constantly and hard to certify, and regulators assumed certifying the inverter is enough.
- Ivor: If the inverter sits behind an EMS together with batteries and industrial equipment, "good enough" is not true anymore.
- Claude: Exactly. The certified inverter cannot stop the EMS above it from commanding sudden swings, or many sites acting at once. Grid behaviour emerges from the whole system, and nobody certifies that.

## 11. The article

- Ivor shared the draft article The Grid and asked whether it is correct and going in the right direction.
- Claude: Yes. Strongest ideas: throughput vs. balance, and the meter as a legal, not an electrical, boundary. To fix: the frequency numbers are too loose for Europe; "no valve" overstates things; the nature section's conclusion does not follow from its numbers. Several sections are drafts.
- Ivor: Restructure the article into a historic overview with short sections on a timeline, preserving my way of thinking; do not remove empty sections and do not touch my content; add the discussion and review comments, as a pull request. Use the Edison Pearl Street photo for the "one generator, one user" section.
- Claude: Pearl Street (1882) fits "the station owner was the Grid", but it ran on direct current, so it had no frequency.
- Ivor: Is the Alliance machine (Floris Nollet) suitable as the first illustration?
- Claude: Even better for "one generator, one user": in the 1860s an Alliance machine lit a lighthouse, one generator feeding one arc lamp, with alternating current. Frequency existed, but nobody cared. It is a magneto without a governor, so it is the very first step.
- Ivor: Use both, and split the sections: first where frequency is no problem, then where it becomes a problem.
- Result: 1860s Alliance machine (one generator, one user, AC, no problem) → 1882 Pearl Street (one station, many users, DC, no problem) → 1891 AC (still no problem) → 1890s: Frequency Becomes a Problem (motors, connected stations).
