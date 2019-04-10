# Split Object

**Status** – _Maintained_ – Until [#138]

[![IRC][IRC Badge]][IRC]

###### [Usage](#usage) | [Documentation](#modes) | [Contributing](CONTRIBUTING)

> Split object for [Kakoune].

[![asciicast](https://asciinema.org/a/239870.svg)](https://asciinema.org/a/239870)

## Installation

### [Pathogen]

``` kak
pathogen-infect /home/user/repositories/github.com/alexherbo2/split-object.kak
```

## Usage

``` kak
map global normal <a-I> ': enter-user-mode split-object<ret>'
```

## Modes

- `split-object`

## Objects

- `b`, `(`, `)`: Parenthesis block
- `B`, `{`, `}`: Braces block
- `r`, `[`, `]`: Brackets block
- `a`, `<`, `>`: Angle block
- `Q`, `"`: Double quote string
- `q`, `'`: Single quote string
- `g`, `` ` ``: Grave quote string
- `c`: Custom object description

[#138]: https://github.com/mawww/kakoune/issues/138
[Kakoune]: https://kakoune.org
[IRC]: https://webchat.freenode.net?channels=kakoune
[IRC Badge]: https://img.shields.io/badge/IRC-%23kakoune-blue.svg
[Pathogen]: https://github.com/alexherbo2/pathogen.kak
