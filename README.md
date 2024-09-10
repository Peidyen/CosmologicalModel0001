# Simplified Cosmological Model

This project simulates the expansion of the universe over time using a simplified cosmological model. The simulation calculates the **scale factor** of the universe (`a(t)`), which represents the relative size of the universe at different points in time.

## Cosmological Model Overview

In this model, we use a basic equation that describes how the universe expands over time based on the **Hubble constant** (`H0`).

### Key Concepts:

- **Hubble Constant (`H0`)**: A measure of how fast the universe is expanding, with a value of **67.4 km/s/Mpc**. This value is commonly accepted based on current cosmological observations.

- **Scale Factor (`a(t)`)**: The scale factor describes the relative size of the universe at any given time `t`. At the present day, the scale factor is defined to be `a(0) = 1`. In the past, the universe was smaller (`a(t) < 1`), and in the future, it will be larger (`a(t) > 1`).

- **Time Step**: We simulate the universe’s expansion over a series of time steps. In this model, each time step represents **1 billion years** (`1e9` years).

- **Total Time**: The simulation runs for a total of **14 billion years**, which is approximately the age of the universe.

## The Equation

The expansion of the universe is modeled using the following equation for the **scale factor**:

\[
a(t) = \exp\left(\frac{H_0 \cdot t}{1e9}\right)
\]

Where:
- \( a(t) \) is the scale factor at time \( t \),
- \( H_0 \) is the Hubble constant (67.4 km/s/Mpc),
- \( t \) is the time in years,
- \( 1e9 \) is a conversion factor to express time in billions of years.

### Explanation:

- At **t = 0** (the present time), the scale factor is `a(0) = 1`, meaning the universe is at its current size.
- As **t** increases, the scale factor grows exponentially, representing the ongoing expansion of the universe.

## Simulation

The simulation calculates the scale factor at each time step (1 billion years) for a total of 14 billion years.

### Example Output:

Here’s an example of the output, showing how the scale factor changes over time:

| Time (Billion Years) | Scale Factor |
|----------------------|--------------|
| 0.00                 | 1.0000       |
| 1.00                 | 1.0715       |
| 2.00                 | 1.1489       |
| 3.00                 | 1.2327       |
| 4.00                 | 1.3235       |
| ...                  | ...          |
| 14.00                | 2.1055       |

### Plot of the Simulation:

The plot below shows how the scale factor grows over time:

![Cosmological Expansion Plot](path/to/your/plot.png)
