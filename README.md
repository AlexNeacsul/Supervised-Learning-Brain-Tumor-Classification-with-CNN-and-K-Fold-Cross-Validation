# Supervised-Learning-Brain-Tumor-Classification-with-CNN-and-K-Fold-Cross-Validation
[cite_start]Proiectul implementează **$k$-Fold Cross-Validation** (cu $k=5$ fold-uri) [cite: 44] [cite_start]și explorează diferite metode de **balansare a datelor**[cite: 181], inclusiv:
* [cite_start]**Funcția de pierdere ponderată** (**Weighted Loss**)[cite: 180, 183].
* [cite_start]**Supra-eșantionarea** (**Oversampling**)[cite: 180, 183].
* [cite_start]**Supra-eșantionarea cu augmentare** (**Augmented Oversampling**)[cite: 180].

[cite_start]Se observă că tehnicile de balansare au dus la o **creștere a performanței cu aproximativ 3%** pentru fiecare metrică [cite: 182][cite_start], iar funcția de pierdere ponderată (weighted loss) pare a fi cea mai echilibrată soluție, deoarece îmbunătățește performanța fără a necesita modificări ale setului de date[cite: 183].

### Rezultate Cheie

* [cite_start]**Acuratețe Medie la Validare (fără balansare)**: $0.8448$ [cite: 174]
* **Acuratețe Max. (cu balansare)[cite_start]**: $0.8693$ (Oversampling) [cite: 180]
* [cite_start]**Matricea de Confuzie** și metricile detaliate pe clasă sunt incluse (Precizie, Rapel, Scor F1)[cite: 4, 38].

---
