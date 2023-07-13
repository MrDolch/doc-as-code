# doc-as-code
_How to document code nowadays._

<img alt="product box" src="Produktbox.svg" width="50" height="50" align="left">

This project is **my** playground about software documentation. 

<br clear="all">

## Audience

My content is addressed to software developers.
Since I am native German, some content will be written in German.

## Product box

The product box shows in a few words the main purpose of the project.
Also for whom the product is and what requirements are necessary to use it.

![Product box](Produktbox.svg)

### Purpose of Product box

- If you plan to add new features to the product, you can look here to see if it fits at all.
  Sometimes it is better to develop a new product instead of adding more complexity to an existing one.
- If the project is new to you, you can tell at a glance from the product box what it does.
- A gorgeous product box can be used as a recognizable logo in listings.
- The size of the box is limitted so you need to focus on the most important things.

## Tool support

- ✎ : editable
- ✓ : properly rendered
- ✕ : not rendered
- 🧩 : support via plugin

| Source \ Tool | 🗁 GitHub | 🗁 GitLab | 🗁 BitBucket | 🗁 Confluence | 🛠 Intellij | 🛠 Visual Code | 🌐 Firefox | 🌐 Chrome | ✉ Outlook | ✉ Android | ✉ IOS |
|---------------|----------|----------|-------------|--------------|------------|---------------|-----------|----------|-----------|-----------|-------|
| Markdown      | ✎        | ✎        | ✎           |              | ✎          | ✎             | 🧩         | ✕        | ✕         | ✕         | ✕     |
| AsciiDocs     | ✎        | ✎        | 🧩           |              | ✎          | ✎             | ✕         | ✕        | ✕         | ✕         | ✕     |
| SVG           | ✎        | ✎        |             | ✕            | ✎          | ✎             | ✓         | ✓        |           |           |       |
| PNG           | ✓        | ✓        | ✓           | ✓            | ✓          | ✓             | ✓         | ✓        | ✓         | ✓         | ✓     |
| JavaDoc       | ✕        | ✕        | ✕           |              | ✎          | ✕             |           |          |           |           |       |
| PDF           |          |          |             |              |            |               |           |          | ✓         | ✓         |       |
| RTF           |          |          |             |              |            |               |           |          | ✓         |           |       |
| PlantUml      | ✕        | ✕        | ✕           | 🧩            | ✎          |               | ✕         | ✕        |           |           |       |
| HTML          |          |          |             | 🧩            | ✎          | ✎             | ✓         | ✓        | ✓         |           |       |
|               |          |          |             |              |            |               |           |          |           |           |       |

Since I depend on BitBucket and Intellij, I use Markdown and SVG.
I also use PlantUMl-Digrams but I convert them to SVG in order to see them in BitBucket.
When I need to email documentation to non-developers, then I render it as PDF. Markdown files are hardly to open on office desktops or mobile devices.
