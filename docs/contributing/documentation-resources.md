# Documentation Resources
## External Resources

Our documentation is built on [Material for MkDocs](https://squidfunk.github.io/mkdocs-material/). Both Material and MkDocs provide extensive documentation of their own:

* [Material Documentation](https://squidfunk.github.io/mkdocs-material/reference/)
* [MkDocs Documentation](https://www.mkdocs.org/user-guide/writing-your-docs/)

MkDocs utilizes Markdown, a simple text formatting language. Many resources exist online to teach the basics of Markdown, there's even an interactive [Markdown tutorial](https://www.markdowntutorial.com/) that can be completed in about 10 minutes.

Markdown tables can be a bit of hassle to create manually, but a handy tool is available to help: [Tables Generator](https://www.tablesgenerator.com/markdown_tables#).

## Enabled Features
Material provides a wide range of built-in features that we can enabled or disable as needed. Below is a list of the currently enabled features and accompanying information.

| Feature                                                                                                                                           | Use                                                                                                                                                                                                             |
|---------------------------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [content.action.edit and content.action.view](https://squidfunk.github.io/mkdocs-material/setup/adding-a-git-repository/?h=features#code-actions) | Adds `edit` and `view` code action buttons                                                                                                                                                                      |
| [content.tooltips](https://squidfunk.github.io/mkdocs-material/reference/tooltips/?h=tooltips#improved-tooltips)                                  | When improved tooltips are enabled, Material for MkDocs replaces the browser's rendering logic for title attribute with beautiful little tooltips.                                                              |
| [content.code.copy](https://squidfunk.github.io/mkdocs-material/reference/code-blocks/?h=content+code+copy#code-copy-button)                      | Code blocks can automatically render a button on the right side to allow the user to copy a code block's contents to the clipboard.                                                                             |
| [content.code.annotate](https://squidfunk.github.io/mkdocs-material/reference/code-blocks/?h=content+code+copy#code-annotations)                  | Code annotations offer a comfortable and friendly way to attach arbitrary content to specific sections of code blocks by adding numeric markers in block and inline comments in the language of the code block. |
| [navigation.top](https://squidfunk.github.io/mkdocs-material/setup/setting-up-navigation/?h=navigation#back-to-top-button)                        | A back-to-top button can be shown when the user, after scrolling down, starts to scroll up again. It's rendered centered and just below the header.                                                             |
| [navigation.indexes](https://squidfunk.github.io/mkdocs-material/setup/setting-up-navigation/?h=navigation#section-index-pages)                   | When section index pages are enabled, documents can be directly attached to sections, which is particularly useful for providing overview pages.                                                                |
| [navigation.tabs](https://squidfunk.github.io/mkdocs-material/setup/setting-up-navigation/?h=tabs#navigation-tabs)                                | When tabs are enabled, top-level sections are rendered in a menu layer below the header for viewports above 1220px, but remain as-is on mobile.                                                                 |

## Enabled Extensions
Material provides a wide range of helpful Markdown extensions that provide further functionality to our documentation.  Below is a list of the currently enabled extensions and accompanying information.

| Extension                                                                                                                                     | Use                                                                                                                                                                                                                                                  | Extra Information                                                                                                                                                                          |
|-----------------------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| [abbr](https://squidfunk.github.io/mkdocs-material/setup/extensions/python-markdown/?h=abbr#abbreviations)                                    | The Abbreviations extension adds the ability to add a small tooltip to an element, by wrapping it with an abbr tag. Only plain text (no markup) is supported.                                                                                        |                                                                                                                                                                                            |
| [pymdownx.snippets](https://squidfunk.github.io/mkdocs-material/setup/extensions/python-markdown-extensions/?h=snippets#snippets)             | The Snippets extension adds the ability to embed content from arbitrary files into a document, including other documents or source files, by using a simple syntax.                                                                                  | The snippets extension also allows us to utilize the glossary function of the abbr extension. Adding an abbreviation to `docs-resources/includes/abbreviations.md` will make it global.    |
| [admonition](https://squidfunk.github.io/mkdocs-material/reference/admonitions/?h=admonition#usage)                                           | Admonitions, also known as call-outs, are an excellent choice for including side content without significantly interrupting the document flow.                                                                                                       |                                                                                                                                                                                            |
| [pymdownx.details](https://squidfunk.github.io/mkdocs-material/setup/extensions/python-markdown-extensions/?h=details#details)                | The Details extension supercharges the Admonition extension, making the resulting call-outs [collapsible](https://squidfunk.github.io/mkdocs-material/reference/admonitions/#collapsible-blocks), allowing them to be opened and closed by the user. |                                                                                                                                                                                            |
| [pymdownx.superfences](https://squidfunk.github.io/mkdocs-material/setup/extensions/python-markdown-extensions/?h=superfences#superfences)    | The SuperFences extension allows for arbitrary nesting of code and content blocks inside each other, including admonitions, tabs, lists and all other elements.                                                                                      | We do not utilize the `custom_fences` option.                                                                                                                                              |
| [pymdownx.tilde](https://facelessuser.github.io/pymdown-extensions/extensions/tilde/)                                                         | Tilde optionally adds two different features which are syntactically built around the ~ character: delete which inserts                                                                                                                              | Tilde optionally adds two different features which are syntactically built around the ~ character: delete which inserts `<del></del>` tags and subscript which inserts `<sub></sub>` tags. |
| [pymdownx.highlight](https://squidfunk.github.io/mkdocs-material/setup/extensions/python-markdown-extensions/?h=highlight#highlight)          | The Highlight extension adds support for syntax highlighting of code blocks (with the help of SuperFences) and inline code blocks (with the help of InlineHilite).                                                                                   | * `anchor-linenums` enabled <br/> * `line-spans` enabled <br/> * `pygments_lang_class` enabled                                                                                             |
| [pymdownx.inlinehilite](https://squidfunk.github.io/mkdocs-material/setup/extensions/python-markdown-extensions/?h=inlinehilite#inlinehilite) | The InlineHilite extension add support for syntax highlighting of inline code blocks. It's built on top of the Highlight extension, from which it sources its configuration.                                                                         |                                                                                                                                                                                            |
| [pymdownx.tabbed](https://squidfunk.github.io/mkdocs-material/setup/extensions/python-markdown-extensions/?h=tabbed#tabbed)                   | The Tabbed extension allows the usage of content tabs, a simple way to group related content and code blocks under accessible tabs.                                                                                                                  | * `alternate_style` enabled                                                                                                                                                                |
| [attr_list](https://squidfunk.github.io/mkdocs-material/setup/extensions/python-markdown/?h=attr+list#attribute-lists)                        | The Attribute Lists extension allows to add HTML attributes and CSS classes to almost every Markdown inline- and block-level element with a special syntax.                                                                                          |                                                                                                                                                                                            |
| [pymdownx.emoji](https://squidfunk.github.io/mkdocs-material/reference/icons-emojis/?h=emoji)                                                 | This configuration enables the use of icons and emojis by using simple shortcodes which can be discovered through the icon search.                                                                                                                   | Custom icons stored in `docs-resources/.icons`                                                                                                                                             |
| [md_in_html](https://squidfunk.github.io/mkdocs-material/setup/extensions/python-markdown/?h=md+in+html#markdown-in-html)                     | The Markdown in HTML extension allows for writing Markdown inside of HTML, which is useful for wrapping Markdown content with custom elements.                                                                                                       |                                                                                                                                                                                            |
| [toc](https://squidfunk.github.io/mkdocs-material/setup/extensions/python-markdown/?h=toc#table-of-contents)                                  | The Table of Contents extension automatically generates a table of contents from a document, which Material for MkDocs will render as part of the resulting page                                                                                     |                                                                                                                                                                                            |

## Custom ClanGen Assets
We currently have custom icons set up, which can be utilized across the entire documentation. Below is a table displaying all current icons. 

|             Icon              |            Markdown             |
|:-----------------------------:|:-------------------------------:|
|     :clangen-arrow-left:      |     `:clangen-arrow-left:`      |
|  :clangen-arrow-left-double:  |  `:clangen-arrow-left-double:`  |
|     :clangen-arrow-right:     |     `:clangen-arrow-right:`     |
|      :clangen-cat-head:       |      `:clangen-cat-head:`       |
|     :clangen-clan-blank:      |     `:clangen-clan-blank:`      |
|    :clangen-clan-question:    |    `:clangen-clan-question:`    |
|     :clangen-clan-strike:     |     `:clangen-clan-strike:`     |
|        :clangen-dice:         |        `:clangen-dice:`         |
|       :clangen-droplet:       |       `:clangen-droplet:`       |
|        :clangen-herb:         |        `:clangen-herb:`         |
|        :clangen-leaf:         |        `:clangen-leaf:`         |
|         :clangen-log:         |         `:clangen-log:`         |
|       :clangen-magnify:       |       `:clangen-magnify:`       |
|        :clangen-mouse:        |        `:clangen-mouse:`        |
|         :clangen-paw:         |         `:clangen-paw:`         |
|      :clangen-scratches:      |      `:clangen-scratches:`      |
|      :clangen-snowflake:      |      `:clangen-snowflake:`      |
|       :clangen-sprout:        |       `:clangen-sprout:`        |
|      :clangen-starclan:       |      `:clangen-starclan:`       |
|         :clangen-sun:         |         `:clangen-sun:`         |
