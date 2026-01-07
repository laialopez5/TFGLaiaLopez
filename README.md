# TFG-BioimpressioVascular
Aquest repositori forma part del Treball de Final de Grau Síntesi, Optimització i Caracterització d'una Biotinta de GelMA per a la Biofabricació de Conductes Vasculars. Conté els scripts utilitzats per al processament de les dades mecàniques i biològiques del projecte, així com el G-Code usat per a la bioimpressió. 
# Contingut
- afectacioLAP: Script per comparar GelMA+cells vs GelMA+LAP+cells
- mtt: Script per fer les comparacions de les dades dels assajos MTT per a viabilitat cel·lular
- ciclescompresio: Script per a l'anàlisi cíclica de compressió, càlcul del mòdul de Young i de l'histèresi
- esadisticasolvent: Script per a l'anlisi de l'efecte del medi de dissolució de la GelMA sobre la viabilitat cel·lular
- g-code: Fitxer G-Code utilitzat per a la bioimpressió dels conductes

# Requisits
- Python >= 3.8
- Llibreries Python: pandas, numpy, matplotlib, scipy, statsmodels

# Ús 
1. Col·loca els fitxers de dades a la mateixa carpeta que els scripts
2. Executa els scripts amb Python, per exemple: python ciclescompresio.py
3. Els scripts generen gràfics SVG i taules de resultats directament per consola

# Notes
- Les anàlisis de compressió es truncen al 25% de deformació per normalitzar els cicles
- Els resultats de viabilitat cel·lular inclouen mitjana, desviació estàndard i significació estadística (t-test o ANOVA + post-hoc)
- Els fitxers de G-code corresponen als patrons de deposició emprats durant la impressió 3D



