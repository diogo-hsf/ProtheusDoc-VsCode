<!-- NÃO ESQUECER DE AJUSTAR O ARQUIVO whatsNew.ts com as mudanças consideráveis de versão. -->

# Change Log

All notable changes to the "protheusdoc-vscode" extension will be documented in this file.

---

## [0.4.4] - 2020-03-31

### Added

- Implementado *What's New* para apresentar as novidades e correções da versão.

### Changed

- Ajustado *Hover* para verificar se existe documentação do identificador no arquivo atual, se existir mostra somente deste arquivo, se não mostra todas as ocorrências encontradas [#15](https://github.com/AlencarGabriel/ProtheusDoc-VsCode/issues/15).

### Fixed

- Ajustado *expressões de classe* para interpretarem classes com herança [#11](https://github.com/AlencarGabriel/ProtheusDoc-VsCode/issues/11).
- Retirado *Tab Stop do snippet do return* quando este já vem tipado [#12](https://github.com/AlencarGabriel/ProtheusDoc-VsCode/issues/12).
- Corrigido BUG que ocorria quando a busca de linhas com documentação chegava no fim do arquivo.

### Agradecimentos

- [@izacsc](https://github.com/izacsc) pelas ótimas sugestões de melhorias para a extensão.

---

## [0.4.1] - 2020-02-20

### Added

- Implementado *Hover de Documentação* nas chamadas dos identificadores para mostrar o ProtheusDOC. [Veja mais em https://github.com/AlencarGabriel/ProtheusDoc-VsCode#hover-de-documentações](https://github.com/AlencarGabriel/ProtheusDoc-VsCode#hover-de-documentações).

---

## [0.3.0] - 2020-01-30

### Added

- Implementado *Text Decoration* para os atributos do ProtheusDoc ficarem negritos (para desativar esta decoração [veja aqui](https://github.com/AlencarGabriel/ProtheusDoc-VsCode#configurações-da-extensão)).

### Fixed

- Alterado forma de buscar as configurações, para sempre buscar a configuração atual e não a do momento da ativação da extensão.

---

## [0.2.3] - 2020-01-28

### Added

- Adicionado suporte para interpratação da sintaxe de Classe para adicionar o bloco ProtheusDoc.

### Fixed

- Ajustado problema remanescente da situação de bloco de parâmetros vazio que não havia sido detectado totalmente na 0.1.2 [#6](https://github.com/AlencarGabriel/ProtheusDoc-VsCode/issues/6).
- Melhorado expressões para aceitarem mais espaços entre as palavras [#9](https://github.com/AlencarGabriel/ProtheusDoc-VsCode/issues/9).
- Implementado interpretação das funções para interpretar o tipo `Function` [#8](https://github.com/AlencarGabriel/ProtheusDoc-VsCode/issues/8).

---

## [0.1.2] - 2020-01-27

### Added

- Adicionado suporte para interpratação da sintaxe de método de classe para adicionar o bloco ProtheusDoc.

### Fixed

- Implementado tipos Char e Block (alternativos de Character e CodeBlock) como tipos reconhecidos do ProtheusDoc [#5](https://github.com/AlencarGabriel/ProtheusDoc-VsCode/issues/5).
- Ajustado para que o marcador de parâmetros não seja apresentado caso o método ou função tenha os `( )` mas não tenha definição de parâmetros [#6](https://github.com/AlencarGabriel/ProtheusDoc-VsCode/issues/6).

---

## [0.0.8] - 2020-01-24

### Added

- Adicionado suporte para interpretar tambem a sintaxe de Parâmetros e Retornos usando Tipagem Forte [#2](https://github.com/AlencarGabriel/ProtheusDoc-VsCode/issues/2).

### Fixed

- Ajustes na quebra de linha dos Snippets.
- Refatorado Interface estrutura do Return para funcionar igual os Params.

---

## [0.0.5] - 2020-01-23

### Added

- Adicionado atalho `Shift + Alt + D` para o comando `ProtheusDoc - Adicionar bloco de Documentação`.

### Changed

- Alterado forma como o IntelliSense sugere o comando do ProtheusDoc. Para mais informações [veja aqui](https://github.com/AlencarGabriel/ProtheusDoc-VsCode#snippets).

### Fixed

- Auto Complete está sobrescrevendo as sugestões de string [#3](https://github.com/AlencarGabriel/ProtheusDoc-VsCode/issues/3).
- Ao usar o Snippet está substituindo o conteúdo da linha [#4](https://github.com/AlencarGabriel/ProtheusDoc-VsCode/issues/4).

---

## [0.0.2] - 2020-01-22

### Fixed

- Adicionado compatibilidade com a versão 1.38.0 do VsCode [#1](https://github.com/AlencarGabriel/ProtheusDoc-VsCode/issues/1).

---

## [0.0.1] - 2020-01-22

### Added

- First extension release.