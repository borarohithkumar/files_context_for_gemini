# MASTER LEARNING & CATEGORY TRACKER — 20 NOVEMBER 2026

## Latest reconciliation

- DSA #1–#25 are published per user confirmation.
- LC200 — Number of Islands: completed, recursive four-direction DFS, DSA #24 published.
- LC695 — Max Area of Island: completed, iterative BFS using `deque`, DSA #25 published.
- LC695 approach marks land as water **when enqueuing**, so each land cell enters the queue once; counts component area and updates the maximum.
- Complexity for LC695: **O(R × C) time; O(R × C) worst-case auxiliary queue space**.
- Last LeetCode profile screenshot/value supplied: **140/4115**, before LC695. Current profile total unknown.
- The complete 141-ID register, original curated 47, category map, Termux source-file inventory and project/repository notes remain in the context master linked below. Do not silently replace its cutoff classifications.

## Canonical detailed source

[Open the complete master tracker in the context repository](https://github.com/borarohithkumar/files_context_for_gpt/blob/main/01_Master_Learning_and_Category_Tracker.md)

[Open the start guide](https://github.com/borarohithkumar/files_context_for_gpt/blob/main/00_START_HERE.md)

[Open the publication log and prior captions](https://github.com/borarohithkumar/files_context_for_gpt/blob/main/02_DSA_Post_and_Builder_Log.md)

The repository files were read during this reconciliation. The prior master contains the full 141-ID table and detailed category/repository inventories. This update deliberately records only the new delta here rather than reconstructing a partial copy and risking loss of rows.

## Current Grid / Graph block

| Sequence | Problem | Classification | Status |
|---:|---|---|---|
| DSA #24 | LC200 — Number of Islands | Grid / Graph; connected components; DFS | Completed; Published |
| DSA #25 | LC695 — Max Area of Island | Grid / Graph; connected components; BFS | Completed; Published |
| Next | LC79 — Word Search | Grid DFS + path-specific backtracking | Not yet solved; next completion and DSA #26 candidate |
| Later refresh | LC133 — Clone Graph | Graph traversal + hash map | Historical 2025 solve; refresh required |
| Later refresh | LC417 — Pacific Atlantic Water Flow | Reverse multi-source graph/grid traversal | Historical 2025 solve; refresh required |
| First-time later | LC994 — Rotting Oranges | Multi-source BFS | Not yet in tracked solved IDs |
| First-time later | LC207 — Course Schedule | Directed graph; cycle detection / topological sort | Not yet in tracked solved IDs |
| First-time later | LC743 — Network Delay Time | Dijkstra + min-heap | Not yet in tracked solved IDs |

**Why LC79 next:** it extends the just-practised grid traversal into recursion/backtracking. This is an intentional bridge, not a random category jump. After LC79, refresh LC133 and LC417 before broadening the graph block.

## LC695 implementation review

The user's BFS implementation:
- Scans each cell; starts a BFS only on an unvisited land cell.
- Changes the starting cell to `0` before enqueueing.
- Uses `deque.popleft()` for FIFO traversal.
- Checks four orthogonal neighbours and marks each as `0` before enqueueing.
- Counts cells in the current island and updates `max_area`.

This is correct for LeetCode 695's non-empty rectangular-grid constraints. The in-place mutation avoids a separate visited matrix. No recursive call-stack risk.

## Repository / project inventory — inherited snapshot, not freshly rescanned

The detailed master records these five repositories and their 18 November 2026 tree-SHA baselines:

| Repository | Snapshot file blobs | Main subject |
|---|---:|---|
| [Termux_Android](https://github.com/borarohithkumar/Termux_Android) | 167 | Python, Java, DBMS, interview exercises |
| [TerMind-CLI](https://github.com/borarohithkumar/TerMind-CLI) | 12 | Python CLI, FastAPI, FAISS, cloud/DevOps |
| [ArcHypr-w-Configs](https://github.com/borarohithkumar/ArcHypr-w-Configs) | 487 | Arch Linux / Hyprland configuration |
| [Collaborative-Editor](https://github.com/borarohithkumar/Collaborative-Editor) | 25 | React/Vite, Express/Socket.IO, MongoDB |
| [NoteShare](https://github.com/borarohithkumar/NoteShare) | 38 | React/Vite, Express/Mongoose, JWT, Cloudinary |

**Important:** these counts and tree SHAs are inherited from the 18 November audit. They are not claimed as current. The context repo itself was inspected on 20 November; a fresh full recursive scan of the five source repositories has not yet been completed in this turn.

### Original coding exercises — keep distinct from LeetCode

Already featured in DSA posts:
- DSA #3: `Termux_Android/Python/maxsubspass.py` — custom greedy/sorting exercise.
- DSA #20: `Termux_Android/Python/icsl_1.py` — custom ICSL/HirePro assessment exercise, paired with LC2187 as a related pattern, not the same statement.
- DSA #22: `Termux_Android/Python/infosys_easy.py` — Infosys Food Stamps sample, paired with LC1648 as a related pattern, not the same statement.

Unscheduled originals requiring prompt/constraint verification:
- `Python/infosys_medium.py`
- `Python/infosys_hard.py`
- `Python/tcs1.py`, `tcs2.py`, `tcs11.py`, `tcs12.py`
- Termux Java numbered exercises and DBMS scripts: inspect source contents before classifying; filenames alone do not establish problem statements.
- `Python/word_search.py` was noted in the inherited audit as an incomplete stub, not a completed LC79 solution.

## Builder's Log — separate numbering

1. TerMind — Published.
2. Linux journey: Windows → Fedora → Arch + Hyprland — Planned.
3. ArcHypr-w-Configs — Planned.
4. Termux as a portable development workspace — Planned.
5. Collaborative Editor — Planned.
6. NoteShare — Planned.
7. TerMind cloud / DevOps follow-up — Planned.
8. Cloud / DevOps learning log — Ongoing / planned.

## Repository audit procedure for future updates

1. List the user's repositories and identify the five tracked projects plus any newly created repositories.
2. Compare each default branch's recursive tree SHA with the recorded baseline.
3. If unchanged, retain the inventory and skip rescanning file contents.
4. If changed, inspect added/modified/deleted paths and fetch relevant source files; update the per-file inventory and categorize new coding problems.
5. Never infer a prompt from a generic filename; ask for the original prompt where needed.
6. Do not expose secrets, tokens, shell histories or personal configuration data in public posts.
