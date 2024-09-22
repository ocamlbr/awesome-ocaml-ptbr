---
title: "Awesome OCaml Packages"
date: 2024-09-21
draft: false
description: "Uma lista curada de bibliotecas e ferramentas úteis em OCaml"
---

# Awesome OCaml Packages

## Ferramentas de Build e Gerenciamento de Pacotes
- [Dune](https://dune.build) - Sistema de build para OCaml.
- [Opam](https://opam.ocaml.org) - Gerenciador de Pacotes OCaml.

## Ferramentas de Desenvolvimento
- [ocaml-lsp](https://github.com/ocaml/ocaml-lsp) - Servidor de Protocolo de Linguagem OCaml (LSP).
- [Merlin](https://github.com/ocaml/merlin) - Assistente de contexto para editores de OCaml.

## Desenvolvimento Web
- [Dream](https://aantron.github.io/dream/) - Um framework web fullstack com OCaml.
- [Opium](https://github.com/rgrinberg/opium) - Framework Web Sinatra-like para OCaml.
- [Lwt](https://github.com/ocsigen/lwt) - Uma biblioteca de programação concorrente.
- [Cohttp](https://github.com/mirage/ocaml-cohttp) - Uma biblioteca HTTP para OCaml.
- [Piaf](https://github.com/anmonteiro/piaf) - Um cliente HTTP/1.X e HTTP/2 totalmente assíncrono para OCaml.

## Parsing e Metaprogramação 
- [Menhir](http://gallium.inria.fr/~fpottier/menhir/) - Um gerador de parser LR(1) para OCaml.
- [ocaml-re](https://github.com/ocaml/ocaml-re) - Biblioteca de expressões regulares para OCaml.
- [Angstrom](https://github.com/inhabitedtype/angstrom) - Parser combinators.
- [ppxlib](https://github.com/ocaml-ppx/ppxlib) - Biblioteca base para extensões de sintaxe em OCaml (PPX).

## PPXs
- [ppx_deriving](https://github.com/ocaml-ppx/ppx_deriving) - Extensão de sintaxe para derivar automaticamente implementações de tipos e funções.
- [ppx_let](https://github.com/janestreet/ppx_let) - Sintaxe de açúcar para monads em OCaml.
- [ppx_import](https://github.com/ocaml-ppx/ppx_import) - Uma extensão de sintaxe para importar assinaturas de módulos.
- [ppx_sexp_conv](https://github.com/janestreet/ppx_sexp_conv) - Gera código para converter valores OCaml de/para S-expressions.
- [ppx_fields_conv](https://github.com/janestreet/ppx_fields_conv) - Gera código para acessar e iterar sobre campos de registros.
- [ppx_custom_printf](https://github.com/janestreet/ppx_custom_printf) - Extensão para formatar strings com sintaxe estendida.

## Testes e Qualidade de Código
- [Alcotest](https://github.com/mirage/alcotest) - Um framework de testes de unidade leve e com suporte a cores.
- [OUnit](https://github.com/gildor478/ounit) - Framework de teste de unidade XUnit para OCaml.
- [QCheck](https://github.com/c-cube/qcheck) - Biblioteca de testes baseados em propriedades para OCaml.

## Serialização e Formatação
- [Yojson](https://github.com/ocaml-community/yojson) - Uma biblioteca OCaml para codificação e decodificação JSON.

## Análise Estática e Documentação
- [OCamlFormat](https://github.com/ocaml-ppx/ocamlformat) - Um formatador de código automático para OCaml.
- [fmt](https://github.com/dbuenzli/fmt) - Formatação de Código OCaml.
- [odoc](https://github.com/ocaml/odoc) - Documentação de código.

## Matemática e Computação Científica
- [Owl](https://github.com/owlbarn/owl) - Uma biblioteca de computação científica e numérica para OCaml.

## Interface Gráfica e Linha de Comando
- [Lablgtk](https://github.com/garrigue/lablgtk) - Interface OCaml para GTK+ (bindings).
- [cmdliner](https://github.com/dbuenzli/cmdliner) - Biblioteca para criar aplicações de linha de comando.

## Banco de Dados
- [Caqti](https://github.com/paurkedal/ocaml-caqti) - Uma biblioteca de abstração para acesso a banco de dados relacionais com suporte a MariaDB, PostgreSQL e SQLite3.
- [sqlite3](https://github.com/mmottl/sqlite3-ocaml) - Bindings OCaml para SQLite3.
- [Irmin](https://irmin.org/) - Uma biblioteca de banco de dados distribuído que segue os princípios do Git.

## Criptografia e Segurança
- [Mirage-crypto](https://github.com/mirage/mirage-crypto) - Uma biblioteca de criptografia usada no MirageOS.

## Processamento de Dados
- [csvtool](https://github.com/Chris00/ocaml-csv) - Uma biblioteca e ferramenta de linha de comando para manipulação de arquivos CSV.

## Sistemas Operacionais e Arquivos
- [BOS](https://erratique.ch/software/bos) - Uma biblioteca para interação com o Sistema Operacional (incluindo manipulação de arquivos) via OCaml.

## Redes e Protocolos
- [ocaml-tls](https://github.com/mirleft/ocaml-tls) - Implementação TLS em OCaml puro.

## Interoperabilidade com JavaScript
- [Melange](https://github.com/melange-re/melange) - Um backend para o compilador OCaml que emite JavaScript legível e eficiente.
- [mlx](https://github.com/ocaml-mlx/mlx) - Uma biblioteca que adiciona a uso de JSX em OCaml permitindo uma sintaxe agradável para React em OCaml puro, compilado com Melange.
- [js_of_ocaml](https://github.com/ocsigen/js_of_ocaml) - Compilador de OCaml para JavaScript.

## Bibliotecas Open Source da Jane Street

> A Jane Street é uma empresa que contribui significativamente para o ecossistema OCaml. As bibliotecas que eles publicam tem uma grande sinergia entre si e possuem padrões próprios, mas ainda são muito úteis em projetos gerais.

- [Core](https://github.com/janestreet/core) - Uma biblioteca alternativa à biblioteca padrão do OCaml.
- [Async](https://github.com/janestreet/async) - Uma biblioteca para programação assíncrona.
- [Base](https://github.com/janestreet/base) - Uma biblioteca base completa para OCaml.
- [Incremental](https://github.com/janestreet/incremental) - Uma biblioteca para computações incrementais.
- [Bonsai](https://github.com/janestreet/bonsai) - Uma biblioteca para criar interfaces de usuário web reativas.
- [Ppx_jane](https://github.com/janestreet/ppx_jane) - Uma coleção de extensões de sintaxe ppx comumente usadas.
- [Incr_dom](https://github.com/janestreet/incr_dom) - Uma biblioteca para construir aplicações web dinâmicas usando OCaml.
- [Textutils](https://github.com/janestreet/textutils) - Ferramentas de texto e formatação.
- [Sexplib](https://github.com/janestreet/sexplib) - Serialização e desserialização de S-expressions.
- [Bin_prot](https://github.com/janestreet/bin_prot) - Uma biblioteca para serialização binária rápida.
- [Fieldslib](https://github.com/janestreet/fieldslib) - Sintaxe e funções para trabalhar com campos de registros.
- [Typerep](https://github.com/janestreet/typerep) - Representações de tipos em tempo de execução.
- [Variantslib](https://github.com/janestreet/variantslib) - Funções para trabalhar com variantes.
- [Parsexp](https://github.com/janestreet/parsexp) - Parsing de S-expressions.
- [Ppx_let](https://github.com/janestreet/ppx_let) - Uma extensão de sintaxe para expressões let generalizadas.
