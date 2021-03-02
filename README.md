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
