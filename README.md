# kights-n-knaves
Finds solutions to any knights-n-knaves puzzle using Haskell.

A knight always tells the truth and a knave always lies.

## Usage
Assuming you have Haskell's `stack` and `ghc` installed, you can clone this repository and run `stack build` and then `stack exec knights-n-knaves-exe`. Here is an example session:

```
/path/to/repo $ stack exec knights-n-knaves-exe
Gwen says (Art is a knight) iff (Lance is a knight)
Art says Gwen is a knave
solve

Solution 1:
  Knights: Gwen
  Knaves: Art, Lance
Solution 2:
  Knights: Art
  Knaves: Gwen, Lance
quit
/path/to/repo $
```

Currently, the logical connectives `not`, `and`, `or`, `if`, and `iff` are supported.