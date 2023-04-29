# Permutation and non-permutations schedules for the flow shop minimizing total completion time

This repository contains detailed results for the paper [Benavides, Ritt, Iterated local search heuristics for minimizing total completion time in permutation and non-permutation flow shops, Proc. 25th Int. Conf. Autom. Plan. Sched., 34-31, 2015](https://doi.org/10.1609/icaps.v25i1.13710).

## Detailed results

### Values of the permutation schedules, as reported in Tables 2, 4, and 5

* Permutation schedules with time limit 30nm ms: [Table 2, column "30nm"](tables/t2-30nm.csv)
* Permutation schedules with time limit 60nm ms: [Table 2, column "60nm"](tables/t2-60nm.csv)

### Values of the non-permutation schedules as reported in Table 5

* Non-permutation schedules with time limit 60nm ms: [Table 5, column "60nm"](tables/t5-nps-60nm.csv)
* Non-permutation schedules with time limit 30nm^2 ms: [Table 5, column "30nm²"](tables/t5-nps-30nmm.csv)

### Buffer sizes reported in Table 6

* Buffer sizes for permutation schedules with time limit 30nm ms: [Table 6, column "30nm"](tables/t6-ps-30nm.csv)
* Buffer sizes for permutation schedules with time limit 60nm ms: [Table 6, column "60nm"](tables/t6-ps-60nm.csv)
* Buffer sizes for non-permutation schedules with time limit 60nm ms: [Table 6, column "60nm"](tables/t6-nps-60nm.csv)
* Buffer sizes for non-permutation schedules with time limit 30nm^2 ms: [Table 6, column "30nm²"](tables/t6-nps-30nmm.csv)

### Previous best known values used to compute relative deviations

[The reference values used](tables/taillard-flowtime.csv) are from Pan & Ruiz (2014).

## How to cite

```bibtex
@InProceedings{Benavides.Ritt/2015,
  author = 	 {Alexander J. Benavides and Marcus Ritt},
  title = 	 {Iterated local search heuristics for minimizing total completion time in permutation and non-permutation flow shops},
  crossref = {Proc. 25th Int. Conf. Autom. Plan. Sched.},
  pages =	 {34--41},
  doi =		 {10.1609/icaps.v25i1.13710}
}
```
