## Table Extraction and Subgraph Creation to Enhance 2Kilos-KG
Using Naval Maintenance Manuals to develop CSV Tables for usage in Knowledge Graph Development and General Reference
    Environment Files:
        -environment.yml --no builds specification
        -environment_macos.yml 
        -environment_wsl --for Ubuntu/WSL distributions

table_munger_JFMM.ipynb- Primary resource for 2Kilos Code Disambiguation. Using a snippet from Appendix D for tables. Haven't yet expanded for acronym disambiguation.
table_munger_3M- Pulls tables from Ships 3M manual to provide further context. Not integrated in KG yet.
codeTypes.ttl- Initial .ttl file to specify provenance chain for codeVocabulary.ttl
codeTypeBuilder.ipynb- Constructs Subgraph from .csv files with hooks for integration into 2Kilos-KG
