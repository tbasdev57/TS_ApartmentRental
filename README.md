<a name="readme-top"></a>

# Kasa

#### Location d’appartements entre particuliers en France.

#### Formation OpenClassrooms - Développeur d'applications JavaScript React
#### Projet 11
****
Ce projet, visible sur la branche [Optimized](https://github.com/MichelD-dev/Kasa/tree/Optimized), a d'abord été créé en tirant parti des dernières nouveautés apparues avec React Router v6.4:
- <font color="lightblue">*Loader*</font> incorporé aux routes
- <font color="lightblue">*ErrorElement*</font> pour les pages d'erreur
- <font color="lightblue">*Defer*</font> pour retourner une promesse depuis le *loader*
- Les composants <font color="lightblue">*Await*</font> permettant de résoudre cette promesse avant d'en envoyer le resultat à un composant via un <font color="lightblue">*render prop*</font>
- <font color="lightblue">*useAsyncValue*</font> retourne également la valeur issue de la promesse venant du *loader* et permet de l'utiliser dans le composant enfant d'un *Await*
- <font color="lightblue">*Suspense*</font>, fourni par React 18, permet d'utiliser les fonctions précédentes

Il utilise également certains patterns comme les <font color="lightblue">*composants composés*</font> pour les accordéons, associés à un <font color="lightblue">*Contexte*</font>, et **fait** usage du code-splitting via <font color="lightblue">*React.Lazy*</font> et <font color="lightblue">*Webpack Prefetch*</font>.

Vous trouverez sur la branche par défaut [main](https://github.com/MichelD-dev/Kasa) une version de base n'utilisant pas ou peu ces optimisations, à part les <font color="lightblue">*composants composés*</font> et le <font color="lightblue">*Contexte*</font>.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Prerequisites

In order to make the application works on your engine you must have NodeJS and
npm installed.

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Installation
****
1. Clone this repository (or download a zip file):
   `git clone https://github.com/MichelD-dev/Kasa`

2. Go to the projet root folder `cd kasa`

3. Install the dependencies: `yarn install` or `npm install`

4. (Optional) Configure the application inside the `.env.local` file

5. Launch the application: `yarn start` or `npm run start`

<p align="right">(<a href="#readme-top">back to top</a>)</p>

## Contact:
Michel DELAUNAY - delaunaymichel@hotmail.fr  

Project Link: https://kasa-lodgings.netlify.app/

<p align="right">(<a href="#readme-top">back to top</a>)</p>#   T S _ A p a r t m e n t R e n t a l 
 
 # #   T S _ A p a r t m e n t R e n t a l 
 
 ! [ B u i l d   S t a t u s ] ( h t t p s : / / i m g . s h i e l d s . i o / b a d g e / b u i l d - p a s s i n g - b r i g h t g r e e n ) 
 
 T h i s   p r o j e c t   i s   a   T y p e S c r i p t - b a s e d   a p a r t m e n t   r e n t a l   a p p l i c a t i o n . 
 
 # #   F e a t u r e s 
 
 -   F e a t u r e   1 :   U s e r   a u t h e n t i c a t i o n   a n d   a u t h o r i z a t i o n 
 
 -   F e a t u r e   2 :   A p a r t m e n t   l i s t i n g   a n d   b o o k i n g 
 
 -   F e a t u r e   3 :   P a y m e n t   p r o c e s s i n g 
 
 # #   I n s t a l l a t i o n 
 
 T o   i n s t a l l   t h e   p r o j e c t ,   f o l l o w   t h e s e   s t e p s : 
 
 1 .   C l o n e   t h e   r e p o s i t o r y :   \ g i t   c l o n e   h t t p s : / / g i t h u b . c o m / t b a s d e v 5 7 / T S _ A p a r t m e n t R e n t a l . g i t \ "   > >   R E A D M E . m d 
 e c h o   
 
 2 . 
 
 N a v i g a t e 
 
 t o 
 
 t h e 
 
 p r o j e c t 
 
 d i r e c t o r y : 
 
 \ c d 
 
 T S _ A p a r t m e n t R e n t a l \ " 
 
 3 .   I n s t a l l   d e p e n d e n c i e s :   \ 
 p m   i n s t a l l \ "   > >   R E A D M E . m d 
 e c h o   
 
 4 . 
 
 S t a r t 
 
 t h e 
 
 d e v e l o p m e n t 
 
 s e r v e r : 
 
 \ 
 p m 
 
 r u n 
 
 d e v \ " 
 
 
