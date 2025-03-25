# Codeforces Problems

## A. Olympiad Date

### Problem Statement

**Time Limit:** 1 second
**Memory Limit:** 256 megabytes

The final of the first Olympiad by IT Campus "NEIMARK" is scheduled for March 1, 2025. A nameless intern was tasked with forming the date of the Olympiad using digits — 01.03.2025.

To accomplish this, the intern took a large bag of digits and began drawing them one by one. In total, he drew n digits — the digit a_i was drawn in the i-th turn.

You suspect that the intern did extra work. Determine at which step the intern could have first assembled the digits to form the date of the Olympiad (the separating dots can be ignored), or report that it is impossible to form this date from the drawn digits. Note that leading zeros **must be displayed**.

#### Input
- The first line contains the number of test cases t (1 ≤ t ≤ 10^4)
- For each test case:
  - First line: A single integer n (1 ≤ n ≤ 20)
  - Second line: n integers a_i (0 ≤ a_i ≤ 9) representing the digits drawn

#### Output
For each test case, output the minimum number of digits that the intern could pull out. If all the digits cannot be used to make a date, output 0.

#### Example
**Input:**
```
4
10
2 0 1 2 3 2 5 0 0 1
8
2 0 1 2 3 2 5 0
8
2 0 1 0 3 2 5 0
16
2 3 1 2 3 0 1 9 2 1 0 3 5 4 0 3
```

**Output:**
```
9
0
8
15
```

## B. Team Training

### Problem Statement

**Time Limit:** 2 seconds
**Memory Limit:** 256 megabytes

At the IT Campus "NEIMARK", there are training sessions in competitive programming — both individual and team-based!

For the next team training session, n students will attend, and the skill of the i-th student is given by a positive integer a_i.

The coach considers a team strong if its strength is at least x. The strength of a team is calculated as the number of team members multiplied by the minimum skill among the team members.

For example, if a team consists of 4 members with skills [5,3,6,8], then the team's strength is 4 * min([5,3,6,8]) = 12.

Output the maximum possible number of strong teams, given that each team must have at least one participant and every participant must belong to exactly one team.

#### Input
- The first line contains the number of test cases t (1 ≤ t ≤ 10^4)
- For each test case:
  - First line: Two integers n and x (1 ≤ n ≤ 2 * 10^5, 1 ≤ x ≤ 10^9)
    - n: number of students in training
    - x: minimum strength of a team to be considered strong
  - Second line: n integers a_i (1 ≤ a_i ≤ 10^9) representing student skills

#### Output
For each test case, output the maximum possible number of teams with strength at least x.

#### Example
**Input:**
```
5
6 4
4 5 3 3 2 6
4 10
4 2 1 3
5 3
5 3 2 3 2
3 6
9 1 7
6 10
6 1 3 6 3 2
```

**Output:**
```
4
0
4
2
1
```

## Notes
- Problems are from a Codeforces contest
- Solutions require careful handling of multiple test cases
- Algorithmic thinking and optimization are key to solving these problems
