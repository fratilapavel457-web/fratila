# fratila
Pentru rezolvarea celor 4 challenge-uri am folosit un mediu Linux si am incercat sa urmaresc pas cu pas ce face fiecare program. La inceput am verificat fisierele si am cautat informatii care sa ma ajute sa inteleg programul. Am folosit si cautarea de string-uri si analiza fluxului de executie.

La primul challenge am inceput prin verificarea fisierului si a continutului acestuia. Am cautat string-urile care puteau avea legatura cu flag-ul, dar mesajul nu era afisat direct. Am urmarit mai atent conditiile din program si am vazut unde se ajunge la rezultatul corect. De acolo am reusit sa identific mesajul secret.

Flag-ul obtinut a fost:

`CTF{f1r57_573p_70_50lv1n6_7h3_23rrd_bu6}`


La al doilea challenge am urmarit modul in care programul construia rezultatul. A fost nevoie sa ma uit la mai multe parti ale programului deoarece flag-ul nu era pus direct intr-un singur loc. Am urmarit valorile folosite si modul in care acestea erau prelucrate pana la verificarea finala. Dupa ce am inteles ce face partea respectiva am putut sa gasesc flag-ul.

Flag:

`CCDL{th3_f4ctory_mu57_gr0w}`


La al treilea challenge am urmarit mai multe etape ale executiei. Programul poate fi privit ca un fel de pipeline, unde rezultatul unei etape este folosit mai departe. Am incercat sa urmaresc datele de la inceput pana la rezultatul final si sa vad cum se modifica pe parcurs. Dupa ce am inteles ordinea operatiilor am ajuns la mesajul cautat.

Flag-ul este:

`CTF{m1cr0s3rv1c3_p1p3l1n3_3x3cu710n_succ3ssfu1_2026}`


Ultimul challenge mi s-a parut ceva mai complicat deoarece erau mai multe ramificatii in program. Am urmarit conditiile si am incercat sa vad care dintre ele duc mai departe si care nu duc la rezultatul dorit. Practic am urmarit programul ca pe un labirint si am cautat traseul corect. Dupa ce am gasit ramura buna am ajuns la verificarea finala si am obtinut flag-ul.

Flag:

`jvaCTF{l4byr1n7h_m4573r_2026}`


In concluzie, la aceste probleme am invatat ca nu este suficient sa cauti direct flag-ul. Trebuie mai intai sa intelegi ce face programul si sa urmaresti modul in care sunt prelucrate datele. Unele probleme au fost mai simple, iar la altele a trebuit sa urmaresc mai atent executia si conditiile din program.
