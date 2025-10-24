# Smart Control of Solar-Powered Oil Press

This is the repository that contains the source code for the [SolPrInt website](https://bonjoe.github.io/solprint.demo/).

If you find this work useful for your research please cite:
```
@article{BONZI2025100772,
title = {Smart control of standalone solar-powered oil press: Applying Reinforcement Learning for productivity and energy utilization improvement},
journal = {Renewable Energy Focus},
pages = {100772},
year = {2025},
issn = {1755-0084},
doi = {https://doi.org/10.1016/j.ref.2025.100772},
url = {https://www.sciencedirect.com/science/article/pii/S1755008425000948},
author = {Wiomou Joévin Bonzi and Zhangkai Wu and Sebastian Romuli and Klaus Meissner and Joachim Müller},
keywords = {Deep reinforcement learning, Solar PV, Off-grid control, Microcontroller deployment, Rural agri-processing},
abstract = {In resources constrained rural areas, solar-powered oil extraction can be enhanced through recent advances in artificial intelligence for energy optimization. This study introduces SolPrInt, a deep reinforcement-learning (DRL) based controller for a standalone, photovoltaic-battery powered mechanical oil press. A proximal policy optimization (PPO) agent was trained in MATLAB/Simulink using 15 years of PVGIS-SARAH2 radiation data and peanut-oil extraction benchmarks. A primary training phase followed by an adversarial phase on the 5% least-sunny days reinforced robustness under low-irradiance conditions. The developed agent adapts press rotational speed to real-time PV availability, battery state of charge, and system behavior to ensure energy-efficient use of solar resources. In-silico validation achieved stable rewards and simulated throughput of 96 ± 13.5kg/d under sunny days and 90 ± 20.5kg/d under cloudy days. Compared with conventional fixed-schedule operation (08:00–18:00) under sunny and cloudy conditions, SolPrInt extends operating time, and reduces power outages, while improves oil yield by 0.7 percentage points. Experimental validation on a PV-simulator bench confirmed real-time deployment feasibility on a low-cost ESP32 microcontroller interfaced with a Kern Kraft KK20 press. These findings demonstrate the potential of PV-sensitive DRL control to improve the performance of standalone renewable energy systems, supporting reliable decentralized energy use and contributing to sustainable energy access sustainable energy access. Supplementary materials supporting this work, are available at https://bonjoe.github.io/solprint.demo/}
}
```

# Website License
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
