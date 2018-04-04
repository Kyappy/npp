# Notepad++

## Add VS2015-Dark theme

- Go to `%AppData%\Notepad++\themes` folder
- Add VS2015-Dark.xml file
- Open Notepad++
- Open window under `Settings/Style Configurator` menu
- Find the new added theme in the dropdown

## Add markdown syntax highlighting

- Open window under `Language/Define your language` menu
- Click on the import button
- Select userDefinedLang-markdown.vs2015.dark.xml file
- Restart Notepad++ And apply this language in the  for markdown files
- Reference: [Markdown Syntax Highlighting for Notepad++](https://github.com/Edditoria/markdown-plus-plus)


## Add markdown viewer

- Go to Notepad++ installation folder, then `\plugins` folder
- Add MarkdownViewerPlusPlus.dll (32 or 64 bits)
- Restart Notepad++
- Reference: [MarkdownViewer++](https://github.com/nea/MarkdownViewerPlusPlus
)

## Add style for markdown viewer

- Open window under `Plugins/MarkdownViewer++/Options` menu
- In HTML tab, paste the content of the MarkdownViewerPlusPlus.css file