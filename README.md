# Repositório nº 2 do Projeto sobre Git/GitHub da Dio
Desafio2 do projeto sobre Git/GitHub

## Anotações importantes sobre a aula 🖊️
### Git & GitHub

Git é um sistema de controle de versão distribuído de código aberto e gratuito, projetado para lidar com tudo, de projetos pequenos a grandes. O que isso significa? Significa que com o Git é possível manter um histórico das alterações dos seus arquivos, sabendo quem, por que e quando um arquivo foi editado.
Github e Gitlab são plataformas de hospedagem de código-fonte. Elas permitem que os desenvolvedores contribuam em projetos privados ou abertos (mais conhecidos como projetos open source).
É um repositorio de armazenamento e repositorio de codigo.

#### Qual a principal funcionalidade do Git?
A principal funcionalidade do Git, que o faz ser amplamente utilizado em projetos de desenvolvimento de software, é a possibilidade de fazer o controle de versões de modo colaborativo, ou seja, é possível que o mesmo arquivo seja modificado ao mesmo tempo por dois desenvolvedores diferentes, e que ambas as alterações sejam salvas sem que nenhum código seja sobrescrito.

#### Navegação via command line interface e instalação
Windowx   = - cd  - dir   - mkdir   - del/rmdir
 Unix = - cd  -ls  -mkdir  -rm-rf

#### SHA1 = A sigla SHA significa Secure Hash Algorithm (Algoritmo de Hash Seguro), é um conjunto de funções hash criptográficas projetadas pela NSA (Agência de Segurança Nacional dos EUA).
A encriptaação gera conjunto de caracteres identificador de 40 dígitos.
È uma forma curta de representar um arquivo.


### Objetos fundamentais: 
BLOBS: tipo do objeto, tamanho do arquivo, barra ao contrario com o 0, conteudo de fato desse arquivo. Essa é a estrutura basica de um BLOB.
O BLOB contem metadados do GIT.


#### TREES (arvores):
Armazenam BLOBS. Contém tambem metadados. Guarda o nome do arquivo.
As árvores será responsável por toda estrutura onde estão localizados os arquivos. 

#### COMMITS: 
É o objeto que da sentido a alteração que você está fazendo.
Tem um carimbo de tempo, data, horario que foi criado.
Também possuem um SHA1. Uma vez que você altera o arquivo você altera toda a estrutura do commits. O commits é unico para cada autor.


#### Sistema distribuído:
A arquitetura distribuída faz parte de o que é GIT e isso facilita enormemente o processo de desenvolvimento. Em outros VCS, cada desenvolvedor trabalha em uma cópia do código, que fica armazenado em um repositório central. O que limita as possibilidades de trabalho, pois exige uma conexão ativa com o repositório.
O GIT, pelo contrário, fornece para todos os desenvolvedores seu próprio repositório local, com todo o histórico de  commits. O que traz uma série de vantagens e otimiza o seu desenvolvimento.

#### Segurança: 
O GIT também é um dos VCS mais seguros do mercado. Nele todo o conteúdo dos códigos, assim como a relação entre os diferentes arquivos, diretórios, versões e tags são criptograficamente protegidos por um algoritmo de hashing chamado SHA1.
Esse algoritmo consegue garantir segurança tanto contra mudanças acidentais quanto mudanças maliciosas e assegura que o histórico de alterações seja completamente rastreável.
Além disso, tudo no GIT tem seu checksum calculado antes que seja armazenado. O que significa que nada dentro desse VCS pode ser alterado e que nada pode ser perdido sem que ele perceba.

#### Markdown:
Uma forma mais humana de se escrever o arquivo HTML.
