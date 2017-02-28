# Liens

Markdown supporte deux styles de liens: inline et reference.

Dans les deux styles, le texte du lien est délimité par des [crochets].

Pour créer un lien inline, utlise des parenthèses juste après le texte du lien qui se trouve entre crochets. A l'intérieur des parenthèses, entre l'URL du lien, et accessoirement, ajoute un titre à ce lien, entouré par des guillemets. Exemples:
```markdown
[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)
```

Les liens de type reference ajoute une paire de crochets, à l'intérieur desquels tu choisiras un nom pour les identifier:
```markdown
This is [an example][id] reference-style link.
```

Il est possible de mettre un espace entre chaque paire de crochets pour mieux les démarquer :
```markdown
This is [an example] [id] reference-style link.
```

Tu peux éventuellement mettre un titre à ton lien à l'endroit qui te convient de la manière suivante:
```markdown
[id]: http://example.com/  "Optional Title Here"
```

**GitHub** et **GitBook** supportent les liens classiques en forme d'URL. Il suffit donc simplement d'entrer l'URL pour que le lien soit créé (au lieu d'utiliser les méthodes vues ci-dessus).


---

Un ptit quizz sur markdown:

Selectionne le lien valide:
- [x] `[a link](http://google.fr)`
- [ ] `(a link)[http://google.fr]`

> Les texte du lien est entouré par des [crochets].

Quelles sont les informations correctes à propos de ce lien : ```[a link](http://google.fr "google")```
- [ ] le lien est https://google.fr
- [x] le titre du lien est "google"
- [ ] le texte du lien est "google"
- [x] le texte du lien est "a link"

> Les liens peuvent avoir trois attributs: un text, une URL et un titre.

---

