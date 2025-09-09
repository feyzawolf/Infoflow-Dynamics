# InfoFlow Dynamics: Modeling Information Spread in Universities

This repository contains the **NetLogo simulation** and report for the project:  
**"InfoFlow Dynamics: Analyzing Factors Shaping University Information Spread"**.  

An **agent-based model (ABM)** in NetLogo to explore how information spreads among university students, comparing **face-to-face interactions** with **digital networks**.  

---

## Project Overview

- **Goal**: Understand how **influence, interest, credibility, and communication channels** affect the spread of information in a university setting.  
- **Approach**:  
  - Adapted a **disease contagion model** to simulate “information contagion.”  
  - Modeled two environments:  
    - **Physical space** (face-to-face spread based on proximity).  
    - **Digital network** (online spread via connections).  
  - Ran simulations and conducted sensitivity analyses.  

---

## Tools & Methods

- **NetLogo**: Agent-based modeling environment.  
- **RStudio** + **Python**: Post-simulation analysis (line charts, sensitivity plots).  
- **Simulation details**:  
  - Student agents vary in **influence, interest, and credibility**.  
  - Information spreads via **proximity (physical)** or **network edges (digital)**.  
  - Tracked spread rate, saturation, and bias effects.  

---

## Key Results

- **Influence & credibility** were the strongest drivers of spread.  
- **Interest** mattered less but still influenced outcomes.  
- **Physical settings**: faster spread, nearly all agents informed.  
- **Digital networks**: slower spread, not all agents informed.  
- More spread → more **bias**, reducing credibility of information. 
