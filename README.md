# SecureCode AI demo app

A deliberately vulnerable file used to demonstrate
[SecureCode AI](https://github.com/shorinversion/securecode-ai): `app.py` builds an SQL query
by string concatenation (CWE-89, OWASP A03:2021 Injection).

Pull requests in this repository are opened by the SecureCode AI Architect: it proposes a
parameterized query, validates the patch in an ephemeral copy and opens the PR with
`demo/p917_real_local_demo.py --open-pr`.

Do not use this code anywhere.

---

Намеренно уязвимый файл для демонстрации SecureCode AI: SQL-запрос собирается конкатенацией
строк (CWE-89). Pull request с исправлением открывает агент Архитектор.
