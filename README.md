# Distribution Counting Sort — Algorithm Project

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/jonkolp/DistributionCountingSort-Algo-Project-/blob/main/DistributionCountingSort.ipynb)
[![Python](https://img.shields.io/badge/Python-3.x-blue.svg)](https://www.python.org/)
[![YouTube Demo](https://img.shields.io/badge/YouTube-Video_Walkthrough-red?logo=youtube)](https://youtu.be/ppD1Fg3g3nM)
[![Algorithm](https://img.shields.io/badge/Algorithm-Distribution_Counting_Sort-orange.svg)](#algorithm-overview)
[![Time Complexity](https://img.shields.io/badge/Time_Complexity-Θ(n%20%2B%20k)-brightgreen.svg)](#complexity-analysis)

A comprehensive academic project presenting the **Distribution Counting Sort** algorithm, including Python implementation, full mathematical analysis, slide presentation, and an accompanying video demonstration.

---

## 📌 Project Overview

> **Core Research Question:** *Are there any sorting algorithms that achieve a time complexity superior to the comparison-based lower bound of $\Omega(n \log n)$?*

**Distribution Counting Sort** answers this with **yes**, leveraging the **Space-and-Time Trade-Off** (Input Enhancement) strategy. By trading extra memory to record value frequencies and their cumulative distributions, it sorts integers within a known range $[l, u]$ in **linear time** $\Theta(n + k)$, completely bypassing the comparison barrier.

### Key Characteristics

- **Non-Comparison Sorting:** Does not rely on pairwise element comparisons ($A[i] < A[j]$).
- **Linear Time Complexity:** Runs in $\Theta(n + k)$ time where $n$ is the input size and $k = u - l + 1$ is the range of values.
- **Stable Sorting:** Preserves the relative order of duplicate elements by traversing the input array from right to left during placement.
- **Out-of-Place:** Requires auxiliary storage for the frequency/distribution array $D$ and the final sorted array $S$.

---

## 🎥 Video Presentation

A complete video presentation explaining the theoretical foundations, step-by-step array transformations, code walkthrough, and complexity derivation is available on YouTube:

[![Watch the Video Presentation](https://img.youtube.com/vi/ppD1Fg3g3nM/maxresdefault.jpg)](https://youtu.be/ppD1Fg3g3nM)

▶ **[Watch the full walkthrough on YouTube](https://youtu.be/ppD1Fg3g3nM)** *(Presented by Youssef Ahmed Hany Abdelrehim)*

---

## 📂 Repository Contents

```text
├── DistributionCountingSort.ipynb   # Interactive Jupyter Notebook (Google Colab ready)
├── Distribution Counting Sort.pptx  # 44-slide detailed presentation & step-by-step trace
├── Algo Project (1).pdf             # Illustrated architectural & trace diagrams
└── README.md                        # Documentation & project guide
