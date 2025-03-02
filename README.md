# Biscuit Library Index (BiLI)
 <small>Created by Biscuit Library Authority (BiLA)</small>


If you would like to have a library calls `mylib`, then:
 - Fork the repository
 - Add your code
 - Make a pull request

## How does a code looks like

### The structure
 - lib_{libname}.biasm
 - require_{libname}.json

### Library BiASM
This is a normal biasm file

### Require JSON
```
{
    "require": [
        "libname#github:user/repo"
    ]    
}
```

## How2Install from the Biscuit Library Index
You can use \
`biscuit install {biscuit} lib#github:isobiscuit/store` or you use `bfetcher lib#github:isobiscuit/store`

