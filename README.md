# Multi-objection Optimal Allocation Model for Water Management of Colorado River
**by Wanqi Hu, Xinran Wang, Yijia Xue**

*names by the alphabetical order of the last names*

**This project is for The Mathematical Contest in Modeling (2022). Our group chose Question 2, and we got H prize.**

## Introduction

Our team is trying to build a mathematical model to determine the allocation plan with the given water level of Lake Powell and Lake Mead. The final plan determines the amount of water that should be supplied by different dams (Glen Canyon or Hoover) to different areas (five U.S. states or Mexico) for different fields of usage (residential, industrial, agricultural, or generating electricity). 

The model is built from simple to complicated step by step. First, we abstract out the structure of
one dam. For each dam, the lake is regarded as a reservoir. Part of the water is allocated to the five states for general usage, part of it flows down, and the other part remains in the lake. The part flowing down passes the power generator, producing electricity, which is also allocated to the five states. Then we further consider the coordination of the two dams. The part of the water flows down from Glen Canyon dam forwards to Hoover dam with a fixed loss rate, and the water flows down from Hoover dam forward to Mexico with a different fixed loss rate. Based on the coordination, we consider the additional water joining into the lakes and supplying part of the water demands of the five states and Mexico, changing the current water level of the lake and water demands that needs to be satisfied from the lake. Coordinated together, Glen Canyon dam and Hoover dam are trying to satisfy a certain ratio of water demands and electricity demands from the five U.S. states and Mexico without exceeding a certain lower bound of the water level.

Based on the coordination system, we try to find an allocation plan that can maximize the social satisfactory degree, economic utility, and ecologic goods, which means we defined a multi-objection optimization problem. For the social satisfactory degree, we define it as the ratio of the actual received supply and the expected demand. The more extra supply they receive, the higher social satisfactory degree they show. Furthermore, we consider the economic utility. Economic utility depends not only on the profit, but the fairness, which gives priority of some fields of water usage to the others, and the efficiency, which sets a penalty of supplying water to the farther states. Last but not the least, we consider the ecologic goods, which set a different penalty to the COD pollution from different fields of water usage.

Based on the constructed model, we simulate the decision of the model under different water and electricity distribution by setting various control factors and changing input variables. The simulation results are compared, evaluated and visualized. The feasibility and stability of water allocation model are verified by sensitivity analysis with respect to demand factors. We suggest that this model has practical significance for the real-life water and electricity allocation management.

*Keywords: Water Allocation, Economy, Multi-objection Optimal Problem, Genetic Algorithm*

## Model Framework

![Model]("https://github.com/Wanqi9Hu/Multi-objection-Optimal-Allocation-Model-for-Water-Management-of-Colorado-River/blob/main/Model%20Framework.png" width="180" height="180")
