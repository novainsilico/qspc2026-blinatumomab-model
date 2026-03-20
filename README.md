# QSP platform of bispecific T-cell engager for multi-scale modeling: Blinatumomab study case

Presented at [QSPC 2026 in Leiden](https://www.qspc.eu/qspc2026/home). The PDF version of the poster is available directly [in this document](./QSPC26_NovaInSilico_poster_Blinatumomab.pdf).

## Full list of references

- **[Liu et al. (2023)]**: Can Liu et al. (2023), Population dynamics of immunological synapse formation induced by bispecific T cell engagers predict clinical pharmacodynamics and treatment resistance, 10.7554/eLife.83659
- **[D’Argouges et al. (2008)]**: Sandrine d’Argouges et al. (2008), Combination of rituximab with blinatumomab (MT103/MEDI-538), a T cell-engaging CD19-/CD3-bispecific antibody, for highly efficient lysis of human B lymphoma cells, 10.1016/j.leukres.2008.08.025
- **[Brandl et al. (2006)]**: Christian Brandl et al. (2007), The effect of dexamethasone on polyclonal T cell activation and redirected target cell lysis as induced by a CD19/CD3-bispecific single-chain antibody construct, 10.1007/s00262-007-0298-z
- **[Zhu et al. (2016)]**: Min Zhu et al. (2016), Blinatumomab, a Bispecific T-cell Engager (BiTE®) for CD-19 Targeted Cancer Immunotherapy: Clinical Pharmacology and Its Implications, 10.1007/s40262-016-0405-4
- **[Clements et al. (2019)]**: Clements, J.D., Zhu, M., Kuchimanchi, M. et al. Population Pharmacokinetics of Blinatumomab in Pediatric and Adult Patients with Hematological Malignancies. Clin Pharmacokinet 59, 463–474 (2020), ,10.1007/s40262-019-00823-8
- **[Katz et al. (2022)]**: Katz, D. A., Morris, J. D., Chu, M. P., David, K. A., Thieblemont, C., Morley, N. J., … González-Barca, E. (2022). Open-label, phase 2 study of blinatumomab after frontline R-chemotherapy in adults with newly diagnosed, high-risk DLBCL. Leukemia & Lymphoma, 63(9), 2063–2073. <https://doi.org/10.1080/10428194.2022.2064981>
- **[Dufner et al. (2019)]**: Vera Dufner, Cyrus M. Sayehli, et al.; Long-term outcome of patients with relapsed/refractory B-cell non-Hodgkin lymphoma treated with blinatumomab. Blood Adv 2019; 3 (16): 2491–2498. doi: <https://doi.org/10.1182/bloodadvances.2019000025>
- **[Lemarre et al. (2023)]**: P. Lemarre, C. Couty, A. Kulesza, A. Schneider, M. Hanke, A.I. Toledo, J. Bosley, N. Afzal, B. Zhao, F. Alemdehy, P. Boross, L. Koopman, C. Thalhauser; Cytotoxic effects of bispecific T-cell engagers in QSP models under the lens of cell encounter. ACOP 2023
- **[Couty et al. (2024)]**: Towards A QSP Platform To Support Drug Development In Hematological Cancers ;Towards A QSP Platform To Support Drug Development In Hematological Cancers. ACOP 2024. 10.70534/TTTE6533

## Original abstract

### Background

Due to their accessible tumor cells, favorable targets with restricted antigens, and clear unmet needs, hematological malignancies represent a promising context for immuno-therapies, in particular for bispecific antibodies. This has translated into multiple approvals, high response rates in refractory settings, and a very active pipeline. One of the main challenges for bispecific antibody dose selection for first-in-human studies is the translation of in vitro cytotoxicity data to human efficacy. Such a translation is difficult due to the complex and non-linear dose response of bispecific T-cell engagers, and the many factors involved in the prediction of human pharmacodynamics such as tumor microenvironment, cellular cross-talk and migration, or cytokine feedback. In this context, quantitative systems pharmacology (QSP) modeling appears as a powerful tool to investigate translation hypotheses and predict in human dose-response curves, while leveraging data from all stages of the clinical development pipeline.

### Methods

Here, we propose a mechanistic multiscale QSP model of T-cell engager mechanism of action and apply it to the in vitro to in vivo translation of Blinatumomab (CD3xCD19 bispecific) efficacy. The model integrates phenomena across multiple scales, from molecular events like receptor binding and regulation to cellular dynamics. A central feature is the computation of immune synapse formation, which serves as the crucial link between scales, derived from the combined effects of cross-linking and cell encounter. This comprehensive representation allows for the capture of downstream effects, including cell differentiation and target cell lysis. The model amounts to approximately 500 parameters, 100 variables, and 150 reactions.

### Results

The model captures synapse formation data as reported by [Liu et al. (2023)], as a function of antibody concentration, E-T ratio and cell densities but also in vitro cytotoxicity data from [D’Argouges et al. (2008)] and activation data from [Brandl et al. (2006)]. The model is also calibrated to capture the PK of Blinatumomab in DLBCL patients [Zhu et al. (2016), Clements et al. (2019), Katz et al. (2022)]. Finally, the translation to human is performed in the context of B-cell non-Hodgkin lymphoma (B-NHL), and a virtual population is calibrated to match stratified progression-free survival (PFS) endpoints as reported by [Dufner et al. (2019)].

### Conclusion

This work establishes a multiscale QSP platform for CD3 T-cell engaging bispecific antibodies in hematological malignancies and provides a mechanistic bridge from in vitro cytotoxicity to predicted human dose-response. By capturing key mechanisms across molecular, cellular, and tissue scales, the framework supports translational analyses and first-in-human dose and schedule selection. More broadly, the platform can be applied to de-risk early clinical decisions, test translational hypotheses, and optimize trial design, including patient stratification and best-responder analyses.
