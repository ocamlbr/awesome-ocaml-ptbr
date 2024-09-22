---
title: "Awesome OCaml Packages"
date: 2024-09-21
draft: false
description: "Uma lista curada de bibliotecas e ferramentas úteis em OCaml"
---

# Awesome OCaml Packages

## Gerenciamento de Pacotes e Ferramentas de Build
- [Opam](https://opam.ocaml.org) - Gerenciador de Pacotes OCaml.
- [Dune](https://dune.build) - Sistema de build para OCaml.
- [esy](http://esy.sh/) - Gerenciador de Pacotes para ReasonML e OCaml que faz mimese ao workflow do NPM.

## Ambiente de Desenvolvimento
- [utop](https://github.com/ocaml-community/utop) - REPL melhorado para OCaml com suporte a histórico, autocompletar e mais.
- [ocaml-lsp](https://github.com/ocaml/ocaml-lsp) - Servidor de Protocolo de Linguagem OCaml (LSP).
- [Merlin](https://github.com/ocaml/merlin) - Assistente de contexto de OCaml para VIM/Emacs.
- [tuareg](https://github.com/ocaml/tuareg) - Modo OCaml para Emacs.
- [ocaml.nvim](https://github.com/tjdevries/ocaml.nvim) - Ferramentas OCaml para Neovim.

## Frameworks e Bibliotecas Web
- [Dream](https://aantron.github.io/dream/) - Framework web fullstack para OCaml.
- [Opium](https://github.com/rgrinberg/opium) - Framework Web Sinatra-like para OCaml.
- [Lwt](https://github.com/ocsigen/lwt) - Biblioteca de programação concorrente.
- [Cohttp](https://github.com/mirage/ocaml-cohttp) - Biblioteca HTTP para OCaml.
- [Piaf](https://github.com/anmonteiro/piaf) - Cliente HTTP/1.X e HTTP/2 totalmente assíncrono para OCaml.
- [Async](https://github.com/janestreet/async) - Biblioteca para programação assíncrona. `Jane Street`

## Desenvolvimento Frontend
- [Melange](https://github.com/melange-re/melange) - Backend para o compilador OCaml que emite JavaScript legível e eficiente.
- [js_of_ocaml](https://github.com/ocsigen/js_of_ocaml) - Compilador de OCaml para JavaScript.
- [jsoo-react](https://github.com/ml-in-barcelona/jsoo-react) - Bindings ReactJS para js_of_ocaml.
- [mlx](https://github.com/ocaml-mlx/mlx) - Biblioteca para uso de JSX em OCaml, compatível com React e Melange.
- [Bonsai](https://github.com/janestreet/bonsai) - Biblioteca para criar interfaces de usuário web reativas. `Jane Street`
- [Incr_dom](https://github.com/janestreet/incr_dom) - Biblioteca para construir aplicações web dinâmicas usando OCaml. `Jane Street`

## Parsing e Metaprogramação 
- [Menhir](http://gallium.inria.fr/~fpottier/menhir/) - Gerador de parser LR(1) para OCaml.
- [ocaml-re](https://github.com/ocaml/ocaml-re) - Biblioteca de expressões regulares para OCaml.
- [Angstrom](https://github.com/inhabitedtype/angstrom) - Parser combinators.
- [ppxlib](https://github.com/ocaml-ppx/ppxlib) - Biblioteca base para extensões de sintaxe em OCaml (PPX).
- [Parsexp](https://github.com/janestreet/parsexp) - Parsing de S-expressions. `Jane Street`

## Extensões de Sintaxe (PPX)
- [ppx_deriving](https://github.com/ocaml-ppx/ppx_deriving) - Derivação automática de implementações de tipos e funções.
- [ppx_let](https://github.com/janestreet/ppx_let) - Sintaxe sugar para monads em OCaml. `Jane Street`
- [ppx_import](https://github.com/ocaml-ppx/ppx_import) - Importação de assinaturas de módulos.
- [ppx_sexp_conv](https://github.com/janestreet/ppx_sexp_conv) - Conversão de valores OCaml de/para S-expressions. `Jane Street`
- [ppx_fields_conv](https://github.com/janestreet/ppx_fields_conv) - Acesso e iteração sobre campos de registros. `Jane Street`
- [ppx_custom_printf](https://github.com/janestreet/ppx_custom_printf) - Formatação de strings com sintaxe estendida. `Jane Street`
- [Ppx_jane](https://github.com/janestreet/ppx_jane) - Coleção de extensões de sintaxe ppx comumente usadas. `Jane Street`

## Interoperabilidade com Outras Linguagens
- [ctypes](https://github.com/yallop/ocaml-ctypes) - Bindings para C.
- [pyml](https://github.com/thierry-martinez/pyml) - Bindings para Python.

## Testes e Qualidade de Código
- [Alcotest](https://github.com/mirage/alcotest) - Framework de testes de unidade leve com suporte a cores.
- [OUnit](https://github.com/gildor478/ounit) - Framework de teste de unidade XUnit para OCaml.
- [QCheck](https://github.com/c-cube/qcheck) - Biblioteca de testes baseados em propriedades para OCaml.

## Serialização e Formatação
- [Yojson](https://github.com/ocaml-community/yojson) - Codificação e decodificação JSON para OCaml.
- [Sexplib](https://github.com/janestreet/sexplib) - Serialização e desserialização de S-expressions. `Jane Street`
- [Bin_prot](https://github.com/janestreet/bin_prot) - Serialização binária rápida. `Jane Street`

## Análise Estática e Documentação
- [OCamlFormat](https://github.com/ocaml-ppx/ocamlformat) - Formatador de código automático para OCaml.
- [fmt](https://github.com/dbuenzli/fmt) - Formatação de Código OCaml.
- [odoc](https://github.com/ocaml/odoc) - Documentação de código.

## Matemática e Computação Científica
- [Owl](https://github.com/owlbarn/owl) - Biblioteca de computação científica e numérica para OCaml.
- [ocamlgraph](https://github.com/backtracking/ocamlgraph) - Biblioteca para gerar imagens de Grafos com OCaml, baseado em Graphviz e formato DOT.
- [ocaml-jupyter](https://github.com/akabe/ocaml-jupyter) - Kernel de OCaml para Jupyter Notebooks.

## Interface Gráfica e Linha de Comando
- [cmdliner](https://github.com/dbuenzli/cmdliner) - Biblioteca para criar aplicações de linha de comando.
- [LablGtk](https://garrigue.github.io/lablgtk/) - Interface OCaml para GTK 2 e 3 (bindings).
- [LablTk](https://garrigue.github.io/labltk/) - Interface OCaml para GUI TCL/Tk.
- [lablqml](https://github.com/Kakadu/lablqml) - Interface com Qt/QML para OCaml.

## Bancos de Dados e Armazenamento
- [Caqti](https://github.com/paurkedal/ocaml-caqti) - Abstração para acesso a bancos de dados relacionais (MariaDB, PostgreSQL, SQLite3).
- [sqlite3](https://github.com/mmottl/sqlite3-ocaml) - Bindings OCaml para SQLite3.
- [ocaml-redis](https://github.com/0xffea/ocaml-redis) - Bindings Redis para OCaml.
- [Irmin](https://irmin.org/) - Banco de dados distribuído que segue os princípios do Git.

## Criptografia e Segurança
- [Mirage-crypto](https://github.com/mirage/mirage-crypto) - Biblioteca de criptografia usada no MirageOS.
- [ocaml-tls](https://github.com/mirleft/ocaml-tls) - Implementação TLS em OCaml puro.

## Processamento de Dados e Texto
- [csvtool](https://github.com/Chris00/ocaml-csv) - Biblioteca e ferramenta de linha de comando para manipulação de arquivos CSV.
- [Textutils](https://github.com/janestreet/textutils) - Ferramentas de texto e formatação. `Jane Street`

## Sistemas Operacionais e Arquivos
- [BOS](https://erratique.ch/software/bos) - Biblioteca para interação com o Sistema Operacional (incluindo manipulação de arquivos) via OCaml.

## Bibliotecas Base e Utilitários
- [Core](https://github.com/janestreet/core) - Biblioteca alternativa à biblioteca padrão do OCaml. `Jane Street`
- [Base](https://github.com/janestreet/base) - Biblioteca base completa para OCaml. `Jane Street`
- [Incremental](https://github.com/janestreet/incremental) - Biblioteca para computações incrementais. `Jane Street`
- [Fieldslib](https://github.com/janestreet/fieldslib) - Sintaxe e funções para trabalhar com campos de registros. `Jane Street`
- [Typerep](https://github.com/janestreet/typerep) - Representações de tipos em tempo de execução. `Jane Street`
