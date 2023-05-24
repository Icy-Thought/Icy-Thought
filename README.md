<p align="center">
<img src="./assets/banner.png" />
</p>

```haskell
-- Personal contact details
contactMe :: (String, String, String)
contactMe _ = (discord, telegram, mail)
  where
    discord  = "-(𝕂eloτ)-#9288"
    telegram = "t.me/MonadicDrag"
    mail     = "icy-thought@proton.me"

-- My life experiences
lifeXP :: ([String], [String], Int)
lifeXP _ = (nativeLang, nationalities, age)
  where
    nativeLang    = ["عربي", "English", "Svenska", "中文"]
    nationalities = ["Iraqi", "Swede"]
    age           = 25

-- Set of skills which I have attained during my stay on this planet
skillSet :: ([(String, [String])], [String], [String])
skillSet _ = (progLang, interests, editors)
  where
    editors = ["Emacs", "Neovim"]
    interests = ["Mathematics", "Science", "Programming (esp. FP)"]
    progLang =
      [ ("Advanced", [""])
      , ("Intermediate", ["Nix", "Lua","Python"])
      , ("Beginner", ["C", "Emacs-Lisp", "Haskell", "Rust"])
      ]
```
