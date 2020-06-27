# Awesome Plugins - iVim

plugins works on iVim, See [the list](./My_Vim_Plugins.md)

## __Python__

Python

| Class    | Plugin      | Vim-ver | Keymap | Lang   | Lang-tools      | Conflict    |
|----------|-------------|---------|--------|--------|-----------------|-------------|
| misc     | python-mode |         |        | Python | pylama flake8 … | jedi-vim    |
| complete | jedi-vim    |         |        | Python | jedi            | python-mode |
| textobj  | pythonsense |         |        |        |                 |             |
| terminal | jupyter-vim |         |        |        |                 |             |

## Chinese 中文

中文相关插件

| Plugin         | Vim-ver | Keymap    | Lang | Lang-tools | Plugin-Deps |
|----------------|---------|-----------|------|------------|-------------|
| ZFVimIM        |         | Customize | VimL |            |             |
| ZFVimIM_pinyin |         |           | txt  |            | ZFVimIM     |
| ZFVimIM_wubi   |         |           | txt  |            | ZFVimIM     |
| ime.vim        |         | Customize | VimL |            |             |




## __viml__

vim script: debug test run

| Advice    | Plugin | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|-----------|--------|---------|--------|------|------------|-------------|
| Must Have | Vfix   |         |        |      |            |             |


## cmdmode ex-mode terminal

cmd ex term

| Plugin       | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|--------------|---------|--------|------|------------|-------------|
| vim-floaterm |         |        |      |            |             |
| vim-repl     |         |        |      |            |             |
| vim-ripple   |         |        |      |            |             |
| codi         |         |        |      |            |             |
| Deol         |         |        |      |            |             |
| jupyter-vim  |         |        |      |            |             |

## code: debug/lint make run tahs test

### debug lint

| Advice | Plugin    | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|--------|-----------|---------|--------|------|------------|-------------|
|        | ale       |         |        |      |            |             |
|        | syntastic |         |        |      |            |             |

### make

| Advice | Plugin    | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|--------|-----------|---------|--------|------|------------|-------------|
|        | neomake   |         |        |      |            |             |

### tags

tags: view generate update

| Advice        | Plugin        | Vim-ver | Keymap | Lang | Lang-tools | Deps  |
|---------------|---------------|---------|--------|------|------------|-------|
| Highly Advice | tagbar        |         |        |      |            | NO    |
| Highly Advice | taglist       |         |        |      |            | ctags |
| Highly Advice | vimtags_vim   |         |        |      |            | NO    |
|               | vista.vim     |         |        |      |            | ctags |
| Not Good      | vim-autotag   |         |        |      |            | ctags |
|               | vim-bgtags    |         |        |      |            | ctags |
|               | vim-gutentags |         |        |      |            | ctags |

## comment

comment docstring

| Advice    | Plugin         | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|-----------|----------------|---------|--------|------|------------|-------------|
| Must Have | nerdcommenter  | 8.1     | Normal | VimL |            |             |
|           | vim-commentary |         | Normal | VimL |            |             |
|           | tcomment       |         | Normal | VimL |            | tlib_vim    |


## complete-framework

completion framework

| Plugin         | Vim-ver | Keymap | Lang   | Lang-tools | LT-Deps          | Conflict        |
|----------------|---------|--------|--------|------------|------------------|-----------------|
| vim-mucomplete |         |        | VimL   |            |                  |                 |
| asyncomplete   |         |        | VimL   |            |                  |                 |
| completor      |         |        | Python |            |                  |                 |
| python-mode    |         |        | Python | jedi       |                  | jedi-vim        |
| neocomplete    |         |        | Lua    |            |                  | UltiSnips-<Tab> |
| deoplete       |         |        | Python | pynvim     | msgpack greenlet |                 |

## complete-snippet engine

completion engine

| Advice    | Plugin    | Vim-ver | Keymap | Lang   | Lang-tools | Plugin-Deps | Conflict |
|-----------|-----------|---------|--------|--------|------------|-------------|----------|
| Must Have | UltiSnips |         | N S    | Python |            |             |          |
|           | vim-vsnip |         |        |        |            |             |          |


## complete-snippets

snippets: UltiSnips snipMate VSCode-snippets

| Advice    | Plugin             | Vim-ver | Keymap | Lang     | Lang-tools | Plugin-Deps |
|-----------|--------------------|---------|--------|----------|------------|-------------|
| Must Have | honza/vim-snippets |         |        | snippets |            |             |
|           | VSCode snippets    |         |        | JSON     |            |             |

## edit fold region textobj clipboard/register/yank

edit fold region textobj clipboard/register/yank

### edit

| Advice    | Plugin     | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|-----------|------------|---------|--------|------|------------|-------------|
| Must Have | Auto-Pairs |         |        | VimL |            |             |
| Must Have | splitjoin  |         |        | VimL |            |             |
|           | vim-move   |         |        | VimL |            |             |

### fold

| Advice        | Plugin         | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|---------------|----------------|---------|--------|------|------------|-------------|
| Highly Advice | FastFold       |         | Yes    | VimL |            |             |
| Highly Advice | FoldText       |         |        | VimL |            |             |
| Highly Advice | vim-fold-cycle |         |        | VimL |            |             |
|               | vxfold         |         |        | VimL |            |             |

### region

region

| Advice        | Plugin | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|---------------|--------|---------|--------|------|------------|-------------|
| Highly Advice | NrrRgn |         |        | VimL |            |             |


### textobj

textobj

| Advice        | Plugin           | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|---------------|------------------|---------|--------|------|------------|-------------|
| Highly Advice | pythonsense      |         |        |      |            |             |
| Highly Advice | vim-textobj-user |         |        | VimL |            |             |

### clipboard/register/yank

clipboard register yank

| Advice        | Plugin       | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|---------------|--------------|---------|--------|------|------------|-------------|
| Highly Advice | YankRing     |         |        | VimL |            |             |
|               | vim-peekaboo |         |        | VimL |            |             |


## explore


### file folder

| Advice    | Plugin      | Vim-ver | Keymap    | Lang | Lang-tools | Plugin-Deps |
|-----------|-------------|---------|-----------|------|------------|-------------|
| Must Have | nerdtree    |         | OwnBuffer | VimL |            |             |
|           | fern        |         |           | VimL |            |             |
|           | defx        |         |           | VimL |            |             |
|           | vim-dirvish |         |           | VimL |            |             |
|           | vaffle      |         |           | VimL |            |             |



### buffer

| Advice | Plugin    | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|--------|-----------|---------|--------|------|------------|-------------|
|        | bufselect | 8.2     |        | VimL |            |             |
|        | thumbnail |         |        | VimL |            |             |


## find & search


find and search: buffer file folder mru text

### buffer in-buffer-search

buffer search

| Advice | Plugin        | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|--------|---------------|---------|--------|------|------------|-------------|
|        | is.vim        |         |        |      |            |             |
|        | incsearch.vim |         |        |      |            |             |
|        | vim-anzu      |         |        |      |            |             |


### __multi__

multi purpose tool

| Advice | Plugin    | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|--------|-----------|---------|--------|------|------------|-------------|
|        | ctrlp     |         |        | VimL |            |             |
|        | searchvim |         |        | VimL |            |             |
|        | LeaderF   |         |        | VimL |            |             |


### file folder

file folder search

| Advice | Plugin      | Vim-ver | Keymap | Lang | CLI-Deps |
|--------|-------------|---------|--------|------|----------|
|        | vim-grepper |         |        |      |          |
|        | ferret      |         |        |      |          |
|        | fzf.vim     |         |        |      | fzf      |


### mru

| Advice | Plugin | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|--------|--------|---------|--------|------|------------|-------------|
|        | mru    |         |        | VimL |            |             |


### text/file content

| Advice | Plugin | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|--------|--------|---------|--------|------|------------|-------------|
|        | loup   |         |        | VimL |            |             |


## filetype

filetype: csv markdown org

| Advice    | Plugin       | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|-----------|--------------|---------|--------|------|------------|-------------|
|           | csv.vim      |         |        | VimL |            |             |
|           | vimwiki      |         |        | VimL |            |             |
|           | vimtex       |         |        | VimL |            |             |
| Must Have | vim-markdown |         |        | VimL |            |             |
|           | vim-orgmode  |         |        | VimL |            |             |

## highlight

highlight: pairs words yanked

| Advice        | Plugin              | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|---------------|---------------------|---------|--------|------|------------|-------------|
| Must Have     | hiPairs             |         |        | VimL |            |             |
| Highly Advice | vim-cursorword      |         |        | VimL |            |             |
| Highly Advice | vim-highlightyanked |         |        | VimL |            |             |
| Highly Advice | vim-illunimate      |         |        | VimL |            |             |

## indent

indent

| Advice        | Plugin     | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|---------------|------------|---------|--------|------|------------|-------------|
|               | IndGuide   |         |        | VimL |            |             |
| Highly Advice | indentLine |         |        | VimL |            |             |


## key

keymap keybinding

| Advice        | Plugin        | Vim-ver | Keymap    | Lang | Lang-tools | Plugin-Deps |
|---------------|---------------|---------|-----------|------|------------|-------------|
| Highly Advice | do.vim        |         |           | VimL |            |             |
|               | vim-freekeys  |         |           | VimL |            |             |
| Must Have     | vim-which-key |         | Customize | VimL |            |             |

## lsp

lsp: language server protocol

| Plugin                | Vim-ver | Keymap | Lang       | Lang-tools  | TerminalTool-Deps |
|-----------------------|---------|--------|------------|-------------|-------------------|
| vim-lsp               |         |        |            |             |                   |
| coc.nvim              |         |        | TypeScript | Node.js npm |                   |
| LanguageClient-neovim |         |        | Rust       |             |                   |

## motion

motion

| Advice        | Plugin             | Vim-ver | Keymap    | Lang | Lang-tools | Plugin-Deps |
|---------------|--------------------|---------|-----------|------|------------|-------------|
| Highly Advice | vim-easymotion     |         | Customize | VimL |            |             |
| Highly Advice | vim-easymotion-chs |         |           | VimL |            |             |
|               | vim-sneak          |         | Normal    | VimL |            |             |



## misc

misc tools

| Advice        | Plugin   | Vim-ver | Keymap | Lang | Lang-tools | TerminalTool-Deps |
|---------------|----------|---------|--------|------|------------|-------------------|
|               | swy-ivim |         |        |      |            |                   |
| Highly Advice | vim-tldr |         |        |      |            | curl unzip git    |


## syntax

syntax for filetypes

| Plugin       | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|--------------|---------|--------|------|------------|-------------|
| vim-polyglot |         |        |      |            |             |


## UI

User Interface

| Advice        | Plugin             | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|---------------|--------------------|---------|--------|------|------------|-------------|
| Must Have     | vim-airline        |         |        |      |            |             |
| Must Have     | traces.vim         |         |        |      |            |             |
| Highly Advice | vim-airline        |         |        |      |            |             |
| Highly Advice | vim-airline-themes |         |        |      |            |             |
| Highly Advice | vim-airline-clock  |         |        |      |            |             |
|               | vim-pencil         |         |        |      |            |             |
|               | goyo               |         |        |      |            |             |
|               | limelight          |         |        |      |            |             |


## work with other CLI tools

mostly not avaliable on iVim

| Advice | Plugin        | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
|--------|---------------|---------|--------|------|------------|-------------|
|        | vim-fugitive  |         |        |      |            |             |
|        | vim-gitgutter |         |        |      |            |             |
|        | zeavim.vim    |         |        |      |            |             |

## Reference


