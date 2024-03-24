# Importanza del changelog

[indice](../../../README.md)

## Introduzione

Qualunque sia la visibilità del vostro progetto :
- personale
- ristretta (ad esempio al team con cui lavorate o all'azienda)
- pubblica (OSS)

E qualunque sia il tipo di progetto (software, documentazione ecc) è sicuramente utile tracciare i cambianti principali.

I modi per farlo sono molteplici, ma probabilmente le decisioni principali da prendere sono due : 
1. Scegliere il modello di versionamento
2. Scegliere la struttura del changelog

## Proposta

Una strada che trovo molto valida è quella di usare : 
- [Versionamento semantico](https://semver.org/)
- [Tenere un changelog](https://keepachangelog.com/)

Un esempio lo trovate in nel [CHANGELOG](../../../CHANGELOG.md) di questo progetto.

## Approfondimento

Tracciare i cambiamenti può essere noioso e complesso. 
Decidere quali modifiche siano sufficientemente significative e come classificarle non è sempre banale.

Ovviamente la tentazione di non mantere un changelog o di mantenerne uno automatico (chi non ha mai pensato almeno una volta di usare il git log al posto di un changelog vero e proprio?)

Per posso citare [Olivier Lacan](https://github.com/olivierlacan/keep-a-changelog), autore del progetto [Tenere un changelog](https://github.com/olivierlacan/keep-a-changelog) :

**"Non lasciare che i tuoi amici facciano copia incolla dei git logs nei changelog."**

### Perché tenere un changelog?

*"Per rendere facile agli utilizzatori e contribuenti vedere con precisione quali modifiche importanti sono state fatte tra ogni release (o versione) del progetto"*

### Chi ha bisogno di un changelog?

*"Le persone ne hanno bisogno. Che si tratti di consumatori o di sviluppatori, gli utenti finali sono persone interessate a ciò che avviene in esso. Se il software è cambiato, allora le persone vogliono sapere come e perché."*

