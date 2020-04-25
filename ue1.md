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
