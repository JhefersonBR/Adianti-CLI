# Adianti-CLI (Em Desenvolvimento)
###### Ferramenta de prompt de comando para uso do Adianti Framework

A ideia deste projeto é utilizar o terminal para gerar codigo do [Adianti Framework](https://www.adianti.com.br/framework "Adianti Framework")

#### Features:
Atraves de alguns comandos no terminal é possível gerar codigo para seu projeto, a idéia é utilizar um **Wizard** via terminal para auxciliar na criação dos componentes.

Com o comando abaixo pro exemplo será possível criar Controles para seu projeto.

```bash
Adianti create control
```

```bash
Adianti create model
```

```bash
Adianti create service
```
Será possível também adicionar componentes de outros usuários atraves, semelhante ao que o composer faz, porém obedecendo a estrutura de arquivos do Adianti. 
Veja:
```bash
Adianti require JhefersonBR/TMediaPlayer
```
Tambem será possível iniciar um novo projeto com o Adianti Framework com apenas uma linha:
```bash
Adianti init
```