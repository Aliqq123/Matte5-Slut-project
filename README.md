
Den exakta lösningen är `y(x) = x²·eˣ`.  
Simuleringarna körs på intervallet `x ∈ [1, 4]`.

## Metoder som jämförs

- **Euler framåt** – en enkel första ordningens metod
- **RK4** – en fjärde ordningens Runge-Kutta-metod, betydligt noggrannare

Steglängder som testas: `h = 1.0`, `0.5` och `0.1`.

## Resultat i korthet

- Vid `h = 1.0` avviker Euler kraftigt, medan RK4 nästan följer den exakta kurvan.
- Vid `h = 0.5` är RK4 praktiskt taget identisk med den exakta lösningen, medan Euler fortfarande ligger under.
- Vid `h = 0.1` är båda metoderna mycket nära den exakta lösningen, men RK4 är extremt exakt.

Slutsatsen är att RK4 ger mycket högre noggrannhet per steg och är effektivare för denna typ av problem.
