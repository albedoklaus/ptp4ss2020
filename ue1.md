# PTP4 Übungsblatt 1

## Aufgabe 1.1

\begin{align}
E &= \frac{\int_{0}^{2\pi}\int_{0}^{\pi/4}\int_{0}^{c\Delta t} u r^2 \text{d}r \sin\Theta \text{d}\Theta \text{d}\Phi \frac{\text{d}A \cos\Theta}{4\pi r^2}}{\text{d}A\cdot\Delta t}
\\
E &= \frac{u}{\Delta t4\pi}\int_{0}^{2\pi}\int_{0}^{\pi/4}\int_{0}^{c\Delta t} \text{d}r \sin\Theta \text{d}\Theta \text{d}\Phi \cos\Theta
\\
E &= \frac{u}{\Delta t4\pi}\int_{0}^{2\pi}\int_{0}^{\pi/4} [r]_{0}^{c\Delta t} \sin\Theta \text{d}\Theta \text{d}\Phi \cos\Theta
\\
E &= \frac{cu}{4\pi}\int_{0}^{2\pi}\int_{0}^{\pi/4} \sin\Theta \text{d}\Theta \text{d}\Phi \cos\Theta
\\
E &= \frac{cu}{4\pi}\int_{0}^{2\pi} [-cos^2\Theta]_{0}^{\pi/4} \text{d}\Phi
\\
E &= \frac{cu}{8\pi}\int_{0}^{2\pi} \text{d}\Phi
\\
E &= \frac{cu}{8\pi} [\Phi]_{0}^{2\pi}
\\
E &= \frac{cu}{4}
\\
\frac{4E}{c} &= u
\end{align}

## Aufgabe 1.3

### Frei verfügbare Energie

Integration des Gesetzes von Rayleigh und Jeans über die Frequenz zur Bestimmung der Gesamtenergie mit frei verfügbarer Strahlung pro Frequenz:

$$
E(T) = \int_0^\infty u(\nu, T) d\nu = \int_0^\infty \frac{8\pi\nu^2}{c^3}k_BT d\nu
$$

Umgestellt ergibt sich für die Gesamtenergie

$$
E(T) = \frac{8\pi}{c^3}k_BT \int_0^\infty \nu^2 d\nu
$$

Somit ist die Gesamtenergie E(T) proportional zu $\nu^3$ und mit $\nu \rightarrow \infty$ folgt $E(T) \rightarrow \infty$

### Energie quantisiert

Integration über das Plancksche Strahlungsgesetz zur Ermittlung der Gesamtenergie bei quantisierter Energie pro Frequenz:

$$
E(T) = \int_0^\infty u(\nu, T) d\nu = \int_0^\infty \frac{8\pi h\nu^3}{c^3}\frac{1}{\exp(\frac{h\nu}{k_BT}) - 1} d\nu
$$

Umgestellt ergibt sich

$$
E(T) = \frac{8\pi (k_BT)^3}{c^3h^2} \int_0^\infty \frac{(\frac{h\nu}{k_BT})^3}{\exp(\frac{h\nu}{k_BT}) - 1} d\nu
$$

wobei das Integral 

$$
\int_0^\infty \frac{x^3}{\exp(x) - 1} dx = \frac{\pi^4}{15}
$$

gegeben ist.
Durch Substitution mit 

$$
x = \frac{h}{k_BT}\nu \Rightarrow d\nu = \frac{k_BT}{h} dx
$$

folgt für die Gesamtenergie

$$
E(T) = \frac{8\pi^5 (k_BT)^4}{15c^3h^3} 
$$
