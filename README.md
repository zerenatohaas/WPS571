# WPS571
Aggregate data from Banco Central do Brasil Working Paper 571

This repository contains aggregate data used in the Banco Central do Brasil Working Paper 571, entitled "Does Fintech Lending Lower Financing Costs? Evidence From An Emerging Market".

The full text can be downloaded at https://www.bcb.gov.br/content/publicacoes/WorkingPaperSeries/wps571.pdf

Data from the working paper are aggregated at the municipality-month level for each type of financial institution.

The Stata dta data file contains 7 fields:
- The Municipality code from IGBE (mun_cd_ibge_cli)
- The year and month (time_id)
- Flags for each type of financial institution:
    - flag_P2P: a 0/1 flag indicating whether there was a working capital loan from P2P platforms at that month - municipality
    - flag_credit_union: a 0/1 flag indicating whether there was a working capital loan from credit unions at that month - municipality
    - flag_private_large_bank: a 0/1 flag indicating whether there was a working capital loan from large private banks at that month - municipality
    - flag_non_large_bank: a 0/1 flag indicating whether there was a working capital loan from non-large private banks at that month - municipality
    - flag_public_bank: a 0/1 flag indicating whether there was a working capital loan from public banks at that month - municipality

The data covers the period from January 2015 to February 2020.
