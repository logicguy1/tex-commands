# tex-commands
Some useful commands for Texlive

# Mathematical Symbols:
- `$a^b$` is $a^b$ (exponents)
- `\int` is $\int$ (`$\int$`)
- `\circ` is used to make a circle or degree symbol such as  $180^{\circ}$ (`$180^{\circ}$`)
- `\space` is used to add spacing inside a mathematical expression.. $\int(x) \space + 1$ (`$\int(x) \space + 1$`)

# Text Coloring:
**NOTE:** in order for colorization you must add package `xcolor`

### Adding It:
```latex
\usepackage{xcolor}
```

---

### Usage:
The available colors are `black, blue, brown, cyan, darkgray, gray, green, lightgray, lime, magenta, olive, orange, pink, purple, red, teal, violet, white, yellow`

```latex
\color{your_color}This is a colored text\color{white} % white is the FG here
```

> ### Demo:

> ##### Code: 
```latex
\usepackage {xcolor}
\color{red}This is a red text\color{white}
\color{orange}This is an orange text\color{white}
\color{yellow}This is a yellow text\color{white}
\color{green}This is a green text\color{white}
\color{blue}This is a blue text\color{white}
\color{purple}This is a purple text\color{white}
```
> ##### Preview:
$$\color{red}This \space is \space a \space red \space text\color{white}$$

$$\color{orange}This \space is \space an \space orange \space text\color{white}$$

$$\color{yellow}This \space is \space a \space yellow \space text\color{white}$$

$$\color{green}This \space is \space a \space green \space text\color{white}$$

$$\color{blue}This \space is \space a \space blue \space text\color{white}$$

$$\color{purple}This \space is \space a \space purple \space text\color{white}$$

# Contributing:
On this README.md you may add an section or fix some mistakes
