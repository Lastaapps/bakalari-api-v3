# Bakaláři API verze 3

Analýza třetí verze API školního systému Bakaláři.

Toto rozhraní (tedy API) primárně slouží ke komunikaci mezi mobilní aplikací *Bakaláři OnLine* a servery jednotlivých škol.

## URL

Všechny adresy [v seznamu endpointů](endpoints.md) začínají lomítkem. Část před lomítkem se pro každou školu liší, odpovídá umístění webové aplikace Bakaláři.

**Příklad:** Pokud je přihlášení do Bakalářů na adrese `https://www.example.com:444/login`, pak bude „část před lomítkem“ odpovídat `https://www.example.com:444`. Adresa modulu marks tedy bude `https://www.example.com:444/api/3/marks`.

## Kam dál?

* [**Přihlášení (login)**](login.md)
* [**Endpointy**](endpoints.md)
* [Seznam škol](schools_list.md)
* [Bakaláři API v1](https://github.com/bakalari-api/bakalari-api)
* [GitHub organizace Bakaláři API](https://github.com/bakalari-api)
