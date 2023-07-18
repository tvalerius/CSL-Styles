# CSL-Styles
Modified versions of prior CSL styles to use for NIH grant proposals. These are used in Zotero for adding references to grants. For guidance on using, installing, or editing citation styles in Zotero, see the documentation: [Styles [Zotero Documentation]](https://www.zotero.org/support/styles) 

***

## NIH Grant Styles
NIH grants require the PMCID (PubMed Central ID) in the References Cited section of the grant, _if there is one for that reference_. This is **not** the same as the PubMed ID (PMID); however, I do like including it if there is no PMCID. The following two styles include the PMCID when present in the Zotero entry. One form is Author-Date, and the other Numeric. When there is space, the Author-Date is more reviewer friendly. The numeric is deliberately not superscript for the in-line citations. It is also recommended that references are "complete" for grants which means all authors are listed. 

Note: There is a distinction between a Bibliography and a References Cited section. A _Bibliography_ contains additional work used in developing the idea presented but has not explicitly been cited. A _References Cited_ section has only things cited within the text. 

### NIH Grant Style - Author-Date

Filename: `NIH-grant-author-date-PMCID.csl`

_**In-line citation style:**_ 

(Oxburgh et al., 2017; Hansen et al., 2022; Shi et al., 2023)

**_Bibliography style:_**

Hansen J, Sealfon R, Menon R, Eadon MT, Lake BB, Steck B, Anjani K, Parikh S, Sigdel TK, Zhang G, Velickovic D, Barwinska D, Alexandrov T, Dobi D, Rashmi P, Otto EA, Rivera M, Rose MP, Anderton CR, Shapiro JP, Pamreddy A, Winfree S, Xiong Y, He Y, de Boer IH, Hodgin JB, Barisoni L, Naik AS, Sharma K, Sarwal MM, Zhang K, Himmelfarb J, Rovin B, El-Achkar TM, Laszik Z, He JC, Dagher PC, Valerius MT, Jain S, Satlin LM, Troyanskaya OG, Kretzler M, Iyengar R, Azeloglu EU, and Kidney Precision Medicine Project. A reference tissue atlas for the human kidney. _Sci Adv_. 2022 Jun;8(23). doi:10.1126/sciadv.abn4965 PMCID: PMC9176741.

Naved BA, Bonventre JV, Hubbell JA, Hukriede NA, Humphreys BD, Kesselman C, Valerius MT, McMahon AP, Shankland SJ, Wertheim JA, White MJV, de Caestecker MP, and Drummond IA. Kidney repair and regeneration: perspectives of the NIDDK Re(Building) a Kidney consortium. _Kidney Int_. 2022 Mar;S0085-2538(22)00183--1. doi:10.1016/j.kint.2022.02.023 PMID: 35276204.

Shi M, McCracken KW, Patel AB, Zhang W, Ester L, Valerius MT, and Bonventre JV. Human ureteric bud organoids recapitulate branching morphogenesis and differentiate into functional collecting duct cell types. _Nat Biotechnol_. 2023 Feb;41(2):252--261. doi:10.1038/s41587-022-01429-5 PMCID: PMC9957856.



### NIH Grant - Numeric (PMCID)
Filename: `NIH-grant-numeric-PMCID.csl`

_**In-line citation style:**_ 

[1–3]

**_Bibliography style:_**


1. Shi M, McCracken KW, Patel AB, Zhang W, Ester L, Valerius MT, Bonventre JV. Human ureteric bud organoids recapitulate branching morphogenesis and differentiate into functional collecting duct cell types. _Nat Biotechnol_. 2023 Feb;41(2):252--61. doi:10.1038/s41587-022-01429-5 PMCID: PMC9957856.

2. Naved BA, Bonventre JV, Hubbell JA, Hukriede NA, Humphreys BD, Kesselman C, Valerius MT, McMahon AP, Shankland SJ, Wertheim JA, White MJV, de Caestecker MP, Drummond IA. Kidney repair and regeneration: perspectives of the NIDDK Re(Building) a Kidney consortium. _Kidney Int_. 2022 Mar 9;S0085-2538(22)00183-1. doi:10.1016/j.kint.2022.02.023 PMID: 35276204.

3. Hansen J, Sealfon R, Menon R, Eadon MT, Lake BB, Steck B, Anjani K, Parikh S, Sigdel TK, Zhang G, Velickovic D, Barwinska D, Alexandrov T, Dobi D, Rashmi P, Otto EA, Rivera M, Rose MP, Anderton CR, Shapiro JP, Pamreddy A, Winfree S, Xiong Y, He Y, de Boer IH, Hodgin JB, Barisoni L, Naik AS, Sharma K, Sarwal MM, Zhang K, Himmelfarb J, Rovin B, El-Achkar TM, Laszik Z, He JC, Dagher PC, Valerius MT, Jain S, Satlin LM, Troyanskaya OG, Kretzler M, Iyengar R, Azeloglu EU, Kidney Precision Medicine Project. A reference tissue atlas for the human kidney. _Sci Adv_. 2022 Jun 10;8(23). doi:10.1126/sciadv.abn4965 PMCID: PMC9176741.

***

### Short form citation style for presentation slides
Filename: `presentation short citations.csl`

I wanted a simple citation form to include in presentations to credit the data source. The more formal styles for grants were too long, so I adapted an existing style to include just the First author, year, journal, and, if present, a DOI. The CSL style is called `presentation short citations.csl` and is designed for short citations to be included on slides for presentations. This way, there is enough short info for viewers to get down in their notes (name, date, journal), and if the slides are posted, the DOI is a usable link. 

_**In-line citation style:**_ (Not used in slides but it exists.)

(Hansen _et al._, 2022; Naved _et al._, 2022; Shi _et al._, 2023)

**_Bibliography style:_** (Included on presentation slides.)

Hansen, J. _et al._ (2022) _Sci Adv_. https://doi.org/10.1126/sciadv.abn4965

Naved, B.A. _et al._ (2022) _Kidney Int_. https://doi.org/10.1016/j.kint.2022.02.023

Shi, M. _et al._ (2023) _Nat Biotechnol_. https://doi.org/10.1038/s41587-022-01429-5

***
