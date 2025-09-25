# Designing-IoT-Pipeline
KemPower

# Goals 
Analyze the data given by Kempower about EV charging and make research and innovation. These will be used by KemPower to decide on expanding the usage in next year.
# Planning
  - ✅ Get access to the Dataset (done)
  - Analyze the results (on progress)
  - Brainstorm ideas to get results from the data set. For example most charged time of the day or month of the year.

    - Currently I am planning to work on 2024 as main focus year since its a complete year and I can analyze full year cycle easily since 2025 hasn't ended yet, but briefly show if the trend seen in 2024 still can be seen in 2025.
# Roles
  - Every roles goes to me :)
# Communication platform
  - Not needed
# The research data will be given. 
---“Kempower Passenger EV Charging Dataset”---
# Documentation
  - All documentation, dataset, analyzes will be saved on my local machine.
# Testing
  - Since this project is mostly based on analizing the data, testing is not necessary.

# Ideas
1. Charging Efficiency Insights per EV Model

What to do: Compare avgPowerW, avgCurrentA, avgVoltageV, and SOC increments per EV model.

Unique angle: Instead of just average power, calculate charging efficiency per kWh of battery per minute.

Why it’s special: Helps identify which models use the infrastructure most efficiently, guiding decisions on hardware upgrades or incentives for slower models.

2. Temperature Impact on Charging Performance

What to do: Analyze avgPowerW and soc changes across temperature bins (tempC).

Unique angle: Instead of simple averages, calculate percentage drop in charging efficiency per degree deviation from optimal range.

Why it’s special: Can suggest seasonal adjustments (like pre-heated chargers in winter) or predict winter charging delays, which most teams ignore.

3. Peak Load & Grid Stress Analysis

What to do: Use sampleTime10sIncrement and weekday to find highest simultaneous load periods.

Unique angle: Combine multiple months to predict peak load times by day and hour, including standard deviation of power.

Why it’s special: Allows the company to plan for grid expansion or smart load balancing, instead of just reporting “most busy hour”.

4. EV Adoption Hotspots

What to do: Aggregate by country and optionally by EVModel to find which EVs are most popular where.

Unique angle: Combine with avgPowerW and SOC to see which regions have faster or more efficient charging.

Why it’s special: Helps decide where to expand stations or optimize power allocation, rather than just knowing raw counts.

5. Battery Health / Charging Pattern Signals

What to do: Track SOC increments per charging session (avgPowerW vs SOC delta) for the same EVModel.

Unique angle: Detect abnormal charging behavior (e.g., SOC rising unusually slow), which may indicate battery degradation or infrastructure mismatch.

Why it’s special: Most teams just report usage counts — detecting battery or infrastructure issues is proactive and predictive.
