# Créditos e licenças do catálogo de peças do Ohmia

O arquivo `catalogo.json` reúne dados compilados e convertidos a partir das fontes abaixo.
As descrições foram lidas por script e convertidas para o formato do Ohmia (modelo, categoria,
encapsulamento, tipo, especificações e link do datasheet). Os valores não foram conferidos um a um
contra os datasheets: confira sempre o datasheet do fabricante antes de usar uma peça.

## Fontes

### Bibliotecas oficiais de símbolos do KiCad
- Repositório: https://gitlab.com/kicad/libraries/kicad-symbols
- Licença: Creative Commons Attribution-ShareAlike 4.0 (CC BY-SA 4.0), com a exceção descrita no
  LICENSE.md da biblioteca para projetos eletrônicos que usem os dados. Quem redistribui a biblioteca
  ou partes dela como coleção, inclusive modificada, deve manter a mesma licença e os créditos.
- Uso no Ohmia: nome, descrição, encapsulamento e link do datasheet de semicondutores, circuitos
  integrados, reguladores, relés, pontes retificadoras e módulos.

### Digi-Key KiCad Library
- Repositório: https://github.com/Digi-Key/digikey-kicad-library
- Licença: Creative Commons Attribution-ShareAlike 4.0 (CC BY-SA 4.0), com a exceção descrita no
  arquivo LICENSE.md do repositório para projetos eletrônicos que usem os dados.
- Uso no Ohmia: fabricante, descrição, encapsulamento e link do datasheet de peças semicondutoras,
  reguladores, relés e circuitos integrados.

### GitPLM Parts
- Repositório: https://github.com/git-plm/parts
- Licença: MIT, Copyright (c) 2024 Git PLM.
- Uso no Ohmia: código do fabricante, fabricante, descrição e link do datasheet de diodos,
  transistores, circuitos integrados, reguladores e módulos.

### Banco de componentes do aplicativo electroDB
- Origem de grande parte das entradas de transistores, MOSFETs, diodos, reguladores, relés e
  circuitos integrados.
- [A CONFIRMAR antes de publicar: licença e termos de uso do banco do electroDB. As entradas dele
  parecem coincidir com as bibliotecas do KiCad e da Digi-Key, já creditadas acima.]

## Licença dos dados do catálogo

Os dados do `catalogo.json` derivados das fontes acima são compartilhados sob a licença
**Creative Commons Attribution-ShareAlike 4.0 International (CC BY-SA 4.0)**:
https://creativecommons.org/licenses/by-sa/4.0/

Isso significa que quem reutilizar ou adaptar o catálogo deve dar crédito às fontes e compartilhar
o resultado sob a mesma licença. O código do site é um arquivo à parte.

Sem garantia: os dados são fornecidos como estão, sem qualquer garantia de exatidão.
