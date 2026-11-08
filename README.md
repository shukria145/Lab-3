# Lab-3: Informed Search & Heuristics
 
## Section 2: Heuristics

### Task 2.1: Misplaced Tiles (Cell 6)
```python
def misplaced_tiles(state):
    count = 0
    for i in range(9):
        if state[i] != 0 and state[i] != GOAL_STATE[i]:
            count += 1
    return count
