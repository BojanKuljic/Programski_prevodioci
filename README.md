# Programski_prevodioci
Mini Projekat u C programskom jeziku koji je zahtevao  pisanje sintakse i semantike kao i samih skripti za uspesno izvrsavanje koda "Prevodioca"!

Bilo je potrebno napraviti
 Match Statement

Napisati pravila za sinktasku primerom:

match <id> number_area
{
    <const1> => num_exp
   [<const2> => num_exp]
   [.....]
   _ => break_me;
};

Realizovati sledeće semantičke provere:
    a) <id> mora biti postojeća promenljiva
    b) const izrazi mora ih imati makar jedan može i više njih
    c) <id> i konstantne moraju biti istog tipa
            - Ako je number area positive sve konstante moraju biti >= 0
            - Ako ke number area negative svr konstante moraju biti < 0
