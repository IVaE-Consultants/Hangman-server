# Hangman-Server

## Installation

### Windows

Download haskell-stack from homepage
```
stack setup
stack install
```

### Mac OS X
```
brew install ghc
brew install haskell-stack
```

## Running
```
stack exec hangman-server-exe
```

## Testing
```
stack test
```

## Adding new packages

Search hackage.haskell.org for package and look at top left corner for package name (and version).

Edit hangman-server.cabal with your favourite editor and add the package name to
the `build-depends:` field of the library section. Then run `stack build`


