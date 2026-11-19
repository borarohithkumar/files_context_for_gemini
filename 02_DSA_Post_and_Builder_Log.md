# DSA Journey & Builder’s Log — Publication Ledger

**Reconciled:** 18 November 2026. The user explicitly confirms that DSA Journey **#1–#22 are all published** and Builder’s Log **#1 is published**. Exact dates/URLs remain blank unless supplied.

## DSA Journey #1–#22 — published

| # | Post topic | Pattern | LinkedIn status | Evidence / notes |
|---:|---|---|---|---|
| 1 | LC146 — LRU Cache | HashMap + doubly linked list | **Published** | Historical post log; exact date/URL not retained |
| 2 | LC56 — Merge Intervals | Sorting + intervals | **Published** | Historical post log; exact date/URL not retained |
| 3 | Maximum Subjects Passed — custom question | Greedy + sorting + budget allocation | **Published** | Custom repository exercise; connection to LC1833 is pattern-only |
| 4 | LC435 — Non-overlapping Intervals | Greedy interval scheduling | **Published** | Historical post log; exact date/URL not retained |
| 5 | LC57 — Insert Interval | Interval insertion/merge | **Published** | Historical post log; exact date/URL not retained |
| 6 | LC452 — Minimum Number of Arrows to Burst Balloons | Greedy interval coverage | **Published** | Historical post log; exact date/URL not retained |
| 7 | LC26 — Remove Duplicates from Sorted Array | In-place two pointers | **Published** | Historical post log; exact date/URL not retained |
| 8 | LC88 — Merge Sorted Array | Backward three-pointer merge | **Published** | Historical post log |
| 9 | LC53 — Maximum Subarray | Kadane’s algorithm | **Published** | Historical post log |
| 10 | LC121 — Best Time to Buy and Sell Stock | One-pass running minimum | **Published** | Historical post log; exact date/URL not retained |
| 11 | LC1299 — Replace Elements with Greatest Element on Right Side | Right-to-left running maximum | **Published** | Historical post log; exact date/URL not retained |
| 12 | LC238 — Product of Array Except Self | Prefix/suffix products | **Published** | Historical post log; exact date/URL not retained |
| 13 | LC242 — Valid Anagram | Character frequency | **Published** | Historical post log; exact date/URL not retained |
| 14 | LC49 — Group Anagrams | Hashing / canonical key | **Published** | Historical post log; exact date/URL not retained |
| 15 | LC560 — Subarray Sum Equals K | Prefix sum + frequency map | **Published** | User-confirmed 8 Nov 2026; URL not supplied |
| 16 | LC35 — Search Insert Position | Binary search / lower bound | **Published** | User now confirms all posts through #22 are live; date/URL not supplied |
| 17 | LC33 — Search in Rotated Sorted Array | Modified binary search | **Published** | User now confirms all posts through #22 are live; LC33 is in historical profile bucket but was revisited in this campaign |
| 18 | LC153 — Find Minimum in Rotated Sorted Array | Modified binary search | **Published** | User now confirms all posts through #22 are live; date/URL not supplied |
| 19 | LC875 — Koko Eating Bananas | Binary search on answer | **Published** | User now confirms all posts through #22 are live; date/URL not supplied |
| 20 | LC2187 + ICSL/HirePro desk-processing exercise | Binary search on feasible time; heap alternative in custom exercise | **Published** | User-confirmed live 18 Nov 2026; custom exercise is Python/icsl_1.py; separate statements |
| 21 | LC74 — Search a 2D Matrix | Binary search on virtual flattened indices | **Published** | User now confirms all posts through #22 are live; date/URL not supplied |
| 22 | LC1648 + Infosys Food Stamps sample | Min-heap + binary search on diminishing-value threshold | **Published** | User now confirms all posts through #22 are live; custom exercise is Python/infosys_easy.py; related, not identical |

## DSA Journey #23 — LC4 draft ready

User supplied two implementations for LC4 — Median of Two Sorted Arrays:
- Merge simulation: advances two pointers for the first floor((m+n)/2)+1 elements; O(m+n) time, O(1) auxiliary space.
- Binary-search partition: searches the partition in the shorter array and checks cross-boundary ordering; O(log(min(m,n))) time, O(1) auxiliary space.
- Accepted/submission status was not explicitly stated.
- LinkedIn status: draft ready, not yet confirmed posted.

## Next deliberate DSA post sequence

| Proposed # | Topic | Category purpose | Status |
|---:|---|---|---|
| **#23** | **LC4 — Median of Two Sorted Arrays** | Finish/capstone the Binary Search block (partition-based binary search) | Draft ready; user supplied merge + partition approaches |
| #24 | LC200 — Number of Islands | Start the Grid / Graph DFS block; this is in the current-known 69 list | Candidate; user approach needed |
| #25 | LC79 — Word Search | Grid DFS + path-specific backtracking; first-time completion after LC200 | Candidate only; complete first, then draft |

**Why LC79 is not #23:** the binary-search series has been the active post block through #22. LC4 is still in the current-known list and is a natural capstone. Only after #23 do we intentionally transition into grid/DFS work. LC200 is already completed according to the supplied 69-list, while LC79 is not among the 140 solved IDs.

## DSA post candidates after the Grid / DFS block

- `Python/infosys_medium.py` — original Infosys coding exercise; code appears to maximise a contiguous subarray sum by up to `k` swaps with outside values using heaps. The original full prompt/constraints are not retained. Candidate post only after user re-confirms the statement and the algorithm is tested.
- `Python/infosys_hard.py` — original Infosys practice exercise; current code finds the smallest absolute difference among distinct values sharing parity by sorting unique even and odd groups. The original prompt is not retained. Candidate post only after prompt/constraints are confirmed.
- `Python/tcs1.py`, `tcs2.py`, `tcs11.py`, `tcs12.py` — TCS practice sets; inspect and inventory problem-by-problem before assigning post numbers.
- The custom problems already featured are #3 Maximum Subjects Passed, #20 ICSL/HirePro, and #22 Infosys Food Stamps. Do not map an original question to a LeetCode ID unless the statement and constraints really match.

## Builder’s Log — separate numbering

| Builder’s Log # | Topic | Status |
|---:|---|---|
| **#1** | **TerMind — Bringing Natural Language to the Linux Terminal** | **Published** — user confirmed |
| #2 | Linux journey: Windows → Fedora → Arch + Hyprland | Planned |
| #3 | ArcHypr-w-Configs | Planned |
| #4 | Termux as a portable development workspace | Planned |
| #5 | Collaborative Editor | Planned |
| #6 | NoteShare | Planned |
| #7 | TerMind cloud / DevOps follow-up | Planned |
| #8 | Cloud / DevOps learning log | Ongoing / planned |

## Publication rules

- #1–#22 DSA are Published based on the user’s latest explicit confirmation. Do not downgrade #16–#19 or #21–#22 to draft status.
- Do not invent exact dates or LinkedIn URLs. Keep unknown fields blank until supplied.
- Builder’s Log numbering is independent from DSA Journey numbering.
- LeetCode completion, local repository code, Accepted screenshot, caption readiness, and LinkedIn publication are separate facts.

---

# DSA Journey #23 — LC4 LinkedIn draft

**𝐃𝐒𝐀 𝐉𝐨𝐮𝐫𝐧𝐞𝐲 #𝟐𝟑 — 𝐌𝐞𝐝𝐢𝐚𝐧 𝐨𝐟 𝐓𝐰𝐨 𝐒𝐨𝐫𝐭𝐞𝐝 𝐀𝐫𝐫𝐚𝐲𝐬 (𝐋𝐞𝐞𝐭𝐂𝐨𝐝𝐞 𝟒)**

Finding the median of two sorted arrays is a great reminder that there can be more than one way to solve a problem — and that choosing the right approach can make a huge difference in efficiency.

I explored **two approaches** for this problem.

**𝐀𝐩𝐩𝐫𝐨𝐚𝐜𝐡 𝟏: 𝐓𝐰𝐨-𝐏𝐨𝐢𝐧𝐭 𝐌𝐞𝐫𝐠𝐞**

🔹 Use two pointers to traverse the sorted arrays in order.
🔹 Process only the first `((m + n) // 2) + 1` elements needed to identify the middle value(s).
🔹 Keep track of the previous and current elements to calculate the median without building a merged array.

**Time Complexity:** O(m + n) in the worst case  
**Auxiliary Space:** O(1)

**𝐀𝐩𝐩𝐫𝐨𝐚𝐜𝐡 𝟐: 𝐁𝐢𝐧𝐚𝐫𝐲 𝐒𝐞𝐚𝐫𝐜𝐡 𝐨𝐧 𝐏𝐚𝐫𝐭𝐢𝐭𝐢𝐨𝐧𝐬**

🔹 Always perform binary search on the smaller array.
🔹 Choose partition positions in both arrays so the left side contains half of the combined elements.
🔹 Check whether the elements on the left partitions are no greater than the elements on the right partitions.
🔹 Once the correct partition is found, calculate the median using only the boundary values.

**Time Complexity:** O(log(min(m, n)))  
**Auxiliary Space:** O(1)

**𝐓𝐡𝐞 𝐤𝐞𝐲 𝐨𝐛𝐬𝐞𝐫𝐯𝐚𝐭𝐢𝐨𝐧:** We don't need to merge the arrays. By finding the correct partition, we can identify the middle element(s) using binary search on the smaller array.

**𝐊𝐞𝐲 𝐭𝐚𝐤𝐞𝐚𝐰𝐚𝐲:** Start with a straightforward solution, understand its cost, and then look for a way to reduce the search space. The optimized approach here turns a linear traversal into logarithmic time.

#Python #DSA #LeetCode #BinarySearch #Arrays #ProblemSolving #LearningInPublic


# DSA Journey #23 — LC4 LinkedIn draft

**𝐃𝐒𝐀 𝐉𝐨𝐮𝐫𝐧𝐞𝐲 #𝟐𝟑 — 𝐌𝐞𝐝𝐢𝐚𝐧 𝐨𝐟 𝐓𝐰𝐨 𝐒𝐨𝐫𝐭𝐞𝐝 𝐀𝐫𝐫𝐚𝐲𝐬 (𝐋𝐞𝐞𝐭𝐂𝐨𝐝𝐞 𝟒)**

Finding the median of two sorted arrays is a great reminder that there can be more than one way to solve a problem — and that choosing the right approach can make a huge difference in efficiency.

I explored **two approaches** for this problem.

**𝐀𝐩𝐩𝐫𝐨𝐚𝐜𝐡 𝟏: 𝐓𝐰𝐨-𝐏𝐨𝐢𝐧𝐭 𝐌𝐞𝐫𝐠𝐞**

🔹 Use two pointers to traverse the sorted arrays in order.
🔹 Process only the first `((m + n) // 2) + 1` elements needed to identify the middle value(s).
🔹 Keep track of the previous and current elements to calculate the median without building a merged array.

**Time Complexity:** O(m + n) in the worst case  
**Auxiliary Space:** O(1)

**𝐀𝐩𝐩𝐫𝐨𝐚𝐜𝐡 𝟐: 𝐁𝐢𝐧𝐚𝐫𝐲 𝐒𝐞𝐚𝐫𝐜𝐡 𝐨𝐧 𝐏𝐚𝐫𝐭𝐢𝐭𝐢𝐨𝐧𝐬**

🔹 Always perform binary search on the smaller array.
🔹 Choose partition positions in both arrays so the left side contains half of the combined elements.
🔹 Check whether the elements on the left partitions are no greater than the elements on the right partitions.
🔹 Once the correct partition is found, calculate the median using only the boundary values.

**Time Complexity:** O(log(min(m, n)))  
**Auxiliary Space:** O(1)

**𝐓𝐡𝐞 𝐤𝐞𝐲 𝐨𝐛𝐬𝐞𝐫𝐯𝐚𝐭𝐢𝐨𝐧:** We don't need to merge the arrays. By finding the correct partition, we can identify the middle element(s) using binary search on the smaller array.

**𝐊𝐞𝐲 𝐭𝐚𝐤𝐞𝐚𝐰𝐚𝐲:** Start with a straightforward solution, understand its cost, and then look for a way to reduce the search space. The optimized approach here turns a linear traversal into logarithmic time.

#Python #DSA #LeetCode #BinarySearch #Arrays #ProblemSolving #LearningInPublic
