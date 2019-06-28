# A Evolução do Sci-fi Ao Longo da História
---------------------------------------------------------------------------------------------------------------------
### Trabalho solicitado pelo professor Adolfo Neto para a disciplina de Introdução à Lógica para Computação
------------------------------------------------------------------------------------------------------------------------

## Tema, Descrição do Tema e Integrantes da Equipe

Integrantes:

  1. Higor ferreira Silva


A finalidade deste trabalho é tirar proveito da chamada "Lógica de Predicados" para desenvolver analogias similares a uma linha do tempo da história da ficção científica nas suas mais variadas facetas. A ideia é contrastar ao máximo as mudanças neste gênero.


##  Frases e Fórmulas

### Propriedades de “objetos”

| Frase   |   Isaac Asimov era ateu.   |
| ----------- | ----------- |
| Fórmula   |  Ateu("Isaac Asimov")       |
| Definições de Predicados/Funções   | Ateu(X): X era ateu.|

---------------------------------------
| Frase   |   Sci-fi é um gênero literário.   |
| ----------- | ----------- |
| Fórmula   |  Gênero-literário("Sci-fi")       |
| Definições de Predicados/Funções   | Gênero literário(X): X é um gênero literário.|

---------------------------------------
| Frase   |   H.G. Wells era um escritor.   |
| ----------- | ----------- |
| Fórmula   |  Escritor("H. G. Wells")       |
| Definições de Predicados/Funções   | Escritor(X): X era escritor.|


### Relações entre “objetos”

| Frase   |  Mary Shelley é mãe da ficção científica.   |
| ----------- | ----------- |
| Fórmula   |  mãe("Mary Shelley", "ficção científica")       |
| Definições de Predicados/Funções   | mãe(X,Y): X é mãe da Y.|

--------------------------------------------
| Frase   |  Hugo Gernsmarck nomeou a ficção científica.   |
| ----------- | ----------- |
| Fórmula   |  Nomeou("Hugo Gernsmarck", "ficção científica")       |
| Definições de Predicados/Funções   | Nomeou(X,Y): X nomeou Y.|

------------------------------------------
| Frase   |  Cyberpunk é um subgênero de sci-fi.   |
| ----------- | ----------- |
| Fórmula   |  Subgênero("Cyberpunk", "sci-fi")       |
| Definições de Predicados/Funções   | Subgênero(X,Y): X é subgênero de Y.|

-----------------------------------------------
| Frase   |  Capitão Nemo é um personagem de Vinte Mil Léguas Submarinas .   |
| ----------- | ----------- |
| Fórmula   |  Personagem("Capitão Nemo", "Vinte Mil Léguas Submarinas")       |
| Definições de Predicados/Funções   | Personagem(X,Y): X é personagem de Y.|

--------------------------------------------
| Frase   |  Samus Aran é uma personagem de Metroid.   |
| ----------- | ----------- |
| Fórmula   |  Personagem("Samus Aran", "Metroid")       |
| Definições de Predicados/Funções   | Personagem(X,Y): X é personagem de Y.|

------------------------------------------------
### Negações

| Frase   |  Capitão Nemo não é sociável.   |
| ----------- | ----------- |
| Fórmula   |  ¬Sociável("Capitão Nemo")       |
| Definições de Predicados/Funções   |         |

--------------------------------------------
| Frase   |  Náutilus não é um monstro.   |
| ----------- | ----------- |
| Fórmula   |  ¬Monstro("Náutilus")       |
| Definições de Predicados/Funções   | |

------------------------------------------
### Conjunções

| Frase   |  Cyber-espaço é um conceito e saiu do livro Neuromancer.   |
| ----------- | ----------- |
| Fórmula   |  Conceito("Cyber-espaço") ^ Saiu("Cyber-espaço","livro Neuromancer")       |
| Definições de Predicados/Funções   | Conceito(X). Saiu(X,Y): Y retorna de onde X saiu.    |

--------------------------------------------
| Frase   |  A Matrix é um mundo e um cyber-espaço.   |
| ----------- | ----------- |
| Fórmula   |  Mundo("Matrix") ^ Cyber-espaço("Matrix")      |
| Definições de Predicados/Funções   | Mundo(X). Cyber-espaço(X). |

------------------------------------------
### Disjunções

| Frase   |  Star Wars é ficção científica ou fantástica.   |
| ----------- | ----------- |
| Fórmula   |  Científica("Star Wars") ∨ Fantástica("Star Wars")     |
| Definições de Predicados/Funções   | Científica(X): retorna que ficção X é. Fantástica(X): retorna que ficção X é.  |

--------------------------------------------
| Frase   |  Dieselpunk é mais moderno ou menos moderno que Cyberpunk.   |
| ----------- | ----------- |
| Fórmula   |  Mais("Dieselpunk") ∨ Menos("Dieselpunk","Cyberpunk")      |
| Definições de Predicados/Funções   | Mais(X). Menos(X,Y): retorna se X é mais moderno ou menos moderno que Y. |

------------------------------------------
### Implicações

| Frase   | Androides não sonham com ovelhas elétricas, então eles sonham com ovelhas reais.    |
| ----------- | ----------- |
| Fórmula   |  ¬Sonham("Androides","ovelhas elétricas") → Sonham("Androides","ovelhas reais")      |
| Definições de Predicados/Funções   | ¬Sonham(X,Y): X não sonha com Y. Sonham(X,Z): X sonha com Z.  |

--------------------------------------------
| Frase   |  B.O.R.E.A.S é um I.A, então B.O.R.E.A.S pensa.  |
| ----------- | ----------- |
| Fórmula   |  I.A("B.O.R.E.A.S") → pensa("B.O.R.E.A.S")      |
| Definições de Predicados/Funções   | |

------------------------------------------
### Generalizações Universais

| Frase   |  Nem todo personagem de metroid representa femininismo.   |
| ----------- | ----------- |
| Fórmula   |  ¬&forall;xMetroid("Personagem") = Representa("feminismo") |
| Definições de Predicados/Funções   | ¬&forall;xMetroid("Personagem"). Representa(Y): Y retorna o que nem todo X representa.|

----------------------------------
| Frase   |  Todo emissário tem séculos de idade.   |
| ----------- | ----------- |
| Fórmula   |  &forall;xTem("Emissário","Séculos de idade") |
| Definições de Predicados/Funções   | &forall;xTem("X","Y"): Todo X tem Y.|

------------------------------------------------
| Frase   |  Todo humano é hospedeiro dos aliens.   |
| ----------- | ----------- |
| Fórmula   |  &forall;xHospedeiro("Emissário","aliens") |
| Definições de Predicados/Funções   | &forall;xHospedeiro("X","Y"): Todo X é hospedeiro de Y.|

------------------------------------------------
### Generalizações Existenciais

| Frase   |  Há pelo menos uma ficção não científica.   |
| ----------- | ----------- |
| Fórmula   |  ∃y(Ficção(y) → ¬Científica(y)) |
| Definições de Predicados/Funções   | Ficção(X): X é uma ficção. ¬Científica(X): X não é científica.|

----------------------------------
| Frase   |  Há pelo menos uma água viva que não sabe de si.   |
| ----------- | ----------- |
| Fórmula   | ∃y(Não-sabe-de-si(y)  |
| Definições de Predicados/Funções   | Não sabe de si(Y): Y não sabe de si.|

------------------------------------------------
| Frase   |  Para toda light-novel há pelo menos um drama pós-apocalíptico.   |
| ----------- | ----------- |
| Fórmula   |  &forall;y("Ligh-novel")   ∃y(drama-pós-apocalíptico((y))  |
| Definições de Predicados/Funções   |  |

------------------------------------------------

## Assinatura

&Sigma;=[R¹, R², C, F¹, F&sup2;, V]

R¹ ={Ateu, Gênero-literário, Escritor, Sociável, Monstro, Conceito, Cyber-espaço, Científica, Mais, I.A, Pensa, Metroid, Ficção, Não-sabe-de-si, drama-pós-apocalíptico}

-------------------------------------------------
R² ={mãe, Nomeou, Subgênero,  Sonham, Tem,Hospedeiro}

------------------------------------------------
C ={"Isaac Asimov", "Sci-fi", "H. G. Wells", "Mary Shelley", "ficção científica", "Hugo Gernsmarck", "Cyberpunk",  "sci-fi", "Capitão Nemo", "Vinte Mil Léguas Submarinas", "Samus Aran", "Metroid", "Náutilus", "Cyber-espaço", "livro Neuromancer", "Matrix", "Star Wars", "Dieselpunk", "Androides", "ovelhas elétricas", "ovelhas reais", "B.O.R.E.A.S", "feminismo", "Personagem", "Emissário", "Séculos de idade", "aliens"}

-----------------------------------------------
 F¹ ={Mundo, Fantástica, Representa}

------------------------------------------------
 F² ={Saiu, Menos}

------------------------------------------------
V={X, Y, Z}

## Modelos

### Exemplo de modelo que satisfaz todas as fórmulas (M&#x2081;)

1. Universo de valores concretos
 
A={vc1, vc2, vc3,vc4, vc5, vc6,vc7, vc8, vc9,vc10, vc11, vc12,vc13, vc14, vc15,vc16, vc17, vc18,vc19, vc20, vc21,vc22, vc23, vc24,vc25, vc26,vc27}

2. Constantes

- "Isaac Asimov"<sup>M<sub>1</sub></sup> =vc1
- "Sci-fi"<sup>M<sub>1</sub></sup> =vc2
- "H. G. Wells"<sup>M<sub>1</sub></sup> =vc3
- "Mary Shelley"<sup>M<sub>1</sub></sup> =vc4
- "ficção científica"<sup>M<sub>1</sub></sup> =vc5
- "Hugo Gernsmarck"<sup>M<sub>1</sub></sup> =vc6
- "Cyberpunk"<sup>M<sub>1</sub></sup>=vc7
- "sci-fi"<sup>M<sub>1</sub></sup> =vc8
- "Capitão Nemo"<sup>M<sub>1</sub></sup> =vc9
- "Vinte Mil Léguas Submarinas"<sup>M<sub>1</sub></sup> =vc10
- "Samus Aran"<sup>M<sub>1</sub></sup> =vc11
- "Metroid"<sup>M<sub>1</sub></sup> =vc12
- "Náutilus"<sup>M<sub>1</sub></sup> =vc13
- "Cyber-espaço"<sup>M<sub>1</sub></sup> =vc14
- "livro Neuromancer"<sup>M<sub>1</sub></sup> =vc15
- "Matrix"<sup>M<sub>1</sub></sup> =vc16
- "Star Wars"<sup>M<sub>1</sub></sup> =vc17
- "Dieselpunk"<sup>M<sub>1</sub></sup> =vc18
- "Androides"<sup>M<sub>1</sub></sup> =vc19
- "ovelhas elétricas"<sup>M<sub>1</sub></sup> =vc20
- "ovelhas reais"<sup>M<sub>1</sub></sup> =vc21
- "B.O.R.E.A.S"<sup>M<sub>1</sub></sup> =vc22
- "feminismo"<sup>M<sub>1</sub></sup> =vc23
- "Personagem"<sup>M<sub>1</sub></sup> =vc24
- "Emissário"<sup>M<sub>1</sub></sup> =vc25
- "Séculos de idade"<sup>M<sub>1</sub></sup> =vc26
- "aliens"<sup>M<sub>1</sub></sup> =vc27

3. Funções
 
Mundo<sup>M<sub>1</sub></sup> (vc14)=vc16<br>
Fantástica<sup>M<sub>1</sub></sup> (...)=vc17<br>
Representa<sup>M<sub>1</sub></sup> (vc12)=vc24<br>
Saiu<sup>M<sub>1</sub></sup> (...)=vc14,vc15
<br>Menos<sup>M<sub>1</sub></sup> (...)=vc18,vc19

4. Predicados

Ateu<sup>M<sub>1</sub></sup> = {vc1}<br>
Gênero-literário<sup>M<sub>1</sub></sup> ={vc2}<br>
Escritor<sup>M<sub>1</sub></sup> ={vc3}<br>
Sociável <sup>M<sub>1</sub></sup> ={vc9} <br>
Monstro<sup>M<sub>1</sub></sup> ={vc13}<br>
Conceito<sup>M<sub>1</sub></sup> ={vc14}<br>
Cyber-espaço <sup>M<sub>1</sub></sup> ={vc15}<br>
Científica <sup>M<sub>1</sub></sup> ={vc17}<br>
Mais<sup>M<sub>1</sub></sup> ={vc18}<br>
I.A<sup>M<sub>1</sub></sup> ={vc22}<br>
Pensa<sup>M<sub>1</sub></sup> ={vc22}<br>
Metroid<sup>M<sub>1</sub></sup> ={vc23,vc24}<br>
Ficção<sup>M<sub>1</sub></sup> ={....}<br>
Não-sabe-de-si<sup>M<sub>1</sub></sup> ={...}<br>
drama-pós-apocalíptico <sup>M<sub>1</sub></sup> ={...}<br>
mãe <sup>M<sub>1</sub></sup> ={vc4,vc5}<br>
Nomeou<sup>M<sub>1</sub></sup> ={vc5,vc6}<br>
Subgênero <sup>M<sub>1</sub></sup> ={vc7,vc18}<br>
Sonham <sup>M<sub>1</sub></sup> ={vc20,vc21}<br>
Tem <sup>M<sub>1</sub></sup> ={vc25,vc26}<br>
Hospedeiro <sup>M<sub>1</sub></sup> ={vc27}
 

### Exemplo de modelo que não satisfaz todas as fórmulas (M&#x2082;)

1. Universo de valores concretos
 
A={vc1, vc2, vc3,vc4, vc5, vc6,vc7, vc8, vc9,vc10, vc11, vc12,vc13, vc14, vc15,vc16, vc17, vc18,vc19, vc20, vc21,vc22, vc23, vc24,vc25, vc26,vc27,vc28,vc29}

2. Constantes

- "Isaac Asimov"<sup>M<sub>2</sub></sup> =vc1
- "Sci-fi"<sup>M<sub>2</sub></sup> =vc2
- "H. G. Wells"<sup>M<sub>2</sub></sup> =vc3
- "Mary Shelley"<sup>M<sub>2</sub></sup> =vc4
- "ficção científica"<sup>M<sub>2</sub></sup> =vc5
- "Hugo Gernsmarck"<sup>M<sub>2</sub></sup> =vc6
- "Biopunk"<sup>M<sub>2</sub></sup>=vc7
- "sci-fi"<sup>M<sub>2</sub></sup> =vc8
- "Capitão Nemo"<sup>M<sub>2</sub></sup> =vc9
- "Vinte Mil Léguas Submarinas"<sup>M<sub>2</sub></sup> =vc10
- "Samus Aran"<sup>M<sub>2</sub></sup> =vc11
- "Metroid"<sup>M<sub>2</sub></sup> =vc12
- "Náutilus"<sup>M<sub>2</sub></sup> =vc13
- "Cyber-espaço"<sup>M<sub>2</sub></sup> =vc14
- "livro Neuromancer"<sup>M<sub>2</sub></sup> =vc15
- "Matrix"<sup>M<sub>2</sub></sup> =vc16
- "Star Wars"<sup>M<sub>2</sub></sup> =vc17
- "Dieselpunk"<sup>M<sub>2</sub></sup> =vc18
- "Androides"<sup>M<sub>2</sub></sup> =vc19
- "ovelhas elétricas"<sup>M<sub>2</sub></sup> =vc20
- "ovelhas reais"<sup>M<sub>2</sub></sup> =vc21
- "B.O.R.E.A.S"<sup>M<sub>2</sub></sup> =vc22
- "feminismo"<sup>M<sub>2</sub></sup> =vc23
- "Personagem"<sup>M<sub>2</sub></sup> =vc24
- "Emissário"<sup>M<sub>2</sub></sup> =vc25
- "Séculos de idade"<sup>M<sub>2</sub></sup> =vc26
- "aliens"<sup>M<sub>2</sub></sup> =vc27
- "Cyberpunk"<sup>M<sub>2</sub></sup> =vc28
- "Dançarino"<sup>M<sub>2</sub></sup> =vc29


3. Funções
 
Mundo<sup>M<sub>2</sub></sup> (vc14)=vc16<br>
Fantástica<sup>M<sub>2</sub></sup> (...)=vc17<br>
Representa<sup>M<sub>2</sub></sup> (vc12)=vc24<br>
Saiu<sup>M<sub>2</sub></sup> (...)=vc14,vc15<br>
Menos<sup>M<sub>2</sub></sup> (...)=vc28,vc19<br>

4. Predicados

Ateu<sup>M<sub>2</sub></sup> = {vc1}<br>
Gênero-literário<sup>M<sub>2</sub></sup> ={vc2}<br>
Dançarino<sup>M<sub>2</sub></sup> ={vc3}<br>
Sociável <sup>M<sub>2</sub></sup> ={vc9} <br>
Monstro<sup>M<sub>2</sub></sup> ={vc13}<br>
Conceito<sup>M<sub>2</sub></sup> ={vc14}<br>
Cyber-espaço <sup>M<sub>2</sub></sup> ={vc15}<br>
Científica <sup>M<sub>2</sub></sup> ={vc17}<br>
Mais<sup>M<sub>2</sub></sup> ={vc28}<br>
I.A<sup>M<sub>2</sub></sup> ={vc22}<br>
Pensa<sup>M<sub>2</sub></sup> ={vc22}<br>
Metroid<sup>M<sub>2</sub></sup> ={vc23,vc24}<br>
Ficção<sup>M<sub>2</sub></sup> ={....}<br>
Não-sabe-de-si<sup>M<sub>2</sub></sup> ={...}<br>
drama-pós-apocalíptico <sup>M<sub>2</sub></sup> ={...}<br>
mãe <sup>M<sub>2</sub></sup> ={vc4,vc5}<br>
Nomeou<sup>M<sub>2</sub></sup> ={vc5,vc6}<br>
Subgênero <sup>M<sub>2</sub></sup> ={vc7,vc18}<br>
Sonham <sup>M<sub>2</sub></sup> ={vc20,vc21}<br>
Tem <sup>M<sub>2</sub></sup> ={vc25,vc26}<br>
Hospedeiro <sup>M<sub>2</sub></sup> ={vc27}<br>
Escritor <sup>M<sub>2</sub></sup> ={ }<br>
Biopunk <sup>M<sub>2</sub></sup> ={ }
