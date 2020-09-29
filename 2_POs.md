Potential Outcomes
================
João Pedro S. Macalós
9/29/2020

  - [Today](#today)
  - [Potential Outcomes](#potential-outcomes)
      - [PO.1](#po.1)

## Today

<table class="table" style="margin-left: auto; margin-right: auto;">

<thead>

<tr>

<th style="text-align:left;">

N

</th>

<th style="text-align:left;">

Session

</th>

<th style="text-align:left;">

Reading

</th>

<th style="text-align:left;">

Date

</th>

<th style="text-align:left;">

Time

</th>

</tr>

</thead>

<tbody>

<tr>

<td style="text-align:left;">

1

</td>

<td style="text-align:left;">

DAGs and the Structural Causal Model

</td>

<td style="text-align:left;">

Ch. 4

</td>

<td style="text-align:left;">

09/22/2020

</td>

<td style="text-align:left;">

19h CET

</td>

</tr>

<tr>

<td style="text-align:left;font-weight: bold;color: white !important;background-color: red !important;">

2

</td>

<td style="text-align:left;font-weight: bold;color: white !important;background-color: red !important;">

Potential Outcomes: Introduction

</td>

<td style="text-align:left;font-weight: bold;color: white !important;background-color: red !important;">

Ch. 5

</td>

<td style="text-align:left;font-weight: bold;color: white !important;background-color: red !important;">

09/29/2020

</td>

<td style="text-align:left;font-weight: bold;color: white !important;background-color: red !important;">

19h CET

</td>

</tr>

<tr>

<td style="text-align:left;">

3

</td>

<td style="text-align:left;">

Matching and subclassification

</td>

<td style="text-align:left;">

Ch. 6

</td>

<td style="text-align:left;">

10/06/2020

</td>

<td style="text-align:left;">

19h CET

</td>

</tr>

<tr>

<td style="text-align:left;">

–

</td>

<td style="text-align:left;">

BREAK

</td>

<td style="text-align:left;">

–

</td>

<td style="text-align:left;">

10/13/2020

</td>

<td style="text-align:left;">

19h CET

</td>

</tr>

<tr>

<td style="text-align:left;">

4

</td>

<td style="text-align:left;">

Instrumental variables

</td>

<td style="text-align:left;">

Ch. 8

</td>

<td style="text-align:left;">

10/20/2020

</td>

<td style="text-align:left;">

19h CET

</td>

</tr>

<tr>

<td style="text-align:left;">

5

</td>

<td style="text-align:left;">

Dagifying IVs

</td>

<td style="text-align:left;">

TBD

</td>

<td style="text-align:left;">

10/27/2020

</td>

<td style="text-align:left;">

19h CET

</td>

</tr>

<tr>

<td style="text-align:left;">

6

</td>

<td style="text-align:left;">

Regression Discontinuity Designs

</td>

<td style="text-align:left;">

Ch. 7

</td>

<td style="text-align:left;">

11/03/2020

</td>

<td style="text-align:left;">

19h CET

</td>

</tr>

<tr>

<td style="text-align:left;">

–

</td>

<td style="text-align:left;">

BREAK - YSI Plenary

</td>

<td style="text-align:left;">

–

</td>

<td style="text-align:left;">

11/10/2020

</td>

<td style="text-align:left;">

19h CET

</td>

</tr>

<tr>

<td style="text-align:left;">

–

</td>

<td style="text-align:left;">

BREAK - YSI Plenary

</td>

<td style="text-align:left;">

–

</td>

<td style="text-align:left;">

11/17/2020

</td>

<td style="text-align:left;">

19h CET

</td>

</tr>

<tr>

<td style="text-align:left;">

7

</td>

<td style="text-align:left;">

Difference-in-differences

</td>

<td style="text-align:left;">

Ch. 9

</td>

<td style="text-align:left;">

11/24/2020

</td>

<td style="text-align:left;">

19h CET

</td>

</tr>

<tr>

<td style="text-align:left;">

8

</td>

<td style="text-align:left;">

Dagifying DiD

</td>

<td style="text-align:left;">

TBD

</td>

<td style="text-align:left;">

12/01/2020

</td>

<td style="text-align:left;">

19h CET

</td>

</tr>

<tr>

<td style="text-align:left;">

9

</td>

<td style="text-align:left;">

Front-door criterion: a new research design?

</td>

<td style="text-align:left;">

TBD

</td>

<td style="text-align:left;">

12/08/2020

</td>

<td style="text-align:left;">

19h CET

</td>

</tr>

<tr>

<td style="text-align:left;">

10

</td>

<td style="text-align:left;">

Conclusion

</td>

<td style="text-align:left;">

–

</td>

<td style="text-align:left;">

12/15/2020

</td>

<td style="text-align:left;">

19h CET

</td>

</tr>

</tbody>

</table>

# Potential Outcomes

Main reference:

  - Cunningham (2020), ch. 5

Extra:

  - Angrist and Pischke (2009) “Mostly Harmless Econometrics”, ch. 2
    
      - Morgan and Winship (2014) “Counterfactuals and causal
        inference”, ch. 2

## PO.1

Comparison of two states of the world

Counterfactuals Y1, Y0

  
![\\begin{align}&#10;\\alpha = \\beta \*PO +
\\epsilon&#10;\\end{align}](https://latex.codecogs.com/png.latex?%5Cbegin%7Balign%7D%0A%5Calpha%20%3D%20%5Cbeta%20%2APO%20%2B%20%5Cepsilon%0A%5Cend%7Balign%7D
"\\begin{align}
\\alpha = \\beta *PO + \\epsilon
\\end{align}")  

Cause is defined as Y1 - Y0

Funfamental problem of CI

Quantities of interest ATE

ATT, ATU

They cannot be observed, but we try to estimate them

SDO (simple difference of means) Is a comparison

In observation studies, this quantity will be most likely a biased
estimate of the ATE

That’s because the potential outcomes are not independent (ex-ante) of
the selection to treatment

Decomposition of SDO into ATE + SB + HE

Randomization Ensures by design the indepence condition

It removes SB and HE

Seeing is believing \[Monte Carlo\]

STAR Example
