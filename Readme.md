# Lenhart Solutions website content
https://www.lenhartsolutions.com/


## Dev Setup

```
choco install hugo-extended
choco install golang
```

## Develop

```
hugo server -D
```


## Build
```
hugo
```
Files are generated in the `public/` directory.


## Deploy

Push to master (uses github actions)

## Notes

Added a theme this way
```
git submodule add https://github.com/kakawait/hugo-tranquilpeak-theme.git themes/hugo-tranquilpeak-theme
```

Uses shortcodes https://hugomods.com/en/docs/shortcodes/

```
hugo mod init github.com/xclayl/lenhart-solutions-site
```