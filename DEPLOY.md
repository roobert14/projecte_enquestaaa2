El projecte està estructurat amb dues branques principals: main i dev. La branca main conté la versió estable i final del projecte, mentre que dev s’ha utilitzat per fer petites millores i canvis abans d’integrar-los.

El desenvolupament s’ha realitzat primer en local amb totes les funcionalitats de l’enquesta funcionant. Després s’ha pujat el projecte a GitHub i s’ha creat la branca dev per fer millores addicionals.

Un cop finalitzats els canvis en dev, s’ha creat una Pull Request cap a main per revisar i integrar les modificacions. Finalment, s’ha fet el merge de la PR.

El projecte s’ha desplegat a Vercel utilitzant la branca main, obtenint una URL pública funcional.

Actualment, les dades de l’aplicació es guarden en memòria local (arrays JavaScript). La persistència en base de dades amb Supabase es realitzarà a la fase IA5.