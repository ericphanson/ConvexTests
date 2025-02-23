Table of contents:

```@contents
Pages = ["Hypatia.md"]
Depth = 4
```


Compilation warmup gives an estimate of 1 minute, 24 seconds of compilation time.

## Hypatia 
These tests were run on September 13, 2022 at 13:09 (UTC).


Excluded problems and classes of problems:
```julia
Regex[r"mip"]
```

### Tests

Tests took 8 minutes, 3 seconds to run (after warmup).

```@raw html
<table>
<tr class="header">
<td style="text-align:left;border-right: solid 2px;">testset</td>
<td style="text-align:center;">pass</td>
<td style="text-align:center;">fail</td>
<td style="text-align:center;">error</td>
<td style="text-align:center;">broken</td>
<td style="text-align:center;">total</td>
</tr>
<tr><td style="text-align:left;border-right: solid 2px;">Hypatia tests</td>
<td style="text-align:center;color:green;">2328</td>
<td style="text-align:center;color:red;">20</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2348</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;Convex</td>
<td style="text-align:center;color:green;">721</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">721</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;SumOfSquares</td>
<td style="text-align:center;color:green;">1607</td>
<td style="text-align:center;color:red;">20</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1627</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp</td>
<td style="text-align:center;color:green;">443</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">446</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_term_fixed</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_horn</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_scaled_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_univariate_sum</td>
<td style="text-align:center;color:green;">34</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">34</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_quartic_comparison</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_scaled_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_concave_then_convex_cubic</td>
<td style="text-align:center;color:green;">11</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">11</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_cheby_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_term</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_quartic_constant</td>
<td style="text-align:center;color:green;">33</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">33</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_options_pricing</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;color:red;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">10</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 30</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 35</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 40</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 45</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 50</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdsos_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp</td>
<td style="text-align:center;color:green;">495</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">499</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_univariate_sum</td>
<td style="text-align:center;color:green;">34</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">34</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_options_pricing</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">10</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 30</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 35</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 40</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 45</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 50</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_cheby_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_quartic_comparison</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_cheby_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_horn</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_term</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_term_fixed</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_scaled_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_scaled_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_quartic_constant</td>
<td style="text-align:center;color:green;">33</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">33</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_concave_then_convex_cubic</td>
<td style="text-align:center;color:green;">11</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">11</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;dsos_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">669</td>
<td style="text-align:center;color:red;">13</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">682</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo5_infeasible</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;simple_matrix</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_concave_then_convex_cubic</td>
<td style="text-align:center;color:green;">11</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">11</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_term_fixed</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;rearrangement</td>
<td style="text-align:center;color:green;">25</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">25</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;maxcut</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;with γ=3.9 it should be infeasible</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;with γ=4.1 it should be feasible</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_term</td>
<td style="text-align:center;color:green;">44</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">44</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_scaled_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal_rem</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo5_feasible</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;chebyshev</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo9</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_cheby_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_feasible_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_horn</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BPT12e399_rem</td>
<td style="text-align:center;color:green;">48</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">48</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_infeasible_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_feasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal_4</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_infeasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quadratic_feasible_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;color:red;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_scaled_univariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;motzkin</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sosdemo10</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;BPT12e399_maxdegree</td>
<td style="text-align:center;color:green;">56</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">56</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_infeasible_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_options_pricing</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;color:red;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">10</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 30</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 35</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 40</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 45</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 50</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_quartic_constant</td>
<td style="text-align:center;color:green;">33</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">33</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_infeasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_univariate_sum</td>
<td style="text-align:center;color:green;">34</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">34</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_bivariate_quadratic</td>
<td style="text-align:center;color:green;">53</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">53</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;choi</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_feasible_scaled_lyapunov_switched_system</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal_4_rem</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sos_quartic_comparison</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;quartic_ideal_2_rem</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr></table>
```

### Errors

```julia
Error in testset K = 35:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 61.74308592833959 ≈ 9.85 (atol=0.1, rtol=0.0)

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 15528.010847221063 ≈ 132.63 (atol=0.1, rtol=0.0)

Error in testset K = 50:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.UNKNOWN_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 50:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:32
  Expression: ≈(JuMP.objective_value(model), expected, atol = atol, rtol = rtol)
   Evaluated: 15764.317981702452 ≈ 132.63 (atol=0.1, rtol=0.0)

Error in testset with γ=3.9 it should be infeasible:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/maxcut.jl:37
  Expression: JuMP.dual_status(model) == MOI.INFEASIBILITY_CERTIFICATE
   Evaluated: MathOptInterface.NEARLY_INFEASIBILITY_CERTIFICATE == MathOptInterface.INFEASIBILITY_CERTIFICATE

Error in testset chebyshev:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/chebyshev.jl:31
  Expression: JuMP.termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.ALMOST_OPTIMAL == MathOptInterface.OPTIMAL

Error in testset chebyshev:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/chebyshev.jl:32
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

Error in testset sos_horn:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/horn.jl:51
  Expression: termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.ALMOST_OPTIMAL == MathOptInterface.OPTIMAL

Error in testset sos_horn:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/horn.jl:53
  Expression: primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

Error in testset quadratic_feasible_scaled_lyapunov_switched_system:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:58
  Expression: JuMP.termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.ALMOST_OPTIMAL == MathOptInterface.OPTIMAL

Error in testset quadratic_feasible_scaled_lyapunov_switched_system:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:59
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

Error in testset quadratic_feasible_lyapunov_switched_system:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:58
  Expression: JuMP.termination_status(model) == MOI.OPTIMAL
   Evaluated: MathOptInterface.ALMOST_OPTIMAL == MathOptInterface.OPTIMAL

Error in testset quadratic_feasible_lyapunov_switched_system:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/lyapunov_switched_system.jl:59
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

Error in testset K = 30:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

Error in testset K = 35:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

Error in testset K = 40:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

```


### Timing information
```julia
 ────────────────────────────────────────────────────────────────────────────────
                                        Time                    Allocations      
                               ───────────────────────   ────────────────────────
       Tot / % measured:             483s /  99.8%           38.2GiB /  99.9%    

 Section               ncalls     time    %tot     avg     alloc    %tot      avg
 ────────────────────────────────────────────────────────────────────────────────
 SumOfSquares               1     260s   53.9%    260s   18.0GiB   47.1%  18.0GiB
   socp                     1     107s   22.2%    107s   7.63GiB   20.0%  7.63GiB
     sdsos_term_fixed       1    23.5s    4.9%   23.5s   1.45GiB    3.8%  1.45GiB
     sdsos_horn             1    14.9s    3.1%   14.9s   0.97GiB    2.5%  0.97GiB
     sdsos_univaria...      1    13.0s    2.7%   13.0s   1.01GiB    2.7%  1.01GiB
     sdsos_concave_...      1    11.9s    2.5%   11.9s    789MiB    2.0%   789MiB
     sdsos_cheby_un...      1    7.57s    1.6%   7.57s    451MiB    1.2%   451MiB
     sdsos_univaria...      1    6.40s    1.3%   6.40s    388MiB    1.0%   388MiB
     sdsos_options_...      1    5.54s    1.1%   5.54s    364MiB    0.9%   364MiB
     sdsos_term             1    5.28s    1.1%   5.28s    383MiB    1.0%   383MiB
     sdsos_scaled_u...      1    4.90s    1.0%   4.90s    292MiB    0.7%   292MiB
     sdsos_quartic_...      1    4.26s    0.9%   4.26s    249MiB    0.6%   249MiB
     sdsos_quartic_...      1    774ms    0.2%   774ms   28.4MiB    0.1%  28.4MiB
     sdsos_scaled_b...      1   48.4ms    0.0%  48.4ms   5.97MiB    0.0%  5.97MiB
     sdsos_bivariat...      1   9.45ms    0.0%  9.45ms    601KiB    0.0%   601KiB
   sdp                      1     106s   22.0%    106s   7.25GiB   19.0%  7.25GiB
     quartic_ideal_rem      1    8.04s    1.7%   8.04s    562MiB    1.4%   562MiB
     sosdemo5_infea...      1    8.02s    1.7%   8.02s    524MiB    1.3%   524MiB
     rearrangement          1    7.39s    1.5%   7.39s    449MiB    1.2%   449MiB
     sos_concave_th...      1    5.37s    1.1%   5.37s    441MiB    1.1%   441MiB
     sos_horn               1    5.33s    1.1%   5.33s    308MiB    0.8%   308MiB
     simple_matrix          1    4.73s    1.0%   4.73s    383MiB    1.0%   383MiB
     sos_scaled_biv...      1    4.39s    0.9%   4.39s    229MiB    0.6%   229MiB
     chebyshev              1    4.32s    0.9%   4.32s    289MiB    0.7%   289MiB
     quartic_ideal          1    4.26s    0.9%   4.26s    221MiB    0.6%   221MiB
     sos_term_fixed         1    4.14s    0.9%   4.14s    216MiB    0.6%   216MiB
     quartic_ideal_4        1    3.89s    0.8%   3.89s    247MiB    0.6%   247MiB
     maxcut                 1    3.85s    0.8%   3.85s    190MiB    0.5%   190MiB
     sos_cheby_univ...      1    3.84s    0.8%   3.84s    203MiB    0.5%   203MiB
     sos_term               1    3.34s    0.7%   3.34s    184MiB    0.5%   184MiB
     BPT12e399_rem          1    3.16s    0.7%   3.16s   79.5MiB    0.2%  79.5MiB
     quartic_feasib...      1    3.10s    0.6%   3.10s    117MiB    0.3%   117MiB
     sos_quartic_co...      1    3.09s    0.6%   3.09s    172MiB    0.4%   172MiB
     quartic_ideal_...      1    3.04s    0.6%   3.04s    176MiB    0.5%   176MiB
     sos_options_pr...      1    2.84s    0.6%   2.84s    212MiB    0.5%   212MiB
     sosdemo10              1    1.89s    0.4%   1.89s    182MiB    0.5%   182MiB
     sos_univariate...      1    1.67s    0.3%   1.67s    110MiB    0.3%   110MiB
     sosdemo9               1    962ms    0.2%   962ms   50.1MiB    0.1%  50.1MiB
     quadratic_feas...      1    910ms    0.2%   910ms   51.8MiB    0.1%  51.8MiB
     sos_univariate...      1    890ms    0.2%   890ms   35.1MiB    0.1%  35.1MiB
     quadratic_infe...      1    782ms    0.2%   782ms   41.9MiB    0.1%  41.9MiB
     choi                   1    557ms    0.1%   557ms   63.9MiB    0.2%  63.9MiB
     sosdemo5_feasible      1    435ms    0.1%   435ms   73.8MiB    0.2%  73.8MiB
     BPT12e399_maxd...      1    332ms    0.1%   332ms   9.38MiB    0.0%  9.38MiB
     sos_quartic_co...      1    154ms    0.0%   154ms   21.9MiB    0.1%  21.9MiB
     motzkin                1    103ms    0.0%   103ms   4.92MiB    0.0%  4.92MiB
     sos_bivariate_...      1   26.0ms    0.0%  26.0ms    598KiB    0.0%   598KiB
     quartic_infeas...      1   24.3ms    0.0%  24.3ms   2.11MiB    0.0%  2.11MiB
     quadratic_feas...      1   20.4ms    0.0%  20.4ms   1.99MiB    0.0%  1.99MiB
     quartic_ideal_...      1   19.9ms    0.0%  19.9ms   1.15MiB    0.0%  1.15MiB
     quartic_infeas...      1   10.1ms    0.0%  10.1ms   1.47MiB    0.0%  1.47MiB
     sos_scaled_uni...      1   9.63ms    0.0%  9.63ms    596KiB    0.0%   596KiB
     quadratic_infe...      1   5.41ms    0.0%  5.41ms   1.18MiB    0.0%  1.18MiB
     quartic_feasib...      1   4.74ms    0.0%  4.74ms    766KiB    0.0%   766KiB
   lp                       1    46.7s    9.7%   46.7s   3.07GiB    8.1%  3.07GiB
     dsos_options_p...      1    7.01s    1.5%   7.01s    469MiB    1.2%   469MiB
     dsos_concave_t...      1    6.35s    1.3%   6.35s    464MiB    1.2%   464MiB
     dsos_univariat...      1    4.98s    1.0%   4.98s    263MiB    0.7%   263MiB
     dsos_cheby_biv...      1    4.83s    1.0%   4.83s    285MiB    0.7%   285MiB
     dsos_term_fixed        1    4.23s    0.9%   4.23s    227MiB    0.6%   227MiB
     dsos_horn              1    3.92s    0.8%   3.92s    259MiB    0.7%   259MiB
     dsos_scaled_bi...      1    3.87s    0.8%   3.87s    219MiB    0.6%   219MiB
     dsos_term              1    3.52s    0.7%   3.52s    195MiB    0.5%   195MiB
     dsos_quartic_c...      1    3.28s    0.7%   3.28s    182MiB    0.5%   182MiB
     dsos_bivariate...      1    986ms    0.2%   986ms   38.5MiB    0.1%  38.5MiB
     dsos_quartic_c...      1    165ms    0.0%   165ms   22.1MiB    0.1%  22.1MiB
     dsos_univariat...      1   9.32ms    0.0%  9.32ms    663KiB    0.0%   663KiB
     dsos_cheby_uni...      1   7.76ms    0.0%  7.76ms    689KiB    0.0%   689KiB
     dsos_scaled_un...      1   7.75ms    0.0%  7.75ms    664KiB    0.0%   664KiB
 Convex                     1     222s   46.1%    222s   20.2GiB   52.9%  20.2GiB
   sdp                      1     119s   24.7%    119s   10.7GiB   28.1%  10.7GiB
     sdp_quantum_re...      1    19.2s    4.0%   19.2s   1.75GiB    4.6%  1.75GiB
     sdp_lieb_ando          1    11.8s    2.4%   11.8s    906MiB    2.3%   906MiB
     sdp_trace_logm...      1    5.54s    1.1%   5.54s    576MiB    1.5%   576MiB
     sdp_quantum_re...      1    5.03s    1.0%   5.03s    292MiB    0.7%   292MiB
     sdp_operator_n...      1    4.75s    1.0%   4.75s    320MiB    0.8%   320MiB
     sdp_geom_mean_...      1    3.60s    0.7%   3.60s    124MiB    0.3%   124MiB
     sdp_quantum_re...      1    2.83s    0.6%   2.83s    150MiB    0.4%   150MiB
     sdp_Partial_trace      1    2.43s    0.5%   2.43s    208MiB    0.5%   208MiB
     sdp_relative_e...      1    2.39s    0.5%   2.39s    207MiB    0.5%   207MiB
     sdp_quantum_re...      1    2.32s    0.5%   2.32s   18.4MiB    0.0%  18.4MiB
     sdp_quantum_re...      1    2.28s    0.5%   2.28s    146MiB    0.4%   146MiB
     sdp_quantum_re...      1    2.20s    0.5%   2.20s    146MiB    0.4%   146MiB
     sdp_trace_mpow...      1    2.12s    0.4%   2.12s    228MiB    0.6%   228MiB
     sdp_geom_mean_...      1    2.06s    0.4%   2.06s    234MiB    0.6%   234MiB
     sdp_trace_mpow...      1    1.98s    0.4%   1.98s   26.8MiB    0.1%  26.8MiB
     sdp_quantum_re...      1    1.94s    0.4%   1.94s   13.2MiB    0.0%  13.2MiB
     sdp_matrix_fra...      1    1.93s    0.4%   1.93s    147MiB    0.4%   147MiB
     sdp_sum_larges...      1    1.89s    0.4%   1.89s    130MiB    0.3%   130MiB
     sdp_quantum_ch...      1    1.59s    0.3%   1.59s   66.7MiB    0.2%  66.7MiB
     sdp_geom_mean_...      1    1.36s    0.3%   1.36s    122MiB    0.3%   122MiB
     sdp_dual_lambd...      1    1.09s    0.2%   1.09s   66.0MiB    0.2%  66.0MiB
     sdp_min_maxeig...      1    1.08s    0.2%   1.08s    111MiB    0.3%   111MiB
     sdp_lambda_min...      1    958ms    0.2%   958ms   95.2MiB    0.2%  95.2MiB
     sdp_geom_mean_...      1    932ms    0.2%   932ms   85.4MiB    0.2%  85.4MiB
     sdp_nuclear_no...      1    862ms    0.2%   862ms   87.8MiB    0.2%  87.8MiB
     sdp_Complex_Va...      1    780ms    0.2%   780ms   36.6MiB    0.1%  36.6MiB
     sdp_relative_e...      1    663ms    0.1%   663ms   18.0MiB    0.0%  18.0MiB
     sdp_geom_mean_...      1    655ms    0.1%   655ms   56.4MiB    0.1%  56.4MiB
     sdp_socp_norm2...      1    655ms    0.1%   655ms   46.7MiB    0.1%  46.7MiB
     sdp_trace_mpow...      1    645ms    0.1%   645ms   21.4MiB    0.1%  21.4MiB
     sdp_socp_sumsq...      1    637ms    0.1%   637ms   54.0MiB    0.1%  54.0MiB
     sdp_geom_mean_...      1    621ms    0.1%   621ms   82.3MiB    0.2%  82.3MiB
     sdp_trace_logm...      1    529ms    0.1%   529ms   37.8MiB    0.1%  37.8MiB
     sdp_trace_mpow...      1    524ms    0.1%   524ms   12.4MiB    0.0%  12.4MiB
     sdp_geom_mean_...      1    375ms    0.1%   375ms   35.5MiB    0.1%  35.5MiB
     sdp_Complex_Se...      1    373ms    0.1%   373ms   27.6MiB    0.1%  27.6MiB
     sdp_sdp_variables      1    306ms    0.1%   306ms   28.7MiB    0.1%  28.7MiB
     sdp_socp_abs_atom      1    298ms    0.1%   298ms   21.9MiB    0.1%  21.9MiB
     sdp_geom_mean_...      1    294ms    0.1%   294ms   19.7MiB    0.1%  19.7MiB
     sdp_quantum_re...      1    273ms    0.1%   273ms   21.6MiB    0.1%  21.6MiB
     sdp_trace_mpow...      1    264ms    0.1%   264ms   15.8MiB    0.0%  15.8MiB
     sdp_geom_mean_...      1    257ms    0.1%   257ms   15.9MiB    0.0%  15.9MiB
     sdp_trace_mpow...      1    256ms    0.1%   256ms   17.6MiB    0.0%  17.6MiB
     sdp_quantum_re...      1    253ms    0.1%   253ms   17.2MiB    0.0%  17.2MiB
     sdp_trace_mpow...      1    244ms    0.1%   244ms   18.1MiB    0.0%  18.1MiB
     sdp_geom_mean_...      1    241ms    0.0%   241ms   11.9MiB    0.0%  11.9MiB
     sdp_operator_n...      1    237ms    0.0%   237ms   23.4MiB    0.1%  23.4MiB
     sdp_matrix_fra...      1    233ms    0.0%   233ms   18.1MiB    0.0%  18.1MiB
     sdp_geom_mean_...      1    209ms    0.0%   209ms   23.7MiB    0.1%  23.7MiB
     sdp_geom_mean_...      1    197ms    0.0%   197ms   18.5MiB    0.0%  18.5MiB
     sdp_nuclear_no...      1    190ms    0.0%   190ms   18.7MiB    0.0%  18.7MiB
     sdp_Real_Varia...      1    173ms    0.0%   173ms   5.50MiB    0.0%  5.50MiB
     sdp_sigma_max_...      1    166ms    0.0%   166ms   16.6MiB    0.0%  16.6MiB
     sdp_quantum_re...      1    156ms    0.0%   156ms   14.4MiB    0.0%  14.4MiB
     sdp_geom_mean_...      1    146ms    0.0%   146ms   17.6MiB    0.0%  17.6MiB
     sdp_trace_logm...      1    126ms    0.0%   126ms   6.75MiB    0.0%  6.75MiB
     sdp_geom_mean_...      1    118ms    0.0%   118ms   18.0MiB    0.0%  18.0MiB
     sdp_geom_mean_...      1    117ms    0.0%   117ms   18.6MiB    0.0%  18.6MiB
     sdp_sdp_constr...      1    116ms    0.0%   116ms   10.0MiB    0.0%  10.0MiB
     sdp_kron_atom          1    112ms    0.0%   112ms   11.2MiB    0.0%  11.2MiB
     sdp_geom_mean_...      1    101ms    0.0%   101ms   17.8MiB    0.0%  17.8MiB
     sdp_geom_mean_...      1   86.7ms    0.0%  86.7ms   14.1MiB    0.0%  14.1MiB
     sdp_Issue_198          1   73.7ms    0.0%  73.7ms   5.40MiB    0.0%  5.40MiB
     sdp_quantum_re...      1   62.7ms    0.0%  62.7ms   3.10MiB    0.0%  3.10MiB
     sdp_quantum_re...      1   7.58ms    0.0%  7.58ms    432KiB    0.0%   432KiB
   affine                   1    41.5s    8.6%   41.5s   3.77GiB    9.9%  3.77GiB
     affine_Partial...      1    4.34s    0.9%   4.34s    516MiB    1.3%   516MiB
     affine_hcat_atom       1    3.19s    0.7%   3.19s    249MiB    0.6%   249MiB
     affine_permute...      1    3.09s    0.6%   3.09s    375MiB    1.0%   375MiB
     affine_dot_mul...      1    2.94s    0.6%   2.94s    174MiB    0.4%   174MiB
     affine_multipl...      1    2.88s    0.6%   2.88s    246MiB    0.6%   246MiB
     affine_vcat_atom       1    2.50s    0.5%   2.50s    231MiB    0.6%   231MiB
     affine_transpo...      1    1.85s    0.4%   1.85s    105MiB    0.3%   105MiB
     affine_add_atom        1    1.67s    0.3%   1.67s   80.1MiB    0.2%  80.1MiB
     affine_Diagona...      1    1.57s    0.3%   1.57s    125MiB    0.3%   125MiB
     affine_satisfy...      1    1.30s    0.3%   1.30s   55.8MiB    0.1%  55.8MiB
     affine_conv_atom       1    1.04s    0.2%   1.04s   49.5MiB    0.1%  49.5MiB
     affine_dot_atom        1    915ms    0.2%   915ms   27.2MiB    0.1%  27.2MiB
     affine_index_atom      1    899ms    0.2%   899ms   44.1MiB    0.1%  44.1MiB
     affine_dualvalue       1    852ms    0.2%   852ms   75.5MiB    0.2%  75.5MiB
     affine_reshape...      1    756ms    0.2%   756ms   31.3MiB    0.1%  31.3MiB
     affine_sum_atom        1    357ms    0.1%   357ms   24.0MiB    0.1%  24.0MiB
     affine_kron_atom       1    267ms    0.1%   267ms   16.3MiB    0.0%  16.3MiB
     affine_single_...      1    234ms    0.0%   234ms   22.6MiB    0.1%  22.6MiB
     affine_diag_atom       1    195ms    0.0%   195ms   16.2MiB    0.0%  16.2MiB
     affine_dot_ato...      1    162ms    0.0%   162ms   6.21MiB    0.0%  6.21MiB
     affine_single_...      1    144ms    0.0%   144ms   17.7MiB    0.0%  17.7MiB
     affine_negate_...      1    108ms    0.0%   108ms   3.88MiB    0.0%  3.88MiB
     affine_trace_atom      1   65.6ms    0.0%  65.6ms   3.43MiB    0.0%  3.43MiB
   socp                     1    26.9s    5.6%   26.9s   2.65GiB    7.0%  2.65GiB
     socp_dual_mini...      1    5.51s    1.1%   5.51s    510MiB    1.3%   510MiB
     socp_quad_form...      1    3.28s    0.7%   3.28s   98.7MiB    0.3%  98.7MiB
     socp_rational_...      1    1.56s    0.3%   1.56s    161MiB    0.4%   161MiB
     socp_inv_pos_atom      1    1.56s    0.3%   1.56s   99.1MiB    0.3%  99.1MiB
     socp_sum_squar...      1    1.43s    0.3%   1.43s    108MiB    0.3%   108MiB
     socp_quad_over...      1    1.02s    0.2%   1.02s   41.1MiB    0.1%  41.1MiB
     socp_norm_cons...      1    953ms    0.2%   953ms   57.3MiB    0.1%  57.3MiB
     socp_dual_norm...      1    953ms    0.2%   953ms   81.0MiB    0.2%  81.0MiB
     socp_rational_...      1    673ms    0.1%   673ms   54.9MiB    0.1%  54.9MiB
     socp_fix_multi...      1    519ms    0.1%   519ms   42.2MiB    0.1%  42.2MiB
     socp_square_atom       1    475ms    0.1%   475ms   27.4MiB    0.1%  27.4MiB
     socp_huber_atom        1    438ms    0.1%   438ms   37.1MiB    0.1%  37.1MiB
     socp_geo_mean_...      1    365ms    0.1%   365ms   25.8MiB    0.1%  25.8MiB
     socp_dual_frob...      1    317ms    0.1%   317ms   37.7MiB    0.1%  37.7MiB
     socp_fix_and_f...      1    294ms    0.1%   294ms   21.0MiB    0.1%  21.0MiB
     socp_rational_...      1    184ms    0.0%   184ms   11.0MiB    0.0%  11.0MiB
     socp_sqrt_atom         1   76.1ms    0.0%  76.1ms   1.29MiB    0.0%  1.29MiB
   constant                 1    11.8s    2.4%   11.8s   0.95GiB    2.5%  0.95GiB
     constant_fix!_...      1    4.32s    0.9%   4.32s    292MiB    0.7%   292MiB
     constant_Issue...      1    3.11s    0.6%   3.11s    250MiB    0.6%   250MiB
     constant_Issue...      1    1.21s    0.3%   1.21s   81.7MiB    0.2%  81.7MiB
     constant_fix!_...      1    839ms    0.2%   839ms   61.5MiB    0.2%  61.5MiB
     constant_Test_...      1    469ms    0.1%   469ms   19.2MiB    0.0%  19.2MiB
     constant_fix!_...      1    369ms    0.1%   369ms   19.2MiB    0.0%  19.2MiB
   exp                      1    9.47s    2.0%   9.47s    913MiB    2.3%   913MiB
     exp_log_atom           1    6.53s    1.4%   6.53s    654MiB    1.7%   654MiB
     exp_entropy_atom       1    537ms    0.1%   537ms   42.1MiB    0.1%  42.1MiB
     exp_log_sum_ex...      1    438ms    0.1%   438ms   32.2MiB    0.1%  32.2MiB
     exp_exp_atom           1    368ms    0.1%   368ms   25.1MiB    0.1%  25.1MiB
     exp_logistic_l...      1    346ms    0.1%   346ms   17.1MiB    0.0%  17.1MiB
     exp_log_perspe...      1    269ms    0.1%   269ms   13.7MiB    0.0%  13.7MiB
     exp_relative_e...      1   73.2ms    0.0%  73.2ms   5.47MiB    0.0%  5.47MiB
   lp                       1    7.33s    1.5%   7.33s    685MiB    1.8%   685MiB
     lp_dotsort_atom        1    1.30s    0.3%   1.30s   91.3MiB    0.2%  91.3MiB
     lp_sumlargest_...      1    700ms    0.1%   700ms   48.1MiB    0.1%  48.1MiB
     lp_min_atom            1    674ms    0.1%   674ms   49.3MiB    0.1%  49.3MiB
     lp_max_atom            1    536ms    0.1%   536ms   44.0MiB    0.1%  44.0MiB
     lp_minimum_atom        1    453ms    0.1%   453ms   40.6MiB    0.1%  40.6MiB
     lp_sumsmallest...      1    437ms    0.1%   437ms   31.5MiB    0.1%  31.5MiB
     lp_dual_abs_atom       1    358ms    0.1%   358ms   21.2MiB    0.1%  21.2MiB
     lp_neg_atom            1    335ms    0.1%   335ms   19.6MiB    0.1%  19.6MiB
     lp_maximum_atom        1    293ms    0.1%   293ms   13.5MiB    0.0%  13.5MiB
     lp_dual_norm_i...      1    125ms    0.0%   125ms   4.29MiB    0.0%  4.29MiB
     lp_pos_atom            1    107ms    0.0%   107ms   9.41MiB    0.0%  9.41MiB
     lp_dual_norm_1...      1   91.3ms    0.0%  91.3ms   4.13MiB    0.0%  4.13MiB
     lp_hinge_loss_...      1    264μs    0.0%   264μs   57.3KiB    0.0%  57.3KiB
   sdp_and_exp              1    5.91s    1.2%   5.91s    504MiB    1.3%   504MiB
     sdp_and_exp_lo...      1    5.75s    1.2%   5.75s    489MiB    1.3%   489MiB
 ────────────────────────────────────────────────────────────────────────────────

```

## Version information
`versioninfo()`:
```julia
Julia Version 1.6.7
Commit 3b76b25b64 (2022-07-19 15:11 UTC)
Platform Info:
  OS: Linux (x86_64-pc-linux-gnu)
  CPU: Intel(R) Xeon(R) CPU E5-2673 v3 @ 2.40GHz
  WORD_SIZE: 64
  LIBM: libopenlibm
  LLVM: libLLVM-11.0.1 (ORCJIT, haswell)
```

Manifest:
```julia
      Status `~/work/ConvexTests.jl/ConvexTests.jl/Hypatia/Manifest.toml`
  [14f7f29c] AMD v0.5.0
  [c3fe647b] AbstractAlgebra v0.22.3
  [1520ce14] AbstractTrees v0.4.2
  [6e4b80f9] BenchmarkTools v1.3.1
  [d360d2e6] ChainRulesCore v1.15.5
  [9e997f8a] ChangesOfVariables v0.1.4
  [523fee87] CodecBzip2 v0.7.2
  [944b1d66] CodecZlib v0.7.0
  [861a8166] Combinatorics v1.0.2
  [bbf7d656] CommonSubexpressions v0.3.0
  [34da2185] Compat v4.2.0
  [25c3070e] ComplexOptInterface v0.1.2
  [f65535da] Convex v0.15.2
  [cb7cb77b] ConvexTests v0.1.0 `~/work/ConvexTests.jl/ConvexTests.jl`
  [da8f5974] Cyclotomics v0.3.2
  [9a962f9c] DataAPI v1.10.0
  [864edb3b] DataStructures v0.18.13
  [e2d170a0] DataValueInterfaces v1.0.0
  [163ba53b] DiffResults v1.0.3
  [b552c78f] DiffRules v1.11.1
  [ffbed154] DocStringExtensions v0.8.6
  [7c1d4256] DynamicPolynomials v0.4.5
  [e2ba6199] ExprTools v0.1.8
  [f6369f11] ForwardDiff v0.10.32
  [14197337] GenericLinearAlgebra v0.3.3
  [d5909c97] GroupsCore v0.4.0
  [b99e6be6] Hypatia v0.7.0
  [18e54dd8] IntegerMathUtils v0.1.0
  [3587e190] InverseFunctions v0.1.7
  [92d709cd] IrrationalConstants v0.1.1
  [42fd0dbc] IterativeSolvers v0.9.2
  [82899510] IteratorInterfaceExtensions v1.0.0
  [692b3bcd] JLLWrappers v1.4.1
  [682c06a0] JSON v0.21.3
  [4076af6c] JuMP v1.3.0
  [40e66cde] LDLFactorizations v0.9.0
  [8ac3fa9e] LRUCache v1.3.0
  [7a12625a] LinearMaps v3.8.0
  [2ab3a3ac] LogExpFunctions v0.3.18
  [1914dd2f] MacroTools v0.5.9
  [b8f27783] MathOptInterface v1.8.1
  [c03570c3] Memoize v0.4.4
  [be282fd4] MultivariateBases v0.1.5
  [f4abf1af] MultivariateMoments v0.3.9
  [102ac46a] MultivariatePolynomials v0.4.6
  [d8a4904e] MutableArithmetics v1.0.4
  [77ba4419] NaNMath v1.0.1
  [bac558e1] OrderedCollections v1.4.1
  [69de0a69] Parsers v2.4.0
  [8bc5a954] PermutationGroups v0.3.2
  [ddf597a6] PolyJuMP v0.6.2
  [3a141323] PolynomialRoots v1.0.0
  [21216c6a] Preferences v1.3.0
  [27ebfcd6] Primes v0.5.3
  [fb686558] RandomExtensions v0.4.3
  [3cdcf5f2] RecipesBase v1.2.1
  [189a3867] Reexport v1.2.2
  [ae029012] Requires v1.3.0
  [af85af4c] RowEchelon v0.2.1
  [8e049039] SemialgebraicSets v0.2.5
  [276daf66] SpecialFunctions v2.1.7
  [0c0c59c1] StarAlgebras v0.1.7
  [90137ffa] StaticArrays v1.5.6
  [1e83bf80] StaticArraysCore v1.3.0
  [4b9e565b] SumOfSquares v0.6.2
  [858aa9a9] SymbolicWedderburn v0.3.0
  [f9bf3ced] TableTestSets v0.1.0 `https://github.com/ericphanson/TableTestSets.jl#master`
  [3783bdb8] TableTraits v1.0.1
  [bd369af6] Tables v1.7.0
  [a759f4b9] TimerOutputs v0.5.21
  [3bb67fe8] TranscodingStreams v0.9.9
  [6e34b625] Bzip2_jll v1.0.8+0
  [efe28fd5] OpenSpecFun_jll v0.5.5+0
  [8e850b90] libblastrampoline_jll v3.1.0+2
  [0dad84c5] ArgTools
  [56f22d72] Artifacts
  [2a0f44e3] Base64
  [ade2ca70] Dates
  [f43a241f] Downloads
  [9fa8497b] Future
  [b77e0a4c] InteractiveUtils
  [b27032c2] LibCURL
  [76f85450] LibGit2
  [8f399da3] Libdl
  [37e2e46d] LinearAlgebra
  [56ddb016] Logging
  [d6f4376e] Markdown
  [a63ad114] Mmap
  [ca575930] NetworkOptions
  [44cfe95a] Pkg
  [de0858da] Printf
  [9abbd945] Profile
  [3fa0cd96] REPL
  [9a3f8284] Random
  [ea8e919c] SHA
  [9e88b42a] Serialization
  [6462fe0b] Sockets
  [2f01184e] SparseArrays
  [10745b16] Statistics
  [4607b0f0] SuiteSparse
  [fa267f1f] TOML
  [a4e569a6] Tar
  [8dfed614] Test
  [cf7118a7] UUIDs
  [4ec0a83e] Unicode
  [e66e0078] CompilerSupportLibraries_jll
  [deac9b47] LibCURL_jll
  [29816b5a] LibSSH2_jll
  [c8ffd9c3] MbedTLS_jll
  [14a3606d] MozillaCACerts_jll
  [05823500] OpenLibm_jll
  [83775a58] Zlib_jll
  [8e850ede] nghttp2_jll
  [3f19e933] p7zip_jll
```
