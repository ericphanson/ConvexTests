Table of contents:

```@contents
Pages = ["Clarabel.md"]
Depth = 4
```


Compilation warmup gives an estimate of 55 seconds of compilation time.

## Clarabel 
These tests were run on September 13, 2022 at 13:07 (UTC).


Excluded problems and classes of problems:
```julia
Regex[r"mip"]
```

### Tests

Tests took 6 minutes, 57 seconds to run (after warmup).

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
<tr><td style="text-align:left;border-right: solid 2px;">Clarabel tests</td>
<td style="text-align:center;color:green;">2345</td>
<td style="text-align:center;color:red;">3</td>
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
<td style="text-align:center;color:green;">1624</td>
<td style="text-align:center;color:red;">3</td>
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
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
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
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;K = 50</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;color:red;">1</td>
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
<td style="text-align:center;color:green;">499</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">499</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">682</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">682</td>
</tr></table>
```

### Errors

```julia
Error in testset K = 30:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

Error in testset K = 45:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.OTHER_RESULT_STATUS == MathOptInterface.FEASIBLE_POINT

Error in testset K = 50:
Test Failed at /home/runner/.julia/packages/SumOfSquares/JDoOM/test/Tests/options_pricing.jl:31
  Expression: JuMP.primal_status(model) == MOI.FEASIBLE_POINT
   Evaluated: MathOptInterface.NEARLY_FEASIBLE_POINT == MathOptInterface.FEASIBLE_POINT

```


### Timing information
```julia
 ────────────────────────────────────────────────────────────────────────────────
                                        Time                    Allocations      
                               ───────────────────────   ────────────────────────
       Tot / % measured:             417s /  99.9%           38.1GiB /  99.9%    

 Section               ncalls     time    %tot     avg     alloc    %tot      avg
 ────────────────────────────────────────────────────────────────────────────────
 Convex                     1     211s   50.7%    211s   20.1GiB   52.7%  20.1GiB
   sdp                      1     139s   33.4%    139s   12.1GiB   31.8%  12.1GiB
     sdp_lieb_ando          1    28.2s    6.8%   28.2s   1.49GiB    3.9%  1.49GiB
     sdp_quantum_re...      1    13.9s    3.4%   13.9s   1.52GiB    4.0%  1.52GiB
     sdp_quantum_re...      1    11.2s    2.7%   11.2s    366MiB    0.9%   366MiB
     sdp_quantum_re...      1    9.86s    2.4%   9.86s    256MiB    0.7%   256MiB
     sdp_quantum_re...      1    8.78s    2.1%   8.78s    248MiB    0.6%   248MiB
     sdp_quantum_re...      1    7.72s    1.9%   7.72s    243MiB    0.6%   243MiB
     sdp_trace_logm...      1    5.01s    1.2%   5.01s   0.98GiB    2.6%  0.98GiB
     sdp_operator_n...      1    3.75s    0.9%   3.75s    308MiB    0.8%   308MiB
     sdp_geom_mean_...      1    2.88s    0.7%   2.88s    119MiB    0.3%   119MiB
     sdp_trace_mpow...      1    2.35s    0.6%   2.35s    493MiB    1.3%   493MiB
     sdp_Partial_trace      1    1.89s    0.5%   1.89s    194MiB    0.5%   194MiB
     sdp_quantum_re...      1    1.84s    0.4%   1.84s   18.3MiB    0.0%  18.3MiB
     sdp_relative_e...      1    1.68s    0.4%   1.68s    190MiB    0.5%   190MiB
     sdp_trace_mpow...      1    1.66s    0.4%   1.66s   28.0MiB    0.1%  28.0MiB
     sdp_quantum_re...      1    1.50s    0.4%   1.50s   13.2MiB    0.0%  13.2MiB
     sdp_sum_larges...      1    1.48s    0.4%   1.48s    117MiB    0.3%   117MiB
     sdp_matrix_fra...      1    1.44s    0.3%   1.44s    130MiB    0.3%   130MiB
     sdp_geom_mean_...      1    1.42s    0.3%   1.42s    197MiB    0.5%   197MiB
     sdp_quantum_ch...      1    1.09s    0.3%   1.09s   68.7MiB    0.2%  68.7MiB
     sdp_geom_mean_...      1    1.04s    0.2%   1.04s    112MiB    0.3%   112MiB
     sdp_dual_lambd...      1    782ms    0.2%   782ms   65.9MiB    0.2%  65.9MiB
     sdp_min_maxeig...      1    754ms    0.2%   754ms   98.4MiB    0.3%  98.4MiB
     sdp_socp_sumsq...      1    748ms    0.2%   748ms   53.3MiB    0.1%  53.3MiB
     sdp_lambda_min...      1    640ms    0.2%   640ms   82.6MiB    0.2%  82.6MiB
     sdp_geom_mean_...      1    634ms    0.2%   634ms   73.1MiB    0.2%  73.1MiB
     sdp_Complex_Va...      1    618ms    0.1%   618ms   35.8MiB    0.1%  35.8MiB
     sdp_trace_mpow...      1    608ms    0.1%   608ms   26.2MiB    0.1%  26.2MiB
     sdp_nuclear_no...      1    598ms    0.1%   598ms   76.6MiB    0.2%  76.6MiB
     sdp_relative_e...      1    529ms    0.1%   529ms   18.0MiB    0.0%  18.0MiB
     sdp_socp_norm2...      1    527ms    0.1%   527ms   46.3MiB    0.1%  46.3MiB
     sdp_geom_mean_...      1    438ms    0.1%   438ms   47.3MiB    0.1%  47.3MiB
     sdp_geom_mean_...      1    411ms    0.1%   411ms   53.0MiB    0.1%  53.0MiB
     sdp_trace_logm...      1    398ms    0.1%   398ms   35.7MiB    0.1%  35.7MiB
     sdp_trace_mpow...      1    394ms    0.1%   394ms   12.4MiB    0.0%  12.4MiB
     sdp_geom_mean_...      1    379ms    0.1%   379ms   70.2MiB    0.2%  70.2MiB
     sdp_Complex_Se...      1    285ms    0.1%   285ms   29.5MiB    0.1%  29.5MiB
     sdp_socp_abs_atom      1    245ms    0.1%   245ms   21.4MiB    0.1%  21.4MiB
     sdp_geom_mean_...      1    239ms    0.1%   239ms   19.7MiB    0.1%  19.7MiB
     sdp_sdp_variables      1    231ms    0.1%   231ms   27.8MiB    0.1%  27.8MiB
     sdp_trace_mpow...      1    219ms    0.1%   219ms   21.5MiB    0.1%  21.5MiB
     sdp_operator_n...      1    206ms    0.0%   206ms   23.5MiB    0.1%  23.5MiB
     sdp_quantum_re...      1    202ms    0.0%   202ms   24.5MiB    0.1%  24.5MiB
     sdp_geom_mean_...      1    201ms    0.0%   201ms   15.9MiB    0.0%  15.9MiB
     sdp_trace_mpow...      1    201ms    0.0%   201ms   16.2MiB    0.0%  16.2MiB
     sdp_trace_mpow...      1    189ms    0.0%   189ms   18.9MiB    0.0%  18.9MiB
     sdp_matrix_fra...      1    178ms    0.0%   178ms   17.4MiB    0.0%  17.4MiB
     sdp_geom_mean_...      1    164ms    0.0%   164ms   21.6MiB    0.1%  21.6MiB
     sdp_nuclear_no...      1    134ms    0.0%   134ms   18.6MiB    0.0%  18.6MiB
     sdp_sigma_max_...      1    127ms    0.0%   127ms   16.6MiB    0.0%  16.6MiB
     sdp_geom_mean_...      1    114ms    0.0%   114ms   20.3MiB    0.1%  20.3MiB
     sdp_quantum_re...      1    112ms    0.0%   112ms   20.5MiB    0.1%  20.5MiB
     sdp_Real_Varia...      1    108ms    0.0%   108ms   5.21MiB    0.0%  5.21MiB
     sdp_geom_mean_...      1    107ms    0.0%   107ms   20.0MiB    0.1%  20.0MiB
     sdp_sdp_constr...      1   94.3ms    0.0%  94.3ms   9.64MiB    0.0%  9.64MiB
     sdp_trace_logm...      1   94.2ms    0.0%  94.2ms   6.75MiB    0.0%  6.75MiB
     sdp_geom_mean_...      1   78.5ms    0.0%  78.5ms   21.3MiB    0.1%  21.3MiB
     sdp_geom_mean_...      1   76.7ms    0.0%  76.7ms   19.1MiB    0.0%  19.1MiB
     sdp_geom_mean_...      1   75.2ms    0.0%  75.2ms   12.0MiB    0.0%  12.0MiB
     sdp_quantum_re...      1   72.7ms    0.0%  72.7ms   15.9MiB    0.0%  15.9MiB
     sdp_geom_mean_...      1   67.5ms    0.0%  67.5ms   18.9MiB    0.0%  18.9MiB
     sdp_kron_atom          1   60.2ms    0.0%  60.2ms   10.9MiB    0.0%  10.9MiB
     sdp_Issue_198          1   59.7ms    0.0%  59.7ms   5.35MiB    0.0%  5.35MiB
     sdp_geom_mean_...      1   57.4ms    0.0%  57.4ms   14.3MiB    0.0%  14.3MiB
     sdp_quantum_re...      1   57.4ms    0.0%  57.4ms   3.02MiB    0.0%  3.02MiB
     sdp_quantum_re...      1   7.14ms    0.0%  7.14ms    349KiB    0.0%   349KiB
   affine                   1    31.6s    7.6%   31.6s   3.47GiB    9.1%  3.47GiB
     affine_Partial...      1    3.00s    0.7%   3.00s    347MiB    0.9%   347MiB
     affine_hcat_atom       1    2.49s    0.6%   2.49s    237MiB    0.6%   237MiB
     affine_dot_mul...      1    2.47s    0.6%   2.47s    174MiB    0.4%   174MiB
     affine_permute...      1    2.36s    0.6%   2.36s    378MiB    1.0%   378MiB
     affine_multipl...      1    2.28s    0.5%   2.28s    243MiB    0.6%   243MiB
     affine_vcat_atom       1    1.86s    0.4%   1.86s    206MiB    0.5%   206MiB
     affine_transpo...      1    1.43s    0.3%   1.43s   95.2MiB    0.2%  95.2MiB
     affine_add_atom        1    1.21s    0.3%   1.21s   79.5MiB    0.2%  79.5MiB
     affine_Diagona...      1    1.14s    0.3%   1.14s    114MiB    0.3%   114MiB
     affine_satisfy...      1    1.07s    0.3%   1.07s   55.0MiB    0.1%  55.0MiB
     affine_conv_atom       1    876ms    0.2%   876ms   48.8MiB    0.1%  48.8MiB
     affine_index_atom      1    769ms    0.2%   769ms   43.3MiB    0.1%  43.3MiB
     affine_dot_atom        1    691ms    0.2%   691ms   15.1MiB    0.0%  15.1MiB
     affine_dualvalue       1    648ms    0.2%   648ms   75.1MiB    0.2%  75.1MiB
     affine_reshape...      1    602ms    0.1%   602ms   30.5MiB    0.1%  30.5MiB
     affine_sum_atom        1    288ms    0.1%   288ms   23.3MiB    0.1%  23.3MiB
     affine_kron_atom       1    230ms    0.1%   230ms   16.3MiB    0.0%  16.3MiB
     affine_single_...      1    201ms    0.0%   201ms   21.9MiB    0.1%  21.9MiB
     affine_diag_atom       1    133ms    0.0%   133ms   15.7MiB    0.0%  15.7MiB
     affine_dot_ato...      1    132ms    0.0%   132ms   5.99MiB    0.0%  5.99MiB
     affine_single_...      1    113ms    0.0%   113ms   17.5MiB    0.0%  17.5MiB
     affine_negate_...      1   90.8ms    0.0%  90.8ms   3.72MiB    0.0%  3.72MiB
     affine_trace_atom      1   55.8ms    0.0%  55.8ms   3.27MiB    0.0%  3.27MiB
   socp                     1    18.4s    4.4%   18.4s   2.19GiB    5.7%  2.19GiB
     socp_quad_form...      1    2.72s    0.7%   2.72s   98.1MiB    0.3%  98.1MiB
     socp_dual_mini...      1    2.24s    0.5%   2.24s    161MiB    0.4%   161MiB
     socp_sum_squar...      1    1.18s    0.3%   1.18s    106MiB    0.3%   106MiB
     socp_rational_...      1    1.16s    0.3%   1.16s    135MiB    0.3%   135MiB
     socp_inv_pos_atom      1    954ms    0.2%   954ms   81.9MiB    0.2%  81.9MiB
     socp_quad_over...      1    806ms    0.2%   806ms   40.7MiB    0.1%  40.7MiB
     socp_dual_norm...      1    762ms    0.2%   762ms   79.2MiB    0.2%  79.2MiB
     socp_norm_cons...      1    662ms    0.2%   662ms   57.2MiB    0.1%  57.2MiB
     socp_rational_...      1    611ms    0.1%   611ms   53.8MiB    0.1%  53.8MiB
     socp_square_atom       1    434ms    0.1%   434ms   25.8MiB    0.1%  25.8MiB
     socp_fix_multi...      1    417ms    0.1%   417ms   41.2MiB    0.1%  41.2MiB
     socp_huber_atom        1    373ms    0.1%   373ms   36.6MiB    0.1%  36.6MiB
     socp_geo_mean_...      1    330ms    0.1%   330ms   25.1MiB    0.1%  25.1MiB
     socp_fix_and_f...      1    264ms    0.1%   264ms   20.4MiB    0.1%  20.4MiB
     socp_dual_frob...      1    246ms    0.1%   246ms   37.1MiB    0.1%  37.1MiB
     socp_rational_...      1    152ms    0.0%   152ms   9.29MiB    0.0%  9.29MiB
     socp_sqrt_atom         1   98.0ms    0.0%  98.0ms   1.29MiB    0.0%  1.29MiB
   constant                 1    8.88s    2.1%   8.88s    892MiB    2.3%   892MiB
     constant_fix!_...      1    3.40s    0.8%   3.40s    281MiB    0.7%   281MiB
     constant_Issue...      1    2.01s    0.5%   2.01s    172MiB    0.4%   172MiB
     constant_Issue...      1    1.00s    0.2%   1.00s   86.4MiB    0.2%  86.4MiB
     constant_fix!_...      1    652ms    0.2%   652ms   60.7MiB    0.2%  60.7MiB
     constant_Test_...      1    346ms    0.1%   346ms   18.5MiB    0.0%  18.5MiB
     constant_fix!_...      1    306ms    0.1%   306ms   19.9MiB    0.1%  19.9MiB
   lp                       1    5.37s    1.3%   5.37s    641MiB    1.6%   641MiB
     lp_dotsort_atom        1    870ms    0.2%   870ms   75.9MiB    0.2%  75.9MiB
     lp_sumlargest_...      1    561ms    0.1%   561ms   47.5MiB    0.1%  47.5MiB
     lp_min_atom            1    473ms    0.1%   473ms   37.9MiB    0.1%  37.9MiB
     lp_sumsmallest...      1    383ms    0.1%   383ms   30.5MiB    0.1%  30.5MiB
     lp_max_atom            1    373ms    0.1%   373ms   32.4MiB    0.1%  32.4MiB
     lp_minimum_atom        1    354ms    0.1%   354ms   39.4MiB    0.1%  39.4MiB
     lp_dual_abs_atom       1    283ms    0.1%   283ms   20.6MiB    0.1%  20.6MiB
     lp_neg_atom            1    237ms    0.1%   237ms   19.3MiB    0.0%  19.3MiB
     lp_maximum_atom        1    191ms    0.0%   191ms   13.2MiB    0.0%  13.2MiB
     lp_dual_norm_i...      1   94.6ms    0.0%  94.6ms   3.95MiB    0.0%  3.95MiB
     lp_pos_atom            1   80.7ms    0.0%  80.7ms   9.07MiB    0.0%  9.07MiB
     lp_dual_norm_1...      1   67.6ms    0.0%  67.6ms   3.86MiB    0.0%  3.86MiB
     lp_hinge_loss_...      1    219μs    0.0%   219μs   57.3KiB    0.0%  57.3KiB
   exp                      1    4.30s    1.0%   4.30s    427MiB    1.1%   427MiB
     exp_log_atom           1    1.95s    0.5%   1.95s    172MiB    0.4%   172MiB
     exp_entropy_atom       1    435ms    0.1%   435ms   41.6MiB    0.1%  41.6MiB
     exp_log_sum_ex...      1    354ms    0.1%   354ms   31.8MiB    0.1%  31.8MiB
     exp_exp_atom           1    292ms    0.1%   292ms   23.2MiB    0.1%  23.2MiB
     exp_logistic_l...      1    284ms    0.1%   284ms   16.2MiB    0.0%  16.2MiB
     exp_log_perspe...      1    218ms    0.1%   218ms   13.3MiB    0.0%  13.3MiB
     exp_relative_e...      1   57.8ms    0.0%  57.8ms   5.15MiB    0.0%  5.15MiB
   sdp_and_exp              1    3.31s    0.8%   3.31s    364MiB    0.9%   364MiB
     sdp_and_exp_lo...      1    3.23s    0.8%   3.23s    349MiB    0.9%   349MiB
 SumOfSquares               1     205s   49.3%    205s   18.0GiB   47.3%  18.0GiB
   sdp                      1    84.7s   20.4%   84.7s   7.30GiB   19.2%  7.30GiB
     sosdemo5_infea...      1    6.71s    1.6%   6.71s    529MiB    1.4%   529MiB
     quartic_ideal_rem      1    6.06s    1.5%   6.06s    560MiB    1.4%   560MiB
     rearrangement          1    5.77s    1.4%   5.77s    445MiB    1.1%   445MiB
     sos_concave_th...      1    4.30s    1.0%   4.30s    482MiB    1.2%   482MiB
     sos_horn               1    4.28s    1.0%   4.28s    305MiB    0.8%   305MiB
     simple_matrix          1    3.81s    0.9%   3.81s    383MiB    1.0%   383MiB
     sos_scaled_biv...      1    3.47s    0.8%   3.47s    229MiB    0.6%   229MiB
     quartic_ideal          1    3.41s    0.8%   3.41s    222MiB    0.6%   222MiB
     chebyshev              1    3.32s    0.8%   3.32s    270MiB    0.7%   270MiB
     sos_term_fixed         1    3.31s    0.8%   3.31s    216MiB    0.6%   216MiB
     quartic_ideal_4        1    3.20s    0.8%   3.20s    247MiB    0.6%   247MiB
     sos_cheby_univ...      1    3.01s    0.7%   3.01s    204MiB    0.5%   204MiB
     maxcut                 1    2.78s    0.7%   2.78s    187MiB    0.5%   187MiB
     sos_term               1    2.78s    0.7%   2.78s    185MiB    0.5%   185MiB
     quartic_ideal_...      1    2.58s    0.6%   2.58s    177MiB    0.5%   177MiB
     sos_quartic_co...      1    2.51s    0.6%   2.51s    171MiB    0.4%   171MiB
     sos_options_pr...      1    2.47s    0.6%   2.47s    207MiB    0.5%   207MiB
     quartic_feasib...      1    2.38s    0.6%   2.38s    117MiB    0.3%   117MiB
     BPT12e399_rem          1    2.37s    0.6%   2.37s   80.2MiB    0.2%  80.2MiB
     sosdemo5_feasible      1    1.46s    0.4%   1.46s   84.6MiB    0.2%  84.6MiB
     sosdemo10              1    1.45s    0.3%   1.45s    183MiB    0.5%   183MiB
     sos_univariate...      1    1.37s    0.3%   1.37s    110MiB    0.3%   110MiB
     sos_univariate...      1    725ms    0.2%   725ms   35.9MiB    0.1%  35.9MiB
     sosdemo9               1    645ms    0.2%   645ms   50.2MiB    0.1%  50.2MiB
     quadratic_feas...      1    603ms    0.1%   603ms   50.2MiB    0.1%  50.2MiB
     quadratic_infe...      1    493ms    0.1%   493ms   38.3MiB    0.1%  38.3MiB
     choi                   1    451ms    0.1%   451ms   64.2MiB    0.2%  64.2MiB
     BPT12e399_maxd...      1    299ms    0.1%   299ms   9.60MiB    0.0%  9.60MiB
     sos_quartic_co...      1    121ms    0.0%   121ms   22.0MiB    0.1%  22.0MiB
     motzkin                1   78.7ms    0.0%  78.7ms   4.98MiB    0.0%  4.98MiB
     quartic_ideal_...      1   16.5ms    0.0%  16.5ms   1.06MiB    0.0%  1.06MiB
     quartic_infeas...      1   16.0ms    0.0%  16.0ms   1.66MiB    0.0%  1.66MiB
     sos_scaled_uni...      1   10.5ms    0.0%  10.5ms    402KiB    0.0%   402KiB
     sos_bivariate_...      1   9.94ms    0.0%  9.94ms    404KiB    0.0%   404KiB
     quartic_infeas...      1   4.36ms    0.0%  4.36ms    953KiB    0.0%   953KiB
     quartic_feasib...      1   4.30ms    0.0%  4.30ms    851KiB    0.0%   851KiB
     quadratic_infe...      1   3.80ms    0.0%  3.80ms    626KiB    0.0%   626KiB
     quadratic_feas...      1   3.71ms    0.0%  3.71ms    513KiB    0.0%   513KiB
   socp                     1    82.6s   19.9%   82.6s   7.59GiB   19.9%  7.59GiB
     sdsos_term_fixed       1    19.8s    4.8%   19.8s   1.77GiB    4.6%  1.77GiB
     sdsos_horn             1    11.7s    2.8%   11.7s   0.93GiB    2.5%  0.93GiB
     sdsos_concave_...      1    9.44s    2.3%   9.44s    825MiB    2.1%   825MiB
     sdsos_univaria...      1    9.16s    2.2%   9.16s    804MiB    2.1%   804MiB
     sdsos_cheby_un...      1    5.86s    1.4%   5.86s    451MiB    1.2%   451MiB
     sdsos_univaria...      1    5.00s    1.2%   5.00s    385MiB    1.0%   385MiB
     sdsos_options_...      1    4.26s    1.0%   4.26s    333MiB    0.9%   333MiB
     sdsos_scaled_u...      1    3.74s    0.9%   3.74s    292MiB    0.7%   292MiB
     sdsos_term             1    3.38s    0.8%   3.38s    256MiB    0.7%   256MiB
     sdsos_quartic_...      1    3.17s    0.8%   3.17s    249MiB    0.6%   249MiB
     sdsos_quartic_...      1    577ms    0.1%   577ms   27.1MiB    0.1%  27.1MiB
     sdsos_scaled_b...      1   72.1ms    0.0%  72.1ms   5.77MiB    0.0%  5.77MiB
     sdsos_bivariat...      1   10.7ms    0.0%  10.7ms    406KiB    0.0%   406KiB
   lp                       1    37.7s    9.1%   37.7s   3.14GiB    8.2%  3.14GiB
     dsos_options_p...      1    5.50s    1.3%   5.50s    462MiB    1.2%   462MiB
     dsos_concave_t...      1    5.12s    1.2%   5.12s    505MiB    1.3%   505MiB
     dsos_univariat...      1    4.10s    1.0%   4.10s    268MiB    0.7%   268MiB
     dsos_cheby_biv...      1    3.93s    0.9%   3.93s    284MiB    0.7%   284MiB
     dsos_term_fixed        1    3.45s    0.8%   3.45s    226MiB    0.6%   226MiB
     dsos_horn              1    3.22s    0.8%   3.22s    254MiB    0.7%   254MiB
     dsos_scaled_bi...      1    3.08s    0.7%   3.08s    219MiB    0.6%   219MiB
     dsos_term              1    2.96s    0.7%   2.96s    196MiB    0.5%   196MiB
     dsos_quartic_c...      1    2.56s    0.6%   2.56s    181MiB    0.5%   181MiB
     dsos_bivariate...      1    914ms    0.2%   914ms   39.2MiB    0.1%  39.2MiB
     dsos_quartic_c...      1    159ms    0.0%   159ms   21.7MiB    0.1%  21.7MiB
     dsos_univariat...      1   8.43ms    0.0%  8.43ms    371KiB    0.0%   371KiB
     dsos_cheby_uni...      1   7.34ms    0.0%  7.34ms    397KiB    0.0%   397KiB
     dsos_scaled_un...      1   7.06ms    0.0%  7.06ms    372KiB    0.0%   372KiB
 ────────────────────────────────────────────────────────────────────────────────

```

## Version information
`versioninfo()`:
```julia
Julia Version 1.6.7
Commit 3b76b25b64 (2022-07-19 15:11 UTC)
Platform Info:
  OS: Linux (x86_64-pc-linux-gnu)
  CPU: Intel(R) Xeon(R) Platinum 8370C CPU @ 2.80GHz
  WORD_SIZE: 64
  LIBM: libopenlibm
  LLVM: libLLVM-11.0.1 (ORCJIT, icelake-server)
```

Manifest:
```julia
      Status `~/work/ConvexTests.jl/ConvexTests.jl/Clarabel/Manifest.toml`
  [14f7f29c] AMD v0.5.0
  [c3fe647b] AbstractAlgebra v0.22.3
  [1520ce14] AbstractTrees v0.4.2
  [6e4b80f9] BenchmarkTools v1.3.1
  [d360d2e6] ChainRulesCore v1.15.5
  [9e997f8a] ChangesOfVariables v0.1.4
  [61c947e1] Clarabel v0.3.0
  [523fee87] CodecBzip2 v0.7.2
  [944b1d66] CodecZlib v0.7.0
  [861a8166] Combinatorics v1.0.2
  [bbf7d656] CommonSubexpressions v0.3.0
  [34da2185] Compat v4.2.0
  [25c3070e] ComplexOptInterface v0.1.2
  [f65535da] Convex v0.15.2
  [cb7cb77b] ConvexTests v0.1.0 `~/work/ConvexTests.jl/ConvexTests.jl`
  [a8cc5b0e] Crayons v4.1.1
  [da8f5974] Cyclotomics v0.3.2
  [9a962f9c] DataAPI v1.10.0
  [a93c6f00] DataFrames v1.3.5
  [864edb3b] DataStructures v0.18.13
  [e2d170a0] DataValueInterfaces v1.0.0
  [163ba53b] DiffResults v1.0.3
  [b552c78f] DiffRules v1.11.1
  [ffbed154] DocStringExtensions v0.9.1
  [7c1d4256] DynamicPolynomials v0.4.5
  [e2ba6199] ExprTools v0.1.8
  [59287772] Formatting v0.4.2
  [f6369f11] ForwardDiff v0.10.32
  [d5909c97] GroupsCore v0.4.0
  [18e54dd8] IntegerMathUtils v0.1.0
  [3587e190] InverseFunctions v0.1.7
  [41ab1584] InvertedIndices v1.1.0
  [92d709cd] IrrationalConstants v0.1.1
  [82899510] IteratorInterfaceExtensions v1.0.0
  [692b3bcd] JLLWrappers v1.4.1
  [682c06a0] JSON v0.21.3
  [4076af6c] JuMP v1.3.0
  [40e66cde] LDLFactorizations v0.9.0
  [8ac3fa9e] LRUCache v1.3.0
  [2ab3a3ac] LogExpFunctions v0.3.18
  [1914dd2f] MacroTools v0.5.9
  [b8f27783] MathOptInterface v1.8.1
  [c03570c3] Memoize v0.4.4
  [e1d29d7a] Missings v1.0.2
  [be282fd4] MultivariateBases v0.1.5
  [f4abf1af] MultivariateMoments v0.3.9
  [102ac46a] MultivariatePolynomials v0.4.6
  [d8a4904e] MutableArithmetics v1.0.4
  [77ba4419] NaNMath v1.0.1
  [bac558e1] OrderedCollections v1.4.1
  [46dd5b70] Pardiso v0.5.4
  [69de0a69] Parsers v2.4.0
  [8bc5a954] PermutationGroups v0.3.2
  [ddf597a6] PolyJuMP v0.6.2
  [2dfb63ee] PooledArrays v1.4.2
  [21216c6a] Preferences v1.3.0
  [08abe8d2] PrettyTables v1.3.1
  [27ebfcd6] Primes v0.5.3
  [bfc457fd] QDLDL v0.3.0
  [fb686558] RandomExtensions v0.4.3
  [189a3867] Reexport v1.2.2
  [af85af4c] RowEchelon v0.2.1
  [8e049039] SemialgebraicSets v0.2.5
  [a2af1166] SortingAlgorithms v1.0.1
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
  [1d5cc7b8] IntelOpenMP_jll v2018.0.3+2
  [856f044c] MKL_jll v2022.1.0+0
  [efe28fd5] OpenSpecFun_jll v0.5.5+0
  [0dad84c5] ArgTools
  [56f22d72] Artifacts
  [2a0f44e3] Base64
  [ade2ca70] Dates
  [f43a241f] Downloads
  [9fa8497b] Future
  [b77e0a4c] InteractiveUtils
  [4af54fe1] LazyArtifacts
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
