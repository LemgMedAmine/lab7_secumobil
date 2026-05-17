# lab7_secumobil


Lancement de MobSF :
MobSF est lancé avec Docker et connecté à l’émulateur Android. Les logs confirment que l’environnement est prêt pour l’analyse dynamique.

<img width="841" height="279" alt="Capture d&#39;écran 2026-05-17 223050" src="https://github.com/user-attachments/assets/9b60887c-2054-4b0e-87ac-f137c19ee0d8" />

Interface Dynamic Analyzer :
Interface principale de l’analyse dynamique MobSF avec l’émulateur, les options Frida, Logcat, proxy, capture d’écran et génération de rapport.

<img width="1844" height="897" alt="Capture d&#39;écran 2026-05-17 223109" src="https://github.com/user-attachments/assets/a84eff65-0d0d-4e1d-973f-76863c338f84" />


Application DIVA lancée :
L’application DIVA est ouverte dans MobSF. Les modules de vulnérabilités sont disponibles et l’instrumentation Frida est active.

<img width="606" height="396" alt="Capture d&#39;écran 2026-05-17 223129" src="https://github.com/user-attachments/assets/6338953f-2dc2-4e34-89cc-df1bffa78a8a" />

Test Insecure Logging :
Test de journalisation non sécurisée. Une valeur sensible est saisie pour vérifier si elle apparaît dans les logs Android.

<img width="375" height="476" alt="Capture d&#39;écran 2026-05-17 223140" src="https://github.com/user-attachments/assets/c7af1bc5-606c-4bcd-a58f-27d8dfdd1559" />

Résultat Logcat :
Logcat affiche la donnée saisie, ce qui confirme une fuite d’information sensible dans les logs.
<img width="783" height="61" alt="Capture d&#39;écran 2026-05-17 223154" src="https://github.com/user-attachments/assets/e0107945-8dff-42c2-9755-2db06cdcb38c" />

Test Hardcoding Issues :
Le test montre l’utilisation d’une clé codée en dur. Le message Access granted confirme que la clé entrée est acceptée.
<img width="415" height="781" alt="Capture d&#39;écran 2026-05-17 223204" src="https://github.com/user-attachments/assets/4f14ea77-a5c2-485c-bc47-ad15c7dc7122" />


