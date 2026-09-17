<div align="center">
  <img width="702" height="396" alt="header_github" src="https://github.com/user-attachments/assets/3d5b1193-11ec-47ec-adee-17d08c4a1bc3" />
</div>

![](https://komarev.com/ghpvc/?username=DeepLeau)

<h2>De l'électron à l'idée</h2>
<sub><i>ou : pourquoi je n'ai jamais vraiment arrêté de démonter des trucs</i></sub>

<br>

Ce qui me fascine dans l'informatique, ce n'est pas vraiment le code, c'est l'empilement.

Un transistor qui ouvre ou ferme le passage d'un courant. Assemblés, ils deviennent des portes logiques : ET, OU, NON, la logique de Boole prenant forme dans le silicium. Empilées, elles deviennent un processeur, capable de compter, comparer, décider. Au-dessus, un compilateur traduit une intention humaine en instructions binaires. Encore au-dessus, un langage me permet d'écrire `if user.is_authenticated` sans jamais penser à la tension aux bornes d'un transistor.

Chaque couche cache la précédente et l'assume à la fois. Mais un compilateur reste déterministe, documenté, avec un contrat stable : je peux toujours redescendre vérifier ce qu'il produit. C'est le même geste que démonter un appareil pour voir ce qu'il y a dedans, sauf qu'ici rien ne casse quand on ouvre. Comprendre le système jusqu'en bas, puis choisir consciemment à quel étage construire : voilà ce qui m'anime depuis toujours.

L'IA change la donne. C'est un accélérateur de connaissances fantastique, elle compresse des années d'apprentissage en quelques requêtes bien posées. Mais un modèle de langage est une couche probabiliste, sans interface stable ni garantie de reproductibilité. Ce qu'il produit reste vérifiable, bien sûr : du code, ça se lit, ça se teste, ça s'exécute. Le piège est ailleurs. Cette vérification demande exactement le jugement que l'usage confortable de l'outil dispense d'acquérir. Plus on délègue, moins on construit de quoi relire ce qu'on délègue. Le problème n'est donc pas l'abstraction en soi, c'est l'abstraction sans contrat, adossée à une compétence qui s'atrophie.

Commoditiser l'intelligence ne fera pas disparaître les ingénieurs pour autant. L'électricité aussi est devenue une commodité : il y a aujourd'hui des millions d'électriciens, et une poignée de gens qui conçoivent les réseaux, les transformateurs et les normes qui rendent leur métier possible. Les deux sont utiles, ils ne sont simplement pas le même métier. Moi, c'est le second qui m'intéresse : celui où il faut encore savoir pourquoi ça marche, et pas seulement que ça marche. On voit déjà ce que coûte l'inverse : des géants d'argile qui, à chaque amélioration des modèles, s'effritent un peu plus. Pas de couche à eux, juste un raccourci vers celle de quelqu'un d'autre.

Je pourrais avoir tort. Si ces modèles finissent par offrir des contrats aussi stables et vérifiables qu'un compilateur, la distinction s'effondre, et il ne restera qu'une couche de plus à apprivoiser comme toutes les autres.

## Ce que je construis avec ça

**Kurtel**, une mémoire darwinienne pour les agents de code IA (Claude Code, Codex).

Darwinienne au sens strict : l'agent produit des tentatives qui divergent, ce qui se confirme utile survit et se transmet, le reste meurt. Kurtel oublie exprès. C'est la sélection qui compte, pas l'accumulation.

L'agent que je vise n'a pas de disque : sa fenêtre de contexte se comporte comme une RAM effacée à chaque redémarrage. Lui donner une mémoire sélective, c'est lui offrir un disque qui trie plutôt qu'un disque qui empile.

Et puisque je passe le texte ci-dessus à me méfier des couches opaques : la mémoire est lisible, et on peut toujours redescendre voir pourquoi un souvenir a survécu et un autre non.

## Envie de creuser ensemble

Outils backend open-source, infrastructure pour agents IA, ou toute conversation sur pourquoi les choses marchent comme elles marchent.

Contact

<a href="mailto:thomas.bodenan@gmail.com"><img src="https://img.shields.io/badge/Gmail-D14836?style=flat-square&logo=gmail&logoColor=white"></a> <a href="https://www.linkedin.com/in/thomas-bodénan"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=flat-square&logo=linkedin&logoColor=white"></a> <a href="https://portfolio-thomas-iota.vercel.app/"><img src="https://img.shields.io/badge/Portfolio-000000?style=flat-square&logo=vercel&logoColor=white"></a>
