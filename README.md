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

### Sidebar navigation
```toml
[[params.navigation.sidebar]]
    title = "sidebar 1"
    [[params.navigation.sidebar.item]]
        page = "/_index.md"
    [[params.navigation.sidebar.item]]
        text = "Top page"
        link = "/"
    [[params.navigation.sidebar.item]]
        page = "/_page.md"
        text = "override text"
[[params.navigation.sidebar]]
    title = "sidebar 2"
    [[params.navigation.sidebar.item]]
        text = "page"
        link = "/"
```

### Git page info
```toml
[params.pageinfo]
    commit = "<a href=\"https://github.com/your-name/repo-name/commit/{{hash}}\">{{hash}}</a>"
    change = "<a href=\"https://github.com/your-name/repo-name/commits/master/content/{{file}}\">View on GitHub</a>"
    subject = true
```

### Advanced ToC
```toml
[params]
toc = true
tocMove = true
tocTitle = "index"
tocMinimum = 2
```

### Disable meta description
```toml
[params]
outDescription = false
```

### noindex
```toml
[params]
noindex = true
```
