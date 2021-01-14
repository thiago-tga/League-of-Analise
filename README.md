# LEAGUE OF ANALISE

## Introdução

League of Analise é um conjunto de dashboards que visa maximizar a performance de times e jogadores profissionais por meio das análise de suas partidas.

## Tabela de Conteúdos

<!--ts-->
   * [Introdução](#Introducao)
   * [Tabela de Conteudo](#tabela-de-conteudo)
   * [Status do projeto](#status-do-projeto)
   * [Informações do projeto](#informacoes-do-projeto)
      * [Variáveis de ambiente](#variaveis-de-ambiente)
      * [Portas de acesso](#portas-de-acesso)
      * [Dependências](#dependencias)
   * [Autores](#autores)     
<!--te-->
## Status do projeto

League of Analise está em construção

## Informações do projeto

### Variáveis de ambiente
|         Nome          |            Padrão            |                   Descrição                    |
| :-------------------: | :--------------------------: | :--------------------------------------------: |
| `MYSQL_ROOT_PASSWORD` |         `secret-pwd`         |                 Senha do root                  |
|   `MYSQL_DATABASE`    |     `League-of-Analise`      |               Banco a ser criado               |
|     `MYSQL_USER`      |         `LOA123USER`         |   Usuário com permissões para atuar no banco   |
|   `MYSQL_PASSWORD`    |       `LOA123PASSWORD`       |                Senha do usuário                |
|    `JAVA_TIMEZONE`    |         `US/Pacific`         |                  Fuso horário                  |
|     `MB_DB_FILE`      | `/metabase-data/metabase.db` |         Arquivo com dados do metabase          |
|     `MB_DB_TYPE`      |           `mysql`            |       Configuração do banco do Metabase        |
|    `MB_DB_DBNAME`     |     `League-of-Analise`      | Banco a ser utilizado pelo sistema do Metabase |
|     `MB_DB_PORT`      |            `3306`            |                 Porta do MySQL                 |
|     `MB_DB_USER`      |         `LOA123USER`         | Usuário que o Metabase deve utilizar no banco  |
|     `MB_DB_PASS`      |       `LOA123PASSWORD`       |          Senha do usuário do Metabase          |
|     `MB_DB_HOST`      |           `mysql`            |           Nome do container do MySQL           |

### Portas de acesso
| Serviço  | Porta padrão |
| :------: | :----------: |
| Metabase |     3000     |
|  MySQL   |     3306     |

## Dependências
- `docker`
- `docker-compose`
- `git bash` - opcional

> O `git bash` é necessário devido a uma falha no `docker-compose`.

## Iniciando o ambiente

#### Passo 1: Entrar no diretório do projeto

```bash
 $ cd <caminho-do-projeto>
```

#### Passo 2: Iniciar o ambiente

```bash
$ docker-compose up
```
#### Passo 3: Iniciar o metabase

#### Observações:

- O MySQL está utilizando a porta 3306 por padrão, se necessário, isso pode ser alterado no arquivo `docker-compose.yml`
- Se encontrar algum erro com o código 87, tente iniciar o docker-compose pelo git bash

## Autores
<table>
  <tr>
    <td align="center">
      <a href="https://github.com/thiago-tga"><img style="border-radius: 50%;" src="https://media-exp1.licdn.com/dms/image/C4D03AQHR-AZMVpN9iA/profile-displayphoto-shrink_400_400/0/1610584257602?e=1616025600&v=beta&t=-nYa_s1xQjXgPNRmpIPf1EWWFsXH3Px7dHmpzEMj-2I" width="100px;" alt=""/><br /><sub><b>Thiago Gomes</b></sub>
      </a>
      <br />
      <a href="https://github.com/thiago-tga" title="GitHub">💻
      <a href="https://www.instagram.com/thiaguio/" title="instagram">📷
      <a href="https://www.linkedin.com/in/thiago-araujo-23761115a/" title="linkedin">💼
      </a>
      </td>
    <td align="center">
      <a href="https://github.com/ericwdw"><img style="border-radius: 50%;" src="https://media-exp1.licdn.com/dms/image/C4E03AQGpNM1tpAROkg/profile-displayphoto-shrink_800_800/0/1610571216667?e=1616025600&v=beta&t=VKiTo1YaXKHklmhfhyom6S4SIeqIGlc-v7lD28Iggh4" width="100px;" alt=""/><br /><sub><b>Eric Abrunhosa</b></sub>
      </a>
      <br />
      <a href="https://github.com/ericwdw" title="GitHub">💻
      <a href="https://www.instagram.com/abrunhosaeric/" title="instagram">📷
      <a href="https://www.linkedin.com/in/eric-gomes-silva-abrunhosa-119176114/" title="linkedin">💼
      </a>
      </td>
      <td align="center">
      <a href="https://github.com/araujo-gui"><img style="border-radius: 50%;" src="https://scontent-gig2-1.cdninstagram.com/v/t51.2885-15/e35/128150499_2813583022219207_7403888593573471144_n.jpg?_nc_ht=scontent-gig2-1.cdninstagram.com&_nc_cat=107&_nc_ohc=3wTqbaWNWtMAX_Lt3BK&tp=1&oh=3c290cb720da417bae5ca982f4491af8&oe=6028F0CA" width="100px;" alt=""/><br /><sub><b>Guilhermina Araujo</b></sub>
      </a>
      <br />
      <a href="https://github.com/araujo-gui" title="GitHub">💻
      <a href="https://www.instagram.com/guiiaaraujo_/" title="instagram">📷
      <a href=" https://www.linkedin.com/in/guilhermina-ara%C3%BAjo-b780b5108/" title="linkedin">💼
      </a>
      </td>
      <td align="center">
      <a href="https://github.com/HenryLucena"><img style="border-radius: 50%;" src="blob:https://web.whatsapp.com/d0e20c82-5e72-410c-9f8e-1a7d27c89533" width="100px;" alt=""/><br /><sub><b>Henryque Lucena</b></sub>
      </a>
      <br />
      <a href="https://github.com/HenryLucena" title="GitHub">💻
      <a href="https://www.facebook.com/henryque.lucena" title="instagram">📷
      <a href="https://www.linkedin.com/in/henryque-porto-6486a91b0" title="linkedin">💼
      </a>
      </td>
      <td align="center">
      <a href="https://github.com/ScarlateAlves"><img style="border-radius: 50%;" src="https://avatars2.githubusercontent.com/u/71666563?s=460&u=7eaab4581687f896fa8c83353b1cd18b83791002&v=4" width="100px;" alt=""/><br /><sub><b>Scarlet Alves</b></sub>
      </a>
      <br />
      <a href="https://github.com/ScarlateAlves" title="GitHub">💻
      <a href="https://www.instagram.com/scaralves10/" title="instagram">📷
      <a href="https://www.linkedin.com/in/scarlate-alves-518ab5127/" title="linkedin">💼
      </a>
      </td>
  </tr>
</table>