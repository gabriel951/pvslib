# Summary for `float/axm_bnd`
Run started at 16:30:18 9/1/2023.

_Note_: Time below is expressed in format DD:HH:MM:SS.SSS.
## Grand Totals 
|            | Formulas | Attempted | Succeeded | Missing | Total Time |
| ---:       | :---:    | :---:     | :---:     | :---:   | ---        |
| **totals** | **137**   | **137**    | **137**    | **0**  | **55.854 s**   |
|top|0|0|0|0|0.000|
|ieee754_double|0|0|0|0|0.000|
|ieee754_double_base|22|22|22|0|32.009|
|ieee754_format_parameters|7|7|7|0|0.448|
|ieee754_semantics|11|11|11|0|1.007|
|ieee754_data|0|0|0|0|0.000|
|ieee754_domain|37|37|37|0|10.277|
|ieee754_qlt|1|1|1|0|0.121|
|ieee754_qle|1|1|1|0|0.113|
|ieee754_qgt|1|1|1|0|0.123|
|ieee754_qge|1|1|1|0|0.126|
|ieee754_qeq|1|1|1|0|0.128|
|ieee754_qun|0|0|0|0|0.000|
|ieee754_add|3|3|3|0|0.824|
|ieee754_sub|4|4|4|0|1.425|
|ieee754_mul|3|3|3|0|1.771|
|ieee754_max|0|0|0|0|0.000|
|ieee754_min|0|0|0|0|0.000|
|ieee754_div|6|6|6|0|1.263|
|ieee754_abs|1|1|1|0|0.031|
|ieee754_sqt|2|2|2|0|0.060|
|ieee754_neg|2|2|2|0|0.081|
|ieee754_single|0|0|0|0|0.000|
|ieee754_single_base|22|22|22|0|4.206|
|aerr_ulp__double|2|2|2|0|0.050|
|aerr_ulp_abs|0|0|0|0|0.000|
|ieee754_nearest_even_rounding|1|1|1|0|0.030|
|aerr_ulp_add|0|0|0|0|0.000|
|aerr_ulp_div|5|5|5|0|1.641|
|aerr_ulp_mul|0|0|0|0|0.000|
|aerr_ulp_sqt|2|2|2|0|0.070|
|aerr_ulp_sub|0|0|0|0|0.000|
|aerr_ulp__single|2|2|2|0|0.050|
|ieee754_operations|0|0|0|0|0.000|
## Detailed Summary 
## `top`
No formula declaration found.
## `ieee754_double`
No formula declaration found.
## `ieee754_double_base`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|er_ub_value|✅ proved - incomplete|shostak|16.152|
|er_lb_value|✅ proved - incomplete|shostak|15.142|
|add_double_finite_def|✅ proved - incomplete|shostak|0.030|
|sub_double_finite_def|✅ proved - incomplete|shostak|0.049|
|mul_double_finite_def|✅ proved - incomplete|shostak|0.060|
|div_double_finite_def_TCC1|✅ proved - incomplete|shostak|0.048|
|div_double_finite_def|✅ proved - incomplete|shostak|0.091|
|qeq_double_finite_def|✅ proved - incomplete|shostak|0.020|
|qge_double_finite_def|✅ proved - incomplete|shostak|0.027|
|qgt_double_finite_def|✅ proved - incomplete|shostak|0.030|
|qle_double_finite_def|✅ proved - incomplete|shostak|0.030|
|qlt_double_finite_def|✅ proved - incomplete|shostak|0.030|
|neg_double_finite_def|✅ proved - incomplete|shostak|0.020|
|finite?_double_add|✅ proved - complete|shostak|0.020|
|finite?_double_sub|✅ proved - incomplete|shostak|0.030|
|finite?_double_mul|✅ proved - incomplete|shostak|0.020|
|finite?_double_div|✅ proved - incomplete|shostak|0.026|
|finite?_double_neg|✅ proved - complete|shostak|0.020|
|double__finite?_projs_finite?_add|✅ proved - incomplete|shostak|0.030|
|double__finite?_projs_finite?_sub|✅ proved - incomplete|shostak|0.020|
|double__finite?_projs_finite?_mul|✅ proved - incomplete|shostak|0.034|
|double__finite?_projs_finite?_div|✅ proved - incomplete|shostak|0.080|

## `ieee754_format_parameters`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|ieee754_radix_TCC1|✅ proved - complete|shostak|0.010|
|ieee754_subtype_above_1|✅ proved - complete|shostak|0.020|
|ieee754_precision_TCC1|✅ proved - complete|shostak|0.030|
|ieee754_precision_subtype_above_1|✅ proved - complete|shostak|0.025|
|ieee754_maxExp_TCC1|✅ proved - complete|shostak|0.080|
|ieee754_maxExp_subtype_above_1|✅ proved - complete|shostak|0.040|
|ieee754_minExp_TCC1|✅ proved - complete|shostak|0.243|

## `ieee754_semantics`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|emin_TCC1|✅ proved - complete|shostak|0.745|
|proj_def_pZero_TCC1|✅ proved - complete|shostak|0.020|
|proj_def_nZero_TCC1|✅ proved - complete|shostak|0.010|
|expr_judgement_TCC1|✅ proved - incomplete|shostak|0.030|
|add_inv_TCC1|✅ proved - complete|shostak|0.030|
|proj_round_TCC1|✅ proved - incomplete|shostak|0.020|
|round_monotone_TCC1|✅ proved - incomplete|shostak|0.020|
|is_finite_safe_projection_er_real|✅ proved - incomplete|shostak|0.050|
|safe_projection_er_real_proj_TCC1|✅ proved - incomplete|shostak|0.020|
|safe_projection_er_real_proj|✅ proved - incomplete|shostak|0.050|
|is_finite_safe_projection|✅ proved - incomplete|shostak|0.012|

## `ieee754_data`
No formula declaration found.
## `ieee754_domain`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|emin_TCC1|✅ proved - complete|shostak|0.020|
|lesseqp_TCC1|✅ proved - complete|shostak|0.010|
|significand_lt_first_discrepancy|✅ proved - complete|shostak|0.160|
|smax_TCC1|✅ proved - complete|shostak|0.030|
|smin_TCC1|✅ proved - complete|shostak|0.021|
|smin_TCC2|✅ proved - complete|shostak|0.030|
|szero_TCC1|✅ proved - complete|shostak|0.020|
|smax_is_max|✅ proved - complete|shostak|0.030|
|smin_is_min|✅ proved - complete|shostak|0.070|
|IMP_sigma_TCC1|✅ proved - complete|shostak|0.020|
|value_TCC1|✅ proved - complete|shostak|0.042|
|value_TCC2|✅ proved - complete|shostak|0.010|
|value_TCC3|✅ proved - complete|shostak|0.040|
|value_TCC4|✅ proved - complete|shostak|0.040|
|significand_zero_value_zero|✅ proved - incomplete|shostak|0.343|
|significand_le_value_le_TCC1|✅ proved - complete|shostak|0.030|
|significand_le_value_le|✅ proved - incomplete|shostak|4.607|
|value_monotonicity|✅ proved - incomplete|shostak|1.890|
|exactly_representable_symm_0|✅ proved - incomplete|shostak|0.496|
|er_real_value|✅ proved - incomplete|shostak|0.020|
|zero_is_er|✅ proved - incomplete|shostak|0.304|
|er_real_TCC1|✅ proved - incomplete|shostak|0.010|
|er_lb_TCC1|✅ proved - complete|shostak|0.020|
|er_lb_TCC2|✅ proved - incomplete|shostak|0.020|
|er_lower_bound|✅ proved - incomplete|shostak|0.050|
|er_ub_TCC1|✅ proved - incomplete|shostak|0.018|
|er_upper_bound|✅ proved - incomplete|shostak|0.050|
|er_min_pos_TCC1|✅ proved - complete|shostak|0.020|
|er_min_pos_TCC2|✅ proved - incomplete|shostak|0.020|
|er_min_pos_prop|✅ proved - incomplete|shostak|0.595|
|er_max_neg_TCC1|✅ proved - incomplete|shostak|0.020|
|er_max_neg_prop|✅ proved - incomplete|shostak|0.400|
|r_real_TCC1|✅ proved - incomplete|shostak|0.000|
|ulp_TCC1|✅ proved - complete|shostak|0.040|
|ulp_TCC2|✅ proved - complete|shostak|0.030|
|ulp_TCC3|✅ proved - incomplete|shostak|0.370|
|ulp_TCC4|✅ proved - incomplete|shostak|0.381|

## `ieee754_qlt`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|qlt_finite_def|✅ proved - incomplete|shostak|0.121|

## `ieee754_qle`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|qle_finite_def|✅ proved - incomplete|shostak|0.113|

## `ieee754_qgt`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|qgt_finite_def|✅ proved - incomplete|shostak|0.123|

## `ieee754_qge`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|qge_finite_def|✅ proved - incomplete|shostak|0.126|

## `ieee754_qeq`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|qeq_finite_def|✅ proved - incomplete|shostak|0.128|

## `ieee754_qun`
No formula declaration found.
## `ieee754_add`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|add_finite_def|✅ proved - incomplete|shostak|0.248|
|add_finites_is_finite|✅ proved - complete|shostak|0.295|
|finite?_projs_finite?_add|✅ proved - incomplete|shostak|0.281|

## `ieee754_sub`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|sub_correct__nZero_finite_TCC1|✅ proved - incomplete|shostak|0.030|
|sub_finite_def|✅ proved - incomplete|shostak|0.540|
|sub_finites_is_finite|✅ proved - incomplete|shostak|0.391|
|finite?_projs_finite?_sub|✅ proved - incomplete|shostak|0.464|

## `ieee754_mul`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|mul_finite_def|✅ proved - incomplete|shostak|0.566|
|mul_finites_is_finite|✅ proved - incomplete|shostak|0.601|
|finite?_projs_finite?_mul|✅ proved - incomplete|shostak|0.604|

## `ieee754_max`
No formula declaration found.
## `ieee754_min`
No formula declaration found.
## `ieee754_div`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|div_correct__finite_TCC1|✅ proved - incomplete|shostak|0.030|
|div_finite_def_TCC1|✅ proved - incomplete|shostak|0.021|
|div_finite_def_TCC2|✅ proved - incomplete|shostak|0.020|
|div_finite_def|✅ proved - incomplete|shostak|0.252|
|div_finites_is_finite|✅ proved - incomplete|shostak|0.749|
|finite?_projs_finite?_div|✅ proved - incomplete|shostak|0.191|

## `ieee754_abs`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|abs_correct__finite_TCC1|✅ proved - incomplete|shostak|0.031|

## `ieee754_sqt`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|sqt_correct__finite_TCC1|✅ proved - incomplete|shostak|0.040|
|sqt_correct__finite_TCC2|✅ proved - incomplete|shostak|0.020|

## `ieee754_neg`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|neg_finite_def|✅ proved - incomplete|shostak|0.030|
|neg_finites_is_finite|✅ proved - complete|shostak|0.051|

## `ieee754_single`
No formula declaration found.
## `ieee754_single_base`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|er_ub_value|✅ proved - incomplete|shostak|1.772|
|er_lb_value|✅ proved - incomplete|shostak|1.755|
|add_single_finite_def|✅ proved - incomplete|shostak|0.021|
|sub_single_finite_def|✅ proved - incomplete|shostak|0.040|
|mul_single_finite_def|✅ proved - incomplete|shostak|0.050|
|div_single_finite_def_TCC1|✅ proved - incomplete|shostak|0.050|
|div_single_finite_def|✅ proved - incomplete|shostak|0.082|
|qeq_single_finite_def|✅ proved - incomplete|shostak|0.020|
|qge_single_finite_def|✅ proved - incomplete|shostak|0.030|
|qgt_single_finite_def|✅ proved - incomplete|shostak|0.024|
|qle_single_finite_def|✅ proved - incomplete|shostak|0.030|
|qlt_single_finite_def|✅ proved - incomplete|shostak|0.030|
|neg_single_finite_def|✅ proved - incomplete|shostak|0.020|
|finite?_single_add|✅ proved - complete|shostak|0.024|
|finite?_single_sub|✅ proved - incomplete|shostak|0.030|
|finite?_single_mul|✅ proved - incomplete|shostak|0.020|
|finite?_single_div|✅ proved - incomplete|shostak|0.020|
|finite?_single_neg|✅ proved - complete|shostak|0.020|
|single__finite?_projs_finite?_add|✅ proved - incomplete|shostak|0.024|
|single__finite?_projs_finite?_sub|✅ proved - incomplete|shostak|0.020|
|single__finite?_projs_finite?_mul|✅ proved - incomplete|shostak|0.030|
|single__finite?_projs_finite?_div|✅ proved - incomplete|shostak|0.094|

## `aerr_ulp__double`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|aerr_div_def_TCC1|✅ proved - complete|shostak|0.030|
|aerr_sqt_def_TCC1|✅ proved - complete|shostak|0.020|

## `aerr_ulp_abs`
No formula declaration found.
## `ieee754_nearest_even_rounding`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|nearest_even_rounding_TCC1|✅ proved - incomplete|shostak|0.030|

## `aerr_ulp_add`
No formula declaration found.
## `aerr_ulp_div`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|aerr_ulp_div_TCC1|✅ proved - complete|shostak|0.375|
|aerr_ulp_div_TCC2|✅ proved - complete|shostak|0.060|
|aerr_ulp_div_TCC3|✅ proved - incomplete|shostak|1.024|
|aerr_ulp_div_correct_TCC1|✅ proved - incomplete|shostak|0.102|
|aerr_ulp_div_correct_TCC2|✅ proved - incomplete|shostak|0.080|

## `aerr_ulp_mul`
No formula declaration found.
## `aerr_ulp_sqt`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|aerr_ulp_sqt_TCC1|✅ proved - complete|shostak|0.020|
|aerr_ulp_sqt_correct_TCC1|✅ proved - incomplete|shostak|0.050|

## `aerr_ulp_sub`
No formula declaration found.
## `aerr_ulp__single`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|aerr_div_def_TCC1|✅ proved - complete|shostak|0.030|
|aerr_sqt_def_TCC1|✅ proved - complete|shostak|0.020|

## `ieee754_operations`
No formula declaration found.## Platform information 
|  |  |
|---|---|
| PVS Version | 7.1.0 |
| Lisp| International Allegro CL Enterprise Edition 10.1 [64-bit Linux (x86-64)] (Nov 14, 2020 18:29)|
| Patch Version| n/a|
| Library Path| `/home/cmunoz/local/pvs-7.1.0/nasalib/pvsio_utils/`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/float/`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/`<br/>`/home/cmunoz/local/pvs-7.1.0/lib/`|
| Loaded Patches | `/home/cmunoz/local/pvs-7.1.0/nasalib/.pvs.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20230712-static-update.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20230710-tcc-gen.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20230709-pvsio.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20230708-prelude-attachments.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20230707-defattach.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20230706-extrategies.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20221018-proveit-init.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20220902-manip-syntax-matching.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20220902-manip-manip-utilities.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20220514-conversions.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20220512-exprjudgements.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20210707-trivial-judgements.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20210701-breakpoint-reached-when-restoring-from-binaries.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20210623-cl2pvs.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20210421-prooflite.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20210323-wish.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20210301-pvseval-update.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20210225-cl2pvs.lisp`|
