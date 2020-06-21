# Awesome Plugins - iVim

plugins works on iVim

## __Python__

Python

| Plugin      | Vim-ver | Keymap | Lang   | Lang-tools      | Conflict    |
| ---         | ---     | ---    | ---    | ---             | ---         |
| python-mode |         |        | Python | pylama flake8 … | jedi-vim    |
| jedi-vim    |         |        | Python | jedi            | python-mode |

## Chinese 中文

中文相关插件

| Plugin         | Vim-ver | Keymap    | Lang | Lang-tools | Plugin-Deps |
| ---            | ---     | ---       | ---  | ---        | ---         |
| ZFVimIM        |         | Customize | VimL |            |             |
| ZFVimIM_pinyin |         |           | txt  |            | ZFVimIM     |
| ZFVimIM_wubi   |         |           | txt  |            | ZFVimIM     |
| ime.vim        |         | Customize | VimL |            |             |




## __viml__

vim script: debug test run

| Advice    | Plugin | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
| ---       | ---    | ---     | ---    | ---  | ---        | ---         |
| Must Have | Vfix   |         |        |      |            |             |


## code: debug/lint run test

comment docstring

| Advice | Plugin    | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
| ---    | ---       | ---     | ---    | ---  | ---        | ---         |
|        | ale       |         |        |      |            |             |
|        | syntastic |         |        |      |            |             |
|        |           |         |        |      |            |             |


## comment

comment docstring

| Advice    | Plugin         | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
| ---       | ---            | ---     | ---    | ---  | ---        | ---         |
| Must Have | nerdcommenter  | 8.1     | Normal | VimL |            |             |
|           | vim-commentary |         | Normal | VimL |            |             |
|           | tcomment       |         | Normal | VimL |            | tlib_vim    |


## complete-framework

completion framework

| Plugin         | Vim-ver | Keymap | Lang   | Lang-tools | LT-Deps          | Conflict        |
| ---            | ---     | ---    | ---    | ---        | ---              | ---             |
| vim-mucomplete |         |        | VimL   |            |                  |                 |
| asyncomplete   |         |        | VimL   |            |                  |                 |
| python-mode    |         |        | Python | jedi       |                  | jedi-vim        |
| neocomplete    |         |        | Lua    |            |                  | UltiSnips-<Tab> |
| deoplete       |         |        | Python | pynvim     | msgpack greenlet |                 |

## complete-snippet engine

completion engine

| Advice    | Plugin    | Vim-ver | Keymap | Lang   | Lang-tools | Plugin-Deps | Conflict |
| ---       | ---       | ---     | ---    | ---    | ---        | ---         | ---      |
| Must Have | UltiSnips |         | N S    | Python |            |             |          |
|           | vim-vsnip |         |        |        |            |             |          |


## complete-snippets

snippets: UltiSnips snipMate VSCode-snippets

| Advice    | Plugin             | Vim-ver | Keymap | Lang     | Lang-tools | Plugin-Deps |
| ---       | ---                | ---     | ---    | ---      | ---        | ---         |
| Must Have | honza/vim-snippets |         |        | snippets |            |             |
|           | VSCode snippets    |         |        | JSON     |            |             |

## edit fold region yank/clipboard

edit fold region clipboard/yank

| Advice        | Plugin         | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
| ---           | ---            | ---     | ---    | ---  | ---        | ---         |
| Must Have     | Auto-Pairs     |         |        | VimL |            |             |
| Highly Advice | vim-fold-cycle |         |        | VimL |            |             |
| Highly Advice | NrrRgn         |         |        | VimL |            |             |
| Highly Advice | YankRing       |         |        | VimL |            |             |


## explore

explore file folder

| Advice    | Plugin      | Vim-ver | Keymap    | Lang | Lang-tools | Plugin-Deps |
| ---       | ---         | ---     | ---       | ---  | ---        | ---         |
| Must Have | nerdtree    |         | OwnBuffer | VimL |            |             |
|           | fern        |         |           | VimL |            |             |
|           | defx        |         |           | VimL |            |             |
|           | vim-dirvish |         |           | VimL |            |             |
|           | vaffle      |         |           | VimL |            |             |

## filetype

filetype: csv markdown org

| Advice    | Plugin       | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
| ---       | ---          | ---     | ---    | ---  | ---        | ---         |
|           | csv.vim      |         |        | VimL |            |             |
| Must Have | vim-markdown |         |        | VimL |            |             |
|           | vim-orgmode  |         |        | VimL |            |             |

## highlight

highlight: pairs words yanked

| Advice        | Plugin              | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
| ---           | ---                 | ---     | ---    | ---  | ---        | ---         |
| Must Have     | hiPairs             |         |        | VimL |            |             |
| Highly Advice | vim-cursorword      |         |        | VimL |            |             |
| Highly Advice | vim-highlightyanked |         |        | VimL |            |             |
| Highly Advice | vim-illunimate      |         |        | VimL |            |             |

## indent

indent

| Advice        | Plugin     | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
| ---           | ---        | ---     | ---    | ---  | ---        | ---         |
|               | IndGuide   |         |        | VimL |            |             |
| Highly Advice | indentLine |         |        | VimL |            |             |


## key

keymap keybinding

| Advice        | Plugin        | Vim-ver | Keymap    | Lang | Lang-tools | Plugin-Deps |
| ---           | ---           | ---     | ---       | ---  | ---        | ---         |
| Highly Advice | do.vim        |         |           | VimL |            |             |
|               | vim-freekeys  |         |           | VimL |            |             |
| Must Have     | vim-which-key |         | Customize | VimL |            |             |

## lsp

lsp: language server protocol

| Plugin  | Vim-ver | Keymap | Lang       | Lang-tools  | TerminalTool-Deps |
| ---     | ---     | ---    | ---        | ---         | ---               |
| coc     |         |        | TypeScript | Node.js npm |                   |
| vim-lsp |         |        |            |             |                   |

## motion

motion

| Advice        | Plugin             | Vim-ver | Keymap    | Lang | Lang-tools | Plugin-Deps |
| ---           | ---                | ---     | ---       | ---  | ---        | ---         |
| Highly Advice | vim-easymotion     |         | Customize | VimL |            |             |
| Highly Advice | vim-easymotion-chs |         |           | VimL |            |             |
|               | vim-sneak          |         | Normal    | VimL |            |             |



## misc

| Advice        | Plugin   | Vim-ver | Keymap | Lang | Lang-tools | TerminalTool-Deps |
| ---           | ---      | ---     | ---    | ---  | ---        | ---               |
|               | swy-ivim |         |        |      |            |                   |
| Highly Advice | vim-tldr |         |        |      |            | curl unzip git    |


## syntax

syntax for filetypes

| Plugin       | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
| ---          | ---     | ---    | ---  | ---        | ---         |
| vim-polyglot |         |        |      |            |             |

## UI

User Interface

| Advice        | Plugin             | Vim-ver | Keymap | Lang | Lang-tools | Plugin-Deps |
| ---           | ---                | ---     | ---    | ---  | ---        | ---         |
| Must Have     | vim-airline        |         |        |      |            |             |
| Highly Advice | vim-airline-themes |         |        |      |            |             |
|               | vim-pencil         |         |        |      |            |             |
|               | goyo               |         |        |      |            |             |
|               | limelight          |         |        |      |            |             |


