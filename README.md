# První projekt z předmětu IOS (operační systémy) VUT FIT, Brno - Synchronizace

## Hodnocení

```
15:celkem bodu za projekt
#-- automaticke hodnoceni -----------------------------
= make
:ok:make
= prepare tests: resources
:kontrola syntaxe vystupu => check_syntax.out
Alarm clock
#:0:xklyme00: chyba pri spusteni, mozne priciny:
#:chybny soubor, timeout 5s nebo limit velikosti souboru
= base_* : zakladni testy
Alarm clock
#:0:xklyme00: chyba pri spusteni, mozne priciny:
#:chybny soubor, timeout 5s nebo limit velikosti souboru
0:test_a_base_counter: zablokovani nebo segmentation fault
1:ok:test_b_base_Z: posloupnost Z ok
1:ok:test_c_base_U: posloupnost U ok
1:ok:test_d_base_services: poradi/typ/pocet sluzeb ok
1:ok:test_e_base_closing: poradi closing a entering office
1:ok:test_f_base_ZUservices: kombinovany test Z + U + obsluha sluzeb ok
:ok:test_g_counter: navratovy kod je 0
1:ok:test_g_counter
1:ok:test_i_Z: posloupnost Z
1:ok:test_j_U: posloupnost U
1:ok:test_k_services: poradi/typ/pocet sluzeb
1:ok:test_l_closing: poradi closing a entering office
2:ok:test_m_ZUservices: kombinovany test Z + U + poradi a cisla sluzeb
2:ok:test_n_sync_sleep: synchronizace poradi, typu a poctu obslouzenych sluzeb + prace urednika (castejsi prepinani procesu)
2:ok:test_o_sync_nosleep: synchronizace poradi, typu a poctu obslouzenych sluzeb + prace urednika (zruseno cekani pomoci usleep apod.)
= test spravneho ukonceni pri chybe
1:ok:test_q_error_1: osetreni chybneho vstupu
= resources
: pocet procesu ok (14, mel by byt 14)
: pocet volani wait (waitpid) ok
grep: type: No such file or directory
#------------------------------------------------------
17:celkove score (max pro hodnoceni 15)
15:celkem bodu za projekt
```

## Zadání
Naleznete v souboru [zadani-2023.pdf](https://github.com/TheKlima/ios-project2-2023-vut-fit/blob/main/zadani-2023.pdf)
