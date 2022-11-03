<h1> Table Extraction and Subgraph Creation to Enhance 2Kilos-KG </h1>
Using Naval Maintenance Manuals to develop CSV Tables for usage in Knowledge Graph Development and General Reference
   <p> Environment Files: </p>
    <ul>
        <li>-environment.yml --no builds specification</li>
        <li>-environment_macos.yml </li>
        <li>-environment_wsl --for Ubuntu/WSL distributions</li>

<ol>
<li>table_munger_JFMM.ipynb- Primary resource for 2Kilos Code Disambiguation. Using a snippet from Appendix D for tables. Haven't yet expanded for acronym disambiguation.</li>
<li>table_munger_3M- Pulls tables from Ships 3M manual to provide further context. Not integrated in KG yet.</li>
<li>codeTypes.ttl- Initial .ttl file to specify provenance chain for codeVocabulary.ttl</li>
<li>codeTypeBuilder.ipynb- Constructs Subgraph from .csv files with hooks for integration into 2Kilos-KG</li>
</ol>
