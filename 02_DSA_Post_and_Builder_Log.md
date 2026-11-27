# 02 — DSA Post & Builder's Log
**Last Updated:** November 26, 2026 | **Published Count:** `29` DSA Posts + `1` Builder's Log

---

## 1. Ready-to-Publish Draft: DSA Journey #30

```text
𝐃𝐒𝐀 𝐉𝐨𝐮𝐫𝐧𝐞𝐲 #𝟑𝟎 — 𝐂𝐨𝐧𝐭𝐚𝐢𝐧𝐞𝐫 𝐖𝐢𝐭𝐡 𝐌𝐨𝐬𝐭 𝐖𝐚𝐭𝐞𝐫 (𝐋𝐞𝐞𝐭𝐂𝐨𝐝𝐞 𝟏𝟏)

Continuing our Two Pointers series, this problem shifts from searching for a target sum to maximizing an area bounded by two vertical lines.

A brute-force approach checks every pair of lines in O(n²) time, which doesn't scale for large inputs. By placing pointers at both ends, we can eliminate suboptimal choices in a single pass.

𝐌𝐲 𝐀𝐩𝐩𝐫𝐨𝐚𝐜𝐡: 𝐂𝐎𝐍𝐕𝐄𝐑𝐆𝐈𝐍𝐆 𝐓𝐖𝐎 𝐏𝐎𝐈𝐍𝐓𝐄𝐑𝐒

🔹 𝐈𝐧𝐢𝐭𝐢𝐚𝐥𝐢𝐳𝐞 𝐩𝐨𝐢𝐧𝐭𝐞𝐫𝐬: Place one pointer at the start (left) and one at the end (right) to begin with the maximum possible width.

🔹 𝐂𝐚𝐥𝐜𝐮𝐥𝐚𝐭𝐞 𝐚𝐫𝐞𝐚: At each step, compute width × min(height[left], height[right]) and update the maximum area found so far.

🔹 𝐌𝐨𝐯𝐞 𝐭𝐡𝐞 𝐬𝐡𝐨𝐫𝐭𝐞𝐫 𝐥𝐢𝐧𝐞: Move the pointer pointing to the shorter vertical line inward.

𝐓𝐡𝐞 𝐊𝐞𝐲 𝐎𝐛𝐬𝐞𝐫𝐯𝐚𝐭𝐢𝐨𝐧: The water level is always limited by the shorter line. Moving the taller line inward can only decrease the width while the height remains capped by the shorter line—so only moving the shorter pointer gives a chance to find a taller boundary that compensates for the reduced width.

𝐂𝐨𝐦𝐩𝐥𝐞𝐱𝐢𝐭𝐲 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬:
• Time Complexity: O(n) — each element is visited at most once.
• Auxiliary Space: O(1) — only pointer and max-area variables are used.

#Python #DSA #LeetCode #TwoPointers #Greedy #ProblemSolving #Coding #LearningInPublic
```

---

## 2. Complete DSA Journey Publication Ledger (`#1` to `#30`)

| Post # | Problem / Exercise | Pattern Batch | Status |
|---:|---|---|---|
| 1 | LC 146 — LRU Cache | Design / Linked Lists | Published |
| 2 | LC 56 — Merge Intervals | Greedy / Intervals | Published |
| 3 | Termux `maxsubspass.py` — Maximum Subjects Passed | Greedy / Sorting | Published |
| 4 | LC 435 — Non-overlapping Intervals | Greedy / Intervals | Published |
| 5 | LC 452 — Minimum Number of Arrows to Burst Balloons | Greedy / Intervals | Published |
| 6 | LC 57 — Insert Interval | Greedy / Intervals | Published |
| 7 | LC 238 — Product of Array Except Self | Arrays / Prefix-Suffix | Published |
| 8 | LC 128 — Longest Consecutive Sequence | Hashing / Frequency | Published |
| 9 | LC 49 — Group Anagrams | Hashing / Frequency | Published |
| 10 | LC 347 — Top K Frequent Elements | Hashing / Heap | Published |
| 11 | LC 15 — 3Sum | Two Pointers | Published |
| 12 | Arrays, Strings & Hashing Consolidation | Arrays / Strings | Published |
| 13 | LC 3 — Longest Substring Without Repeating Characters | Sliding Window | Published |
| 14 | LC 992 — Subarrays with K Different Integers | Sliding Window | Published |
| 15 | LC 560 — Subarray Sum Equals K | Prefix Sum + HashMap | Published |
| 16 | LC 704 & LC 35 — Binary Search Foundations | Binary Search | Published |
| 17 | LC 33 — Search in Rotated Sorted Array *(Historical Refreshed)* | Binary Search | Published |
| 18 | LC 153 — Find Minimum in Rotated Sorted Array | Binary Search | Published |
| 19 | LC 875 — Koko Eating Bananas | Binary Search on Answer | Published |
| 20 | LC 2187 + Termux `icsl_1.py` | Binary Search on Answer | Published |
| 21 | LC 74 — Search a 2D Matrix | Binary Search | Published |
| 22 | LC 1648 + Termux `infosys_easy.py` | Binary Search on Answer | Published |
| 23 | LC 4 — Median of Two Sorted Arrays | Binary Search | Published |
| 24 | LC 200 — Number of Islands | Grid / Graph Traversal | Published |
| 25 | LC 695 — Max Area of Island | Grid / Graph Traversal | Published |
| 26 | LC 79 — Word Search | Grid / Graph Traversal | Published |
| 27 | LC 133 — Clone Graph | Grid / Graph Traversal | Published |
| 28 | LC 417 — Pacific Atlantic Water Flow | Grid / Graph Traversal | Published |
| 29 | LC 167 — Two Sum II *(Historical Refreshed)* | Two Pointers | Published |
| **30** | **LC 11 — Container With Most Water** | **Two Pointers** | **Accepted & Draft Ready** |

---

## 3. Builder's Log Ledger (Independent Series)
| Log # | Topic | Status |
|---:|---|---|
| 1 | TerMind-CLI Architecture & Hybrid NLP-to-Bash Design | Published |
| 2 | Linux Journey: Moving from Windows to Fedora to Arch Linux + Hyprland | Planned |
| 3 | Configuring Hyprland & Wayland Productivity (`ArcHypr-w-Configs`) | Planned |
| 4 | Building a Portable CLI Dev Environment on Android (`Termux_Android`) | Planned |
| 5 | Containerizing a Real-Time Collaborative Text Editor (`Collaborative-Editor`) | Planned |
| 6 | Full-Stack Academic Resource Sharing (`NoteShare`) | Planned |
| 7 | Productionizing TerMind API on AWS EC2 with Terraform, Nginx, Certbot & Grafana | Planned |
| 8 | Visualizing Algorithms & Intuition (`AlgoPulse`) | Planned |
