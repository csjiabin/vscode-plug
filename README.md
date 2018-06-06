相似功能的插件，不推荐全都装上，请挑选一个使用
本列表所有插件都经过本人测试，且认为相对好用，但是不代表不存在任何问题，大多数可能与编辑器版本或是插件版本有关
如不能使用，请尝试更新编辑器和插件。其余问题，可以到插件对应的代码仓库提交issue

插件列表
---
名称 |	简述
---|---
Auto Close Tag |	自动闭合HTML标签
Auto Import	Typescript | 自动import提示
Auto Rename Tag |	修改HTML标签时，自动修改匹配的标签
Beautify css/sass/scss/less |	css/sass/less格式化
Better Align |	对齐赋值符号和注释
Better Comments |	编写更加人性化的注释
Bookmarks |	添加行书签
Bracket Pair Colorizer |	用不同颜色高亮显示匹配的括号
Can I Use |	HTML5、CSS3、SVG的浏览器兼容性检查
Code Runner |	运行选中代码段（支持大量语言，包括Node）
Code Spellchecke |r	单词拼写检查
CodeBing |	在VSCode中弹出浏览器并搜索，可编辑搜索引擎
Color Highlight |	颜色值在代码中高亮显示
Color Info | 小窗口显示颜色值，rgb,hsl,cmyk,hex等等
Color Picker |	拾色器
Dash |	集成Dash
Debugger for Chrome |	调试Chrome
Document This |	注释文档生成
ESLint |	ESLint插件，高亮提示
EditorConfig for VS Code |	EditorConfig插件
Emoji |	在代码中输入emoji
File Peek |	根据路径字符串，快速定位到文件
Font-awesome codes for html |	FontAwesome提示代码段
Git Blame |	在状态栏显示当前行的Git信息
Git History(git log) |	查看git log
GitLens |	显示文件最近的commit和作者，显示当前行commit信息
Guides |	高亮缩进基准线
Gulp Snippets |	Gulp代码段
HTML CSS Class Completion |	CSS class提示
HTML CSS Support |	css提示（支持vue）
HTMLHint |	HTML格式提示
htmltagwrap |	包裹HTML
Import Cost |	行内显示导入（import/require）的包的大小
Indenticator |	缩进高亮
IntelliSense for css class names |	css class输入提示
JavaScript (ES6) code snippets |	ES6语法代码段
JavaScript Standard Style |	Standard风格
JSON to TS |	JSON结构转化为typescript的interface
JSON Tools |	格式化和压缩JSON
Less IntelliSense |	less变量与混合提示
Lodash |	Lodash代码段
Log Wrapper |	生产打印选中变量的代码
MochaSnippets |	Mocha代码段
Node modules resolve |	快速导航到Node模块
Code Outline |	展示代码结构树
Output Colorizer |	彩色输出信息
Partial Diff |	对比两段代码或文件
Path Autocomplete |	路径完成提示
Path Intellisense |	另一个路径完成提示
PostCss Sorting |	css排序
Prettify JSON |	格式化JSON
Project Manager |	快速切换项目
Quokka.js |	不需要手动运行，行内显示变量结果
REST Client |	发送REST风格的HTTP请求
React Native Storybooks |	storybook预览插件，支持react
React Playground |	为编辑器提供一个react组件运行环境，方便调试
React Standard Style code snippets |	react standar风格代码块
Sass |	sass插件
Settings Sync |	VSCode设置同步到Gist
Sort Typescript Imports |	typescript的import排序
Sort lines |	排序选中行
String Manipulation |	字符串转换处理（驼峰、大写开头、下划线等等）
SVG Viewer |	SVG查看器
Syncing |	vscode设置同步到gist
TODO Parser |	Todo管理
TS/JS postfix completion |	ts/js后缀提示
TSLint |	TypeScript语法检查
Test Spec Generator |	测试用例生成（支持chai、should、jasmine）
TypeScript Import |	TS自动import
TypeSearch |	TS声明文件搜索
Types auto installer |	自动安装@types声明依赖
VSCode Great Icons |	文件图标拓展
Version Lens |	package.json文件显示模块当前版本和最新版本
View Node Package |	快速打开选中模块的主页和代码仓库
VueHelper |	Vue2代码段（包括Vue2 api、vue-router2、vuex2）
filesize |	状态栏显示当前文件大小
ftp-sync |	同步文件到ftp
gitignore |	.gitignore文件语法
htmltagwrap |	快捷包裹html标签
language-stylus |	Stylus语法高亮和提示
markdownlint |	Markdown格式提示
npm Intellisense |	导入模块时，提示已安装模块名称
npm |	运行npm命令
stylelint |	css/sass/less代码风格
vetur |	目前比较好的Vue语法高亮
vscode-database |	操作数据库，支持mysql和postgres
vscode-icons |	文件图标，方便定位文件
vscode-random |	随机字符串生成器
vscode-spotify |	集成spotify，播放音乐
vscode-styled-components |	styled-components高亮支持
vscode-styled-jsx |	styled-jsx高亮支持

附录：个人的VSCode首选项配置（仅供参考）
---
```
{
  "editor.tabSize": 2,
  "files.associations": {
      "*.vue": "vue"
  },
  "eslint.autoFixOnSave": true,
  "eslint.options": {
      "extensions": [
          ".js",
          ".vue"
      ]
  },
  "eslint.validate": [
      "javascript",
      "javascriptreact",
      "vue",
      "vue-html"
  ],
  "search.exclude": {
      "**/node_modules": true,
      "**/bower_components": true,
      "**/dist": true
  },
  "emmet.syntaxProfiles": {
      "javascript": "jsx",
      "vue": "html",
      "vue-html": "html"
  },
  "git.confirmSync": false,
  "window.zoomLevel": 0,
  "vsicons.projectDetection.autoReload": true,
  "typescript.check.tscVersion": false,
  "editor.renderWhitespace": "boundary",
  "editor.cursorBlinking": "smooth",
  "workbench.colorTheme": "Solarized Light",
  "workbench.iconTheme": "vscode-great-icons",
  "editor.minimap.enabled": true,
  "editor.minimap.renderCharacters": false,
  "tslint.autoFixOnSave": true,
  "editor.fontFamily": "'Droid Sans Mono', 'Courier New', monospace, 'Droid Sans Fallback'",
  "beautify.tabSize": 2,
  "window.title": "${dirty}${activeEditorMedium}${separator}${rootName}",
  "typescript.extension.sortImports.maxNamedImportsInSingleLine": 5,
  "typescript.extension.sortImports.omitSemicolon": true,
  "editor.codeLens": true,
  "editor.snippetSuggestions": "top",
  "react-native-storybooks.port": 6006
}
```
