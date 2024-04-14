Proiectul meu este bazat pe tema cabinetului medical, astfel am dezvoltat urmatoarele clase:

    Medic, clasa abstracta, din care este mostenit MedicGeneralist si MedicSpecialist
    Persoana, clasa abstracta, care reprezinta entitatea de baza a sistemului, din ea este mostenita clasa Medic si Client
    Programare, clasa abstracta, din care este mostenita ProgramareConsult si ProgramareUrgenta
    Pe langa acestea, mai am clase speciale pentru utilizarea sistemului, precum serviciul de programare, un singleton care sa -l instantieze si un meniu prin care putem interactiona cu aplicatia.

Sistemul mai dispune de urmatoarele 10 metode de servicii:
1. ServiciuProgramare.addClient()
2. ServiciuProgramare.addMedic()
3. ServiciuProgramare.getProgramariSortate()
4. Programare.calculeazaCost()
5. ServiciuProgramare.totalIncasari() + ServiciuProgramare.totalIncasariIntreDouaDate(Data, Data)
6. Client.addProgramare()
7. ServiciuProgramare.getProgramariCuUnAnumitMedic() + parametrizat
8. ServiciuProgramare.addProgramare()
9. ServiciuProgramare.getProgramariPersoana() + parametrizat
10. ServiciuProgramare.reminderProgramare(Persoana, Medic)
