# Summary for `TU_Games`
Run started at 21:49:3 9/1/2023.

_Note_: Time below is expressed in format DD:HH:MM:SS.SSS.
## Grand Totals 
|            | Formulas | Attempted | Succeeded | Missing | Total Time |
| ---:       | :---:    | :---:     | :---:     | :---:   | ---        |
| **totals** | **24**   | **24**    | **24**    | **0**  | **1.643 s**   |
|top|0|0|0|0|0.000|
|players_set|0|0|0|0|0.000|
|coalition_fun|7|7|7|0|0.375|
|imputations|3|3|3|0|0.135|
|tu_game|14|14|14|0|1.133|
## Detailed Summary 
## `top`
No formula declaration found.
## `players_set`
No formula declaration found.
## `coalition_fun`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|coalition_fun_TCC1|✅ proved - complete|shostak|0.023|
|subsets_are_finite|✅ proved - complete|shostak|0.105|
|tot_S_0|✅ proved - incomplete|shostak|0.038|
|tot_distrib|✅ proved - incomplete|shostak|0.044|
|tot_mult_const|✅ proved - incomplete|shostak|0.007|
|tot_distrib_sub|✅ proved - incomplete|shostak|0.081|
|tot_div_const|✅ proved - incomplete|shostak|0.077|

## `imputations`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|subset_core_I|✅ proved - incomplete|shostak|0.036|
|subset_I_PI|✅ proved - incomplete|shostak|0.042|
|subset_PI_FP|✅ proved - incomplete|shostak|0.057|

## `tu_game`

| Formula | Proof Status | Decision Procedure | Time |
| ---     | ---          | ---                | ---  |
|solution_concept_TCC1|✅ proved - incomplete|shostak|0.047|
|a_test|✅ proved - incomplete|shostak|0.008|
|test_param|✅ proved - incomplete|shostak|0.010|
|tau_v_TCC1|✅ proved - complete|shostak|0.016|
|tau_x_TCC1|✅ proved - complete|shostak|0.125|
|bstar_TCC1|✅ proved - incomplete|shostak|0.030|
|affinestar_TCC1|✅ proved - incomplete|shostak|0.093|
|interch_impl_desir|✅ proved - complete|shostak|0.047|
|interch_is_sym|✅ proved - complete|shostak|0.055|
|DES_implies_ETP|✅ proved - incomplete|shostak|0.019|
|SIVA_implies_NE|✅ proved - incomplete|shostak|0.027|
|PO_core|✅ proved - incomplete|shostak|0.048|
|affine_bij|✅ proved - complete|shostak|0.076|
|COV_core|✅ proved - incomplete|shostak|0.532|
## Platform information 
|  |  |
|---|---|
| PVS Version | 7.1.0 |
| Lisp| International Allegro CL Enterprise Edition 10.1 [64-bit Linux (x86-64)] (Nov 14, 2020 18:29)|
| Patch Version| n/a|
| Library Path| `/home/cmunoz/local/pvs-7.1.0/nasalib/pvsio_utils/`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/float/`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/`<br/>`/home/cmunoz/local/pvs-7.1.0/lib/`|
| Loaded Patches | `/home/cmunoz/local/pvs-7.1.0/nasalib/.pvs.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20230712-static-update.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20230710-tcc-gen.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20230709-pvsio.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20230708-prelude-attachments.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20230707-defattach.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20230706-extrategies.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20221018-proveit-init.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20220902-manip-syntax-matching.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20220902-manip-manip-utilities.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20220514-conversions.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20220512-exprjudgements.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20210707-trivial-judgements.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20210701-breakpoint-reached-when-restoring-from-binaries.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20210623-cl2pvs.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20210421-prooflite.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20210323-wish.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20210301-pvseval-update.lisp`<br/>`/home/cmunoz/local/pvs-7.1.0/nasalib/pvs-patches/patch-20210225-cl2pvs.lisp`|
