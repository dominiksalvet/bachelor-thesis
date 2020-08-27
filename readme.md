# Návrh modelu procesoru

Cílem této práce je navrhnout [model 64bitového procesoru](https://github.com/dominiksalvet/risc63) vlastní instrukční sady a doložit jeho funkčnost. Tato instrukční sada respektuje RISC principy při snaze zvýšit hustotu výsledného kódu. Za tímto účelem definuje výhradně instrukční slova s délkou 16 bitů. Referenční model implementující tuto instrukční sadu je popsán v [jazyce VHDL](https://github.com/dominiksalvet/uvod_do_vhdl) pomocí základního pětistupňového pipeliningu. Lze ho simulovat pomocí programu GHDL a, s malým úsilím, implementovat do hradlového pole dostatečné kapacity. Správné chování procesoru a jeho stěžejních modulů je doloženo pomocí test bench souborů.

Plný text práce je k dostání v souboru [bachelor-thesis.pdf](bachelor-thesis.pdf). Pro funkční odkazy je doporučeno soubor stáhnout a otevřít lokálně.

## Licence

Tato práce je licencována pod licencí [Apache License 2.0](license).
