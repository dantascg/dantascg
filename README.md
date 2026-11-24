# Leonardo Dantas

`Desenvolvedor Back-end / Full-stack`

<a href="mailto:leonardodaaj@gmail.com"><img src="https://img.shields.io/badge/Gmail-leonardodaaj%40gmail.com-1a1b27?style=flat-square&logo=gmail&logoColor=white" /></a>
<img src="https://img.shields.io/badge/Maceió-AL-1a1b27?style=flat-square&logo=googlemaps&logoColor=white" />
<img src="https://img.shields.io/badge/Aberto_a-estágio-1a1b27?style=flat-square" />


## Sobre mim

Estudante de **Ciência da Computação** na UNINASSAU (6º período), com foco em desenvolvimento **back-end com Python e Django**. Gosto de resolver problemas reais: já fiz desde um sistema de gestão que usa **IA generativa** pra transformar mensagens de WhatsApp em pedidos até uma **API de folha de pagamento** com as regras de INSS e IRRF.

- Procurando **estágio em desenvolvimento de software** (back-end / full-stack)
- Trabalho mais com Python, Django, Django REST Framework e APIs REST
- Me preocupo com testes automatizados, segurança e integridade dos dados
- Inglês avançado: leio documentação técnica e acompanho reuniões


## Tecnologias

<p>
  <img src="https://skillicons.dev/icons?i=python,django,postgres,sqlite,supabase,git,github,ts,js,nextjs,react,html,css,java,dart,flutter&theme=dark" />
</p>


## Projetos em destaque

#### [Extrait Club System](https://github.com/dantascg/extrait_sys)
Sistema de gestão para venda de decants de perfume que acontecia em grupos de WhatsApp. O operador cola a mensagem, a **IA (GPT-OSS 120B via Groq)** extrai os pedidos em JSON, uma pessoa revisa (*draft-first*) e o sistema grava tudo com **transações atômicas**, controla estoque em ml e gera as cobranças. Tem login obrigatório, validação no servidor da saída da IA, proteção contra XSS e testes automatizados.

<p align="center">
  <a href="https://github.com/dantascg/extrait_sys"><img src="https://raw.githubusercontent.com/dantascg/extrait_sys/main/docs/screenshots/revisao.png" width="85%" alt="Tela de revisão do Extrait Club" /></a>
</p>

`Python` `Django` `Groq API` `LLM` `SQLite` `Testes`

#### [Nexo — Projeto de Extensão em Segurança de Dados](https://github.com/yanswo/nexo)
Plataforma web feita em equipe num projeto de extensão universitária sobre **segurança de dados**. Minhas contribuições:
- **Autenticação com Supabase:** cadastro, login e sessão com cookies no servidor, e um *proxy* que renova a sessão e protege as rotas privadas.
- **Aba de Segurança:** um **testador de senhas** que mede a força com `zxcvbn` e verifica se a senha já vazou na base do *Have I Been Pwned* usando **k-anonymity**. Só os 5 primeiros caracteres do hash SHA-1 saem do navegador, então a senha nunca é enviada. Também fiz um **quiz de phishing** e um checklist de boas práticas.

`Next.js` `React` `TypeScript` `Supabase` `Segurança da Informação`

#### [API de Folha de Pagamento](https://github.com/dantascg/sistema-rh-backend)
API REST com o motor de cálculo da folha de pagamento, aplicando as faixas progressivas de **INSS e IRRF de 2025**. Usa `Decimal` pra evitar erro de arredondamento em dinheiro, valida tudo nos Serializers e tem cobertura de testes unitários.
`Python` `Django REST Framework` `APIs REST` `Unit Tests`

#### [App Minhas Receitas](https://github.com/dantascg/receitas-app-mobile)
App mobile feito em equipe para organizar receitas, funcionando offline. Fiquei responsável pela arquitetura, pela interface e pela persistência local.
`React Native` `Expo` `Context API` `AsyncStorage`

#### [Jurandir Corretor](https://github.com/dantascg/Jurandir-corretor)
Site de imobiliária com vitrine pública e painel para cadastrar imóveis. Autenticação e banco no **Supabase** com políticas RLS, e tratamento das fotos no navegador (redimensiona e remove os metadados EXIF).
`HTML` `CSS` `JavaScript` `Supabase`

<details>
<summary><b>Ver mais projetos</b></summary>
<br>

| Projeto | Descrição | Stack |
|---|---|---|
| [tibia-api](https://github.com/dantascg/tibia-api) | Busca de personagens do Tibia consumindo a API TibiaData | Python · Django |
| [Desafio Felicidade 2019](https://github.com/dantascg/synapta-desafio-felicidade-2019) | Análise de dados do Relatório Mundial de Felicidade (156 países) | Python · pandas · matplotlib |
| [paradigmas-taskmanager](https://github.com/dantascg/paradigmas-taskmanager) | Melhoria com testes num gerenciador de tarefas open source | Python |
| [projeto_escola_flutter](https://github.com/dantascg/projeto_escola_flutter) | App escolar com perfis de aluno, professor e coordenador | Flutter · Dart |
| [CineClick](https://github.com/dantascg/CineClick) | Site para amantes de filmes e séries | HTML · CSS |

</details>


## Estatísticas

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=dantascg&show_icons=true&theme=tokyonight&hide_border=true&locale=pt-br&include_all_commits=true" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=dantascg&layout=compact&theme=tokyonight&hide_border=true&locale=pt-br" />
</p>

<p align="center">
  <img src="https://streak-stats.demolab.com?user=dantascg&theme=tokyonight&hide_border=true&locale=pt_BR" />
</p>
