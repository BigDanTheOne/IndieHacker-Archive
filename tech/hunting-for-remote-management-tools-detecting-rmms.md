# Hunting for remote management tools - Detecting RMMs

**Author:** Stef Collart
**Date:** November 13, 2024
**Source:** https://www.indiehackers.com/post/qSqYGrCvC25PCMLcTctc

---

This technical piece addresses challenges in identifying Remote Management and Monitoring (RMM) tools across organizational environments using security investigation methods.

## Key Lessons

1. **Widespread Adoption Challenge:** Most organizations deploy multiple RMM tools simultaneously, indicating absence of clear software policies that distinguish authorized from potentially malicious installations.

2. **Deduplication Strategy:** The authors resolved duplicate detection entries by grouping results around recognizable tool names, reducing noise in large-scale environments with tens of thousands of hosts.

3. **Query Optimization:** Using the `has_any` operator with indexed three-character terms significantly improves search speed compared to broader `contains` operations.

4. **Multi-Field Detection:** Searching across filenames, folder paths, process command lines, and remote URLs increases detection likelihood while accepting increased duplicate findings requiring consolidation.

## Tech Stack Mentioned
- Kusto Query Language (KQL) - Primary hunting methodology
- Microsoft Security Suite - Platform for query execution
- SIEM logs - Data source foundation

The article includes a comprehensive datatable of 80+ RMM tools including TeamViewer, AnyDesk, ConnectWise, LogMeIn, and others with associated detection keywords.
