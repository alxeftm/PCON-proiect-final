# (Titlul)
Reactive Visuals – Visualizator 3D reactiv la sunet

Un program dezvoltat in Max care genereaza forme 3D reactive in functie de un fisier audio incarcat. Foloseste o combinatie de analiza audio pe benzi, matrice video si rendering 3D care raspund in timp real la benzile de frecvente.

## (Instalare)
1. Necesita Max 8.6 sau versiune mai noua.
2. Descarca si instaleaza Max.
3. Deschide fisierul direct in Max.
4. Verifica daca ai activitate pe placa de sunet.

## (Utilizare)
1. Incarca un fisier in obiectul sfplay~.
2. Apasa START pentru a porni redarea.
3. Visuals vor raspunde la spectrul audio.
4. Camera video este optionala si poate influenta dinamica punctelor (IN CURS DE IMPLEMENTARE).
5. Sliderele controleaza diversi parametri de efecte.

## (Istoric)
(19.05) Prima versiune. Citire matrice din camera si crearea unor elemente din patch.

(30.05 - 01.06) A doua versiune. Moduri si vizualizare avansata si reactiva in functie de fisierul audio si parametrii/activitatea pe benzi de frecventa.

(14.06 - 16.06) A treia versiune. Testare finala a ultimelor optimizari, ajustari vizuale.

## (Link-uri)
https://www.youtube.com/watch?v=pxDtFFIbBDI
- elemente de generare vizuala

https://docs.cycling74.com/legacy/max8/refpages/jit.gl.isosurf

# Dezvoltarea proiectului

Pentru început:

1. Creează-ți cont pe Github
2. Download și install [Github Desktop](https://desktop.github.com/)
3. Citește [acest ghid](https://charlesmartin.com.au/blog/2020/08/09/student-project-repository) și ține la îndemână [Markdown Cheat Sheet](https://www.markdownguide.org/cheat-sheet).

Apoi, procesul este următorul (inspirat de [aici](https://cs.anu.edu.au/courses/comp1720/deliverables/05-major-project/#submission-process)):

1. *fork* al acestui template către propriul tău cont de Github

![](assets/fork.gif)

_(dacă preferi cumva ca repo-ul să nu fie vizibil de către public, îl poți seta ca Private din Settings - "Change visibility". Atunci trebuie să mă adaugi drept colaborator, ca eu să am acces.)_

2. *clone* al repo-ului din Github Desktop pentru a-l downloada local

![](assets/clone.gif)

3. *commit* și *push* pe măsură ce lucrezi la proiect. Ultima versiune push-ată pe server înainte de deadline va conta pentru evaluare.

![](assets/commit.gif)

## Elemente obligatorii

1. Acest readme completat. Titlu, descriere, mod de utilizare, istoric, link-uri utile.

   Poți include și imagini și chiar [gif-uri animate](https://www.screentogif.com/), sau link-uri către materiale audio/video.
   
   Vezi [aici](https://charlesmartin.com.au/blog/2020/08/09/student-project-repository) mai multe sugestii.

2. [Declarația de originalitate](statement-of-originality.yml) completată. Tot ce nu este inclus acolo va fi considerat 100% contribuție proprie.

    *(formatul este adaptat de [aici](https://gitlab.cecs.anu.edu.au/comp1720/2018/comp1720-2018-major-project/-/blob/master/statement-of-originality.yml). Da, este un pic ironic să refolosim un doc [de altundeva](https://cs.anu.edu.au/courses/comp1720/resources/faq/#how-do-i-fill-out-my-statement-of-originality), dar menționăm sursa deci nu este plagiat!)*

3. Proiectul în sine. Tot codul trebuie să fie prezent, proiectul trebuie să poată rula conform instrucțiunilor din readme. Dacă e nevoie de asset-uri mari (sunete, video etc), [folosește Git LFS](https://git-lfs.github.com/) sau include link de download în instrucțiunile de instalare.

