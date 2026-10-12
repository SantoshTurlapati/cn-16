# Experiment 16: Network Simulation Using NS-2 / NCTUns Practical

## Aim
Study network simulation and perform packet-drop, TCP/UDP traffic, congestion, and throughput experiments described in the supplied practical.

## Requirements
- Computer with the relevant tool/simulator installed
- Authorized local lab target or simulator environment
- Folder to save output and screenshots

## Procedure
1. Review the simulator available in your lab. The supplied document mentions NS2 in the aim but its procedural steps refer to NCTUns GUI features; confirm which simulator your instructor expects.
2. Create and save the topology using the simulator's supported file format.
3. Configure hosts, links, queue sizes, traffic sources/sinks, and statistics according to the lab handout.
4. Run the simulation using the simulator's run controls.
5. Open the generated results/log files and record packet drops, collisions, sent packets, and throughput as applicable.
6. Repeat the simulation after changing one parameter at a time, such as bandwidth or queue size, and compare the results.
7. Capture screenshots of the topology, configuration, running simulation, and results.

## Commands / examples

### Traffic generator command shown in source (verify for your simulator)
```text
stg -u 1024 100 1.0.1.2
```

### Receiver/log command shown in source (verify for your simulator)
```text
rtg -u -w log1
```

### TCP/UDP examples
```text
The source mentions ttcp and stcp/rtcp commands; validate their availability and syntax in your installed simulator.
```

## Observation table

| No. | Test / configuration | Observed result | Evidence file |
|---:|---|---|---|
| 1 | Initial run | Fill in after your run | `evidence/` |
| 2 | Changed configuration / second test | Fill in after your run | `evidence/` |

## Result
Write the result only after completing the practical and checking the actual output.

## Conclusion
This experiment helps study the relevant network tool/simulator and interpret its results.

## Important notes
The source handout mixes NS2 terminology with NCTUns GUI steps and commands. Do not assume every command works in standard NS-2; follow your instructor's lab setup and simulator version.

## Evidence checklist
- [ ] Screenshot of setup or topology
- [ ] Screenshot of command/configuration
- [ ] Screenshot of actual output/results
- [ ] Record the date, environment, and parameters changed
