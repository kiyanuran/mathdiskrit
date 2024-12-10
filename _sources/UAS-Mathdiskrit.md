---
title: UAS-Mathdiskrit

---

# Rafli UAS 
1.
$\begin{array}{c|c|c|c|cc}P&Q&R&\ S&(P\to\ Q)\to(R\to\ S)\\\hline\text{T}&\text{F}&\text{Т}&\text{F}&\text{F}\\\text{Т}&\text{T}&\text{F}&\text{F}&\text{F}\\\text{F}&\text{F}&\text{T}&\text{T}&\text{T}\\\text{F}&\text{T}&\text{F}&\text{T}&\text{T}\\\text{T}&\text{T}&\text{F}&\text{T}&\text{T}\\\text{F}&\text{F}&\text{T}&\text{F}&\text{F}\\\text{F}&\text{T}&\text{T}&\text{F}&\text{F}\\\text{T}&\text{F}&\text{F}&\text{T}&\text{T}\end{array}$

2.

| A | B | C | D | E | F | G |
| -------- | -------- | -------- | -------- | -------- | -------- | -------- |
| B,C,D,E,F     | A,D,G     | A,D,E     | A,B,C     | A,C     | A,G     | B,F|
#### Hitunglah Clossenes Centrality(G)!
Rumus:
$C_C(v_i) = \left[ \frac{1}{n-1} \sum_{j \neq i} g(v_i, v_j) \right]^{-1} = \frac{n-1}{\sum_{j \neq i} g(v_i, v_j)}$
#### Answer
Diket:
$v_i$=G
n = 7 (Banyaknya Node)
Jarak Terpendek Dari Node G
G to A = 2
G to B = 1
G to C = 3
G to D = 2
G to E = 3
G to F = 1
${\sum_{j \neq i} g(v_i, v_j)}$ = 12
- $C_C(G)$ = $\frac{7-1}{12}$ 
- $C_C(G)$ = $\frac{6}{12}$ = 0,5 atau $\frac{1}{2}$ 
#### Hitunglah Betweennes Centrality(F)!
Rumus:
$C_B(v) = \sum_{s \neq v \neq t} \frac{\sigma_{st}(v)}{\sigma_{st}}$
#### Answer
Diket:
$v$ = F
Jarak antara node yang melewati F :
A to G = 1/1
B to G = 2/2
C to G = 2/2
D to G = 3/3
E to G = 2/2
Jumlah Jalur Terpendek = 5
$C_B(F)$ = 5
