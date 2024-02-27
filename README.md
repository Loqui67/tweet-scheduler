Je lance une bouteille à la mer, mais je cherche un programme open-source (ou gratuit), une application web, ou quelque chose (toujours gratuit), qui permettrait de programmer (à la limite, je peux schedule de mon côté via un serveur et des tâches CRON) des Tweets ainsi que des Threads Twitter (avec des images ou/et vidéo).

J'ai beau cherché, j'ai trouvé des fragments de vieux codes sur github ou autre, mais rien de concluant. J'ai cherché des heures sur google pour trouver un service web permettant ça, mais les offres gratuites proposent au maximum 1 ou 2 programmation simultanée. Or, j'aimerais un truc un peu plus conséquent.
Sinon, savez-vous où je pourrais trouver une réponse potentielle à ma demande ?
Dans le pire des cas, je pourrais programmer cet outil, mais j'ai pas forcément le temps de le faire, donc je dis pas non à une base solide trainant quelque part ^^

Pas spécialement. Même si j'apprécierais une interface graphique (ou web) pour enregistrer mes tweets avec le/les médias associés (avec en prime, possibilité de mettre des "alt" sur ces médias) ainsi que la date et heure de publication. Puis derrière, que ça les sauvegardes en json ou autre pour les publier via finalement quelques lignes de code.
Ha, et le plus important, c'est la possibilité de créer des threads (avec si possible un compteur de caractère sous chaque "tweet" pour éviter de dépasser et de renvoyer une erreur ^^)

Une interface graphique ou web (je préférerais que ça soit du web pour facilité l'accès si l'app est "sur un serveur") :
Champ texte
"upload" d'images associé au tweet (sous forme de lien ou de fichier (ou juste de fichier), avec possibilité de mettre un "alt" sur chacune des images)
compteur de nombre de caractère sous ce champ texte (ou limitation du nombre pour pas que ça dépasse celui de Twitter)
possibilité d'ajouter d'autres champs texte (et upload d'image (4 maximum par tweet)) afin de créer un Thread
Date Picker ou un truc qui y ressemble pour programmer quand le tweet sera envoyé

Enregistrement de ça sous le format que tu veux (JSON de pref et les images (si ce n'est pas un lien) dans un dossier, car la base de donnée, ça peut être "lourd" pour rien).
Attention, si les images sont sous forme de lien, il faut qu'au final, le tweet ai des images et pas des liens.

Possibilité de voir les Tweets / Threads déjà créé par le passé et de les modifier

Automatisation derrière pour envoyer tout ce beau monde directement sur Twitter.

This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
