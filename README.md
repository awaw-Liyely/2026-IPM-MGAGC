# 2026-IPM-MGAGC

**The code  will be open-sourced upon the acceptance of this paper to ensure reproducibility.**

This is the code for the accepted paper:

**Authors:** Ye Li, Lei Yang, Binbin Sang\*, Guoyin Wang\*

**Title:**  *Multi-granularity Granular-ball Anchor Graph Clustering with Self-Weighting*

 **Information Processing and Management (IPM).**



MGAGC.ipynb is the main function file, The reported results for all metrics (ACC, NMI, and Time) correspond to the best performance selected from all parameter trials.

If you have any questions, please connect liyely@126.com



Example Output on the **Iris** dataset:

```txt
=== Processing dataset 1/1: Iris ===
Generating anchors using granular ball clustering...
Generated anchor matrix: (4, 29)
Samples: 150, Features: 4, True clusters: 3
Anchor matrix shape: (4, 29)
Testing k values: [1 3]
Number of runs per combination: 10
  Testing combination 1/20: k=1, beta=0.010000, lambda_init=1.0
   Results: acc=0.2400±0.0000, nmi=0.4773±0.0000, ari=0.1540±0.0000
  Testing combination 2/20: k=1, beta=0.030000, lambda_init=1.0
   Results: acc=0.2400±0.0000, nmi=0.4773±0.0000, ari=0.1540±0.0000
  Testing combination 3/20: k=1, beta=0.050000, lambda_init=1.0
   Results: acc=0.2400±0.0000, nmi=0.4773±0.0000, ari=0.1540±0.0000
  Testing combination 4/20: k=1, beta=0.070000, lambda_init=1.0
   Results: acc=0.2400±0.0000, nmi=0.4773±0.0000, ari=0.1540±0.0000
  Testing combination 5/20: k=1, beta=0.090000, lambda_init=1.0
   Results: acc=0.2400±0.0000, nmi=0.4773±0.0000, ari=0.1540±0.0000
  Testing combination 6/20: k=1, beta=0.110000, lambda_init=1.0
   Results: acc=0.2400±0.0000, nmi=0.4773±0.0000, ari=0.1540±0.0000
  Testing combination 7/20: k=1, beta=0.130000, lambda_init=1.0
   Results: acc=0.2400±0.0000, nmi=0.4773±0.0000, ari=0.1540±0.0000
  Testing combination 8/20: k=1, beta=0.150000, lambda_init=1.0
   Results: acc=0.2400±0.0000, nmi=0.4773±0.0000, ari=0.1540±0.0000
  Testing combination 9/20: k=1, beta=0.170000, lambda_init=1.0
   Results: acc=0.2400±0.0000, nmi=0.4773±0.0000, ari=0.1540±0.0000
  Testing combination 10/20: k=1, beta=0.190000, lambda_init=1.0
   Results: acc=0.2400±0.0000, nmi=0.4773±0.0000, ari=0.1540±0.0000
  Testing combination 11/20: k=3, beta=0.010000, lambda_init=1.0
   Results: acc=0.8467±0.0000, nmi=0.7490±0.0000, ari=0.6537±0.0000
  Testing combination 12/20: k=3, beta=0.030000, lambda_init=1.0
   Results: acc=0.8867±0.0000, nmi=0.8353±0.0000, ari=0.8340±0.0000
  Testing combination 13/20: k=3, beta=0.050000, lambda_init=1.0
   Results: acc=0.9733±0.0000, nmi=0.9011±0.0000, ari=0.9222±0.0000
  Testing combination 14/20: k=3, beta=0.070000, lambda_init=1.0
   Results: acc=0.9733±0.0000, nmi=0.9011±0.0000, ari=0.9222±0.0000
  Testing combination 15/20: k=3, beta=0.090000, lambda_init=1.0
   Results: acc=0.9733±0.0000, nmi=0.9011±0.0000, ari=0.9222±0.0000
  Testing combination 16/20: k=3, beta=0.110000, lambda_init=1.0
   Results: acc=0.9733±0.0000, nmi=0.9011±0.0000, ari=0.9222±0.0000
  Testing combination 17/20: k=3, beta=0.130000, lambda_init=1.0
   Results: acc=0.9733±0.0000, nmi=0.9011±0.0000, ari=0.9222±0.0000
  Testing combination 18/20: k=3, beta=0.150000, lambda_init=1.0
   Results: acc=0.9733±0.0000, nmi=0.9011±0.0000, ari=0.9222±0.0000
  Testing combination 19/20: k=3, beta=0.170000, lambda_init=1.0
   Results: acc=0.9733±0.0000, nmi=0.9011±0.0000, ari=0.9222±0.0000
  Testing combination 20/20: k=3, beta=0.190000, lambda_init=1.0
   Results: acc=0.9733±0.0000, nmi=0.9011±0.0000, ari=0.9222±0.0000
Iris completed, saved 20 results to ./experiment_results/MGAGC\Iris_MGAGC.xlsx

All datasets processed! Results saved in ./experiment_results/MGAGC directory
```

