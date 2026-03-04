---
layout: project
title: Nutcracker Design Analysis
description: Design analysis of a nutcracker 
image: /assets/images/nutcracker.png
---

## Problem Statement and Objective (Find)

Design a nutcracker capable of cracking a standard macademica nut with force input from 1) a human's grip and 2) a linear actuator. Find the dimensions of the nutcracker and an appropriate linear actuator to use. 

## Constraints and Input Parameters (Given)

- Average max grip force for women 20-30: 65 lbs
- Macademia cracking force: 222.18 N
- Average macademia nut diameter: 1 inch

## Approach
Assumptions:
- Rigid members
- Negligible friction at hinge
- Point contact between nut and jaws
- For the linear actuator design, I assumed the handle would be roughly a straight line

The nutcracker was modeled as a lever system. Mechanical advantage was calculated using

$$
MA = \frac{L_{handle}}{L_{jaw}}
$$

The greater the ratio between $$ L_{handle} $$ and $$ L_{jaw} $$, the less force input needed fron the user. However, the required length of the tool is greater.

For the linear actuator design, 

## Nutcracker Design and usability discussion

![Nutcracker diagram](/assets/images/nutcracker.png)

## Usability of linear actuator nutcracker
The addition of the linear actuator makes the overall design much wider, but not much longer. This iteration is much more accesible in design, seeing as it does not rely on variable human grip strength. With the guarenteed input force from the linear actuator, this version will reliably crack macademia nuts for any user. 

