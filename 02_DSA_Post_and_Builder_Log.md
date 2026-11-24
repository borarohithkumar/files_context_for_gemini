# DSA Journey & Builder's Log — Publication Ledger

**Reconciled:** 24 November 2026. User confirms DSA #1–#26 Published and Builder's Log #1 Published. LC133 and LC417 implementations were supplied; under the user's rule, supplied implementations are Accepted.

## Publication ledger

| # | Problem/topic | Pattern | Acceptance / review status | LinkedIn status |
|---:|---|---|---|---|
| 1 | LC146 LRU Cache | Hash map + doubly linked list | Historical solution | Published |
| 2 | LC56 Merge Intervals | Sorting + interval merge | Historical solution | Published |
| 3 | Maximum Subjects Passed — custom question | Greedy + sorting + budget | Custom exercise featured | Published |
| 4 | LC435 Non-overlapping Intervals | Greedy interval scheduling | Historical solution | Published |
| 5 | LC57 Insert Interval | Interval insertion / merge | Historical solution | Published |
| 6 | LC452 Minimum Number of Arrows to Burst Balloons | Greedy interval coverage | Historical solution | Published |
| 7 | LC26 Remove Duplicates from Sorted Array | Slow/fast two pointers | Historical solution | Published |
| 8 | LC88 Merge Sorted Array | Backward two pointers | Historical solution | Published |
| 9 | LC53 Maximum Subarray | Kadane | Historical solution | Published |
| 10 | LC121 Best Time to Buy and Sell Stock | Running minimum | Historical solution | Published |
| 11 | LC1299 Replace Elements with Greatest Element on Right Side | Suffix maximum | Historical solution | Published |
| 12 | LC238 Product of Array Except Self | Prefix / suffix products | Historical solution | Published |
| 13 | LC242 Valid Anagram | Frequency count | Historical solution | Published |
| 14 | LC49 Group Anagrams | Hashing / canonical grouping | Historical solution | Published |
| 15 | LC560 Subarray Sum Equals K | Prefix sum + frequency map | Historical solution | Published |
| 16 | LC35 Search Insert Position | Lower-bound binary search | Historical solution | Published |
| 17 | LC33 Search in Rotated Sorted Array | Modified binary search | Historical solution | Published |
| 18 | LC153 Find Minimum in Rotated Sorted Array | Modified binary search | Historical solution | Published |
| 19 | LC875 Koko Eating Bananas | Binary search on answer | Historical solution | Published |
| 20 | LC2187 + ICSL/HirePro original exercise | Binary search on feasible time; heap alternative in original | Custom + LeetCode companion | Published |
| 21 | LC74 Search a 2D Matrix | Flattened binary search | Historical solution | Published |
| 22 | LC1648 + Infosys Food Stamps sample | Heap + threshold binary search | Custom + LeetCode companion | Published |
| 23 | LC4 Median of Two Sorted Arrays | Partial merge scan + binary-search partition | Historical solution | Published |
| 24 | LC200 Number of Islands | Grid DFS / connected components | Historical solution | Published |
| 25 | LC695 Max Area of Island | Grid BFS / component area | Historical solution | Published |
| 26 | LC79 Word Search | Grid DFS + path-specific backtracking | Accepted under submitted-implementation rule | Published |
| 27 | LC133 Clone Graph | Graph DFS + original-to-clone hashmap | Accepted; approach reviewed; caption ready | **Not confirmed published** |
| 28 candidate | LC417 Pacific Atlantic Water Flow | Reverse multi-source reachability | Accepted; approach reviewed; caption not yet drafted | Not published / not confirmed |

## LC133 — DSA #27 review record

- User supplied recursive DFS clone implementation.
- Correctly returns `None` for empty input.
- Maintains an original-node → cloned-node map.
- Creates and memoizes a clone before recursively cloning neighbours, preventing cycle recursion and duplicate clone nodes.
- Complexity: O(V + E) time and O(V) auxiliary space.
- LinkedIn caption is ready in the prior conversation; publication remains unconfirmed.

## LC417 — next candidate review record

- User supplied recursive boundary-seeded DFS for Pacific and Atlantic oceans.
- Accepted by the user's explicit rule: they only send submitted approaches after acceptance.
- Core logic is correct: reverse search from each ocean boundary; move from current cell to neighbour only when `neighbour_height >= current_height`; intersect the two reachable sets.
- Complexity: O(R×C) time and O(R×C) space.
- Python implementation note: recursive depth may become large, so iterative stack-based DFS is safer for maximum grids.
- Caption has not been drafted; LinkedIn publication has not been confirmed.

## Original coding-question posts — separate from LeetCode

| Post | Source exercise | Path | Pattern / relationship | Status |
|---:|---|---|---|---|
| #3 | Maximum Subjects Passed | `Termux_Android/Python/maxsubspass.py` | Greedy + sorting + budget | Published |
| #20 | ICSL/HirePro desk-processing exercise | `Termux_Android/Python/icsl_1.py` | Related pattern companion LC2187; different statement | Published |
| #22 | Infosys Food Stamps | `Termux_Android/Python/infosys_easy.py` | Related pattern companion LC1648; different statement | Published |

Pending original exercises and candidate classifications are documented in `01_Master_Learning_and_Category_Tracker.md`. The user confirms the original prompts for `infosys_medium.py` and `infosys_hard.py` are available. For other files without prompts, frame/find an equivalent statement from source logic when the problem enters a batch. Basic exercises are not standalone post candidates.

## Builder's Log (separate series)

| # | Topic | Status |
|---:|---|---|
| 1 | TerMind — Bringing Natural Language to the Linux Terminal | Published |
| 2 | Windows → Fedora → Arch + Hyprland journey | Planned |
| 3 | ArcHypr-w-Configs | Planned |
| 4 | Termux as a portable development workspace | Planned |
| 5 | Collaborative Editor | Planned |
| 6 | NoteShare | Planned |
| 7 | TerMind cloud / DevOps follow-up | Planned |
| 8 | Cloud / DevOps learning log | Ongoing / planned |

## Rules to maintain

- DSA #1–#26 Published per user confirmation.
- A submitted LeetCode implementation from the user means Accepted; do not ask again.
- Accepted, approach reviewed, caption ready and LinkedIn Published are separate statuses.
- Do not mark a post Published without user confirmation.
- Pattern-batch sequencing is the default, not random problem selection.
- Do not repeat a previously published problem as a new standalone post.
- Do not assign exact dates or LinkedIn URLs unless supplied.
- Builder's Log numbering is independent of DSA Journey numbering.
- The GitHub context repo remains read/copy-only; this ledger is maintained locally.
