# Summit
**S**imple **U**ltimate **M**inimal A**MiT**  
Hugo theme for [AMiT](https://amit.jyn.jp/)

## Usage
### Catchphrase
```toml
[pamas]
catchphrase = "Your site catchphrase"
```

### Footer
```toml
[params]
footer = "{{catchphrase}}<br>&copy; {{year}} <a href=\"/\">FooBar</a>"
```

### Header navigation
```toml
[[params.navigation.header]]
    page = "/_index.md"
[[params.navigation.header]]
    text = "Top page"
    link = "/"
[[params.navigation.header]]
    page = "/_page.md"
    text = "override text"
```
