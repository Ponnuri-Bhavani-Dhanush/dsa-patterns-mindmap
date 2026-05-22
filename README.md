# 🧠 DSA Patterns Mind Map

> An interactive, visual reference for **26 core DSA patterns** mapped to **200+ LeetCode problems** — built to help you study smarter, not harder.

🔗 **[Live Demo →](https://ponnuri-bhavani-dhanush.github.io/dsa-patterns-mindmap)**

---

## ✨ Features

- **26 DSA patterns** grouped into 5 strategy categories
- **200+ LeetCode problems** mapped to each pattern with difficulty tags
- Click any pattern node to see its problems, definition, triggers, and common mistakes
- Zoom, pan, expand, and collapse the entire map freely
- Legends, credits, and UI stay pinned — never disappear on pan/zoom
- Fully self-contained — single HTML file, no install needed

---

## 🗺️ Pattern Coverage

### 🔵 Linear / Pointer
| Pattern | Priority | Problems |
|---|---|---|
| Two Pointers | Must-Know | 10 |
| Fast & Slow Pointers | Must-Know | 9 |
| Sliding Window (Fixed) | Must-Know | 7 |
| Sliding Window (Variable) | Must-Know | 8 |
| Linked List Reversal | Important | 7 |

### 🟢 Data Access / Query
| Pattern | Priority | Problems |
|---|---|---|
| Prefix Sum | Important | 8 |
| Binary Search | Must-Know | 10 |
| Monotonic Stack | Must-Know | 9 |
| Monotonic Queue | Important | 6 |
| Segment Tree | Important | 6 |
| Fenwick Tree (BIT) | Advanced | 5 |
| Sqrt Decomposition | Skip | 3 |

### 🟡 Problem Solving Strategy
| Pattern | Priority | Problems |
|---|---|---|
| Greedy | Important | 10 |
| Dynamic Programming | Must-Know | 13 |
| Backtracking | Must-Know | 10 |
| Meet in the Middle | Advanced | 4 |
| Bit Manipulation | Important | 10 |

### 🔴 Graph / Tree
| Pattern | Priority | Problems |
|---|---|---|
| Union-Find (DSU) | Must-Know | 8 |
| Topological Sort | Important | 8 |
| Successor Graphs | Advanced | 4 |
| Max Flow / Min Cut | Advanced | 3 |
| SCC (Kosaraju's) | Advanced | 4 |

### 🟣 String / Geometric
| Pattern | Priority | Problems |
|---|---|---|
| String Hashing | Advanced | 6 |
| Trie (Prefix Tree) | Important | 8 |
| Sweep Line | Advanced | 6 |
| Z-Algo / Suffix Array | Advanced | 4 |

---

## 🎮 How to Use

| Action | How |
|---|---|
| Expand / Collapse a group | Click any group node |
| View problems for a pattern | Click a pattern (leaf) node |
| Zoom in / out | Scroll wheel |
| Pan the map | Click and drag |
| Reset the view | Click **⊙ Reset** button |
| Expand all nodes | Click **⊞ Expand All** |
| Collapse all nodes | Click **⊟ Collapse All** |

---

## 🚀 Run Locally

No server needed. Just download and open:

```bash
git clone https://github.com/yourusername/dsa-patterns-map.git
cd dsa-patterns-map
# open index.html in any browser
```

Or simply [download the HTML file](./index.html) directly and open it in your browser.

---

## 🛠️ Built With

- [D3.js v7](https://d3js.org/) — radial tree layout and zoom/pan
- Vanilla HTML + CSS + JavaScript — zero frameworks, zero dependencies
- Single file — everything is self-contained in `index.html`

---

## 📸 Preview

> Zoom into any pattern to see its LeetCode problems, use-case triggers, and the most common mistake to avoid.

---

## 🤝 Contributing

Found a problem mapped to the wrong pattern? Want to add more problems or a new pattern?

1. Fork this repo
2. Edit `index.html` — problem data is in the `lcData` object at the top of the `<script>` tag
3. Open a Pull Request with a clear description of what you changed and why

---

## 📄 License

MIT License — free to use, share, and modify with attribution.

---

<p align="center">
  Made with 💜 by <a href="https://www.instagram.com/override.void.dhanush">@override.void.dhanush</a>
</p>
