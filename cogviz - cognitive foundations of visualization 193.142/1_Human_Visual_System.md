# Human Visual System

## Human Visual System and Information Visualization (InfoViz)

Information Visualization (InfoViz) is the process of transforming data into visual representations that humans can interpret. A deep understanding of how humans perceive visual information is essential to design effective visualizations, as it directly influences how users extract meaning and insights from the data.

> 📌 **Key Point**: Visualizations must be aligned with the capabilities and limitations of the human visual system to be effective.

![Human Visual System Overview](/cogviz%20-%20cognitive%20foundations%20of%20visualization%20193.142/imgs/1_Human_Visual_System/1_HVS.png)

---

## How Can We Know if a Visualization is Better?

The **effectiveness** of a visualization is not a matter of personal taste.

- Is it about subjective preference? → **No**
- Why? → Because **effectiveness** depends on **how the human brain processes visual information**, which is an **objective** process.

---

## What is the Role of a Visualization Designer?

The work of a visualization designer typically follows a cycle:

1. **Ideation** → coming up with visualization concepts  
2. **Visualization** → creating the visual representation  
3. **Evaluation** → testing and iterating to improve

> 🔁 The first version of a visualization is rarely the best — **iteration** is essential.

This iterative process introduces the concept of a **solution space** — a set of possible designs. To navigate this space, one must clearly understand:

- The **tasks** the user aims to accomplish  
- The **effectiveness** of different designs for those tasks

---

## What are Task and Effectiveness?

- **Task**: A specific goal or action that a user needs to perform using a visualization (e.g., compare values, find trends, identify outliers).
- **Effectiveness**: How well a human can successfully accomplish a given task using a visualization.

> ⚠️ A visualization is not "better" in general — it is better **for a specific task**.  
> Without a clearly defined task, effectiveness **cannot be measured**.

If someone asks:  
**“Which visualization is better?”**  
Your answer should be:  
**“Better for what task?”**

---

## Applied Perception in Visualization

This involves using insights from **human perception and cognitive science** to inform the design of visualizations. The goal is to create visualizations that:

- Are **backed by scientific knowledge**
- Are **tailored for specific tasks**
- **Leverage perceptual strengths** (e.g., color, shape, spatial position)

> Example: Choosing map colors using scientifically informed palettes  
🔗 [ColorBrewer](https://colorbrewer2.org/#type=sequential&scheme=BuGn&n=3)

---

## How Does the Human Visual Processing System Work?

Visual processing is a **complex system** that enables humans to perceive and interpret the world. It involves:

1. **Capturing light**
2. **Processing visual features**
3. **Constructing internal representations** using the brain

---

### 1) The Eye and Light Capture

![Eye Anatomy](/cogviz%20-%20cognitive%20foundations%20of%20visualization%20193.142/imgs/1_Human_Visual_System/2_Eye_Anatomy.png)

- **Cornea**: Transparent outer lens that begins focusing incoming light  
- **Pupil**: Dynamic opening that adjusts its size to regulate light intake  
- **Lens**: Further refines the light focus toward the back of the eye  
- **Retina**: Light-sensitive layer where **photoreceptors** detect information:
  - **Rods**: Sensitive to low light; enable night vision  
  - **Cones**: Active in bright light; enable color and detail vision

The **fovea**, a small central region of the retina (about the size of a thumbnail at arm’s length), has **extremely high resolution** — around 1/10 of a pixel on a standard display.  
Outside the fovea, **resolution drops**, which explains why **peripheral vision is blurry**.

![Foveal Vision](/cogviz%20-%20cognitive%20foundations%20of%20visualization%20193.142/imgs/1_Human_Visual_System/3_Fovea_Vision_Field.png)

---

### 2) From the Eye to the Brain

![Visual Processing Stages](/cogviz%20-%20cognitive%20foundations%20of%20visualization%20193.142/imgs/1_Human_Visual_System/4_From_The_Eye_To_The_Brain.png)

Visual information is processed in **three main stages**:

#### **Stage 1: Feature Perception**
- **Fast**, **parallel**, and **mostly unconscious**
- Processes **low-level features**: orientation, color, texture, motion
- Stored briefly in **iconic memory** (very short-term visual memory)

#### **Stage 2: Pattern Recognition**
- **Slower** and **sequential**
- Influenced by **attention**
- Helps recognize **patterns** among features

> Attention acts as a filter, determining what information moves to the next stage

#### **Stage 3: Object Recognition & Working Memory**
- Objects are now identified and **recognized**
- Relevant information is passed to **working memory** for further processing
  - Working memory is limited to about **6–7 chunks** of information at a time
  - Enables **reasoning**, **decision-making**, and **interpretation**

---
