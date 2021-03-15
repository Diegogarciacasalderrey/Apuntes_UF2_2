# Apuntes_UF2_2
## Optimització
### Hediondez/pestilència del codi(*code smell*)
L'hediondez del codi són problemes que no impideixen que el codi s'executi, però que generen problemes a l'hora de llegir o corregir el codi i/o augmenten el risc d'errors en un futur. Ex: un mètode de 200 línies (caldria separar-ho en submètodes més petits).
### Anàlisi del codi
Hi ha 2 típus d'anàlisi del codi:
- **Análisi dinàmic**: comprova si l'execució del codi fa el que l'usuari vol que es faci. Ex: JUnit.
- **Anàlisi estàtic**: comprova l'estructura del codi sense executar aquest. Ex: limp.
### Refactorització
Procés per a reestructurar un codi sense modificar el seu funcionament. Algunes de les tècniques de refactorització serien:
- Reanomenar variables.
- Passar codi duplicat a funcions.
- Eliminar codi inútil (que no s'executa mai, que és redundant o que s'executa però no s'utilitza mai).
## Documentació
### Tipus de documentació
Hi ha 3 tipus de documentació:
- **Documentació de codi**: documentar el codi per què s'entengui
- **Documentació tècnica**: manual per a administrar l'aplicació
- **Documentació d'usuari**: manual per a l'usuari de l'aplicació
### Formats de documentació
Aquesta documentació normalment es realitza en els següents formats:
- **HTML**: per exemple Javadoc
- **Markdown**: per exemple Git
- **ReStructuredText:** per exemple readthedocs
- **asciiDoc** (alternativa simmilar a Markdown)
## Control de versions
Sistemes més coneguts:
- **CVS**
- **Subversion**
- **Mercurial**
- **Git** és modern, distribuït i intel·ligent i té els següents conceptes:
  - **Repository** (local i remot): és el repositori
  - **Commit**: per fer canvis
  - **Branch**: per fer branques. Pot ser:
    - **Checkout**: canvia de branca
    - **Merge**: uneix 2 repositòris
