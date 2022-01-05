<div class="github-widget" data-repo="rockerBOO/awesome-neovim"></div>
<script async src="https://pagead2.googlesyndication.com/pagead/js/adsbygoogle.js"></script><ins class="adsbygoogle" style="display:block" data-ad-client="ca-pub-6890694312814945" data-ad-slot="5473692530" data-ad-format="auto"  data-full-width-responsive="true"></ins><script>(adsbygoogle = window.adsbygoogle || []).push({});</script>
<!-- lint ignore awesome-git-repo-age -->

<img src="https://neovim.io/logos/neovim-mark-flat.png" align="right" width="144" />

## Awesome Neovim [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)

<!-- Uncomment the awesome badge when the repository is added to awesome main list.
[![Awesome](https://awesome.re/badge-flat.svg)](https://awesome.re)
-->

 &gt; 很棒的 Neovim 插件集合. 主要针对 Neovim 的特定功能.

[Neovim](https://neovim.io/) 是一个基于 Vim 的文本编辑器，专为可扩展性和可用性而设计，以鼓励新的应用程序和贡献.



## Wishlist

有插件可以解决的问题吗？ 将其添加到 [nvim-lua wishlist](https://github.com/nvim-lua/wishlist).

## UI

Neovim 支持多种 UI.

- [CosmicNvim/cosmic-ui](https://github.com/CosmicNvim/cosmic-ui)  - Cosmic-UI 是一个围绕特定 vim 功能的简单包装器. 旨在提供一种快速简便的方法来使用 Neovim 创建 Cosmic UI 体验！
- [yatli/fvim](https://github.com/yatli/fvim) - Cross platform Neovim front-end UI, built with F# + Avalonia.
- [smolck/uivonim](https://github.com/smolck/uivonim) - 目标：功能丰富的跨平台 GUI，利用最新的 Neovim 功能.
- [qvacua/vimr](https://github.com/qvacua/vimr) - Swift 中适用于 macOS 的 Neovim GUI.
- [vhakulinen/gnvim](https://github.com/vhakulinen/gnvim) - Neovim 的 GUI，没有任何网络膨胀.
- [Kethku/neovide](https://github.com/Kethku/neovide) - 在 Rust 中没有废话 Neovim 客户端.
- [beeender/glrnvim](https://github.com/beeender/glrnvim) - 在 alacritty 中启动 Neovim 的终端包装器.
- [akiyosi/goneovim](https://github.com/akiyosi/goneovim) - 用 Golang 编写的 Neovim GUI，使用 Golang qt 后端.
- [DinVim](http://dinvim.com/) - 适用于 macOS 的 DinVim 是一个安全可靠的 macOS 沙盒工作环境，可为 Vim 用户提供真正的 macOS 体验.
- [RMichelsen/Nvy](https://github.com/RMichelsen/Nvy) - C++ 中的 Neovim 客户端.
- [asvetliakov/vscode-neovim](https://github.com/asvetliakov/vscode-neovim) - 用于 Visual Studio Code 的 Neovim 集成.
- [equalsraf/neovim-qt](https://github.com/equalsraf/neovim-qt) - Neovim 客户端库和 GUI，在 Qt5 中.
- [lunixbochs/actualvim](https://github.com/lunixbochs/actualvim) - 使用 Neovim 的 Sublime Text 3 输入模式.
- [vv-vim/vv](https://github.com/vv-vim/vv)  - 适用于 macOS 的 Neovim 客户端. 纯粹、快速、简约的 Vim 体验与良好的 macOS 集成. 针对速度和漂亮的字体渲染进行了优化.
- [jebberjeb/javafx-neovimpane](https://github.com/jebberjeb/javafx-neovimpane) - 一个 JavaFX 文本窗格，由 Neovim 支持，使用 Clojure 创建.
- [rohit-px2/nvui](https://github.com/rohit-px2/nvui) - Neovim 的现代前端.
- [Lyude/neovim-gtk](https://github.com/Lyude/neovim-gtk) - 用 Rust 编写的 GTK3+ 客户端，与具有连字支持的原始 vim-gtk3 非常相似.

## Plugin

### Plugin Manager

- [wbthomason/packer.nvim](https://github.com/wbthomason/packer.nvim)  - 一个受使用包启发的 Neovim 插件管理器. 使用原生包，支持 Luarocks 依赖，用 Lua 编写，允许富有表现力的配置.
- [savq/paq-nvim](https://github.com/savq/paq-nvim) - 用 Lua 编写的 Neovim 包管理器.
- [NTBBloodbath/cheovim](https://github.com/NTBBloodbath/cheovim)  - 用 Lua 编写的 Neovim 配置切换器. 灵感来自化学.

### LSP

#### (requires Neovim 0.5)

- [neovim/nvim-lspconfig](https://github.com/neovim/nvim-lspconfig) - Neovim LSP 客户端的快速入门配置.
- [nvim-lua/lsp-status.nvim](https://github.com/nvim-lua/lsp-status.nvim) - 这是一个 Neovim 插件/库，用于从内置 LSP 客户端生成状态行组件.
- [nvim-lua/lsp_extensions.nvim](https://github.com/nvim-lua/lsp_extensions.nvim) - Repo 为内置 LSP 保存一堆信息和扩展回调.
- [RishabhRD/nvim-lsputils](https://github.com/RishabhRD/nvim-lsputils) - 更好的 nvim-lsp 操作默认值.
- [tami5/lspsaga.nvim](https://github.com/tami5/lspsaga.nvim) - 基于 Neovim 内置 lsp 的轻量级 lsp 插件，具有高性能 UI.
- [onsails/diaglist.nvim](https://github.com/onsails/diaglist.nvim) - quickfix 中的实时渲染工作区诊断，loclist 中的缓冲区诊断.
- [folke/trouble.nvim](https://github.com/folke/trouble.nvim) - 一个漂亮的诊断列表，可帮助您解决代码引起的所有问题.
- [folke/lsp-colors.nvim](https://github.com/folke/lsp-colors.nvim) - 一个插件，为尚不支持内置 LSP 客户端的配色方案添加缺少的 LSP 诊断突出显示组.
- [kosayoda/nvim-lightbulb](https://github.com/kosayoda/nvim-lightbulb) - The plugin shows a lightbulb in the sign column whenever a `textDocument/codeAction` is available at the current cursor position.
- [onsails/lspkind-nvim](https://github.com/onsails/lspkind-nvim) - 该插件为 Neovim lsp 补全添加了类似 vscode 的图标.
- [ojroques/nvim-lspfuzzy](https://github.com/ojroques/nvim-lspfuzzy) - 一个让 LSP 客户端使用 FZF 的小插件.
- [gfanto/fzf-lsp.nvim](https://github.com/gfanto/fzf-lsp.nvim) - 为 lsp 内置的 Neovim 启用 fzf 模糊搜索的强大功能.
- [ray-x/lsp_signature.nvim](https://github.com/ray-x/lsp_signature.nvim) - 键入时 Lsp 签名提示.
- [rmagatti/goto-preview](https://github.com/rmagatti/goto-preview) - 在浮动窗口中预览本机 LSP 的 goto 定义调用.
- [nanotee/sqls.nvim](https://github.com/nanotee/sqls.nvim) - Neovim 的 Sqls（sql 数据库连接插件 + LSP 客户端）插件.
- [jubnzv/virtual-types.nvim](https://github.com/jubnzv/virtual-types.nvim) - Neovim 插件，将类型注释显示为虚拟文本.
- [jose-elias-alvarez/nvim-lsp-ts-utils](https://github.com/jose-elias-alvarez/nvim-lsp-ts-utils) - 用于改善 Neovim 内置 LSP 客户端的 TypeScript 开发体验的实用程序.
- [ray-x/navigator.lua](https://github.com/ray-x/navigator.lua)  - 快速学习现有代码并轻而易举地浏览代码. 一把瑞士军刀让探索 LSP 和 Treesitter 符号成为一件简单的事情.
- [liuchengxu/vista.vim](https://github.com/liuchengxu/vista.vim) - 在当前文件的窗口中列出所有函数和变量.
- [simrat39/symbols-outline.nvim](https://github.com/simrat39/symbols-outline.nvim)  - Neovim 中使用语言服务器协议的符号树状视图. 支持所有您喜欢的语言.
- [tamago324/nlsp-settings.nvim](https://github.com/tamago324/nlsp-settings.nvim) - 使用 JSON 文件设置 Neovim LSP 的插件.
- [simrat39/rust-tools.nvim](https://github.com/simrat39/rust-tools.nvim) - 使用 Neovim 的内置 LSP 在 Rust 中更好地开发的工具.
- [stevearc/aerial.nvim](https://github.com/stevearc/aerial.nvim) - 用于浏览和快速导航的代码大纲窗口.
- [jose-elias-alvarez/null-ls](https://github.com/jose-elias-alvarez/null-ls.nvim) - 使用 Neovim 作为语言服务器，通过 Lua 注入 LSP 诊断、代码操作等.
- [jakewvincent/texmagic.nvim](https://github.com/jakewvincent/texmagic.nvim) - 通过定义任意数量的自定义 LaTeX 构建引擎并使用魔术注释选择它们来增强 Texlab 的 lspconfig 设置.
- [nanotee/nvim-lsp-basics](https://github.com/nanotee/nvim-lsp-basics) - LSP 功能的基本包装器.
- [weilbith/nvim-code-action-menu](https://github.com/weilbith/nvim-code-action-menu) - 代码操作的浮动弹出菜单，用于显示代码操作信息和差异预览.
- [mfussenegger/nvim-lint](https://github.com/mfussenegger/nvim-lint) - Neovim (&gt;= 0.5) 的异步 linter 插件，对内置语言服务器协议支持进行了补充.
- [b0o/SchemaStore.nvim](https://github.com/b0o/SchemaStore.nvim) - 一个 Neovim Lua 插件，提供对 [SchemaStore](https://github.com/SchemaStore/schemastore) 目录.
- [ldelossa/litee.nvim](https://github.com/ldelossa/litee.nvim) - Neovim 缺少的 IDE 功能.

##### LSP Installer

- [anott03/nvim-lspinstall](https://github.com/anott03/nvim-lspinstall) - 易于安装语言服务器.
- [alexaandru/nvim-lspupdate](https://github.com/alexaandru/nvim-lspupdate) - 更新安装（或自动安装如果缺少）LSP 服务器.
- [williamboman/nvim-lsp-installer](https://github.com/williamboman/nvim-lsp-installer) - 轻松安装 50 多个 LSP 服务器 - 完全支持 Windows.

### Completion

- [ms-jpq/coq_nvim](https://github.com/ms-jpq/coq_nvim)  - 快他妈的 Neovim 完成.  SQLite，并发调度器，数百小时的优化.
- [jameshiew/nvim-magic](https://github.com/jameshiew/nvim-magic) - 集成 AI 代码辅助的框架.
- [hrsh7th/nvim-cmp](https://github.com/hrsh7th/nvim-cmp)  - 用 Lua 编写的 Neovim 补全插件.  nvim-compe 的新版本.
  - [hrsh7th/cmp-nvim-lsp](https://github.com/hrsh7th/cmp-nvim-lsp) - Neovim 内置 LSP 客户端的 nvim-cmp 源.
  - [saadparwaiz1/cmp_luasnip](https://github.com/saadparwaiz1/cmp_luasnip) - 用于 luasnip 完成的 nvim-cmp 源.
  - [quangnguyen30192/cmp-nvim-ultisnips](https://github.com/quangnguyen30192/cmp-nvim-ultisnips) - UltiSnips 的 nvim-cmp 源.
  - [hrsh7th/cmp-path](https://github.com/hrsh7th/cmp-path) - 文件系统路径的 nvim-cmp 源.
  - [petertriho/cmp-git](https://github.com/petertriho/cmp-git) - Git 的 nvim-cmp 源.
  - [hrsh7th/cmp-buffer](https://github.com/hrsh7th/cmp-buffer) - 缓冲区字的 nvim-cmp 源.
  - [tzachar/cmp-tabnine](https://github.com/tzachar/cmp-tabnine) - TabNine 的 nvim-cmp 源.
  - [hrsh7th/cmp-nvim-lua](https://github.com/hrsh7th/cmp-nvim-lua) - Neovim Lua API 的 nvim-cmp 源.
  - [lukas-reineke/cmp-rg](https://github.com/lukas-reineke/cmp-rg) - Ripgrep 的 nvim-cmp 源.
  - [f3fora/cmp-spell](https://github.com/f3fora/cmp-spell) - vim 的拼写建议的 nvim-cmp 源.
  - [andersevenrud/compe-tmux](https://github.com/andersevenrud/compe-tmux) - Tmux 的 nvim-cmp 源.
  - [David-Kunz/cmp-npm](https://github.com/David-Kunz/cmp-npm) - NPM 的 nvim-cmp 源.
  - [lukas-reineke/cmp-under-comparator](https://github.com/lukas-reineke/cmp-under-comparator) - 用于更好排序的 nvim-cmp 功能.
  <!--lint ignore double-link-->
- [mini.completion](https://github.com/echasnovski/mini.nvim#minicompletion) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 用于异步两阶段完成. 支持显示完成项信息和独立函数签名.

### Markdown

- [ellisonleao/glow.nvim](https://github.com/ellisonleao/glow.nvim) - 使用发光的 Markdown 预览.
- [davidgranstrom/nvim-markdown-preview](https://github.com/davidgranstrom/nvim-markdown-preview) - 通过 Neovim 的作业控制 API 使用 pandoc 和实时服务器在浏览器中进行 Markdown 预览.
- [jghauser/auto-pandoc.nvim](https://github.com/jghauser/auto-pandoc.nvim) - 利用 yaml 块轻松进行 pandoc 转换.
- [jghauser/follow-md-links.nvim](https://github.com/jghauser/follow-md-links.nvim) - 按回车键跟随内部降价链接.
- [jakewvincent/mkdnflow.nvim](https://github.com/jakewvincent/mkdnflow.nvim) - Markdown 笔记本导航（跟随内部和外部 Markdown 链接，创建链接，跳转到链接等）
- [jubnzv/mdeval.nvim](https://github.com/jubnzv/mdeval.nvim) - 一个 Neovim 插件，用于评估 Markdown 文档中的代码块.
- [mjlbach/babelfish.nvim](https://github.com/mjlbach/babelfish.nvim) - 使用 Treesitter 将 Markdown 转换为 vimdoc 的 Neovim 插件.
- [kdheepak/panvimdoc](https://github.com/kdheepak/panvimdoc) - 到 vimdoc GitHub 操作的 pandoc.

### Syntax

- [nvim-treesitter/nvim-treesitter](https://github.com/nvim-treesitter/nvim-treesitter) - Neovim Treesitter 配置和抽象层.
- [nvim-treesitter/nvim-treesitter-textobjects](https://github.com/nvim-treesitter/nvim-treesitter-textobjects) - 使用 tree-sitter 查询创建您自己的文本对象.
- [RRethy/nvim-treesitter-textsubjects](https://github.com/RRethy/nvim-treesitter-textsubjects) - 位置和语法感知文本对象，_做你的意思_.
- [blackCauldron7/surround.nvim](https://github.com/blackCauldron7/surround.nvim) - 用 Lua 编写的 Neovim 环绕文本对象插件.
<!--lint ignore double-link-->
- [mini.surround](https://github.com/echasnovski/mini.nvim#minisurround) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 用于处理文本环境（添加、删除、替换、查找、突出显示）. 完全支持点重复.

### Terminal integration

- [LoricAndre/OneTerm.nvim](https://github.com/LoricAndre/OneTerm.nvim) - 用于在终端中运行命令的插件框架.
- [nikvdp/neomux](https://github.com/nikvdp/neomux) - 从 Neovim 内部运行的 shell 控制 Neovim.
- [akinsho/nvim-toggleterm.lua](https://github.com/akinsho/nvim-toggleterm.lua) - 帮助轻松管理多个终端窗口的 Neovim Lua 插件.
- [norcalli/nvim-terminal.lua](https://github.com/norcalli/nvim-terminal.lua) - Neovim 的高性能文件类型模式，它利用正确的颜色代码隐藏和突出显示您的缓冲区.
- [numToStr/FTerm.nvim](https://github.com/numToStr/FTerm.nvim) - 没有用 Lua 编写的废话浮动终端.
- [oberblastmeister/termwrapper.nvim](https://github.com/oberblastmeister/termwrapper.nvim) - Neovim 终端功能的包装器，使它们更加用户友好.
- [pianocomposer321/consolation.nvim](https://github.com/pianocomposer321/consolation.nvim) - Neovim 的通用终端包装器和管理插件，用 Lua 编写.
- [jghauser/kitty-runner.nvim](https://github.com/jghauser/kitty-runner.nvim)  - 穷人的REPL. 轻松地将缓冲线和命令发送到 kitty 终端.
- [jlesquembre/nterm.nvim](https://github.com/jlesquembre/nterm.nvim) - 一个 Neovim 插件，用于与终端交互，并带有通知.
- [s1n7ax/nvim-terminal](https://github.com/s1n7ax/nvim-terminal) - 一个简单易用的多终端插件.

### Snippet

- [norcalli/snippets.nvim](https://github.com/norcalli/snippets.nvim) - Lua 中的片段.
- [hrsh7th/vim-vsnip](https://github.com/hrsh7th/vim-vsnip) - 支持 LSP/VSCode 代码段格式的 vim/nvim 代码段插件.
- [rafamadriz/friendly-snippets](https://github.com/rafamadriz/friendly-snippets) - 各种与 vim-vsnip 完美集成的编程语言的片段集合.
- [L3MON4D3/LuaSnip](https://github.com/L3MON4D3/LuaSnip) - 用 Lua 编写的 Neovim 片段引擎.
- [dcampos/nvim-snippy](https://github.com/dcampos/nvim-snippy) - 用 Lua 编写的片段插件，支持 [vim-snippets](https://github.com/honza/vim-snippets).

### Register

- [gennaro-tedesco/nvim-peekup](https://github.com/gennaro-tedesco/nvim-peekup) - 与 vim 寄存器动态交互.
- [tversteeg/registers.nvim](https://github.com/tversteeg/registers.nvim) - vim 寄存器的非侵入式最小预览.
- [acksld/nvim-neoclip.lua](https://github.com/AckslD/nvim-neoclip.lua) - 具有望远镜集成功能的剪贴板管理器 Neovim 插件.

### Marks

- [chentau/marks.nvim](https://github.com/chentau/marks.nvim) - 更好的用户体验，用于查看 vim 标记并与之交互.

### Fuzzy Finder

- [nvim-telescope/telescope.nvim](https://github.com/nvim-telescope/telescope.nvim) - Telescope.nvim 是一个高度 [extendable](https://github.com/nvim-telescope/telescope.nvim/wiki/Extensions) 列表上的模糊查找器. 基于 Neovim 核心的最新出色功能构建.  Telescope 以模块化为中心，允许轻松定制.
- [vijaymarupudi/nvim-fzf](https://github.com/vijaymarupudi/nvim-fzf)  - 在`Neovim` (&gt;= 0.5) 中使用 fzf 的 Lua API. 允许 UI 速度和可用性的完全异步.
- [amirrezaask/fuzzy.nvim](https://github.com/amirrezaask/fuzzy.nvim) - Fuzzy.nvim 提供了一个简单的机制和管道来在 Neovim 中创建模糊匹配.
- [camspiers/snap](https://github.com/camspiers/snap)  - 一个可扩展的模糊查找器. 类似于 Telescope，并针对性能进行了优化，尤其是在大型代码库中进行 grep 时.
- [ibhagwan/fzf-lua](https://github.com/ibhagwan/fzf-lua)  - `fzf.vim` 的 Lua 版本，高性能和完全异步，支持 `nvim-web-devicons`、git 指标、LSP、quickfix/位置列表等. 还支持 [`skim`](https://github.com/lotabout/skim) 作为其 fzf 二进制文件.
- [jvgrootveld/telescope-zoxide](https://github.com/jvgrootveld/telescope-zoxide) - 望远镜集成 [zoxide](https://github.com/ajeetdsouza/zoxide)，一个跟踪您使用情况的智能目录选择器.
<!--lint ignore double-link-->
- [mini.fuzzy](https://github.com/echasnovski/mini.nvim#minifuzzy) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 具有执行一个字符串与其他字符串的模糊匹配以及快速望远镜分类器的功能.

### Note Taking

- [oberblastmeister/neuron.nvim](https://github.com/oberblastmeister/neuron.nvim) - 记录与望远镜.nvim 集成的神经元插件.
- [jbyuki/nabla.nvim](https://github.com/jbyuki/nabla.nvim) - 在 Neovim 中记录您的科学笔记.
- [nvim-neorg/neorg](https://github.com/nvim-neorg/neorg)  - 现代性遇到疯狂的可扩展性. 在 Neovim 中组织您的生活的未来.
- [nvim-orgmode/orgmode](https://github.com/nvim-orgmode/orgmode) - 用 Lua 为 Neovim 0.5+ 编写的 Orgmode 克隆.
- [NFrid/due.nvim](https://github.com/NFrid/due.nvim) - 将日期字符串的到期时间显示为虚拟文本.
- [jbyuki/venn.nvim](https://github.com/jbyuki/venn.nvim) - 在 Neovim 中绘制 ASCII 图表.
- [stevearc/gkeep.nvim](https://github.com/stevearc/gkeep.nvim) - Neovim 的 Google Keep 集成.

### Color

- [norcalli/nvim-colorizer.lua](https://github.com/norcalli/nvim-colorizer.lua) - Neovim 的高性能彩色荧光笔，没有外部依赖！
- [sunjon/Shade.nvim](https://github.com/sunjon/Shade.nvim) - Shade 是一个 Neovim 插件，可以使您的非活动窗口变暗，让您更容易一目了然地看到活动窗口.
- [winston0410/range-highlight.nvim](https://github.com/winston0410/range-highlight.nvim) - 一个非常轻量级的插件 (~ 120loc)，可以突出显示您在命令行中输入的范围.
- [xiyaowong/nvim-transparent](https://github.com/xiyaowong/nvim-transparent) - 使您的 Neovim 透明.
- [folke/twilight.nvim](https://github.com/folke/twilight.nvim) - 将您正在使用 TreeSitter 编辑的代码的非活动部分变暗.

### Colorscheme Creation

- [tjdevries/colorbuddy.nvim](https://github.com/tjdevries/colorbuddy.nvim)  - Neovim 的配色方案助手. 用Lua写的！ 快速简便的配色方案.
- [norcalli/nvim-base16.lua](https://github.com/norcalli/nvim-base16.lua) - 用于在 Neovim 中设置 base16 主题的程序化 Lua 库.
- [rktjmp/lush.nvim](https://github.com/rktjmp/lush.nvim) - 将 Neovim 主题定义为 Lua 中的 DSL，具有实时反馈.
- [Iron-E/nvim-highlite](https://github.com/Iron-E/nvim-highlite) - 对开发人员来说逻辑“精简”的配色方案模板.
<!--lint ignore double-link-->
- [mini.base16](https://github.com/echasnovski/mini.nvim#minibase16) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 为手动提供的调色板快速实现 base16 主题.

### Colorscheme

#### Tree-sitter Supported Colorscheme

 Tree-sitter 是 Neovim 0.5 中的一个新系统，它可以增量地将您的代码解析为一个有效的树，即使您的语法有错误也是如此. 这些配色方案专门为 Tree-sitter 高光组设置了颜色.  Vim 颜色方案将与开箱即用的新组一起使用.

- [shaeinst/roshnivim-cs](https://github.com/shaeinst/roshnivim-cs) - 用 Lua 编写的 Neovim 配色方案，专为具有 Tree-sitter 支持的 roshnivim 制作.
- [rafamadriz/neon](https://github.com/rafamadriz/neon)  - 可定制的配色方案，具有出色的斜体和粗体支持、深色和浅色变体. 与 Tree-sitter 一起工作并看起来不错.
- [tomasiser/vim-code-dark](https://github.com/tomasiser/vim-code-dark) - 深色配色方案的灵感来自 Visual Studio Code 的 Dark+ 方案的外观.
- [Mofiqul/vscode.nvim](https://github.com/Mofiqul/vscode.nvim) - 带有 vscode 浅色和深色主题的 Neovim 的 vim-code-dark 颜色方案的 Lua 端口.
- [marko-cerovac/material.nvim](https://github.com/marko-cerovac/material.nvim) - Material.nvim 是一个高度可配置的配色方案，用 Lua 编写并基于材料调色板.
- [bluz71/vim-nightfly-guicolors](https://github.com/bluz71/vim-nightfly-guicolors) - Nightfly 是一种深色 GUI 配色方案，其灵感源自 Sarah Drasner 的 Night Owl 主题.
- [bluz71/vim-moonfly-colors](https://github.com/bluz71/vim-moonfly-colors) - Moonfly 是一种深色配色方案，支持 Tree-sitter.
- [ChristianChiarulli/nvcode-color-schemes.vim](https://github.com/ChristianChiarulli/nvcode-color-schemes.vim) - Nvcode、onedark、nord colorchemes 与 Tree-sitter 支持.
- [folke/tokyonight.nvim](https://github.com/folke/tokyonight.nvim) - 用 Lua 编写的干净、深色和浅色的 Neovim 主题，支持 LSP、Tree-sitter 和许多插件.
- [sainnhe/sonokai](https://github.com/sainnhe/sonokai) - 基于 Monokai Pro 的高对比度和鲜艳配色方案.
- [kyazdani42/blue-moon](https://github.com/kyazdani42/blue-moon) - Neovim 的深色配色方案源自 Palenight 和 carbonight.
- [mhartington/oceanic-next](https://github.com/mhartington/oceanic-next) - Neovim 的下一个海洋主题.
- [glepnir/zephyr-nvim](https://github.com/glepnir/zephyr-nvim) - 支持 Tree-sitter 的深色配色方案.
- [rockerBOO/boo-colorscheme-nvim](https://github.com/rockerBOO/boo-colorscheme-nvim) - Neovim 的配色方案，手动支持 LSP、Tree-sitter.
- [jim-at-jibba/ariake-vim-colors](https://github.com/jim-at-jibba/ariake-vim-colors)  - 伟大的原子主题的端口. 有树保姆支持的黑暗和光明.
- [Th3Whit3Wolf/onebuddy](https://github.com/Th3Whit3Wolf/onebuddy) - 光暗原子一个主题.
- [RishabhRD/nvim-rdark](https://github.com/RishabhRD/nvim-rdark) - 用 Lua 编写的 Neovim 深色配色方案.
- [ishan9299/modus-theme-vim](https://github.com/ishan9299/modus-theme-vim) - 这是 Protesilaos Stavrou 为 emacs 开发的配色方案.
- [sainnhe/edge](https://github.com/sainnhe/edge) - 灵感来自 Atom One 和 Material 的干净优雅的配色方案.
- [theniceboy/nvim\-deus](https://github.com/theniceboy/nvim-deus) - 支持 Tree-sitter 的 Vim-deus.
- [bkegley/gloombuddy](https://github.com/bkegley/gloombuddy) - Neovim 的 Gloom 主题.
- [Th3Whit3Wolf/one-nvim](https://github.com/Th3Whit3Wolf/one-nvim) - Atom One 启发了 Neovim 的深色和浅色配色方案.
- [PHSix/nvim-hybrid](https://github.com/PHSix/nvim-hybrid) - 用 Lua 编写的 Neovim 配色方案.
- [Th3Whit3Wolf/space-nvim](https://github.com/Th3Whit3Wolf/space-nvim) - 一个 spacemacs 启发了 Neovim 的深色和浅色配色方案.
- [yonlu/omni.vim](https://github.com/yonlu/omni.vim) - Vim 的 Omni 配色方案.
- [ray-x/aurora](https://github.com/ray-x/aurora) - 具有 Tree-sitter 和 LSP 支持的 24 位深色主题.
- [novakne/kosmikoa.nvim](https://github.com/novakne/kosmikoa.nvim) - Neovim 的配色方案.
- [tanvirtin/monokai.nvim](https://github.com/tanvirtin/monokai.nvim) - 用 Lua 编写的 Neovim Monokai 主题.
- [nekonako/xresources-nvim](https://github.com/nekonako/xresources-nvim) - Neovim 配色方案基于您的 xresources 颜色.
- [savq/melange](https://github.com/savq/melange) - Neovim 和 Vim ️ 的深色配色方案.
- [RRethy/nvim-base16](https://github.com/RRethy/nvim-base16)  - 用于构建 base16 配色方案的 Neovim 插件. 包括对 Treesitter 和 LSP 高亮组的支持.
- [fenetikm/falcon](https://github.com/fenetikm/falcon) - 终端、Vim 和朋友的配色方案.
- [andersevenrud/nordic.nvim](https://github.com/andersevenrud/nordic.nvim) - 北欧风格的配色方案.
- [shaunsingh/nord.nvim](https://github.com/shaunsingh/nord.nvim) - 基于 Nord 调色板的 Neovim 主题.
- [MordechaiHadad/nvim-papadark](https://github.com/MordechaiHadad/nvim-papadark) - 我自己的 Neovim 配色方案.
- [ishan9299/nvim-solarized-lua](https://github.com/ishan9299/nvim-solarized-lua) - 用于 Neovim 0.5 的 Lua 中的日晒配色方案.
- [shaunsingh/moonlight.nvim](https://github.com/shaunsingh/moonlight.nvim) - VSCode 的 NeoVim 月光配色方案的端口，用 Lua 编写，内置支持原生 LSP、Tree-sitter 和更多插件.
- [navarasu/onedark.nvim](https://github.com/navarasu/onedark.nvim) - A One Dark Theme for Neovim 0.5 written in Lua based on Atom's One Dark Theme.
- [lourenci/github-colors](https://github.com/lourenci/github-colors) - 利用 Tree-sitter 获得 100% 准确度的 GitHub 颜色.
- [sainnhe/gruvbox-material](https://github.com/sainnhe/gruvbox-material) - Gruvbox 修改具有更柔和的对比度和 Tree-sitter 支持.
- [sainnhe/everforest](https://github.com/sainnhe/everforest) - 基于绿色的配色方案设计为温暖、柔软且易于呵护眼睛.
- [NTBBloodbath/doom-one.nvim](https://github.com/NTBBloodbath/doom-one.nvim) - Neovim 的 Doom-emacs 的 Doom-one 的 Lua 端口.
- [dracula/vim](https://github.com/dracula/vim) - 著名的美丽黑暗主题.
- [yashguptaz/calvera-dark.nvim](https://github.com/yashguptaz/calvera-dark.nvim) - 一个港口 [VSCode Calvara Dark](https://github.com/saurabhdaware/vscode-calvera-dark) 带有 Tree-sitter 和许多其他插件支持的 Neovim 主题.
- [nxvu699134/vn-night.nvim](https://github.com/nxvu699134/vn-night.nvim)  - 用 Lua 编写的深色 Neovim 配色方案. 支持内置 LSP 和 Tree-sitter.
- [adisen99/codeschool.nvim](https://github.com/adisen99/codeschool.nvim) - 用 Lua 编写的 Neovim 代码学校配色方案，具有 Tree-sitter 和内置 lsp 支持.
- [projekt0n/github-nvim-theme](https://github.com/projekt0n/github-nvim-theme)  - 一个用 Lua 编写的 Neovim、kitty、alacritty 的 GitHub 主题. 支持内置 LSP 和 Tree-sitter.
- [kdheepak/monochrome.nvim](https://github.com/kdheepak/monochrome.nvim) - 16 位单色配色方案，使用 hsluv 实现感知上不同的灰色，并支持 Tree-sitter 和其他常用插件.
- [rose-pine/neovim](https://github.com/rose-pine/neovim) - 全天然松木、人造毛皮和优雅极简主义者的一点苏荷氛围.
- [mcchrish/zenbones.nvim](https://github.com/mcchrish/zenbones.nvim) - vim/neovim 配色方案的集合，旨在使用对比度和字体变化突出显示代码.
- [catppuccin/nvim](https://github.com/catppuccin/nvim)  - 温暖的中调深色主题，炫耀充满活力的自我！ 支持原生 LSP、Tree-sitter 等！
- [FrenzyExists/aquarium-vim](https://github.com/FrenzyExists/aquarium-vim) - A dark, yet vibrant colorscheme for Neovim.
- [EdenEast/nightfox.nvim](https://github.com/EdenEast/nightfox.nvim) - 柔和的深色、完全可定制的 Neovim 主题，支持 lsp、treesitter 和各种插件.
- [kvrohit/substrata.nvim](https://github.com/kvrohit/substrata.nvim) - 用 Lua 编写的 Neovim 冷色暗色调方案移植自 [arzg/vim-substrata](https://github.com/arzg/vim-substrata) 主题.
- [ldelossa/vimdark](https://github.com/ldelossa/vimdark)  - 夜间的最小 Vim 主题. 松散地基于 vim-monotonic 和 chrome 的深色阅读器扩展. 白天也包括一个轻松的主题.
- [mangeshrex/uwu.vim](https://github.com/Mangeshrex/uwu.vim) - 用 vimscript 编写的美丽而黑暗的 vim 配色方案.
- [adisen99/apprentice.nvim](https://github.com/adisen99/apprentice.nvim) - 基于 Lua 编写的 Neovim 配色方案 [Apprentice](https://github.com/romainl/Apprentice) 带有 Tree-sitter 和内置 lsp 支持的颜色模式.
- [olimorris/onedarkpro.nvim](https://github.com/olimorris/onedarkpro.nvim)  - Neovim 的一个 Dark Pro 主题，用 Lua 编写并基于 VS Code 主题. 包括具有完全可自定义的颜色、样式和亮点的深色和浅色主题.
- [rmehri01/onenord.nvim](https://github.com/rmehri01/onenord.nvim) - Neovim 主题，结合了 Nord 和 Atom One Dark 调色板，可提供更生动的编程体验.
- [RishabhRD/gruvy](https://github.com/RishabhRD/gruvy) - 没有 colorbuddy 的 Gruvbuddy 使用 Lush.
<!--lint ignore double-link-->
- [minischeme](https://github.com/echasnovski/mini.nvim#plugin-colorscheme) - 配色方案 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 它是 base16 的变体，具有根据最佳感知均匀性选择的强调色.
- [luisiacc/gruvbox-baby](https://github.com/luisiacc/gruvbox-baby) - 一个现代的 gruvbox 主题，具有完整的 treeitter 支持.
- [titanzero/zephyrium](https://github.com/titanzero/zephyrium) - zephyr 风格的主题，用 Lua 编写，支持 TreeSitter.

#### Lua Colorscheme

这些配色方案可能不是直接专门用于 Tree-sitter 的，而是用 Lua 编写的.

- [tjdevries/gruvbuddy.nvim](https://github.com/tjdevries/gruvbuddy.nvim) - 我的盒子颜色.
- [ellisonleao/gruvbox.nvim](https://github.com/ellisonleao/gruvbox.nvim) - Gruvbox 社区配色方案 Lua 端口.
- [metalelf0/jellybeans-nvim](https://github.com/metalelf0/jellybeans-nvim) - Neovim 的 jellybeans 配色方案端口.

### Utility

- [famiu/bufdelete.nvim](https://github.com/famiu/bufdelete.nvim) - 在不丢失窗口布局的情况下删除 Neovim 缓冲区.
<!--lint ignore double-link-->
- [mini.bufremove](https://github.com/echasnovski/mini.nvim#minibufremove) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 用于在保存窗口布局时删除缓冲区（取消显示、删除、擦除）.
- [jghauser/mkdir.nvim](https://github.com/jghauser/mkdir.nvim) - 保存文件时自动创建丢失的目录.
- [matbme/JABS.nvim](https://github.com/matbme/JABS.nvim) - 漂亮且最小的缓冲区切换器窗口.
- [clojure-vim/jazz.nvim](https://github.com/clojure-vim/jazz.nvim) - 酸 + 即兴 = 爵士.
- [sudormrfbin/cheatsheet.nvim](https://github.com/sudormrfbin/cheatsheet.nvim) - 可搜索的备忘单.
- [code-biscuits/nvim-biscuits](https://github.com/code-biscuits/nvim-biscuits)  - 各种饼干的 Neovim 端口. 最终也有更多受支持的语言.
- [Pocco81/AbbrevMan.nvim](https://github.com/Pocco81/AbbrevMan.nvim) - 用于管理 vim 缩写的 NeoVim 插件.
- [kazhala/close-buffers.nvim](https://github.com/kazhala/close-buffers.nvim) - 根据不同情况删除多个vim缓冲区.
- [rktjmp/paperplanes.nvim](https://github.com/rktjmp/paperplanes.nvim) - 将选择或缓冲区发布到在线粘贴箱.
- [max397574/better-escape.nvim](https://github.com/max397574/better-escape.nvim) - 创建快捷方式以逃避插入模式而不会延迟.
- [rcarriga/nvim-notify](https://github.com/rcarriga/nvim-notify) - A fancy, configurable, notification manager for NeoVim.
- [saifulapm/chartoggle.nvim](https://github.com/saifulapm/chartoggle.nvim) - 在 Neovim 的行尾切换任何字符.
- [stevearc/dressing.nvim](https://github.com/stevearc/dressing.nvim) - 改进内置的`vim.ui` 接口与望远镜、fzf 等.

### Icon

- [kyazdani42/nvim-web-devicons](https://github.com/kyazdani42/nvim-web-devicons) - 一个 Lua 叉 [vim-devicons](https://github.com/ryanoasis/vim-devicons).
- [yamatsum/nvim-nonicons](https://github.com/yamatsum/nvim-nonicons) - nvim-web-devicons 的配置集合.

### Debugging

- [mfussenegger/nvim-dap](https://github.com/mfussenegger/nvim-dap) - Neovim 的调试适配器协议客户端实现.
- [sakhnik/nvim-gdb](https://github.com/sakhnik/nvim-gdb) - GDB、LLDB、PDB/PDB++ 和 BashDB 的薄包装.
- [rcarriga/nvim-dap-ui](https://github.com/rcarriga/nvim-dap-ui) - 用户界面是 nvim-dap.
- [Pocco81/DAPInstall.nvim](https://github.com/Pocco81/DAPInstall.nvim) - 一个 NeoVim 插件，用于管理 Nvim-dap 的多个调试器.

### Spellcheck

- [lewis6991/spellsitter.nvim](https://github.com/lewis6991/spellsitter.nvim) - 使用 tree-sitter 启用 Neovim 的拼写检查器.

### Neovim Lua Development

- [tjdevries/nlua.nvim](https://github.com/tjdevries/nlua.nvim) - Neovim 的 Lua 开发.
- [svermeulen/vimpeccable](https://github.com/svermeulen/vimpeccable) - 帮助用 Lua 或任何基于 Lua 的语言编写 .vimrc 的命令.
- [nanotee/nvim-lua-guide](https://github.com/nanotee/nvim-lua-guide) - 在 Neovim 中使用 Lua 的指南.
- [rafcamlet/nvim-luapad](https://github.com/rafcamlet/nvim-luapad) - 用于嵌入式 Lua 引擎的交互式实时 Neovim 暂存器 - 输入并观看！.
- [nvim-lua/plenary.nvim](https://github.com/nvim-lua/plenary.nvim)  - 全体会议：已满； 完全的; 全部的; 绝对; 不合格. 我不想写两次的所有 Lua 函数.
- [nvim-lua/popup.nvim](https://github.com/nvim-lua/popup.nvim) - Neovim 中来自 vim 的 Popup API 的实现.
- [tjdevries/vlog.nvim](https://github.com/tjdevries/vlog.nvim) - 单个文件，无依赖性，轻松复制和粘贴日志文件以添加到您的 Neovim Lua 插件中.
- [bfredl/nvim-luadev](https://github.com/bfredl/nvim-luadev)  - Neovim Lua 插件的 REPL/调试控制台.  `:Luadev` 命令将打开一个临时窗口，该窗口将显示执行 Lua 代码的输出.
- [jbyuki/one-small-step-for-vimkind](https://github.com/jbyuki/one-small-step-for-vimkind)  - Neovim Lua 语言的适配器. 它允许您调试在 Neovim 实例（可以调试 Neovim Lua 插件的 Lua 插件）中运行的任何 Lua 代码.
- [tami5/sqlite.lua](https://github.com/tami5/sqlite.lua) - Lua 和 Neovim 的 SQLite/LuaJIT 绑定.
- [folke/lua-dev.nvim](https://github.com/folke/lua-dev.nvim) - init.Lua 和插件开发的开发设置，以及 Neovim Lua API 的完整签名帮助、文档和完成.
- [MunifTanjim/nui.nvim](https://github.com/MunifTanjim/nui.nvim) - Neovim 的 UI 组件库.
- [m00qek/plugin-template.nvim](https://github.com/m00qek/plugin-template.nvim) - 设置测试基础设施和 GitHub 操作的插件模板.

### Fennel

- [Olical/aniseed](https://github.com/Olical/aniseed) - 使用 Fennel（Lisp 到 Lua）配置和扩展 Neovim.
- [rktjmp/hotpot.nvim](https://github.com/rktjmp/hotpot.nvim) - Neovim 内部无缝、透明的茴香.

### Tabline

- [romgrk/barbar.nvim](https://github.com/romgrk/barbar.nvim) - Neovim 标签插件.
- [akinsho/bufferline.nvim](https://github.com/akinsho/bufferline.nvim) - 使用 Lua 构建的 Neovim 的时髦缓冲线.
- [crispgm/nvim-tabline](https://github.com/crispgm/nvim-tabline) - 带有 Lua 的 tabline.vim 的 Neovim 端口.
- [alvarosevilla95/luatab.nvim](https://github.com/alvarosevilla95/luatab.nvim) - 一个用 Lua 编写的简单表格.
- [johann2357/nvim-smartbufs](https://github.com/johann2357/nvim-smartbufs) - Neovim 中的智能缓冲区管理.
- [kdheepak/tabline.nvim](https://github.com/kdheepak/tabline.nvim) - “缓冲区和标签”标签.
- [noib3/cokeline.nvim](https://github.com/noib3/cokeline.nvim) - 适合有成瘾性格的人的 Neovim 缓冲线.
<!--lint ignore double-link-->
- [mini.tabline](https://github.com/echasnovski/mini.nvim#minitabline) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 对于最小的tabline，在一个选项卡的情况下显示列出的缓冲区，否则回退到默认值.
- [rafcamlet/tabline-framework.nvim](https://github.com/rafcamlet/tabline-framework.nvim) - 用户友好的框架，只需几行代码即可构建您梦想中的标签.

### Statusline

- [NTBBloodbath/galaxyline.nvim](https://github.com/NTBBloodbath/galaxyline.nvim)  - Galaxyline 通过为每个文本区域提供一个提供程序，将 Vim 的状态行组件化. 这意味着您可以使用由galaxyline 提供的api 轻松创建您想要的状态行.
- [tjdevries/express_line.nvim](https://github.com/tjdevries/express_line.nvim) - 支持协同程序、函数和作业.
- [nvim-lualine/lualine.nvim](https://github.com/nvim-lualine/lualine.nvim) - 快速且易于配置的 Neovim 状态栏.
- [adelarsq/neoline.vim](https://github.com/adelarsq/neoline.vim) - 使用 Lua 的 Neovim 状态栏/标签栏插件.
- [ojroques/nvim-hardline](https://github.com/ojroques/nvim-hardline)  - 状态线/缓冲线. 它的灵感来自 [vim-airline](https://github.com/vim-airline/vim-airline) 但旨在尽可能轻巧和简单.
- [datwaft/bubbly.nvim](https://github.com/datwaft/bubbly.nvim) - Neovim 的气泡状态行.
- [beauwilliams/statusline.lua](https://github.com/beauwilliams/statusline.lua) - 用 Lua 编写的 Neovim 的零配置最小状态行，具有出色的集成和极快的速度！
- [tamton-aquib/staline.nvim](https://github.com/tamton-aquib/staline.nvim)  - Lua 中 Neovim 的现代轻量级状态栏. 主要使用 unicode 符号来显示信息.
- [Famiu/feline.nvim](https://github.com/Famiu/feline.nvim) - 用 Lua 编写的 Neovim 的简约、时尚和可定制的状态栏.
- [windwp/windline.nvim](https://github.com/windwp/windline.nvim) - The next generation statusline for Neovim. Animation statusline.
- [konapun/vacuumline.nvim](https://github.com/konapun/vacuumline.nvim) - 受航空公司启发的星系线配置.
<!--lint ignore double-link-->
- [mini.statusline](https://github.com/echasnovski/mini.nvim#ministatusline) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 用于最小和快速状态行. 支持根据窗口宽度更改内容.

### Statusline component

- [SmiteshP/nvim-gps](https://github.com/SmiteshP/nvim-gps) - 简单的状态栏组件，显示您在内部工作的范围.

### Cursorline

- [yamatsum/nvim-cursorline](https://github.com/yamatsum/nvim-cursorline) - Neovim 的插件，可突出显示光标词和行.
- [xiyaowong/nvim-cursorword](https://github.com/xiyaowong/nvim-cursorword)  - nvim-cursorline 的一部分. 突出显示光标下的单词.
- [RRethy/vim-illuminate](https://github.com/RRethy/vim-illuminate)  - 突出显示光标下的单词.  Neovim的内置LSP可用，可以更智能地突出显示.
<!--lint ignore double-link-->
- [mini.cursorword](https://github.com/echasnovski/mini.nvim#minicursorword) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 用于自动突出显示光标下的单词（在可自定义的延迟后显示）.

### Startup

- [glepnir/dashboard-nvim](https://github.com/glepnir/dashboard-nvim) - Neovim 的简约仪表板，灵感来自 doom-emacs.
- [goolord/alpha-nvim](https://github.com/goolord/alpha-nvim) - 快速且高度可定制的迎宾员，如 [vim-startify](https://github.com/mhinz/vim-startify)/dashboard-nvim 用于 Neovim.
<!--lint ignore double-link-->
- [mini.starter](https://github.com/echasnovski/mini.nvim#ministarter) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 对于开始屏幕. 显示的项目是完全可定制的，项目选择可以使用带有即时视觉反馈的前缀查询来完成.
- [henriquehbr/nvim-startup.lua](https://github.com/henriquehbr/nvim-startup.lua) - 显示 Neovim 启动时间.
- [startup-nvim/startup.nvim](https://github.com/startup-nvim/startup.nvim) - 完全可定制的 Neovim 迎宾器.

### Indent

- [glepnir/indent-guides.nvim](https://github.com/glepnir/indent-guides.nvim) - 缩进插件.
- [lukas-reineke/indent-blankline.nvim](https://github.com/lukas-reineke/indent-blankline.nvim) - Lua 中的 IndentLine 替换，具有更多功能和 treeitter 支持.

### Game

- [ThePrimeagen/vim-be-good](https://github.com/ThePrimeagen/vim-be-good) - Vim-be-good 是一个 Neovim 插件，旨在让您在 Vim 运动方面做得更好.
- [ThePrimeagen/vim-apm](https://github.com/ThePrimeagen/vim-apm) - Vim APM，每分钟操作数，是自 vim-slicedbread 以来最伟大的插件.
- [alec-gibson/nvim-tetris](https://github.com/alec-gibson/nvim-tetris) - 为 Neovim 带来 emacs 最大的功能——俄罗斯方块！
- [seandewar/nvimesweeper](https://github.com/seandewar/nvimesweeper) - 在您最喜欢的文本编辑器中玩扫雷.

### File explorer

- [kyazdani42/nvim-tree.lua](https://github.com/kyazdani42/nvim-tree.lua) - Neovim 的简单快速的文件浏览器树！.
- [luukvbaal/nnn.nvim](https://github.com/luukvbaal/nnn.nvim) - 文件浏览器由 [nnn](https://github.com/jarun/nnn) 和路亚.
- [tamago324/lir.nvim](https://github.com/tamago324/lir.nvim) - 简单的文件浏览器.
- [TimUntersberger/neofs](https://github.com/TimUntersberger/neofs) - 用 Lua 编写的 Neovim 文件管理器.
- [kevinhwang91/rnvimr](https://github.com/kevinhwang91/rnvimr) - 一个用于 Neovim 的简单而惊人的文件浏览器.
- [Xuyuanp/yanil](https://github.com/Xuyuanp/yanil) - Lua 中的另一个 Nerdtree.
- [ms-jpq/chadtree](https://github.com/ms-jpq/chadtree)  - Neovim 的文件管理器. 比 NERDTree 好.
- [is0n/fm-nvim](https://github.com/is0n/fm-nvim) - Neovim 插件，可让您在 Neovim 中使用您最喜欢的终端文件管理器（和模糊查找器）.

### Dependency management

- [akinsho/dependency-assist.nvim](https://github.com/akinsho/dependency-assist.nvim) - 搜索并添加新的依赖项（飞镖，现在，但很快就会生锈）.
- [vuki656/package-info.nvim](https://github.com/vuki656/package-info.nvim) - 在 package.json 中将最新的包版本显示为虚拟文本.

### Git

- [f-person/git-blame.nvim](https://github.com/f-person/git-blame.nvim) - 显示 git 责备信息.
- [lewis6991/gitsigns.nvim](https://github.com/lewis6991/gitsigns.nvim) - Git 集成：标志、大块头动作、责备等.
- [TimUntersberger/neogit](https://github.com/TimUntersberger/neogit) - Neovim 的 Magit 克隆，可能会改变一些东西以适应 Vim 哲学.
- [tveskag/nvim-blame-line](https://github.com/tveskag/nvim-blame-line) - 一个小插件，使用 Neovims 虚拟文本在当前行的末尾打印 git blame 信息.
- [ruifm/gitlinker.nvim](https://github.com/ruifm/gitlinker.nvim)  - 为多个 git 主机生成可共享的文件永久链接. 灵感来自 tpope/vim-fugitive 的 :GBrowse.
- [tanvirtin/vgit.nvim](https://github.com/tanvirtin/vgit.nvim) - 用于 Neovim 的可视化 Git 插件，以增强您的 git 体验.
- [sindrets/diffview.nvim](https://github.com/sindrets/diffview.nvim) - 单标签页界面，可轻松循环浏览任何 git rev 的所有修改文件的差异.
- [kdheepak/lazygit.nvim](https://github.com/kdheepak/lazygit.nvim) - 用于从 Neovim 中调用 lazygit 的插件.

### Programming languages support

- [go.nvim](https://github.com/ray-x/go.nvim) - 基于 lsp 和 Treesitter 的 Golang 插件.
- [akinsho/flutter-tools.nvim](https://github.com/akinsho/flutter-tools.nvim) - 使用本机 lsp 在 Neovim 中构建 flutter 和 dart 应用程序.
- [crispgm/nvim-go](https://github.com/crispgm/nvim-go) - Neovim 的 Golang 开发插件的最小实现.
- [gennaro-tedesco/nvim-jqx](https://github.com/gennaro-tedesco/nvim-jqx) - json 文件的交互界面.
- [edolphin-ydf/goimpl.nvim](https://github.com/edolphin-ydf/goimpl.nvim) - 为类型生成接口存根.
- [lean.nvim](https://github.com/Julian/lean.nvim) - Neovim 支持 [Lean Theorem Prover](https://leanprover.github.io/).
- [rafaelsq/nvim-goc.lua](https://github.com/rafaelsq/nvim-goc.lua) - 使用 Golang Code Coverage 突出显示您的缓冲区.

### Comment

- [numToStr/Comment.nvim](https://github.com/numToStr/Comment.nvim)  - Neovim 智能而强大的评论插件. 支持注释字符串、动作、点重复等.
- [b3nj5m1n/kommentary](https://github.com/b3nj5m1n/kommentary) - 用 Lua 编写的评论插件.
- [glepnir/prodoc.nvim](https://github.com/glepnir/prodoc.nvim) - 评论和支持生成注释.
- [gennaro-tedesco/nvim-commaround](https://github.com/gennaro-tedesco/nvim-commaround) - 用 Lua 编写的快速轻便的评论插件.
- [folke/todo-comments.nvim](https://github.com/folke/todo-comments.nvim) - 在您的项目中突出显示、列出和搜索待办事项评论.
- [terrortylor/nvim-comment](https://github.com/terrortylor/nvim-comment) - 使用内置的注释字符串选项在 Neovim 中切换注释.
- [winston0410/commented.nvim](https://github.com/winston0410/commented.nvim) - 支持计数和多种评论模式等的评论插件.
- [s1n7ax/nvim-comment-frame](https://github.com/s1n7ax/nvim-comment-frame) - 添加基于源文件的评论框.
- [danymat/neogen](https://github.com/danymat/neogen)  - 更好的注释生成器. 支持多种语言和注释约定.
<!--lint ignore double-link-->
- [mini.comment](https://github.com/echasnovski/mini.nvim#minicomment) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 用于每行注释. 完全支持点重复.

### Collaborative Editing

- [jbyuki/instant.nvim](https://github.com/jbyuki/instant.nvim) - 一个用 Lua 编写的 Neovim 协作编辑插件，没有依赖项.

### Quickfix

- [kevinhwang91/nvim-bqf](https://github.com/kevinhwang91/nvim-bqf) - nvim-bqf 的目标是让 Neovim 的 quickfix 窗口更好.
- [gitlab.com/yorickpeterse/nvim-pqf](https://gitlab.com/yorickpeterse/nvim-pqf) - 更漂亮的 Neovim 快速修复/位置列表窗口.
- [stevearc/qf_helper.nvim](https://github.com/stevearc/qf_helper.nvim) - Neovim quickfix 的一系列改进.

### Motion

- [tjdevries/train.nvim](https://github.com/tjdevries/train.nvim) - 用 vim 动作训练自己并制作自己的火车轨道.
- [phaazon/hop.nvim](https://github.com/phaazon/hop.nvim) - Hop 是一个类似于 EasyMotion 的插件，允许您以尽可能少的击键次数跳转到文档中的任何位置.
- [ggandor/lightspeed.nvim](https://github.com/ggandor/lightspeed.nvim) - 一个类似 Sneak 的插件，通过提前显示的标签提供无与伦比的导航速度，消除了输入搜索模式和选择目标之间的停顿.
<!--lint ignore double-link-->
- [mini.jump](https://github.com/echasnovski/mini.nvim#minijump) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 更智能地跳转到单个字符.
- [mfussenegger/nvim-ts-hint-textobject](https://github.com/mfussenegger/nvim-ts-hint-textobject) - 区域选择，在由 treeitter 提供支持的文档的 AST 节点上提供提示.

### Code Runner

- [michaelb/sniprun](https://github.com/michaelb/sniprun) - 直接从 Neovim 运行任何语言的部分代码.
- [pianocomposer321/yabs.nvim](https://github.com/pianocomposer321/yabs.nvim) - 另一个用 Lua 编写的 Neovim 构建系统.
- [CRAG666/code_runner.nvim](https://github.com/CRAG666/code_runner.nvim) - 您可以拥有的最好的代码运行器，具有超能力.
- [is0n/jaq-nvim](https://github.com/is0n/jaq-nvim) - Lua 中 Neovim 的另一个 Quickrun 插件.

### GitHub

- [pwntester/octo.nvim](https://github.com/pwntester/octo.nvim)  - 处理来自 Neovim 的 GitHub 问题和 PR. 只需编辑问题描述.
- [pwntester/codeql.nvim](https://github.com/pwntester/codeql.nvim) - 帮助编写和测试 CodeQL 查询的 Neovim 插件.

### Search

- [kevinhwang91/nvim-hlslens](https://github.com/kevinhwang91/nvim-hlslens) - 帮助您更好地浏览搜索信息，无缝跳转匹配实例.
- [rktjmp/highlight-current-n.nivm](https://github.com/rktjmp/highlight-current-n.nvim)  - 突出显示当前 /, ? 或 \* 在按 n 或 N 时匹配光标下，然后让路.

### Scrollbar

- [Xuyuanp/scrollbar.nvim](https://github.com/Xuyuanp/scrollbar.nvim) - Neovim 的滚动条.
- [dstein64/nvim-scrollview](https://github.com/dstein64/nvim-scrollview) - 显示交互式滚动条的 Neovim 插件.

### Scrolling

- [karb94/neoscroll.nvim](https://github.com/karb94/neoscroll.nvim) - Neovim 的平滑滚动.

### Mouse

- [notomo/gesture.nvim](https://github.com/notomo/gesture.nvim) - Neovim 的鼠标手势插件.

### Project

- [nyngwang/NeoRoot.lua](https://github.com/nyngwang/NeoRoot.lua) - 将当前工作目录更改为光标所在的缓冲区，并尝试上升 2 个级别，但在遇到您定义的项目根目录之一后停止.
- [windwp/nvim-projectconfig](https://github.com/windwp/nvim-projectconfig) - 根据项目目录加载 Neovim 配置.
- [windwp/nvim-spectre](https://github.com/windwp/nvim-spectre) - 搜索和替换 Neovim 面板.
- [ahmedkhalf/project.nvim](https://github.com/ahmedkhalf/project.nvim) - 一个多合一的 Neovim 插件，提供卓越的项目管理.
- [klen/nvim-config-local](https://github.com/klen/nvim-config-local) - 从工作目录安全加载本地配置文件.

### Browser integration

- [glacambre/firenvim](https://github.com/glacambre/firenvim) - 将 Neovim 直接嵌入您的浏览器，无需提问.

### Editing support

- [windwp/nvim-ts-autotag](https://github.com/windwp/nvim-ts-autotag) - 使用 treeitter 自动关闭和自动重命名 xml、html、jsx 标签.
- [windwp/nvim-autopairs](https://github.com/windwp/nvim-autopairs) - Lua 为 Neovim 编写的极简自动配对.
- [steelsojka/pears.nvim](https://github.com/steelsojka/pears.nvim) - Neovim 的自动配对插件.
<!--lint ignore double-link-->
- [mini.pairs](https://github.com/echasnovski/mini.nvim#minipairs) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 用于具有最少默认值和功能来执行每个键映射的自动配对.
- [monaqa/dial.nvim](https://github.com/monaqa/dial.nvim) - 扩展增量/减量.
- [p00f/nvim-ts-rainbow](https://github.com/p00f/nvim-ts-rainbow) - Rainbow :rainbow: 使用 tree-sitter :rainbow: 的 Neovim 括号.
- [AckslD/nvim-revJ.lua](https://github.com/AckslD/nvim-revJ.lua) - Neovim Lua 插件，用于对参数执行与连接线 (J) 相反的操作.
- [edluffy/specs.nvim](https://github.com/edluffy/specs.nvim) - 一个快速、轻量级的 Neovim Lua 插件，可以密切关注光标的跳跃位置.
- [JoosepAlviste/nvim-ts-context-commentstring](https://github.com/JoosepAlviste/nvim-ts-context-commentstring)  - 一个 Neovim 插件，用于根据文件中的光标位置设置 `commentstring` 选项. 该位置是通过 treeitter 查询检查的.
- [Pocco81/TrueZen.nvim](https://github.com/Pocco81/TrueZen.nvim) - 干净优雅的 NeoVim 无干扰写作.
- [Pocco81/HighStr.nvim](https://github.com/Pocco81/HighStr.nvim) - 一个 NeoVim 插件，用于像在普通文档编辑器中一样突出显示视觉选择！
- [Pocco81/AutoSave.nvim](https://github.com/Pocco81/AutoSave.nvim) - 一个 NeoVim 插件，用于在世界崩溃或您输入 :qa 之前保存您的工作！
- [folke/zen-mode.nvim](https://github.com/folke/zen-mode.nvim) - Neovim 的无干扰编码.
- [haringsrob/nvim_context_vt](https://github.com/haringsrob/nvim_context_vt) - 显示当前上下文的虚拟文本.
- [romgrk/nvim-treesitter-context](https://github.com/romgrk/nvim-treesitter-context) - 显示当前功能/块上下文的浮动悬停.
- [mizlan/iswap.nvim](https://github.com/mizlan/iswap.nvim)  - 交互式选择和交换函数参数、列表元素等. 由保姆提供动力.
- [nacro90/numb.nvim](https://github.com/nacro90/numb.nvim) - 以不显眼的方式查看线条.
- [abecodes/tabout.nvim](https://github.com/abecodes/tabout.nvim) - 跳出括号、引号、对象等.
- [ethanholz/nvim-lastplace](https://github.com/ethanholz/nvim-lastplace) - 在上次编辑位置重新打开文件.
- [Allendang/nvim-expand-expr](https://github.com/AllenDang/nvim-expand-expr) - 将表达式扩展并重复到多行.
- [h-hg/fcitx.nvim](https://github.com/h-hg/fcitx.nvim) - 分别为每个缓冲区切换和恢复 fcitx 状态.
- [McAuleyPenney/tidy.nvim](https://github.com/McAuleyPenney/tidy.nvim) - 每次保存时清除文件末尾的尾随空格和空行.
<!--lint ignore double-link-->
- [mini.trailspace](https://github.com/echasnovski/mini.nvim#minitrailspace) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 用于自动突出显示尾随空格，并具有删除它的功能.
- [filipdutescu/renamer.nvim](https://github.com/filipdutescu/renamer.nvim) - 类似 VS Code 的 Neovim 重命名 UI，用 Lua 编写.
- [gbprod/cutlass.nvim](https://github.com/gbprod/cutlass.nvim) - 添加与“删除”分开的“剪切”操作的插件.
- [gbprod/substitute.nvim](https://github.com/gbprod/substitute.nvim) - Neovim 插件引入了新的操作员动作以快速替换文本.
- [sQVe/sort.nvim](https://github.com/sQVe/sort.nvim) - 智能支持按行和分隔符排序的排序插件.
- [booperlv/nvim-gomove](https://github.com/booperlv/nvim-gomove) - 一个完整的插件，用于移动和复制块和线，一次完成折叠处理、重新缩进和撤消.

### Formatting

- [mhartington/formatter.nvim](https://github.com/mhartington/formatter.nvim) - 用 Lua 编写的 Neovim 格式运行器.
- [lukas-reineke/format.nvim](https://github.com/lukas-reineke/format.nvim)  - Neovim 的快速异步格式化. 支持格式化嵌入的代码块.
- [sbdchd/neoformat](https://github.com/sbdchd/neoformat) - 用于格式化代码的 (Neo)vim 插件.

### Web development

- [NTBBloodbath/rest.nvim](https://github.com/NTBBloodbath/rest.nvim) - 一个用 Lua 编写的快速 Neovim http 客户端.

### Media

- [ekickx/clipboard-image.nvim](https://github.com/ekickx/clipboard-image.nvim) - Neovim Lua 插件从剪贴板粘贴图像.
- [gwatcha/reaper-keys](https://github.com/gwatcha/reaper-keys) - Reaper DAW 的模式键绑定.
- [madskjeldgaard/reaper-nvim](https://github.com/madskjeldgaard/reaper-nvim) - 来自 Neovim 的远程控制 Reaper DAW.
- [davidgranstrom/scnvim](https://github.com/davidgranstrom/scnvim) - SuperCollider 的 Neovim 前端.

### Discord Rich Presence

- [andweeb/presence.nvim](https://github.com/andweeb/presence.nvim) - 用 Lua 编写的用于 Neovim 的快速和精简的 Discord Rich Presence 插件.

### Command Line

- [notomo/cmdbuf.nvim](https://github.com/notomo/cmdbuf.nvim) - 替代命令行窗口插件.
- [gelguy/wilder.nvim](https://github.com/gelguy/wilder.nvim) - 模糊命令行自动完成插件.

### Session

- [rmagatti/auto-session](https://github.com/rmagatti/auto-session) - Neovim 的小型自动会话管理器.
<!--lint ignore double-link-->
- [mini.sessions](https://github.com/echasnovski/mini.nvim#minisessions) - 模块 [echasnovski/mini.nvim](https://github.com/echasnovski/mini.nvim) 用于会话管理（读、写、删除）.

### Test

- [rcarriga/vim-ultest](https://github.com/rcarriga/vim-ultest) - NeoVim 的终极测试插件.
- [David-Kunz/jester](https://github.com/David-Kunz/jester) - 一个 Neovim 插件，可轻松运行和调试 Jest 测试.

### Preconfigured Configuration

- [SpaceVim/SpaceVim](https://spacevim.org) - 社区驱动的模块化 vim/neovim 发行版，类似于 spacemacs，但适用于 vim/neovim.
- [CosmicNvim/CosmicNvim](https://github.com/CosmicNvim/CosmicNvim) - CosmicNvim 是用于 Web 开发的轻量级和自以为是的 Neovim 配置，专门设计用于提供 COSMIC 编程体验！
- [artart222/CodeArt](https://github.com/artart222/CodeArt) - 一个完全用 Lua 编写的快速通用 IDE，带有适用于 Linux/Windows/macOS 的安装程序，并内置了用于更新它的 `:CodeArtUpdate` 命令.
- [NTBBloodbath/doom-nvim](https://github.com/NTBBloodbath/doom-nvim) - doom-emacs 框架的移植，其目标是为 Neovim 添加有用的功能，以便在稳定高效的开发环境中开始工作，而无需花费大量时间配置一切.
- [crivotz/nv-ide](https://github.com/crivotz/nv-ide) - Neovim 自定义配置，面向全栈开发人员（rails、ruby、php、html、css、SCSS、JavaScript）.
- [ChristianChiarulli/LunarVim](https://github.com/ChristianChiarulli/LunarVim) - 该项目旨在帮助人们从 VSCode 过渡到卓越的文本编辑体验.
- [hackorum/VapourNvim](https://github.com/hackorum/VapourNvim) - 用于类似 vim IDE 的终极体验的 NeoVim 配置.
- [vi-tality/neovitality](https://github.com/vi-tality/neovitality) - 功能齐全的 NeoVim 发行版，与 Nix Flake 打包在一起，易于安装和重现.
- [siduck76/NvChad](https://github.com/siduck76/NvChad) - 尝试使 Neovim cli 与 IDE 一样具有功能性，同时非常美观且不那么臃肿.
- [ashincoder/StarVim](https://github.com/ashincoder/StarVim) - 超越月亮和星星的 IDE 包装器⭐.
- [mjlbach/defaults.nvim](https://github.com/mjlbach/defaults.nvim) - 一个极小的、单个文件和注释的配置模板，演示了 LSP 集成、自动完成、片段、treesitter 等.
- [cstsunfu/.sea.nvim](https://github.com/cstsunfu/.sea.nvim) - 模块化 NeoVim 配置，具有漂亮的 UI 和一些有用的功能（番茄钟、窗口编号）.
- [shaeinst/roshnivim](https://github.com/shaeinst/roshnivim) - Roshnivim，可以称为neovim 的发行版，是预定义的配置，因此您不需要1000 小时将neovim 设置为IDE.

### Keybinding

- [AckslD/nvim-whichkey-setup.lua](https://github.com/AckslD/nvim-whichkey-setup.lua) - 包装 vim-which-key 的插件以简化 Lua 中的设置.
- [folke/which-key.nvim](https://github.com/folke/which-key.nvim) - Neovim 插件，显示一个弹出窗口，其中包含您开始输入的命令的可能键绑定.
- [Iron-E/nvim-cartographer](https://github.com/Iron-E/nvim-cartographer) - Lua 环境更方便的`:map`ping 语法.
- [b0o/mapx.nvim](https://github.com/b0o/mapx.nvim)  - 一个更简单的键映射 API，模仿 Neovim 的`:map`-系列命令. 与 which-key.nvim 集成.
- [LionC/nest.nvim](https://github.com/LionC/nest.nvim)  - Lua 实用程序，可使用级联树简明地映射键. 还允许将 Lua 函数绑定到键.
- [LinArcX/telescope-command-palette.nvim](https://github.com/LinArcX/telescope-command-palette.nvim) - Lua 插件来创建键绑定并用望远镜观察它们.

### Tmux

- [aserowy/tmux.nvim](https://github.com/aserowy/tmux.nvim) - Neovim 的 Tmux 集成具有从 Neovim 内部移动窗格和调整大小的功能.
- [danielpieper/telescope-tmuxinator.nvim](https://github.com/danielpieper/telescope-tmuxinator.nvim) - tmuxinator 与望远镜.nvim 的集成.
- [hkupty/nvimux](https://github.com/hkupty/nvimux) - Neovim 作为 tmux 替代品.
- [numToStr/Navigator.nvim](https://github.com/numToStr/Navigator.nvim) - 在 Neovim 拆分和 Tmux 窗格之间顺畅导航.

### Remote Development

- [chipsenkbeil/distant.nvim](https://github.com/chipsenkbeil/distant.nvim) - 在舒适的本地环境中，在远程机器上编辑文件、运行程序和使用 LSP.
- [jamestthompson3/nvim-remote-containers](https://github.com/jamestthompson3/nvim-remote-containers) - 在 docker 容器内开发，就像 VSCode 一样.

### Split and Window

- [henriquehbr/ataraxis.lua](https://github.com/henriquehbr/ataraxis.lua) - 一种用于提高 Neovim 代码可读性的禅宗模式.
- [gitlab.com/yorickpeterse/nvim-window](https://gitlab.com/yorickpeterse/nvim-window) - 在 Neovim 窗口之间轻松跳转.
- [sindrets/winshift.nvim](https://github.com/sindrets/winshift.nvim) - 轻松重新布置您的窗户.
- [beauwilliams/focus.nvim](https://github.com/beauwilliams/focus.nvim)  - 用 Lua 编写的 Neovim 的自动聚焦和自动调整分割/窗口大小！  Vim 在类固醇上分裂.
- [luukvbaal/stabilize.nvim](https://github.com/luukvbaal/stabilize.nvim) - 稳定窗口打开/关闭事件的窗口内容.

## External

这些工具在 Neovim 外部使用以增强体验.

### Version Manager

- [NTBBloodbath/nvenv](https://github.com/NTBBloodbath/nvenv) - 一个轻量级和极快的 Neovim 版本管理器.
- [shohi/neva](https://github.com/shohi/neva) - 一个用 Lua 编写的 Neovim 版本管理器.

### Boilerplate

- [gennaro-tedesco/boilit](https://github.com/gennaro-tedesco/boilit) - 为 Neovim 插件创建样板结构.

## Vim

- [Vimawesome](https://vimawesome.com/) - 展示了 vim 的各种插件，并有一个 [neovim tag](https://vimawesome.com/?q=tag:neovim) 对于其他针对 Neovim 的插件.
- [awesome-vim](https://github.com/akrawchyk/awesome-vim#tools) - vim 插件和有用指南的简短列表.

## Resource

- [Neovimcraft](https://neovimcraft.com) - 一个专门用于搜索 Neovim 特定插件和在 Lua 中构建插件的指南的站点.