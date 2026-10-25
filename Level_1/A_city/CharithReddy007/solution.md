# 1A: CharithReddy007

## My Enigma number

GitHub username (lowercase): `charithreddy007`

E = 177079

| Character | Value | Multiplier | Product |
| --------- | ----- | ---------- | ------- |
| c | 3 | 1 | 3 |
| h | 8 | 2 | 16 |
| a | 1 | 4 | 4 |
| r | 18 | 8 | 144 |
| i | 9 | 16 | 144 |
| t | 20 | 32 | 640 |
| h | 8 | 64 | 512 |
| r | 18 | 128 | 2304 |
| e | 5 | 256 | 1280 |
| d | 4 | 512 | 2048 |
| d | 4 | 1024 | 4096 |
| y | 25 | 2048 | 51200 |
| 0 | 0 | 4096 | 0 |
| 0 | 0 | 8192 | 0 |
| 7 | 7 | 16384 | 114688 |

Total: E = 177079

---

## 1A: The bridges of your city

**My last four digits:** 7079

### My map

The four outer bridges are P–Q, Q–R, R–S, and S–P. Each outer island also connects to C. Since the digits for P, R, and S are odd, each of those centre bridges has a second parallel bridge. Q's centre bridge remains single.

- P–Q: 1 bridge
- Q–R: 1 bridge
- R–S: 1 bridge
- S–P: 1 bridge
- P–C: 2 bridges
- Q–C: 1 bridge
- R–C: 2 bridges
- S–C: 2 bridges

**Total bridges: 11**

### My guess

Write your own initial guess here before attempting the walk.

### My attempts

Record at least three walks you tried and note where each one got stuck, if it did. Keep the two P–C bridges, two R–C bridges, and two S–C bridges distinct in your notes because each must be crossed separately.

### Bridges touching each island

| Island | Number of bridges |
| ------ | -----------------: |
| P | 4 |
| Q | 3 |
| R | 4 |
| S | 4 |
| C | 7 |

### Possible or impossible?

**Possible.** Exactly two islands have an odd number of bridges touching them: Q has degree 3 and C has degree 7. A connected graph has a walk that uses every bridge exactly once when it has exactly zero or two odd-degree vertices. With two odd-degree vertices, the walk must start at one and finish at the other.

### My walk

One valid walk is:

**C → P → Q → R → S → P → C → R → C → S → C → Q**

This walk uses all 11 bridges exactly once. The two visits along P–C, the two along R–C, and the two along S–C use the separate parallel bridges.

### Why?

Every time a walk enters an island and then leaves it, it uses bridges in pairs. Therefore, an island with an odd number of bridges cannot be both an ordinary middle point and have all its bridges paired up. For a walk using every bridge exactly once, there can be either no odd-degree islands (if it finishes where it started) or exactly two (the start and end islands).

## What surprised me

Write what you found surprising while trying the walks and checking the bridge counts.

## So I think what's happening is

Write your own summary of the pattern you observed.

## The pattern being covered here is...

This problem illustrates Euler trails in graph theory: the number of bridges touching each island determines whether a walk can use every bridge exactly once.

## Did I use AI? For what?

If you used AI, describe honestly how you used it. For example: “I used AI to check my understanding of the Euler-trail rule and verify a candidate walk; I reviewed the reasoning and checked the bridge counts myself.”
