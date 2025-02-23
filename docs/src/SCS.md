Table of contents:

```@contents
Pages = ["SCS.md"]
Depth = 4
```


Compilation warmup gives an estimate of 40 seconds of compilation time.

## SCS 
These tests were run on September 13, 2022 at 13:16 (UTC).

Tests run with `eps=1e-6`.

Excluded problems and classes of problems:
```julia
Regex[r"mip"]
```

### Tests

Tests took 16 minutes, 3 seconds to run (after warmup).

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
<tr><td style="text-align:left;border-right: solid 2px;">SCS tests</td>
<td style="text-align:center;color:green;">2347</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2348</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;Convex</td>
<td style="text-align:center;color:green;">720</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">721</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;constant</td>
<td style="text-align:center;color:green;">28</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">28</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;affine</td>
<td style="text-align:center;color:green;">141</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">141</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;exp</td>
<td style="text-align:center;color:green;">27</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">27</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;socp</td>
<td style="text-align:center;color:green;">101</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">101</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;lp</td>
<td style="text-align:center;color:green;">65</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">65</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp_and_exp</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;sdp</td>
<td style="text-align:center;color:green;">355</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">356</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy4_lowrank</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_relative_entropy</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_min_maxeig_canon_lmi</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_real_1</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_fullhyp</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_cplx_3_8</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_cplx_5_4</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_operator_norm_atom_complex</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_logm_cplx</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Partial_trace</td>
<td style="text-align:center;color:green;">9</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">9</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_real_0</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_real_neg1_optB</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sigma_max_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy3_lowrank</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy3_fullrank</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy_const</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_real_2_3</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy5_lowrank</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_logm_real</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_relative_entropy_argcheck</td>
<td style="text-align:center;color:green;">21</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">21</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Complex_Variable_with_complex_equality_constraints</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sum_largest_eigs</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_cplx_3_5</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_real_1_2</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_argcheck</td>
<td style="text-align:center;color:green;">11</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">11</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_argcheck</td>
<td style="text-align:center;color:green;">7</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">7</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_variables</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_nuclear_norm_atom_complex</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_real_8_5_optA</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_lieb_ando</td>
<td style="text-align:center;color:green;">79</td>
<td style="text-align:center;color:red;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">80</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_matrix_frac_atom_both_arguments_variable</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy2_lowrank</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_kron_atom</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_nuclear_norm_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Issue_198</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_channel_capacity</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_real_neg1_4</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_real_neg3_5_optB</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_lambda_min_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_real_neg3_5_optA</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_real_3_5</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy5_fullrank</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy1_lowrank</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Real_Variables_with_complex_equality_constraints</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_dual_lambda_max_atom</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_norm2_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_real_8_5_optB</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy2_fullrank</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_abs_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_socp_sumsquares_atom</td>
<td style="text-align:center;color:green;">4</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">4</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy_argcheck</td>
<td style="text-align:center;color:green;">16</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">16</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_operator_norm_atom</td>
<td style="text-align:center;color:green;">3</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">3</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_Complex_Semidefinite_constraint</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_logm_argcheck</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_cplx_1_2</td>
<td style="text-align:center;color:green;">2</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">2</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_real_5_4</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy1_fullrank</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_quantum_relative_entropy4_fullrank</td>
<td style="text-align:center;color:green;">6</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">6</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_cplx_neg1_4</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_sdp_constraints</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_argcheck</td>
<td style="text-align:center;color:green;">12</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">12</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_trace_mpower_cplx_2_3</td>
<td style="text-align:center;color:green;">5</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">5</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_hypocone_real_3_8</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;&nbsp;sdp_geom_mean_epicone_real_neg1_optA</td>
<td style="text-align:center;color:green;">1</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1</td>
</tr><tr><td style="text-align:left;border-right: solid 2px;">&nbsp;&nbsp;SumOfSquares</td>
<td style="text-align:center;color:green;">1627</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;">0</td>
<td style="text-align:center;color:blue;">1627</td>
</tr></table>
```

### Errors

```julia
Error in testset sdp_lieb_ando:
Test Failed at /home/runner/.julia/packages/Convex/ukggP/src/problem_depot/problems/sdp.jl:2219
  Expression: ≈(p.optval, QtAB, atol = atol * 5, rtol = rtol)
   Evaluated: 2.2741227803366564 ≈ 2.286531843364841 (atol=0.005, rtol=0.0)

```


### Timing information
```julia
 ────────────────────────────────────────────────────────────────────────────────
                                        Time                    Allocations      
                               ───────────────────────   ────────────────────────
       Tot / % measured:             963s /  99.9%           36.4GiB /  99.9%    

 Section               ncalls     time    %tot     avg     alloc    %tot      avg
 ────────────────────────────────────────────────────────────────────────────────
 Convex                     1     744s   77.3%    744s   18.2GiB   50.1%  18.2GiB
   sdp                      1     670s   69.7%    670s   10.0GiB   27.4%  10.0GiB
     sdp_lieb_ando          1     425s   44.2%    425s    507MiB    1.4%   507MiB
     sdp_quantum_re...      1    84.1s    8.7%   84.1s   17.2MiB    0.0%  17.2MiB
     sdp_quantum_re...      1    59.4s    6.2%   59.4s   17.2MiB    0.0%  17.2MiB
     sdp_quantum_re...      1    13.9s    1.4%   13.9s   1.52GiB    4.2%  1.52GiB
     sdp_quantum_re...      1    12.7s    1.3%   12.7s    126MiB    0.3%   126MiB
     sdp_quantum_re...      1    6.52s    0.7%   6.52s   11.0MiB    0.0%  11.0MiB
     sdp_trace_logm...      1    5.25s    0.5%   5.25s   0.97GiB    2.7%  0.97GiB
     sdp_quantum_re...      1    4.70s    0.5%   4.70s   17.2MiB    0.0%  17.2MiB
     sdp_trace_mpow...      1    3.94s    0.4%   3.94s   25.6MiB    0.1%  25.6MiB
     sdp_operator_n...      1    3.82s    0.4%   3.82s    307MiB    0.8%   307MiB
     sdp_trace_mpow...      1    2.81s    0.3%   2.81s    482MiB    1.3%   482MiB
     sdp_geom_mean_...      1    2.79s    0.3%   2.79s    104MiB    0.3%   104MiB
     sdp_Partial_trace      1    1.89s    0.2%   1.89s    195MiB    0.5%   195MiB
     sdp_quantum_re...      1    1.63s    0.2%   1.63s   18.4MiB    0.0%  18.4MiB
     sdp_relative_e...      1    1.56s    0.2%   1.56s    156MiB    0.4%   156MiB
     sdp_quantum_re...      1    1.46s    0.2%   1.46s   13.2MiB    0.0%  13.2MiB
     sdp_sum_larges...      1    1.45s    0.2%   1.45s    113MiB    0.3%   113MiB
     sdp_matrix_fra...      1    1.42s    0.1%   1.42s    130MiB    0.3%   130MiB
     sdp_geom_mean_...      1    1.42s    0.1%   1.42s    196MiB    0.5%   196MiB
     sdp_quantum_ch...      1    1.34s    0.1%   1.34s   47.7MiB    0.1%  47.7MiB
     sdp_geom_mean_...      1    989ms    0.1%   989ms    109MiB    0.3%   109MiB
     sdp_dual_lambd...      1    766ms    0.1%   766ms   65.1MiB    0.2%  65.1MiB
     sdp_min_maxeig...      1    760ms    0.1%   760ms   98.4MiB    0.3%  98.4MiB
     sdp_trace_mpow...      1    682ms    0.1%   682ms   18.2MiB    0.0%  18.2MiB
     sdp_lambda_min...      1    671ms    0.1%   671ms   82.4MiB    0.2%  82.4MiB
     sdp_geom_mean_...      1    650ms    0.1%   650ms   72.0MiB    0.2%  72.0MiB
     sdp_Complex_Va...      1    614ms    0.1%   614ms   35.7MiB    0.1%  35.7MiB
     sdp_geom_mean_...      1    613ms    0.1%   613ms   49.0MiB    0.1%  49.0MiB
     sdp_quantum_re...      1    585ms    0.1%   585ms   3.78MiB    0.0%  3.78MiB
     sdp_nuclear_no...      1    584ms    0.1%   584ms   74.1MiB    0.2%  74.1MiB
     sdp_relative_e...      1    575ms    0.1%   575ms   18.0MiB    0.0%  18.0MiB
     sdp_socp_sumsq...      1    509ms    0.1%   509ms   53.2MiB    0.1%  53.2MiB
     sdp_trace_logm...      1    496ms    0.1%   496ms   31.6MiB    0.1%  31.6MiB
     sdp_socp_norm2...      1    425ms    0.0%   425ms   46.3MiB    0.1%  46.3MiB
     sdp_geom_mean_...      1    396ms    0.0%   396ms   69.1MiB    0.2%  69.1MiB
     sdp_trace_mpow...      1    379ms    0.0%   379ms   12.4MiB    0.0%  12.4MiB
     sdp_trace_mpow...      1    355ms    0.0%   355ms   13.0MiB    0.0%  13.0MiB
     sdp_geom_mean_...      1    320ms    0.0%   320ms   16.3MiB    0.0%  16.3MiB
     sdp_geom_mean_...      1    315ms    0.0%   315ms   25.0MiB    0.1%  25.0MiB
     sdp_trace_mpow...      1    291ms    0.0%   291ms   16.1MiB    0.0%  16.1MiB
     sdp_socp_abs_atom      1    284ms    0.0%   284ms   21.4MiB    0.1%  21.4MiB
     sdp_sdp_variables      1    284ms    0.0%   284ms   27.3MiB    0.1%  27.3MiB
     sdp_sdp_constr...      1    279ms    0.0%   279ms   9.13MiB    0.0%  9.13MiB
     sdp_geom_mean_...      1    246ms    0.0%   246ms   15.9MiB    0.0%  15.9MiB
     sdp_geom_mean_...      1    241ms    0.0%   241ms   19.7MiB    0.1%  19.7MiB
     sdp_Complex_Se...      1    235ms    0.0%   235ms   21.1MiB    0.1%  21.1MiB
     sdp_trace_mpow...      1    205ms    0.0%   205ms   16.0MiB    0.0%  16.0MiB
     sdp_operator_n...      1    180ms    0.0%   180ms   22.7MiB    0.1%  22.7MiB
     sdp_matrix_fra...      1    174ms    0.0%   174ms   17.4MiB    0.0%  17.4MiB
     sdp_geom_mean_...      1    169ms    0.0%   169ms   16.6MiB    0.0%  16.6MiB
     sdp_nuclear_no...      1    135ms    0.0%   135ms   18.0MiB    0.0%  18.0MiB
     sdp_sigma_max_...      1    132ms    0.0%   132ms   16.1MiB    0.0%  16.1MiB
     sdp_geom_mean_...      1    116ms    0.0%   116ms   15.3MiB    0.0%  15.3MiB
     sdp_geom_mean_...      1    112ms    0.0%   112ms   15.4MiB    0.0%  15.4MiB
     sdp_geom_mean_...      1    109ms    0.0%   109ms   16.0MiB    0.0%  16.0MiB
     sdp_Real_Varia...      1    106ms    0.0%   106ms   5.11MiB    0.0%  5.11MiB
     sdp_quantum_re...      1    103ms    0.0%   103ms   3.69MiB    0.0%  3.69MiB
     sdp_Issue_198          1    103ms    0.0%   103ms   5.22MiB    0.0%  5.22MiB
     sdp_geom_mean_...      1    102ms    0.0%   102ms   15.8MiB    0.0%  15.8MiB
     sdp_trace_logm...      1   93.2ms    0.0%  93.2ms   6.75MiB    0.0%  6.75MiB
     sdp_geom_mean_...      1   78.5ms    0.0%  78.5ms   11.4MiB    0.0%  11.4MiB
     sdp_geom_mean_...      1   68.7ms    0.0%  68.7ms   12.9MiB    0.0%  12.9MiB
     sdp_kron_atom          1   59.1ms    0.0%  59.1ms   10.8MiB    0.0%  10.8MiB
     sdp_quantum_re...      1   55.3ms    0.0%  55.3ms   2.99MiB    0.0%  2.99MiB
     sdp_quantum_re...      1   6.72ms    0.0%  6.72ms    318KiB    0.0%   318KiB
   affine                   1    31.1s    3.2%   31.1s   3.52GiB    9.7%  3.52GiB
     affine_Partial...      1    2.89s    0.3%   2.89s    344MiB    0.9%   344MiB
     affine_hcat_atom       1    2.43s    0.3%   2.43s    238MiB    0.6%   238MiB
     affine_dot_mul...      1    2.39s    0.2%   2.39s    176MiB    0.5%   176MiB
     affine_permute...      1    2.33s    0.2%   2.33s    378MiB    1.0%   378MiB
     affine_multipl...      1    2.21s    0.2%   2.21s    245MiB    0.7%   245MiB
     affine_vcat_atom       1    1.86s    0.2%   1.86s    207MiB    0.6%   207MiB
     affine_transpo...      1    1.48s    0.2%   1.48s    111MiB    0.3%   111MiB
     affine_add_atom        1    1.20s    0.1%   1.20s   79.6MiB    0.2%  79.6MiB
     affine_Diagona...      1    1.08s    0.1%   1.08s    116MiB    0.3%   116MiB
     affine_satisfy...      1    1.04s    0.1%   1.04s   55.0MiB    0.1%  55.0MiB
     affine_conv_atom       1    795ms    0.1%   795ms   48.8MiB    0.1%  48.8MiB
     affine_dot_atom        1    734ms    0.1%   734ms   27.6MiB    0.1%  27.6MiB
     affine_index_atom      1    682ms    0.1%   682ms   43.2MiB    0.1%  43.2MiB
     affine_dualvalue       1    653ms    0.1%   653ms   75.0MiB    0.2%  75.0MiB
     affine_reshape...      1    587ms    0.1%   587ms   30.4MiB    0.1%  30.4MiB
     affine_sum_atom        1    290ms    0.0%   290ms   23.2MiB    0.1%  23.2MiB
     affine_single_...      1    227ms    0.0%   227ms   21.9MiB    0.1%  21.9MiB
     affine_kron_atom       1    206ms    0.0%   206ms   16.3MiB    0.0%  16.3MiB
     affine_diag_atom       1    127ms    0.0%   127ms   15.7MiB    0.0%  15.7MiB
     affine_dot_ato...      1    127ms    0.0%   127ms   5.96MiB    0.0%  5.96MiB
     affine_single_...      1    114ms    0.0%   114ms   17.4MiB    0.0%  17.4MiB
     affine_negate_...      1   86.5ms    0.0%  86.5ms   3.70MiB    0.0%  3.70MiB
     affine_trace_atom      1   53.4ms    0.0%  53.4ms   3.24MiB    0.0%  3.24MiB
   socp                     1    19.3s    2.0%   19.3s   2.23GiB    6.1%  2.23GiB
     socp_quad_form...      1    2.75s    0.3%   2.75s   98.1MiB    0.3%  98.1MiB
     socp_dual_mini...      1    2.23s    0.2%   2.23s    163MiB    0.4%   163MiB
     socp_rational_...      1    1.16s    0.1%   1.16s    132MiB    0.4%   132MiB
     socp_sum_squar...      1    1.12s    0.1%   1.12s    107MiB    0.3%   107MiB
     socp_inv_pos_atom      1    976ms    0.1%   976ms   84.2MiB    0.2%  84.2MiB
     socp_quad_over...      1    763ms    0.1%   763ms   40.7MiB    0.1%  40.7MiB
     socp_dual_norm...      1    753ms    0.1%   753ms   79.0MiB    0.2%  79.0MiB
     socp_norm_cons...      1    720ms    0.1%   720ms   57.4MiB    0.2%  57.4MiB
     socp_rational_...      1    659ms    0.1%   659ms   58.8MiB    0.2%  58.8MiB
     socp_square_atom       1    417ms    0.0%   417ms   25.5MiB    0.1%  25.5MiB
     socp_huber_atom        1    390ms    0.0%   390ms   36.5MiB    0.1%  36.5MiB
     socp_fix_multi...      1    376ms    0.0%   376ms   41.1MiB    0.1%  41.1MiB
     socp_geo_mean_...      1    322ms    0.0%   322ms   25.2MiB    0.1%  25.2MiB
     socp_dual_frob...      1    279ms    0.0%   279ms   37.1MiB    0.1%  37.1MiB
     socp_fix_and_f...      1    259ms    0.0%   259ms   20.4MiB    0.1%  20.4MiB
     socp_rational_...      1    147ms    0.0%   147ms   8.92MiB    0.0%  8.92MiB
     socp_sqrt_atom         1   54.9ms    0.0%  54.9ms   1.29MiB    0.0%  1.29MiB
   constant                 1    9.70s    1.0%   9.70s   1.07GiB    2.9%  1.07GiB
     constant_fix!_...      1    3.36s    0.3%   3.36s    304MiB    0.8%   304MiB
     constant_Issue...      1    2.90s    0.3%   2.90s    335MiB    0.9%   335MiB
     constant_Issue...      1    1.04s    0.1%   1.04s   99.2MiB    0.3%  99.2MiB
     constant_fix!_...      1    635ms    0.1%   635ms   61.2MiB    0.2%  61.2MiB
     constant_Test_...      1    328ms    0.0%   328ms   18.4MiB    0.0%  18.4MiB
     constant_fix!_...      1    298ms    0.0%   298ms   21.0MiB    0.1%  21.0MiB
   lp                       1    5.47s    0.6%   5.47s    641MiB    1.7%   641MiB
     lp_dotsort_atom        1    813ms    0.1%   813ms   75.8MiB    0.2%  75.8MiB
     lp_min_atom            1    514ms    0.1%   514ms   37.4MiB    0.1%  37.4MiB
     lp_sumlargest_...      1    496ms    0.1%   496ms   47.4MiB    0.1%  47.4MiB
     lp_max_atom            1    401ms    0.0%   401ms   31.9MiB    0.1%  31.9MiB
     lp_minimum_atom        1    364ms    0.0%   364ms   39.2MiB    0.1%  39.2MiB
     lp_sumsmallest...      1    364ms    0.0%   364ms   30.1MiB    0.1%  30.1MiB
     lp_dual_abs_atom       1    314ms    0.0%   314ms   20.6MiB    0.1%  20.6MiB
     lp_neg_atom            1    226ms    0.0%   226ms   19.2MiB    0.1%  19.2MiB
     lp_maximum_atom        1    194ms    0.0%   194ms   13.1MiB    0.0%  13.1MiB
     lp_dual_norm_i...      1   91.7ms    0.0%  91.7ms   3.91MiB    0.0%  3.91MiB
     lp_pos_atom            1   80.9ms    0.0%  80.9ms   9.03MiB    0.0%  9.03MiB
     lp_dual_norm_1...      1   68.7ms    0.0%  68.7ms   3.82MiB    0.0%  3.82MiB
     lp_hinge_loss_...      1    173μs    0.0%   173μs   57.3KiB    0.0%  57.3KiB
   sdp_and_exp              1    4.18s    0.4%   4.18s    431MiB    1.2%   431MiB
     sdp_and_exp_lo...      1    4.09s    0.4%   4.09s    415MiB    1.1%   415MiB
   exp                      1    3.76s    0.4%   3.76s    376MiB    1.0%   376MiB
     exp_log_atom           1    1.46s    0.2%   1.46s    122MiB    0.3%   122MiB
     exp_entropy_atom       1    420ms    0.0%   420ms   41.5MiB    0.1%  41.5MiB
     exp_exp_atom           1    333ms    0.0%   333ms   23.0MiB    0.1%  23.0MiB
     exp_log_sum_ex...      1    313ms    0.0%   313ms   31.7MiB    0.1%  31.7MiB
     exp_logistic_l...      1    272ms    0.0%   272ms   16.1MiB    0.0%  16.1MiB
     exp_log_perspe...      1    250ms    0.0%   250ms   13.3MiB    0.0%  13.3MiB
     exp_relative_e...      1   58.4ms    0.0%  58.4ms   5.13MiB    0.0%  5.13MiB
 SumOfSquares               1     218s   22.7%    218s   18.1GiB   49.9%  18.1GiB
   sdp                      1    91.6s    9.5%   91.6s   7.18GiB   19.7%  7.18GiB
     rearrangement          1    6.54s    0.7%   6.54s    469MiB    1.3%   469MiB
     quartic_ideal_rem      1    6.41s    0.7%   6.41s    562MiB    1.5%   562MiB
     sosdemo5_infea...      1    6.22s    0.6%   6.22s    470MiB    1.3%   470MiB
     sos_options_pr...      1    5.75s    0.6%   5.75s    202MiB    0.5%   202MiB
     sos_concave_th...      1    4.52s    0.5%   4.52s    484MiB    1.3%   484MiB
     sos_horn               1    4.44s    0.5%   4.44s    304MiB    0.8%   304MiB
     simple_matrix          1    4.02s    0.4%   4.02s    384MiB    1.0%   384MiB
     sos_cheby_univ...      1    3.66s    0.4%   3.66s    205MiB    0.5%   205MiB
     quartic_ideal          1    3.65s    0.4%   3.65s    223MiB    0.6%   223MiB
     sos_scaled_biv...      1    3.64s    0.4%   3.64s    229MiB    0.6%   229MiB
     chebyshev              1    3.64s    0.4%   3.64s    271MiB    0.7%   271MiB
     sos_term_fixed         1    3.48s    0.4%   3.48s    217MiB    0.6%   217MiB
     quartic_ideal_4        1    3.37s    0.4%   3.37s    248MiB    0.7%   248MiB
     maxcut                 1    3.01s    0.3%   3.01s    168MiB    0.5%   168MiB
     sos_term               1    2.85s    0.3%   2.85s    185MiB    0.5%   185MiB
     quartic_ideal_...      1    2.77s    0.3%   2.77s    178MiB    0.5%   178MiB
     sos_quartic_co...      1    2.72s    0.3%   2.72s    172MiB    0.5%   172MiB
     quartic_feasib...      1    2.47s    0.3%   2.47s    117MiB    0.3%   117MiB
     BPT12e399_rem          1    2.37s    0.2%   2.37s   79.7MiB    0.2%  79.7MiB
     sosdemo10              1    1.57s    0.2%   1.57s    181MiB    0.5%   181MiB
     sos_univariate...      1    1.48s    0.2%   1.48s    111MiB    0.3%   111MiB
     sos_univariate...      1    754ms    0.1%   754ms   35.4MiB    0.1%  35.4MiB
     sosdemo9               1    749ms    0.1%   749ms   49.8MiB    0.1%  49.8MiB
     quadratic_feas...      1    683ms    0.1%   683ms   50.0MiB    0.1%  50.0MiB
     quadratic_infe...      1    547ms    0.1%   547ms   40.8MiB    0.1%  40.8MiB
     choi                   1    535ms    0.1%   535ms   63.6MiB    0.2%  63.6MiB
     BPT12e399_maxd...      1    299ms    0.0%   299ms   9.27MiB    0.0%  9.27MiB
     sosdemo5_feasible      1    209ms    0.0%   209ms   16.6MiB    0.0%  16.6MiB
     sos_quartic_co...      1    126ms    0.0%   126ms   21.7MiB    0.1%  21.7MiB
     motzkin                1   77.4ms    0.0%  77.4ms   4.23MiB    0.0%  4.23MiB
     quartic_infeas...      1   20.5ms    0.0%  20.5ms   1.34MiB    0.0%  1.34MiB
     quartic_ideal_...      1   18.4ms    0.0%  18.4ms   1.03MiB    0.0%  1.03MiB
     sos_bivariate_...      1   11.4ms    0.0%  11.4ms    377KiB    0.0%   377KiB
     sos_scaled_uni...      1   10.8ms    0.0%  10.8ms    376KiB    0.0%   376KiB
     quartic_infeas...      1   6.08ms    0.0%  6.08ms    564KiB    0.0%   564KiB
     quartic_feasib...      1   5.27ms    0.0%  5.27ms    461KiB    0.0%   461KiB
     quadratic_infe...      1   4.98ms    0.0%  4.98ms    538KiB    0.0%   538KiB
     quadratic_feas...      1   4.78ms    0.0%  4.78ms    416KiB    0.0%   416KiB
   socp                     1    87.2s    9.1%   87.2s   7.82GiB   21.5%  7.82GiB
     sdsos_term_fixed       1    21.5s    2.2%   21.5s   2.03GiB    5.6%  2.03GiB
     sdsos_horn             1    12.1s    1.3%   12.1s   0.99GiB    2.7%  0.99GiB
     sdsos_concave_...      1    9.90s    1.0%   9.90s    825MiB    2.2%   825MiB
     sdsos_univaria...      1    9.55s    1.0%   9.55s    819MiB    2.2%   819MiB
     sdsos_cheby_un...      1    5.99s    0.6%   5.99s    452MiB    1.2%   452MiB
     sdsos_univaria...      1    5.15s    0.5%   5.15s    388MiB    1.0%   388MiB
     sdsos_options_...      1    4.52s    0.5%   4.52s    228MiB    0.6%   228MiB
     sdsos_scaled_u...      1    3.91s    0.4%   3.91s    293MiB    0.8%   293MiB
     sdsos_term             1    3.49s    0.4%   3.49s    257MiB    0.7%   257MiB
     sdsos_quartic_...      1    3.39s    0.4%   3.39s    250MiB    0.7%   250MiB
     sdsos_quartic_...      1    609ms    0.1%   609ms   26.8MiB    0.1%  26.8MiB
     sdsos_scaled_b...      1   47.4ms    0.0%  47.4ms   5.75MiB    0.0%  5.75MiB
     sdsos_bivariat...      1   21.2ms    0.0%  21.2ms    379KiB    0.0%   379KiB
   lp                       1    39.1s    4.1%   39.1s   3.12GiB    8.6%  3.12GiB
     dsos_options_p...      1    6.34s    0.7%   6.34s    466MiB    1.3%   466MiB
     dsos_concave_t...      1    5.35s    0.6%   5.35s    507MiB    1.4%   507MiB
     dsos_cheby_biv...      1    4.21s    0.4%   4.21s    285MiB    0.8%   285MiB
     dsos_univariat...      1    3.59s    0.4%   3.59s    241MiB    0.6%   241MiB
     dsos_term_fixed        1    3.47s    0.4%   3.47s    227MiB    0.6%   227MiB
     dsos_scaled_bi...      1    3.24s    0.3%   3.24s    220MiB    0.6%   220MiB
     dsos_horn              1    3.18s    0.3%   3.18s    251MiB    0.7%   251MiB
     dsos_term              1    3.00s    0.3%   3.00s    197MiB    0.5%   197MiB
     dsos_quartic_c...      1    2.66s    0.3%   2.66s    183MiB    0.5%   183MiB
     dsos_bivariate...      1    828ms    0.1%   828ms   38.7MiB    0.1%  38.7MiB
     dsos_quartic_c...      1    126ms    0.0%   126ms   21.7MiB    0.1%  21.7MiB
     dsos_scaled_un...      1   9.45ms    0.0%  9.45ms    354KiB    0.0%   354KiB
     dsos_univariat...      1   9.45ms    0.0%  9.45ms    353KiB    0.0%   353KiB
     dsos_cheby_uni...      1   8.96ms    0.0%  8.96ms    379KiB    0.0%   379KiB
 ────────────────────────────────────────────────────────────────────────────────

```

## Version information
`versioninfo()`:
```julia
Julia Version 1.6.7
Commit 3b76b25b64 (2022-07-19 15:11 UTC)
Platform Info:
  OS: Linux (x86_64-pc-linux-gnu)
  CPU: Intel(R) Xeon(R) Platinum 8272CL CPU @ 2.60GHz
  WORD_SIZE: 64
  LIBM: libopenlibm
  LLVM: libLLVM-11.0.1 (ORCJIT, skylake-avx512)
```

Manifest:
```julia
      Status `~/work/ConvexTests.jl/ConvexTests.jl/SCS/Manifest.toml`
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
  [ffbed154] DocStringExtensions v0.9.1
  [7c1d4256] DynamicPolynomials v0.4.5
  [e2ba6199] ExprTools v0.1.8
  [f6369f11] ForwardDiff v0.10.32
  [d5909c97] GroupsCore v0.4.0
  [18e54dd8] IntegerMathUtils v0.1.0
  [3587e190] InverseFunctions v0.1.7
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
  [be282fd4] MultivariateBases v0.1.5
  [f4abf1af] MultivariateMoments v0.3.9
  [102ac46a] MultivariatePolynomials v0.4.6
  [d8a4904e] MutableArithmetics v1.0.4
  [77ba4419] NaNMath v1.0.1
  [bac558e1] OrderedCollections v1.4.1
  [69de0a69] Parsers v2.4.0
  [8bc5a954] PermutationGroups v0.3.2
  [ddf597a6] PolyJuMP v0.6.2
  [21216c6a] Preferences v1.3.0
  [27ebfcd6] Primes v0.5.3
  [fb686558] RandomExtensions v0.4.3
  [189a3867] Reexport v1.2.2
  [ae029012] Requires v1.3.0
  [af85af4c] RowEchelon v0.2.1
  [c946c3f1] SCS v1.1.2
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
  [656ef2d0] OpenBLAS32_jll v0.3.12+1
  [efe28fd5] OpenSpecFun_jll v0.5.5+0
  [af6e375f] SCS_GPU_jll v3.2.0+0
  [f4f2fc5b] SCS_jll v3.2.0+0
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
