# BA305-Project
My work

table of contents for df names at each stage:

df_no_na: dropped NA rows (48,842 → 45,222)

df_50k_fix: removed “.” from income labels

df_q_fix: converted “?” to NaN and dropped

dfbinaryinc: income as 0/1

df_no_edu: dropped education, kept education-num

df_country: native-country grouped into US / Other

df_encoded: binary encoded the 7 text columns

dfclean: dropped fnlwgt (45,222 × 42)

df_final: after outliers (not created yet)
