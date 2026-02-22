### Procedure

#### Getting Started

1. **Choose a Learning Mode**
   - **Visualization Mode**: Watch the algorithm animate step-by-step on a graph
   - **Code Walkthrough Mode**: Follow the algorithm with synchronized code highlighting

---

#### Using the Simulation

**Step 1: Configure the Graph**
- Set the number of **vertices** (3–7) using the input field
- Set the **source vertex** (starting node for shortest paths)
- Click **Random Graph** to generate a new graph, or
- Click **Build Manually** to create your own custom graph

**Step 2: Run the Algorithm**
- Click **Play** to watch the Bellman-Ford algorithm run automatically
- Use **Next Step** / **Prev Step** to navigate one step at a time
- Adjust the **Speed** dropdown to control animation pace
- Click **Reset** to restart the simulation

**Step 3: Observe and Learn**
- Watch the **Distance Table** update as edges are relaxed
- Notice the **active edge** (highlighted in orange) being processed
- Track the **predecessor (Prev)** column to trace shortest paths
- Monitor the **Relaxation Count** and **Complexity** in the Analysis section

---

#### Building a Custom Graph

1. Click **Build Manually** to open the graph editor
2. Click on a node to **select** it (turns yellow)
3. Click on another node to **create an edge**
4. Enter the edge **weight** (can be negative) and click **Add**
5. Repeat to add more edges
6. Click **Apply** to use your custom graph

---

#### Understanding the Visualization

| Visual Cue | Meaning |
|------------|---------|
| **Green node** | Source vertex |
| **Orange edge** | Currently being processed |
| **Purple node** | Distance just updated |
| **Dashed edge** | Negative weight edge |
| **∞** | Node not yet reachable |

---

#### Tips

- Start with a small graph (3–4 vertices) to understand the basics
- Try adding a **negative weight edge** to see how the algorithm handles it
- Use **Step-by-Step** mode for detailed understanding
- In Code Walkthrough mode, watch which line of code highlights as each step executes