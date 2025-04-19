# Effectiveness in Visualization: Accuracy & Discriminability

**Effectiveness** in visualization refers to how well a visual channel conveys information — especially for **quantitative and categorical data**. Two key factors of effectiveness are **accuracy** and **discriminability**.

---

## Accuracy: How Well a Channel Represents Quantities

### What is Accuracy?
Accuracy refers to **how precisely a channel can represent quantitative information** (like magnitude or comparison). It’s grounded in **psychophysics** — the relationship between **physical stimuli** and **human perception**.

> Our perception often follows a **power law**:  
> Perceived intensity ∝ (Physical intensity)^k

### Channel Accuracy Hierarchy
Experiments by **Cleveland & McGill** show that some channels are more effective than others at conveying magnitude:

| Rank | Visual Channel | Notes |
|------|----------------|-------|
| 1️⃣   | **Position**       | Most accurate |
| 2️⃣   | **Length**         | Still very good |
| 3️⃣   | **Angle**          | Less accurate |
| 4️⃣   | **Area**           | Often over- or under-estimated |
| 5️⃣   | **Color Intensity**| Least accurate for quantities |

> **Design Tip**: Use high-ranking channels when accurate comparisons matter.

---

## Psychophysical Biases in Perception

- **Brightness** → Often **underestimated**
- **Length** → Often **overestimated**

> These biases affect how visualizations are perceived and interpreted.

---

## Chart Examples: Accuracy in Practice

- **Bar charts with aligned bars** → Easy comparison (high accuracy)
- **Pie charts (angle/area)** → Poor comparison
- **Stacked bar charts** → Harder to track change over time
- **Line charts (position + angle)** → Best for time-series comparisons

---

## Trade-offs in Design

Sometimes, high-accuracy channels (like position) can’t be used due to **space or scalability** constraints.

> **Example**:  
Heatmaps use **color intensity**, which is **low in accuracy**, but good for displaying **large datasets compactly**.

---

## Discriminability: How Many Values Can Be Distinguished?

### What is Discriminability?
Discriminability refers to **how many distinct values a viewer can perceive** from a channel (e.g., colors, shapes, sizes).

### Influencing Factors:

1. **Channel Properties**  
   (Follows similar ranking as accuracy)
2. **Spatial Arrangement**  
   (Well-aligned elements are easier to compare)
3. **Size of Marks**  
   (Tiny marks reduce visual clarity)
4. **Cardinality**  
   (Too many categories overwhelm the viewer)

> Don’t overestimate how many values users can perceive — especially with **color** and **shape**.

---

## Examples: When Discriminability Breaks Down

- Tree maps or scatter plots with **many colors/shapes** quickly become **hard to read**
- Categories with **5–7 values** are often the **maximum** that viewers can reasonably distinguish

---

## Solutions for High Cardinality

1. **Grouping** – Combine similar categories  
2. **Filtering** – Show only the most relevant categories  
3. **Faceting** – Use **position** to split data into small multiple views

> **Faceting** allows scalable comparison using high-accuracy channels like position.

---

## Takeaways: Guidelines for Effective Visual Encoding

| Property          | Key Principle                                                 |
|------------------|---------------------------------------------------------------|
| **Accuracy**      | Prioritize **position**, **length** for quantitative data     |
| **Discriminability** | Limit values per channel (5–7), avoid clutter                |
| **Salience**      | Use strong visual features to **attract attention**           |
| **Separability**  | Avoid overlapping channels that interfere (e.g., color + size)|
| **Grouping**      | Use channels that support **grouping and categorization**     |

> **Bottom Line**:  
Effectiveness depends on **task**, **channel choice**, and **how many values can be perceived**.

---
