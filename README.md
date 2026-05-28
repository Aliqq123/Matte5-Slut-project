# Arsalan
Differentialekvationen $y' = 4y+2x^2$

Den exakta lösningen är $y(x) = \frac{17}{16}e^{4x} - \frac{1}{2}x^2 - \frac{1}{4}x - \frac{1}{16}$

Villkor $y(0) = 1$

Simuleringarna körs på intervallet $x \in [0, 3]$.

## Metoder som jämförs
- **Euler framåt** – en enkel första ordningens metod
- **RK4** – en fjärde ordningens Runge-Kutta-metod, betydligt noggrannare

Steglängder som testas: $h = 1.0$, $0.5$ och $0.1$.

## Resultat i korthet
- Vid $h = 1.0$ avviker Euler kraftigt, medan RK4 nästan följer den exakta kurvan.
- Vid $h = 0.5$ är RK4 praktiskt taget identisk med den exakta lösningen, medan Euler fortfarande ligger under.
- Vid $h = 0.1$ är båda metoderna mycket nära den exakta lösningen, men RK4 är extremt exakt.

Slutsatsen är att RK4 ger mycket högre noggrannhet per steg och är effektivare för denna typ av problem.
