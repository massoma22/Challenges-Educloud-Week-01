# Instruction du défi 

Au niveau de ce défi, il était question d'expliquer en ses propres mots: 
- Que sont les réseaux de neurones ? (Utilise des visuels si tu veux – mini-série vidéo optionnelle)
- Que signifie pré-entraîner un modèle vs le fine-tuner ? Donne des exemples comme GPT ou LLaMA.

## Réseaux de neurone 
Un réseau de neurone est un système en intelligence artificielle permettant d'apprendre à partir de données d'entrée. Il est inspiré des neurones du cerveau, c'est-à-dire que c'est un ensemble de noeuds interconnectés où les informations vont circuler. C'est exactement comme les signaux ou impulsions électriques circulent au niveau du cerveau, pour que nous puissions avoir une certaine réponse de l'être humain. De la même manière que la circulation des signaux dans le cerveau humain a pour source une impression externe ou interne ( le touché, une odeur, ou un goût) et pour sortie un certain comportement interne ou externe, de même à l'échelle d'une intelligence artificielle, nous avons des entrées et des sorties .

<img width="1145" height="821" alt="reseau de neurone" src="https://github.com/user-attachments/assets/09db9688-400c-4219-823f-9dcd13c52a72" />
Nous avons sur cette image, une description d'un réseau de neurones 

Imaginons un réseau qui apprend à reconnaître un chat dans une image. On lui montre plein d’images avec et sans chat. Petit à petit, il apprend les différences, comme les formes d'oreilles, les yeux ...etc et il finit par ajuster ses connexions internes pour devenir meilleur, un peu comme quelqu’un qui s’entraîne.


## Le pré-entrainement vs fine-tuning d'un modèle
Lorsqu'on crée un modèle, il passe par 2 grandes étapes: 

### Le pré-entrainement
Ici, le modèle parcourt une grande quantité de texte(article, livres, sites...etc) pour apprendre la langue de manière générale. Il prendra grâce à cela certains champs lexicaux de mot, des associations pour se familiariser au langage. A ce stade, le modèle ne sait pas encore répondre à un dialogue, ou encore resumer un texte. Il absorbe juste les informations. Le modèle issus du pré-entrainement est le modèle de base. On a par exemple GPT et LLaMA

### Le fine-tuning 
Cette étape consiste juste après le pré-entrainement, à la spécialisation du modèle sur une tâche précise comme traduire des textes, faire des resumés, ou encore identifier des bugs dans un code. Un exemple de modèle issus du fine-tuning est chatGPT du modèle de base GPT, conçu pour le chat.

<img width="1536" height="1024" alt="ccd6714f-6f65-4472-9d46-788a85b264c6" src="https://github.com/user-attachments/assets/e7ca6f32-e61d-4ef1-a11e-e13ebadf0035" />
