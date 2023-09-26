# OLA_Pricing_Advertising

## About
Optimize an e-commerce strategy by controlling product pricing and advertising.

## Professors

* Matteo Castiglioni
* Nicola Gatti
* Martino Bernasconi De Luca
  
## The Team

* [Valeria Amato](https://github.com/ValeMTo)
* [Beatrice Insalata](https://github.com/SaladSlayer00)
* [Emanuele Paci](https://github.com/emanuelePaci)
* [Matteo Pancini](https://github.com/MatteoPancini)
* [Andrea Riboni](https://github.com/AndreaRiboni)

---

## Features
- **User Classes:** Users are categorized into three classes (Young & Sporty, Adult & Sporty, Young & Non Sporty).
- **Dynamic Environment:** Simulate daily user clicks, costs, and purchase conversions with Gaussian noise.
- **Optimization Algorithm:** Linear time algorithm for exhaustive search over prices and bids.

### Step 0: Environment Design
- Define a realistic e-commerce scenario.
- Set parameters for the simulator.

### Step 1: Learning for Pricing
- Focus on users in class C1.
- Apply UCB1 and TS algorithms.
- Analyze cumulative regret, reward, and instantaneous metrics.

### Step 2: Learning for Advertising
- Understand advertising curves for class C1.
- Use GP-UCB and GP-TS algorithms.
- Report on cumulative and instantaneous metrics.

### Step 3: Joint Pricing & Advertising
- Combine pricing and advertising strategies for class C1.
- Apply GP-UCB and GP-TS algorithms.
- Analyze cumulative and instantaneous results.

### Step 4: Context Generation
- Explore three user classes (C1, C2, C3).
- Apply GP-UCB and GP-TS algorithms in two scenarios: known and unknown contexts.
- Compare algorithm performances.

### Step 5: Non-Stationary Environments (Two Abrupt Changes)
- Focus on single-user class C1 with unknown pricing curves.
- Adapt to seasonal phases and abrupt changes.
- Use UCB1 and its two non-stationary flavors.
- Compare results and provide sensitivity analysis.

### Step 6: Non-Stationary Environments (Many Abrupt Changes)
- Implement the EXP3 algorithm for adversarial settings.
- Consider fixed bids and multiple phase changes.
- Compare EXP3 with UCB1 and its non-stationary versions.
