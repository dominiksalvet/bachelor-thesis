# Design of the Processor Model

> **Abstract in English:** The goal of this work is to design a 64-bit processor model of a custom instruction set architecture and verify its operation. The instruction set respects RISC principles while putting effort into ~~decreasing~~ increasing final code density. For this purpose, it defines 16-bit instruction words only. The reference model, which implements this instruction set, is described in VHDL language using basic five-stage pipelining. It may be simulated using GHLD software and, with little effort, implemented into gate array of sufficient capacity. The correct behavior of the processor and its key modules is verified by test bench files.

> **Abstrakt v češtině:** Cílem této práce je navrhnout model 64bitového procesoru vlastní instrukční sady a doložit jeho funkčnost. Tato instrukční sada respektuje RISC principy při snaze zvýšit hustotu výsledného kódu. Za tímto účelem definuje výhradně instrukční slova s délkou 16 bitů. Referenční model implementující tuto instrukční sadu je popsán v jazyce VHDL pomocí základního pětistupňového pipeliningu. Lze ho simulovat pomocí programu GHDL a, s malým úsilím, implementovat do hradlového pole dostatečné kapacity. Správné chování procesoru a jeho stěžejních modulů je doloženo pomocí test bench souborů.

## Relevant Sources

* [**Publication home**](https://is.muni.cz/th/uqqoh/?lang=en)
* [Repository copy of thesis text (in Czech)](bachelor-thesis.pdf)
* [Processor source files](https://github.com/dominiksalvet/risc63)
* [Defense presentation (in Czech)](https://www.slideshare.net/DominikSalvet/nvrh-modelu-procesoru)

## License

This work is licensed under the [Apache License 2.0](license).
