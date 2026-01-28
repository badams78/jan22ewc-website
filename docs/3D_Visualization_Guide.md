# How to Read the 3D Taxonomy Landscape

**Date:** January 28, 2026  
**Topic:** Guide to Interpreting the 3D Visualization of the MacroRoundup Project

---

## 1. Introduction: Two Maps, Two Purposes

The EWC Database website now features two distinct ways to visualize the "universe" of macroeconomic articles. While they may look similar at a glance—both show 70 subclusters as dots in space—they use fundamentally different mathematical logics to organize that space.

To get the most out of the site, it is crucial to understand *which map asks which question*.

*   **The 2D Map (t-SNE)** asks: *"Who are my immediate neighbors?"*
*   **The 3D Landscape (MDS)** asks: *"Where do I fit in the global order?"*

This guide focuses on the new **3D Taxonomy Landscape**, explaining how to read its three dimensions (X, Y, Z) and how to interpret the "position" of any given topic within the broader economic universe.

---

## 2. The 2D Chart: Optimized for "Neighborhoods"

Before diving into the 3D chart, we must clarify what the 2D chart does. The 2D charts on the subcluster pages use a technique called **t-SNE** (t-Distributed Stochastic Neighbor Embedding).

### How to Read It
*   **Clusters are meaningful**: If two dots are very close together, they are almost certainly related.
*   **Axes are meaningless**: The X and Y axes in the 2D chart differ from map to map. Being "high up" or "far right" has no consistent definition.
*   **Distances are distorted**: To preserve local neighborhoods, t-SNE often breaks global geography. A cluster on the far left might actually be somewhat related to a cluster on the far right, but the algorithm pushed them apart to make room for local details.

**Use the 2D chart for:** Finding specific, granular connections between similar topics (e.g., seeing that "EV Trade Wars" is right next to "Battery Supply Chains").

---

## 3. The 3D Landscape: Optimized for "Global Geography"

The new 3D visualization uses **MDS** (Multidimensional Scaling). Unlike t-SNE, this technique attempts to preserve the *global* distance relationships between all topics simultaneously.

If t-SNE is a subway map (distorted, topological, useful for stops), MDS is a topographical atlas (internally consistent, directional, true to scale).

### How to Read It
*   **Global Position Matters**: The center of the map represents the "average" content of the database. Outliers are truly idiosyncratic.
*   **Axes Have Meaning**: The directions (X, Y, Z) represent the three most dominant "signals" or "tensions" found in the dataset.
*   **Triangulation**: By seeing where a cluster sits on all three axes, you can understand its "character" (e.g., is it Domestic, Concrete, and Stable? Or Global, Abstract, and in Flux?).

---

## 4. Decoding the Three Dimensions

Our analysis of the embedding space revealed that article similarity isn't driven by simple topic tags (like "Economics" vs "Politics"). Instead, it is driven by deep underlying tensions in the discourse. We have mapped the three most powerful signals to the X, Y, and Z axes.

### X-Axis: The "Scope" Dimension (Domestic vs. Global)

This is the strongest signal in the entire database (statistically capturing the most variance). It separates "inward-looking" topics from "outward-looking" ones.

*   **Left Side (Domestic & Human)**
    *   *Key Topics:* Labor markets, Demographics, Inequality, Education, Healthcare.
    *   *The "Vibe":* These articles are about people living their lives within textual borders. They focus on wages, schools, families, and social mobility. They are often grounded in sociology and political science.
    *   *Example:* "Labor Market Outcomes by Education Level" sits deep on this side.

*   **Right Side (Global & Systemic)**
    *   *Key Topics:* International Trade, China, Supply Chains, Geopolitics, Global Finance.
    *   *The "Vibe":* These articles are about systems that cross borders. They focus on flows of capital, goods, and power between nations. They are grounded in international relations and macro-finance.
    *   *Example:* "China Trade Surplus & Export Growth" sits deep on this side.

**How to spot it:** Rotate the graph so the X-axis runs left-to-right. You will see a clear gradient from "US Workers" on one side to "Global Trade Wars" on the other.

### Y-Axis: The "Tangibility" Dimension (Concrete vs. Abstract)

This axis separates topics based on how "touchable" or theoretical the subject matter is. It often mirrors the divide between "Main Street" (the real economy) and "Wall Street" (the financial economy).

*   **Lower End (Abstract & Financial)**
    *   *Key Topics:* Monetary Policy, Inflation Rates, Bond Yields, Corporate Valuations, Derivatives.
    *   *The "Vibe":* These articles discuss invisible forces and mathematical constructs. Interest rates, P/E ratios, and inflation expectations aren't physical objects; they are theoretical levers.
    *   *Example:* "Fed Rate Cuts & Inflation Risk Concerns" is heavily weighted here.

*   **Upper End (Concrete & Physical)**
    *   *Key Topics:* Infrastructure, Energy Production, Housing, Manufacturing, Supply Chains.
    *   *The "Vibe":* These articles discuss things you can kick. Power plants, houses, shipping containers, and factories. The focus is on the physical constraints of the economy—building things, moving atoms, and digging resources.
    *   *Example:* "US Energy Production & Export Dominance" sits here.

**How to spot it:** Typically, you'll see "The Fed" and "Wall Street" clustered opposite to "Construction" and "Manufacturing."

### Z-Axis: The "Dynamism" Dimension (Stability vs. Flux)

The third dimension (often depth or height in the visualizer) captures the tension between established structures and disruptive forces. It effectively separates the "Old Economy/Government" from the "New Economy/Innovation."

*   **Stable End (Government & Policy)**
    *   *Key Topics:* Fiscal Policy, Taxation, Regulation, Social Security, Pensions.
    *   *The "Vibe":* Institutions, bureaucracy, and long-term obligations. These topics change slowly. They are about maintaining the status quo, funding the state, and managing multi-decade liabilities.
    *   *Example:* "Government Debt Sustainability" anchors this end.

*   **Flux End (Innovation & Disruption)**
    *   *Key Topics:* AI, Tech Startups, R&D, Venture Capital, Market Volatility.
    *   *The "Vibe":* Change, speed, and creative destruction. This is where the "New" happens. Articles here discuss things that didn't exist 5 years ago (LLMs, new fusion tech) or rapid market shifts.
    *   *Example:* "AI Capital Expenditure and Investment Surge" defines this pole.

**How to spot it:** Look for the "vertical" separation between boring but important budget debates (Stable) and exciting but risky tech breakthroughs (Flux).

---

## 5. Summary Table: The 3D Matrix

You can classify any node in the 3D landscape by scoring it on these three traits.

| Dimension | **Low Value (-)** | **High Value (+)** |
| :--- | :--- | :--- |
| **X (Scope)** | **Domestic / Human**<br>*(Wages, School, Family)* | **Global / Systemic**<br>*(Trade, China, Forex)* |
| **Y (Tangibility)** | **Abstract / Finanical**<br>*(Rates, Bonds, Stocks)* | **Concrete / Physical**<br>*(Energy, Housing, Factories)* |
| **Z (Dynamism)** | **Stability / Government**<br>*(Taxes, Debt, Law)* | **Flux / Innovation**<br>*(AI, Tech, Disruption)* |

### Examples of "Triangulating" a Cluster

**1. "Semiconductor Supply Chain"**
*   **X (Global):** HIGH. It's about global trade and China.
*   **Y (Concrete):** HIGH. It's about physical chips and factories.
*   **Z (Flux):** HIGH. It's a cutting-edge, fast-moving tech sector.
*   *Result:* Found in the top-right-front corner (Global/Physical/Flux).

**2. "Minimum Wage Policy"**
*   **X (Domestic):** LOW (Domestic). It's about local US workers.
*   **Y (Concrete):** LOW/MID. It's a policy setting, but affects real people.
*   **Z (Stability):** LOW (Stable). It's a slow-moving legislative topic.
*   *Result:* Found in the bottom-left-back corner (Domestic/Policy/Stable).

**3. "US Treasury Markets"**
*   **X (Global):** MID. US debt is domestic but globally owned.
*   **Y (Abstract):** LOW (Abstract). Pure financial instrument.
*   **Z (Stability):** LOW (Stable). The foundation of the financial system (usually).
*   *Result:* Found near the "floor" of the chart, somewhat central.

---

## 6. Technical Note on Axes Accuracy

It is important to note that the 3D visualizer uses **Multidimensional Scaling (MDS)** to generate this map. MDS is a statistical technique that takes the "distances" between every pair of clusters (how similar they are) and tries to build a 3D shape that best respects those distances.

While the axes described above (Domestic/Global, Abstract/Concrete, Stability/Flux) are the *dominant* mathematical patterns found in the data (via Principal Component Analysis), the MDS algorithm has freedom to "rotate" the map to find the best fit.

Therefore, when you view the chart:
*   The **X-axis** is almost perfectly aligned with the Domestic/Global split.
*   The **Y and Z axes** may be slightly rotated relative to human intuition.
*   **Trust the Neighbors**: Even if an axis label seems slightly off for a specific point, the *relative* position is true. If Cluster A is "above" Cluster B, it is genuinely more "Flux-oriented" or "Concrete" than Cluster B within the context of the dataset.

## 7. Interaction Tips

*   **Rotate (Left Click + Drag):** Essential for understanding depth. A cluster might look "close" to another in 2D, but rotating reveals they are far apart on the Z-axis.
*   **Zoom (Scroll Wheel):** Dive into the dense center "nebula" of the chart where broad macroeconomic topics (GDP, Inflation) often converge.
*   **Hover:** Returns the specific Cluster Name and its Primary Category.
*   **Click:** Navigate directly to the detailed analysis page for any cluster.

## 3D Representation: Click to Navigate

A major new feature in this release is the ability to seamlessly move from the global 3D view to granular analysis.

*   **How it works**: When you see an interesting cluster in the 3D void (e.g., an outlier on the Flux axis), simply click the dot.
*   **Result**: You will be instantly transported to that specific subcluster's detail page, where you can read the articles, see the edge cases, and view the local 2D neighborhood.
*   **Navigation**: Use the "Back to 3D View" link (or browser back button) to return to your exact position in the landscape.

---

*This guide accompanies the January 2026 update to the EWC Database Visualization Suite.*
