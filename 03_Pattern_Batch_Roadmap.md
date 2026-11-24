# Pattern Batch Roadmap

**Core rule:** batch by the same problem-solving pattern, not by a broad topic label. Complete/refresh the batch first, then publish its post-worthy problems in sequence. Keep easy warm-ups as practice and replace them on posting days with a stronger problem in the same pattern.

## Batch A — Converging / sorted two pointers
**Problem IDs:** LC11, LC15, LC42, LC167, LC977, LC125
Use stronger problems LC11, LC15, LC42 and LC167 as post candidates. LC125 and LC977 are supporting practice; avoid an Easy-only posting run.

## Batch B — Same-direction / in-place two pointers
**Problem IDs:** LC26, LC88, LC283, LC344, LC3936, LC189, LC31
LC26 and LC88 already published (#7–#8). LC283, LC344 and LC3936 are short reinforcement; LC189 and LC31 add richer in-place transformations.

## Batch C — Sliding window
**Problem IDs:** LC3, LC424, LC992
A clean three-problem batch: longest unique substring → replacement budget → exactly K distinct via atMost(K).

## Batch D — Binary search — boundaries / rotated arrays / partitions
**Problem IDs:** LC704, LC35, LC33, LC81, LC153, LC69, LC74, LC4
Many foundational members are already posted (#16–#18, #21, #23). Use LC4/LC74/LC33/LC153 as published reference points; future refresh only when recall needs it.

## Batch E — Binary search on answer / monotone feasibility
**Problem IDs:** LC875, LC2187, LC1648
Already posted as #19, #20 and #22. Keep as a completed mini-series; do not repeat without a deliberate re-solve goal.

## Batch F — Intervals — sorting + greedy boundary decisions
**Problem IDs:** LC56, LC57, LC435, LC452
Already published as #2, #4, #5 and #6. This is an established series; avoid re-posting the same IDs.

## Batch G — Greedy — resource allocation / counting / reachability
**Problem IDs:** LC860, LC1833, LC455, LC2144, LC2244, LC55
Use LC1833/LC2244/LC55 as stronger candidates. LC860/LC455/LC2144 are useful supporting exercises, not automatic standalone posts.

## Batch H — Prefix sums / running extrema / subarray state
**Problem IDs:** LC53, LC121, LC1299, LC238, LC560, LC152, LC485
LC53/121/1299/238/560 already have posts #9–#15. LC152 is a fresh stronger follow-up; LC485 is basic reinforcement.

## Batch I — Hashmaps / frequency / sets
**Problem IDs:** LC1, LC217, LC242, LC49, LC128, LC347, LC3692, LC169
Existing #13–#15 cover frequency/hash-prefix. Fresh candidates: LC128, LC347, LC3692; LC1 is a foundational warm-up.

## Batch J — Stack invariants / expression evaluation
**Problem IDs:** LC20, LC150, LC155
LC20 and LC150 are natural validation/evaluation progression; LC155 introduces an augmented stack invariant.

## Batch K — Linked-list pointer patterns
**Problem IDs:** LC206, LC141, LC21, LC19, LC143, LC2, LC23
Sequence around reversal, cycle detection, merge, gap pointer, reorder, addition and k-way merge. LC23 is the heap-assisted capstone.

## Batch L — Tree DFS / structural comparison / postorder states
**Problem IDs:** LC112, LC572, LC297, LC968
Start with path DFS and subtree comparison, then serialization, then LC968 postorder greedy/DP. LC968 is Hard and deserves a dedicated review day.

## Batch M — Graph / grid traversal subpatterns
**Problem IDs:** LC200, LC695, LC79, LC133, LC417
Connected components (#24–#25), path DFS/backtracking (#26), graph clone (#27), reverse multi-source reachability (LC417). Keep each subpattern explicit rather than calling them identical.

## Batch N — Backtracking — combinations / subsets / permutations
**Problem IDs:** LC17, LC39, LC40, LC78, LC90, LC46, LC47, LC51
Group by decision structure: combinations, duplicate-aware combinations, subsets, permutations, duplicate-aware permutations, then N-Queens.

## Batch O — Dynamic programming — 1D / grid / segmentation / optimisation
**Problem IDs:** LC70, LC509, LC62, LC198, LC139, LC322, LC300, LC152
Use LC70/509 only as warm-up; stronger run: LC198 → LC139 → LC322 → LC300/LC152. LC62 is grid DP.

## Batch P — Palindrome string algorithms
**Problem IDs:** LC125, LC5, LC647
LC125 is two pointers; LC5 and LC647 use expand-around-center / DP. Keep the two techniques distinct within a string-focused batch.

## Batch Q — Bit manipulation / number invariants
**Problem IDs:** LC338, LC136, LC191, LC190, LC268, LC204
LC338 adds DP recurrence to bits; LC136/191/190/268 reinforce XOR/popcount/reversal; LC204 is sieve rather than bit manipulation, so tag as adjacent number theory.

## Batch R — Heap / streaming / k-way selection
**Problem IDs:** LC23, LC295, LC347
LC347 top-K, LC23 k-way merge, LC295 online median. Distinct heap use cases; teach them together as priority-queue patterns.

## Batch S — Matrix / grid transformations
**Problem IDs:** LC54, LC48
Spiral boundary simulation and transpose-plus-reverse rotation. Keep distinct from graph traversal.

## Batch T — String processing / numeric parsing
**Problem IDs:** LC2, LC415, LC557, LC151, LC58, LC14, LC7, LC9, LC13, LC1404, LC1342, LC258, LC2235
Separate linked-list LC2 from string arithmetic LC415; do not post trivial warm-ups alone.

## Batch U — Sorting algorithms
**Problem IDs:** LC912
LC912 is a standalone sorting-algorithm exercise; connect to sorting use cases without duplicating interval/greedy posts.

## Batch V — Simulation / combinatorics / game state
**Problem IDs:** LC1823, LC3847
LC1823 Josephus-style elimination; LC3847 direct state simulation. Good adjacent simulation practice, but not one identical algorithm.

## Batch W — SQL track — keep separate from DSA algorithms
**Problem IDs:** LC1731, LC1045, LC619, LC1729, LC596, LC1070, LC1141, LC2356, LC550, LC1174, LC1193, LC1211, LC1633, LC1075, LC1251, LC620, LC1934, LC570, LC1280, LC577, LC1661, LC197, LC1581, LC1068, LC1378, LC1683, LC1148, LC595, LC584, LC1757
SQL practice is a separate curriculum and content stream; group by joins, aggregation, date/window logic and filtering. Do not mix these into DSA post numbering.

## How to run each batch
1. Start with the pattern invariant and one representative problem.
2. Solve/re-solve all relevant items in the batch. Do not assume a past solve means current recall.
3. Mark each problem as Accepted only when an implementation is supplied under the user's rule; mark LinkedIn status separately.
4. For posting, prefer Medium/Hard or otherwise insight-rich questions. Do not force a post for a trivial warm-up; substitute a stronger question from the same pattern on that day.
5. Do not assign a new DSA post number to a problem already represented by a published post, unless the user explicitly chooses a follow-up/alternative explanation.
6. Keep SQL, original assessment exercises, and Builder's Log separate from the LeetCode DSA post ledger.

## Current next steps
- DSA #27: LC133 Clone Graph — solution supplied (therefore Accepted under the user's rule), reviewed; caption ready; publication not confirmed.
- Next candidate after #27: LC417 Pacific Atlantic Water Flow — solution supplied (therefore Accepted), approach reviewed; caption not yet drafted; publication not confirmed.
- After the grid/graph traversal thread, run the converging two-pointer batch as a consecutive series: LC11, LC15, LC42, LC167 as the stronger candidates; LC125/LC977 are supporting practice, not filler posts.
- Follow with the three-problem sliding-window batch LC3 → LC424 → LC992.
- Then decide whether to refresh or extend the established binary-search and greedy/interval series; avoid repeating already-published problems.

## Recommended execution order after LC417
1. **Converging / sorted two pointers:** LC167 (historical re-learn) → LC11 → LC15 → LC42. Use LC125 and LC977 as practice warm-ups only; do not force standalone posts for them.
2. **Sliding window:** LC3 → LC424 (historical re-learn) → LC992. Keep the technique progression explicit: no-repeat window, frequency-budget window, then exactly-K via atMost(K).
3. **Linked-list pointer patterns:** LC141 → LC206 → LC19 → LC143. Then keep the different merge/addition techniques together: LC21 → LC2; LC23 is the heap-assisted k-way merge capstone.
4. **Hashing / frequency / set membership:** LC128 → LC347 → LC3692, with LC1/LC217 as supporting practice and LC242/LC49/LC560 retained as already-published references.
5. **Stacks:** LC20 → LC150 → LC155; compare delimiter matching, expression evaluation and a stack augmented with a running minimum.
6. **Trees:** LC112 → LC572 → LC297 → LC968, ending with the postorder greedy/state problem.
7. **Backtracking:** LC17 → LC78 → LC90 → LC39 → LC40 → LC46 → LC47 → LC51. Keep duplicate-handling and choice reuse as explicit subpatterns.
8. **Dynamic programming:** LC70/LC509 are warm-ups; then LC198 → LC139 → LC322 → LC300 → LC152, with LC62 (grid DP) and LC877 (game DP) in their own subtracks.
9. **Greedy resource allocation / scheduling:** LC1833, LC2244 and LC55 are stronger candidates; LC860, LC455 and LC2144 are supporting exercises rather than forced posts.
10. **Heaps / streaming:** LC347 → LC23 → LC295. The custom `infosys_medium.py` can be assessed in this batch after its prompt and constraints are revisited.
11. **Sorting / inversion / parity:** LC912 plus `infosys_hard.py` and `tcs12.py` can be grouped only after their exact prompts/constraints are reviewed; do not assume they are identical techniques.
12. **Matrix transformations, bit manipulation, palindrome strings and number theory** are later focused mini-batches. Keep LC54/LC48, LC338/LC136/LC190/LC191/LC268, LC5/LC647 and LC204 in their own technique clusters.

## Original-exercise placement
- `infosys_medium.py`: subarray optimisation + two heaps; original prompt available from user; slot into heap/subarray batch after review.
- `infosys_hard.py`: distinct same-parity closest-gap search after sorting; original prompt available from user; slot into sorting / pair-selection batch.
- `tcs2.py`: time-window duplicate transaction detection; reconstruct prompt when the hashing/time-window batch arrives.
- `tcs12.py`: adjacent swaps to target permutation; reconstruct prompt and validate duplicates/constraints before deciding if this is inversion counting.
- `tcs1.py` and `tcs11.py`: basic lookup/discount slabs; retain as practice, not standalone DSA posts.
- Java numbered programs and DBMS scripts: classify only after actual source inspection.

## SQL sequence — independent track
- Basic filters/projections: LC595, LC1757, LC584, LC1683, LC1148, LC620.
- Joins and anti-joins: LC1731, LC1068, LC1075, LC1251, LC1378, LC1581, LC577, LC197.
- Aggregation / GROUP BY / HAVING / DISTINCT: LC1045, LC1729, LC596, LC2356, LC619, LC570, LC1280, LC1633, LC1211, LC1193.
- Date, first-row and conditional-rate queries: LC1070, LC1141, LC550, LC1174, LC1934, LC1661.
- Do not include these in DSA Journey post numbering unless the user explicitly launches a separate SQL series.