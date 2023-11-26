Top 10 OWASP pour LLM
Version 1.0 
Date de publication : 1 août 2023


La frénésie d’intérêt des grands modèles linguistiques (LLM) suite aux chatbots pré-entraînés du marché de masse à la fin de 2022 a été remarquable. Les entreprises, désireuses d’exploiter le potentiel des LLM, les intègrent rapidement dans leurs opérations et leurs relations avecles clients. Pourtant, la vitesse vertigineuse à laquelle les LLM sont adoptés a dépassé l’établissement de protocoles de sécurité complets, laissant de nombreuses applications vulnérables aux problèmes à haut risque.

L’absence d’une ressource unifiée traitant de cesconcerns de sécurité dans les LLM était évidente. Les développeurs, peu familiers avec les risques spécifiques associés aux LLM, se sont retrouvés des ressources dispersées et la mission de l’OWASP semblait parfaitement adaptée pour aider à une adoption plus sûre de cette technologie.
À qui s’adresse-t-il?
Notre public principal est composé dedéveloppeurs, de scientifiques des données et d’experts en sécurité chargés de concevoir et de construire des applications et des plug-ins exploitant les technologies LLM. Notre objectif est de fournir des conseils de sécurité pratiques, pratiques et concis pour aider ces professionnels à naviguer sur le terrain complexe et évolutif de la sécurité LLM.

L’élaboration de la liste
La création de la liste OWASP Top 10 for LLM a été une entreprise majeure, construite sur l’expertise collective d’une équipe internationale de près de 500 experts, avec plus de 125 contributeurs actifs. Nos contributeurs viennent d’horizons divers, y compris des sociétés d’IA, des sociétés de sécurité, des éditeurs de logiciels indépendants, des hyperscalers cloud, des fournisseurs de matériel et des universités.

Au cours d’un mois, nous avons réfléchi et proposé des vulnérabilités potentielles, les membres de l’équipe ayant écrit43 menaces distinctes. Au cours de multiples tours de scrutin, nous avons affiné ces propositions pour en faire une liste concise des dix vulnérabilités les plus critiques. Chaque vulnérabilité a ensuite été examinée et affinée par des sous-équipes dédiées et soumise àun examen public, garantissant ainsi la liste finale la plus complète et la plus exploitable.

Chacune de ces vulnérabilités, ainsi que des exemples communs, des conseils de prévention, des scénarios d’attaque et des références, ont été examinés et affinés par des sous-équipes dédiées et soumis àun examen public, garantissant ainsi la liste finale la plus complète et la plus exploitable.

Relatif à d’autres listes des 10 meilleurs de l’OWASP

Bien que notre liste partage l’ADN avec les types de vulnérabilités trouvés dans d’autres listes OWASP Top 10, nous ne réitérons pas simplement ces vulnérabilités. Instead, nous approfondissons les implications uniques de ces vulnérabilités lorsqu’elles sont rencontrées dans des applications utilisant des LLM.

Notre objectif est de combler le fossé entre les principes généraux de sécurité des applications et les défis spécifiques posés par les LLM. Cela comprend l’exploration de la façon dont les vulnérabilités conventionnelles peuvent poser différents risques ou être exploitées de manière novatrice au sein des LLM, ainsi que la manière dont les stratégies de correction traditionnelles doivent être adaptées aux applications utilisant des LLM.

L’avenir

Cette première version dela liste ne sera pas la dernière. Nous prévoyons de le mettre à jour périodiquement pour suivre le rythme de l’état de l’industrie. Nous travaillerons avec l’ensemble de la communauté pour promouvoir l’état de l’art et créer plus de matériel éducatif pour une gamme d’utilisations. Nouscherchons également à collaborer avec les organismes de normalisation et les gouvernements sur les questions de sécurité de l’IA. Nous vous invitons à rejoindre notre groupe et à contribuer.

Steve Wilson
Chef de projet, OWASP Top 10 pour les applications d’IA LLM
Twitter/X : @virtualsteve



Top 10 OWASP pour LLM

LLM01 : Injection rapide
Cela manipule un grand modèle de langage (LLM) par le biais d’entrées astucieuses, provoquant des actions involontaires de la part du LLM. Les injections directes écrasent les invites du système, tandis que les injections indirectes manipulent les entrées provenant de sources externes.

LLM02 : Gestion de sortie non sécurisée
Cette vulnérabilité se produit lorsqu’une sortie LLM est acceptée sans examen, exposant ainsi les systèmes backend. Une mauvaise utilisation peut entraîner de graves conséquences telles que XSS, CSRF, SSRF, l’escalade des privilèges ou l’exécution de code à distance.

LLM03: Empoisonnement des données
Cela se produit lorsque les données de formation LLM sont falsifiées, introduisant des vulnérabilités ou des biais qui compromettent la sécurité, l’efficacité ou le comportement éthique. Les sources incluent Common Crawl, WebText, OpenWebText et des livres.

LLM04 : Modèle de dénie service
Les attaquants provoquent des opérations gourmandes en ressources sur les LLM, entraînant une dégradation du service ou des coûts élevés. La vulnérabilité est amplifiée en raison de la nature gourmande en ressources des LLM et de l’imprévisibilité des entrées utilisateur.

LLM05 : Vulnérabilités de la chaîne d’approvisionnement
Le cycle de vie des applications LL M peut être compromis par des composants ou des services vulnérables, ce qui entraîne des attaques de sécurité. L’utilisation de jeux de données tiers, de modèles pré-entraînés et de plug-ins peut ajouter des vulnérabilités.

LLM06 : Divulgation d’informations sensibles
LLM peut révéler par inadvertance des donnéesconfidentielles dans ses réponses, ce qui entraîne un accès non autorisé aux données, des violations de la vie privée et des atteintes à la sécurité. Il est crucial de mettre en œuvre un nettoyage des données et des politiques utilisateur strictes pour atténuer ce problème.

LLM07: Conception de plug-in non sécurisé
Les plugins LLM peuvent avoir des entrées non sécurisées et un contrôle d’accès insuffisant. Ce manque de contrôle des applications les rend plus faciles à exploiter et peut entraîner des conséquences telles que l’exécution de code à distance.

LLM08: Agentivité excessive
Les systèmes basés sur LLM peuvent entreprendre des actions entraînant des conséquences imprévues. Le problème découle de l’excès de fonctionnalités, d’autorisations ou d’autonomie accordées aux systèmes basés sur LLM.

LLM09: Dépendance excessive
Les systèmes ou les personnes trop dépendants des LLM sans visionpeuvent être confrontés à des informations erronées, à des problèmes de communication, à des problèmes juridiques et à des failles de sécurité en raison d’un contenu incorrect ou inapproprié généré par des LLM.

LLM10: Vol de modèle
Cela implique l’accès, la copie ou l’exfiltration non autorisés de LLM models propriétaires. L’impact comprend des pertes économiques, un avantage concurrentiel compromis et un accès potentiel à des informations sensibles.
