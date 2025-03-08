# Biscuit Library Index (BiLI)
 <small>Created by Biscuit Library Authority (BiLA)</small>


If you would like to have a library calls `mylib`, then:
 - Fork the repository
 - Add your code
 - Make a pull request

## How does a code looks like

### The structure
 - pkgs/{lib}/lib.biasm //optional, if you want a lib pack
 - require/{lib}/require.json //optional, if you have no requirements

### Library BiASM
This is a normal biasm file

### Require JSON
this is optionial since the new bfetcher structure!
```
{
    "require": [
        "libname#github:user/repo",
        "myofficiallib"
    ]    
}
```

## How2Install from the Biscuit Library Index
You can use \
`biscuit install {biscuit} lib#github:isobiscuit/store` or you use `bfetcher lib#github:isobiscuit/store`

note: you can install official packages (`isobiscuit/store`) with:
`bfetcher {biscuit} myofficialpackage`

