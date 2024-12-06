# Additional experiments for WWW25

## Exp 3: Adding a new baseline: LightDAG

Due to time constraints, we have currently added only one new baseline, LightDAG. We obtained the source code for LightDAG from its authors and conducted the corresponding experiments, as shown below. We will consider adding one or two more baselines in the future.

We specifically choose LightDAG1 from [IPDPS'24] LightDAG: A Low-latency DAG-based BFT Consensus through Lightweight Broadcast [10.1109/IPDPS57955.2024.00093](https://doi.ieeecomputersociety.org/10.1109/IPDPS57955.2024.00093) as our additional baseline.

### Setting:

- node number: $n=10$
- favorable situation: $f=0$
- $\Delta$: 1s

### Results:

- Pic1: Latency v.s.batch size
- Pic2: Throughput v.s. batch size
- Pic3: Latency v.s. throughput

Since LightDAG overlooks the latency optimization of non-leader blocks, it also performs worse than Wukong.
