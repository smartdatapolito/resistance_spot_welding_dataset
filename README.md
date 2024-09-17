# Resistance Spot Welding Dataset
This repository contains a real-world dataset collected from a leading automotive industry, focused on the resistance spot welding process. The dataset includes 1,976 samples with labels indicating the presence of faulty welds (i.e., welds that have not been performed correctly).

The dataset features variables from the welding process, such as voltage, current, and force applied during the weld. Each sample is labeled with a binary value indicating whether the welding was correctly performed (0) or faulty (1).

The repository includes the following files:
- labels.csv: Contains binary values where 1 indicates a faulty welding point.
- voltage.csv: Contains time-series data of the voltage applied during each welding operation.
- current.csv: Contains time-series data of the current applied during each welding operation.
- force.csv: Contains time-series data of the force applied during each welding operation.

All time-series data have been normalized to a range of [0,1] and zero-padded to 1,000 steps (the actual length varies between samples).
