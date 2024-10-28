<p align="center">
<img src="./assets/banner.png" />
</p>

```haskell
-- Personal contact details
contactMe :: (String, String, String)
contactMe _ = (discord, telegram, mail)
  where
    discord  = "NaN"
    telegram = "NaN"
    mail     = "icy-thought@proton.me"

-- My life experiences
lifeXP :: ([String], [String], Int)
lifeXP _ = (nativeLang, nationalities, age)
  where
    nativeLang  = ["عربي", "English", "Svenska"]
    nationality = ["Swedish"]
    age         = 25

-- Set of skills which I have attained during my stay on this planet
skillSet :: ([(String, [String])], [String], [String])
skillSet _ = (progLang, interests, editors)
  where
    editors = ["Emacs", "Neovim"]
    interests = ["Mathematics", "Science", "CompSci"]
    progLang =
      [ ("Advanced", [""])
      , ("Intermediate", ["Nix", "Lua", "Python", "Rust"])
      , ("Beginner", ["C", "Emacs-Lisp", "Haskell"])
      ]
```
