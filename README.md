stringprep-hs
=============

This Haskell library implements the algorithm "StringPrep" from [RFC3454](https://tools.ietf.org/html/rfc3454).

It is [available on Hackage](https://hackage.haskell.org/package/stringprep) under the name "stringprep".

---

Simple usage looks something like:

```haskell
import Text.StringPrep (runStringPrep)
import Text.StringPrep.Profiles (namePrepProfile)

namePreppedText = runStringPrep namePrepProfile yourText
```
