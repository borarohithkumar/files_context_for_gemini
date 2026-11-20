# DSA Journey & Builder's Log — Publication Ledger

**Updated:** 19 November 2026. User confirms DSA Journey #1–#24 published; Builder's Log #1 published. DSA #25 LC695 is ready as a draft, not yet confirmed live.

## DSA Journey — publication ledger

| # | Topic | Pattern / angle | Status |
|---:|---|---|---|
| 1 | LC146 — LRU Cache | Hash map + doubly linked list | **Published** |
| 2 | LC56 — Merge Intervals | Sorting + interval merging | **Published** |
| 3 | Maximum Subjects Passed — custom question | Greedy + sorting + budget allocation | **Published** |
| 4 | LC435 — Non-overlapping Intervals | Greedy interval scheduling | **Published** |
| 5 | LC57 — Insert Interval | Interval insertion / merge | **Published** |
| 6 | LC452 — Minimum Number of Arrows to Burst Balloons | Greedy interval coverage | **Published** |
| 7 | LC26 — Remove Duplicates from Sorted Array | In-place two pointers | **Published** |
| 8 | LC88 — Merge Sorted Array | Backward three-pointer merge | **Published** |
| 9 | LC53 — Maximum Subarray | Kadane’s algorithm | **Published** |
| 10 | LC121 — Best Time to Buy and Sell Stock | One-pass running minimum | **Published** |
| 11 | LC1299 — Replace Elements with Greatest Element on Right Side | Right-to-left running maximum | **Published** |
| 12 | LC238 — Product of Array Except Self | Prefix / suffix products | **Published** |
| 13 | LC242 — Valid Anagram | Character frequency | **Published** |
| 14 | LC49 — Group Anagrams | Hashing / canonical key | **Published** |
| 15 | LC560 — Subarray Sum Equals K | Prefix sum + frequency map | **Published** |
| 16 | LC35 — Search Insert Position | Binary search / lower bound | **Published** |
| 17 | LC33 — Search in Rotated Sorted Array | Modified binary search | **Published** |
| 18 | LC153 — Find Minimum in Rotated Sorted Array | Modified binary search | **Published** |
| 19 | LC875 — Koko Eating Bananas | Binary search on answer | **Published** |
| 20 | LC2187 + ICSL/HirePro desk-processing exercise | Binary search on feasible time; heap alternative in custom exercise | **Published** |
| 21 | LC74 — Search a 2D Matrix | Binary search on virtual flattened indices | **Published** |
| 22 | LC1648 + Infosys Food Stamps sample | Min-heap + binary search on diminishing-value threshold | **Published** |
| 23 | LC4 — Median of Two Sorted Arrays | Partial two-pointer merge + binary-search partition | **Published** |
| 24 | LC200 — Number of Islands | Recursive four-direction grid DFS; in-place marking | **Published** |
| 25 | LC695 — Max Area of Island | Iterative BFS with deque; in-place marking and area aggregation | **Draft ready** |

## DSA Journey #25 — LC695 LinkedIn draft

**𝐃𝐒𝐀 𝐉𝐨𝐮𝐫𝐧𝐞𝐲 #𝟐𝟓 — 𝐌𝐚𝐱 𝐀𝐫𝐞𝐚 𝐨𝐟 𝐈𝐬𝐥𝐚𝐧𝐝 (𝐋𝐞𝐞𝐭𝐂𝐨𝐝𝐞 𝟔𝟗𝟓)**

Continuing with grid traversal, today’s problem builds on the connected-component idea from Number of Islands — but this time, instead of counting islands, the goal is to find the area of the largest one.

**𝐌𝐲 𝐚𝐩𝐩𝐫𝐨𝐚𝐜𝐡: 𝐁𝐫𝐞𝐚𝐝𝐭𝐡-𝐅𝐢𝐫𝐬𝐭 𝐒𝐞𝐚𝐫𝐜𝐡 (𝐁𝐅𝐒)**

🔹 Traverse the grid using nested loops and look for an unvisited land cell (`1`).
🔹 Whenever land is found, mark it as water (`0`) immediately, initialize its island area to `1`, and add its coordinates to a queue.
🔹 Use a `deque` to process cells in FIFO order and explore their four neighbouring directions — up, down, left and right.
🔹 Mark each discovered land cell as visited when adding it to the queue, and increase the current island’s area.
🔹 Once the queue is empty, update the maximum area and continue scanning the grid.

**𝐓𝐡𝐞 𝐤𝐞𝐲 𝐨𝐛𝐬𝐞𝐫𝐯𝐚𝐭𝐢𝐨𝐧:** Marking cells when they are enqueued ensures that each land cell is added to the queue only once. Each BFS traversal therefore explores one complete island without needing a separate `visited` matrix.

**𝐂𝐨𝐦𝐩𝐥𝐞𝐱𝐢𝐭𝐲 𝐀𝐧𝐚𝐥𝐲𝐬𝐢𝐬:**
- Time Complexity: O(R × C)
- Auxiliary Space Complexity: O(R × C) in the worst case for the queue

**𝐊𝐞𝐲 𝐭𝐚𝐤𝐞𝐚𝐰𝐚𝐲:** DFS and BFS are two ways to explore connected components. After using DFS to count islands, BFS lets us measure the size of each component and keep track of the largest one.

#Python #DSA #LeetCode #BFS #GraphTraversal #ProblemSolving #LearningInPublic

## Next deliberate sequence

- **DSA #25:** LC695 — Max Area of Island (draft ready; publish after you attach your code / Accepted screenshot).
- **DSA #26 candidate:** LC79 — Word Search. It is absent from the 141 tracked IDs; complete it first, then share your actual approach.
- Then refresh historical graph problems LC133 and LC417 before moving to the next category block.

## Original assessment exercises — separate queue

- Already published: #3 Maximum Subjects Passed (`Python/maxsubspass.py`), #20 ICSL/HirePro (`Python/icsl_1.py`), #22 Infosys Food Stamps (`Python/infosys_easy.py`). These custom problems are distinct from their LeetCode pattern companions.
- Candidate: `Python/infosys_medium.py` and `Python/infosys_hard.py`; obtain original prompts and constraints before assigning post numbers or writing detailed descriptions.
- Candidate: `Python/tcs1.py`, `tcs2.py`, `tcs11.py`, `tcs12.py`; inspect question-by-question.

## Builder’s Log — separate numbering

| # | Topic | Status |
|---:|---|---|
| 1 | TerMind — Bringing Natural Language to the Linux Terminal | **Published** |
| 2 | Linux journey: Windows → Fedora → Arch + Hyprland | Planned |
| 3 | ArcHypr-w-Configs | Planned |
| 4 | Termux as a portable development workspace | Planned |
| 5 | Collaborative Editor | Planned |
| 6 | NoteShare | Planned |
| 7 | TerMind cloud / DevOps follow-up | Planned |
| 8 | Cloud / DevOps learning log | Ongoing / planned |

## Publication rules

- #1–#24 are Published because the user confirmed them. #25 is not marked Published until the user says it is live.
- Exact dates and LinkedIn URLs remain blank unless supplied.
- LeetCode completion, Accepted status, caption readiness and LinkedIn publication are separate facts.
- Builder’s Log numbering is independent from DSA Journey numbering.
