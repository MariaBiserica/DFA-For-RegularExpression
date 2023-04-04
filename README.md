# Construirea unui automat finit determinist pentru o expresie regulata
Sa se scrie o aplicatie care pentru o expresie regulata r construieste 
un automat finit determinist M = (Q, Σ, δ, q0, F), pentru care T(M) este chiar limbajul descris prin expresia r.

Se va defini o functie care preia ca parametru o expresie regulata r valida si returneaza un obiect de tip automat finit determinist. Automatul returnat trebuie sa recunoasca limbajul reprezentat de r. Vom defini si construi clase si functii auxiliare, care sunt necesare pentru rezolvarea cerintei.

In functia principala se citeste din fisier o expresie regulata. Se verifica daca este valida si numai in caz afirmativ se obtine AFD-ul corespunzator si avem posibilitatea verificarii unui cuvant in automat.
