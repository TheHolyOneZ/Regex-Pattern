# Regex-Pattern
Regex Patterns for: html,css,js,xml blah blah blah

> For one line "//" comments
```regex
^\s*//.*$
```

> For one line ```<!-- -->``` comments
```regex
^\s*<!--.*$
```

> For inline ```<!-- -->``` comments 

```regex
<!--(?!.*\|).*?-->
```

> for One line "/* */" comments
```
^\s*/\*.*?\*/\s*$
```
or
```
^\s*/\*.*\*/\s*$
```

> for inline "/* */" comments

```
/\*.*?\*/
```
