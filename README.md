# Custom LaTeX Commands

This repository contains a collection of custom LaTeX commands and environments designed to enhance your LaTeX documents. Below is a detailed description of each command and environment provided in the `custom_commands.tex` file.

## Required Packages

To use the custom commands and environments, the following packages are required and already included in the custom_commands.tex file:
- `xcolor`
- `tcolorbox`
- `graphicx`
- `xparse`

## Environments

### `example`

Creates a boxed example with gray text.

```latex
\begin{example}
    Your example text here.
\end{example}
```

### `exampleline`

Creates a gray text in a centered minipage.

```latex
\begin{exampleline}
    Your example text here.
\end{exampleline}
```

### `important`

Creates a boxed note with an orange background and border.

```latex
\begin{important}
    Important information here.
\end{important}
```

## Color Commands

Change the color of the text.

### `\blue`

```latex
\blue{Your blue text here.}
```

### `\red`

```latex
\red{Your red text here.}
```

### `\green`

```latex
\green{Your green text here.}
```

### `\orange`

```latex
\orange{Your orange text here.}
```

## Arrow Commands

Commonly used arrows.

### `\ra`

```latex
\ra % renders →
```

### `\Ra`

```latex
\Ra % renders ⇒
```

### `\la`

```latex
\la % renders ←
```

### `\La`

```latex
\La % renders ⇐
```

## Production Commands

Parsing rules representation.

### `\production`

```latex
\production{X}{Y} % renders X → Y
```

### `\productionstar`

```latex
\productionstar{X}{Y} % renders X →* Y
```

### `\pn`

Shortcut for `\production`.

```latex
\pn{X}{Y} % renders X → Y
```

### `\pns`

Shortcut for `\productionstar`.

```latex
\pns{X}{Y} % renders X →* Y
```

## Image Command

Including images with an optional width parameter.

```latex
\img{path/to/image} % includes image with default 100% of text width
\img[0.5]{path/to/image} % includes image with 50% of text width
```

## Highlight Commands

Text highlighting with different colors.

### `\hl`

```latex
\hl{Highlighted text} % default yellow background
\hl[green!30]{Highlighted text} % green background
```

### `\hlgreen`

```latex
\hlgreen{Green highlighted text}
```

### `\hlyellow`

```latex
\hlyellow{Yellow highlighted text}
```

### `\hlorange`

```latex
\hlorange{Orange highlighted text}
```
## Highlight Block Commands

Highlight entire blocks of text with different colors.

### `\hlb`

```latex
\hlb{Your highlighted block text here.} % default yellow background
\hlb[green!30]{Your highlighted block text here.} % green background
```

### `\hlbgreen`

```latex
\hlbgreen{Your green highlighted block text here.}
```

### `\hlbyellow`

```latex
\hlbyellow{Your yellow highlighted block text here.}
```

### `\hlborange`

```latex
\hlborange{Your orange highlighted block text here.}
```

## Additional Section Depth

Deeper sectioning levels.

### `\subsubsubsection`

```latex
\subsubsubsection{Your section title}
```

## Usage

To use the commands and environments, simply include the `custom_commands.tex` file in your LaTeX document preamble:

```latex
\input{custom_commands.tex}
```

This will make all the custom commands and environments available for use in your document.

---

Feel free to contribute to this repository by submitting issues or pull requests if you have any suggestions or improvements. Enjoy using the custom LaTeX commands!