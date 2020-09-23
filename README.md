

# VIEWASTABLE

## MOTIVACE
-----
Tato utilita vytváří a optimalizuje DDL scripty, generované API službou na základě modelu (YAML format) včetně distribuce na jednotlivé prostředí.
 
## Jak to funguje
--------------
- varianta s uloženým heslem v souboru v command line 

>```
>../viewastable **[celá cesta k yaml]** **[cesta k prihlaseni v .py souboru]**
>```

>> Struktura .py file 
>> ```
>> username = ""
>> password = ""
>> ```
- varianta bez uloženého hesla - při spuštení utility dojde k požadavku na authorizaci
 
 >../viewastable **[celá cesta k yaml]** 
  
 - logovani - logování je směrováno do temp adresáře 
 
## Přihlašovací údaje
--------------

- pomocí osobního účtu - je nutno překontrolovat, aby tento účet měl přístup do Manty  
- pomocí technického účtu - lze vyzvednout v trezoru - [více](CYBERARC.md)

## Odkazy
--------------
- [CyberArc](https://cyberark.ds.kb.cz) - trezor technických účtů
- [Manta](https://manta.ds.kb.cz/MantaTD) - utilita pro optimalizaci skriptů