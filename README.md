# 📘 Matemática para los Negocios — Códigos Python

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/NumPy-1.24%2B-013243?style=for-the-badge&logo=numpy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Matplotlib-3.7%2B-11557C?style=for-the-badge&logo=matplotlib&logoColor=white"/>
  <img src="https://img.shields.io/badge/SciPy-1.11%2B-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white"/>
  <img src="https://img.shields.io/badge/Licencia-Académica-green?style=for-the-badge"/>
</p>

---

> **Repositorio oficial de implementaciones numéricas y visualizaciones** del libro  
> *Matemática para los Negocios* (2026). Cada ejemplo y ejercicio cuenta con su propio  
> notebook de código Python independiente, reproduciendo con precisión las gráficas  
> y resultados analíticos del texto.

---

## 📋 Tabla de Contenidos

- [📦 Requisitos](#-requisitos)
- [🗂️ Estructura del Repositorio](#️-estructura-del-repositorio)
- [📗 Capítulo 1 — Funciones Elementales y Modelos Matemáticos](#-capítulo-1--funciones-elementales-y-modelos-matemáticos)
- [📘 Capítulo 2 — Límites y Continuidad](#-capítulo-2--límites-y-continuidad)
- [📙 Capítulo 3 — La Derivada y Reglas de Derivación](#-capítulo-3--la-derivada-y-reglas-de-derivación)
- [📕 Capítulo 4 — Aplicaciones de la Derivada a los Negocios](#-capítulo-4--aplicaciones-de-la-derivada-a-los-negocios)
- [📒 Capítulo 5 — Funciones Trascendentes y sus Aplicaciones](#-capítulo-5--funciones-trascendentes-y-sus-aplicaciones)
- [📓 Capítulo 6 — La Integral Indefinida](#-capítulo-6--la-integral-indefinida)
- [📔 Capítulo 7 — La Integral Definida y sus Aplicaciones](#-capítulo-7--la-integral-definida-y-sus-aplicaciones)
- [🎨 Convención de Estilo Gráfico](#-convención-de-estilo-gráfico)

---

## 📦 Requisitos

```bash
pip install numpy matplotlib scipy sympy
```

| Librería     | Versión mínima | Uso principal                              |
|--------------|----------------|--------------------------------------------|
| `numpy`      | 1.24           | Arreglos numéricos, funciones matemáticas  |
| `matplotlib` | 3.7            | Visualizaciones y gráficas                 |
| `scipy`      | 1.11           | Integración numérica, optimización         |
| `sympy`      | 1.12           | Cálculo simbólico, derivadas, límites      |

---

## 🗂️ Estructura del Repositorio

```
matematica_negocios_2026/
│
├── capitulo01/          # Funciones Elementales y Modelos Matemáticos
│   ├── ej01_funcion_costo_lineal.py
│   ├── ej02_equilibrio_mercado_lineal.py
│   ├── ej03_impuesto_por_unidad.py
│   ├── ej04_punto_equilibrio_empresa.py
│   ├── ej05_beneficio_cuadratico.py
│   ├── ej06_equilibrio_no_lineal.py
│   ├── ej07_excedente_consumidor_productor.py
│   ├── ej08_interes_compuesto_continuo.py
│   └── ej09_elasticidad_precio.py
│
├── capitulo02/          # Límites y Continuidad
│   ├── ej01_limite_intuitivo.py
│   ├── ej02_limite_racional_factorizacion.py
│   ├── ej03_limites_laterales.py
│   ├── ej04_limite_al_infinito_asintota.py
│   ├── ej05_formas_indeterminadas.py
│   ├── ej06_continuidad_equilibrio.py
│   └── ej07_teorema_valor_intermedio.py
│
├── capitulo03/          # La Derivada y Reglas de Derivación
│   ├── ej01_tasa_cambio_promedio_ingreso.py
│   ├── ej02_costo_marginal_datos.py
│   ├── ej03_derivada_raiz_definicion.py
│   ├── ej04_recta_tangente_geometrica.py
│   ├── ej05_reglas_basicas_derivacion.py
│   ├── ej06_regla_producto_cociente.py
│   ├── ej07_regla_cadena.py
│   ├── ej08_derivacion_implicita.py
│   ├── ej09_derivadas_orden_superior.py
│   └── ej10_analisis_marginal.py
│
├── capitulo04/          # Aplicaciones de la Derivada
│   ├── ej01_costo_marginal_vs_incremental.py
│   ├── ej02_maximizacion_beneficio.py
│   ├── ej03_elasticidad_con_derivada.py
│   ├── ej04_costo_medio_optimo.py
│   ├── ej05_extremos_absolutos.py
│   ├── ej06_monotonia_primera_derivada.py
│   ├── ej07_concavidad_inflexion.py
│   ├── ej08_teorema_valor_medio.py
│   └── ej09_analisis_grafico_completo.py
│
├── capitulo05/          # Funciones Trascendentes
│   ├── ej01_derivada_exponencial.py
│   ├── ej02_derivada_logaritmo.py
│   ├── ej03_diferenciacion_logaritmica.py
│   ├── ej04_valor_futuro_presente.py
│   ├── ej05_tiempo_duplicacion.py
│   ├── ej06_crecimiento_decaimiento.py
│   ├── ej07_modelo_logistico.py
│   └── ej08_elasticidad_exp_log.py
│
├── capitulo06/          # La Integral Indefinida
│   ├── ej01_antiderivadas_basicas.py
│   ├── ej02_sustitucion_simple.py
│   ├── ej03_sustitucion_avanzada.py
│   ├── ej04_integracion_por_partes.py
│   ├── ej05_fracciones_parciales.py
│   └── ej06_acumulacion_capital.py
│
├── capitulo07/          # La Integral Definida y sus Aplicaciones
│   ├── ej01_sumas_riemann.py
│   ├── ej02_comparacion_puntos_riemann.py
│   ├── ej03_tfc_integral_definida.py
│   ├── ej04_area_parabola_recta.py
│   ├── ej05_area_tres_intersecciones.py
│   ├── ej06_area_respecto_y.py
│   ├── ej07_excedente_consumidor_productor.py
│   ├── ej08_valor_presente_flujo_continuo.py
│   ├── ej09_integrales_impropias.py
│   └── ej10_valor_medio_costos_promedio.py
│
├── figuras/             # Imágenes generadas por cada script
└── README.md
```

---

## 📗 Capítulo 1 — Funciones Elementales y Modelos Matemáticos

### Teoría

Una **función** $f: D \subseteq \mathbb{R} \to \mathbb{R}$ asigna a cada valor $x$ del dominio exactamente un valor $f(x)$. En economía, las funciones modelan relaciones causales: costos, ingresos, beneficios, oferta y demanda.

Las **funciones lineales** $f(x) = mx + b$ tienen tasa de cambio constante $m$ (pendiente). El **equilibrio de mercado** ocurre cuando la cantidad demandada iguala a la ofrecida: $Q_d = Q_s$.

---

### Ejemplo 1.1 — Función de Costo Total Lineal

> Sea $C(x) = 80x + 2500$ el costo total (soles) de producir $x$ unidades. Representar gráficamente e identificar el costo fijo y el costo variable unitario.

```python
import numpy as np
import matplotlib.pyplot as plt

x = np.linspace(0, 100, 400)
C = 80 * x + 2500  # Costo total: C(x) = 80x + 2500

plt.figure(figsize=(10, 6))
plt.plot(x, C, 'b-', linewidth=2.5, label=r'$C(x) = 80x + 2500$')
plt.axhline(y=2500, color='gray', linestyle='--', alpha=0.7, label='Costo fijo = S/ 2,500')
plt.scatter([0], [2500], color='red', zorder=5, s=100, label='Intercepto $(0, 2500)$')
plt.fill_between(x, 2500, C, alpha=0.15, color='blue', label='Costo variable total')
plt.grid(True, alpha=0.3)
plt.xlabel('Producción $x$ (unidades)', fontsize=12)
plt.ylabel('Costo total $C(x)$ (soles)', fontsize=12)
plt.title('Función de Costo Total Lineal', fontsize=14, fontweight='bold')
plt.legend(fontsize=10)
plt.tight_layout()
plt.savefig('figuras/fig_c01_costo_lineal.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 1.2 — Equilibrio de Mercado Lineal

> Dadas $Q_d = 200 - 4P$ y $Q_s = 50 + 6P$. Encontrar el precio $P^*$ y cantidad de equilibrio $Q^*$.
>
> **Solución analítica:** $200 - 4P = 50 + 6P \Rightarrow P^* = 15$, $Q^* = 140$.

```python
import numpy as np
import matplotlib.pyplot as plt

P = np.linspace(0, 50, 400)
Qd = 200 - 4 * P   # Función de demanda
Qs = 50 + 6 * P    # Función de oferta

P_eq, Q_eq = 15, 140

plt.figure(figsize=(10, 6))
plt.plot(Qd, P, 'b-', linewidth=2.5, label=r'Demanda: $Q_d = 200 - 4P$')
plt.plot(Qs, P, 'r-', linewidth=2.5, label=r'Oferta: $Q_s = 50 + 6P$')
plt.scatter([Q_eq], [P_eq], color='green', zorder=5, s=150,
            label=f'Equilibrio $(Q^*, P^*) = ({Q_eq}, {P_eq})$')
plt.axhline(y=P_eq, color='green', linestyle='--', alpha=0.5)
plt.axvline(x=Q_eq, color='green', linestyle='--', alpha=0.5)
plt.grid(True, alpha=0.3)
plt.xlabel('Cantidad $Q$', fontsize=12)
plt.ylabel('Precio $P$ (soles)', fontsize=12)
plt.title('Equilibrio de Mercado Lineal', fontsize=14, fontweight='bold')
plt.legend(fontsize=10)
plt.xlim(0, 220)
plt.ylim(0, 50)
plt.tight_layout()
plt.savefig('figuras/fig_c01_equilibrio_lineal.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 1.3 — Efecto de un Impuesto por Unidad

> Mercado con $Q_d = 300 - 5P$ y $Q_s = 40 + 3P$. El gobierno impone un impuesto $t = 8$ soles/unidad. Determinar: equilibrio original, nuevo equilibrio, recaudación fiscal.
>
> **Solución:** $P^*_0 = 32.5$, $Q^*_0 = 137.5$ → con impuesto: $P_c = 35.5$, $Q_t = 122.5$, Recaudación = S/ 980.

```python
import numpy as np
import matplotlib.pyplot as plt

P = np.linspace(0, 70, 400)
Qd = 300 - 5 * P
Qs_orig = 40 + 3 * P
t = 8
Qs_imp = 16 + 3 * P   # Oferta desplazada por impuesto: Qs = 40 + 3(P - 8)

P_eq0, Q_eq0 = 32.5, 137.5
Pc, Qt, Pp = 35.5, 122.5, 27.5

fig, axes = plt.subplots(1, 2, figsize=(14, 6))

# Panel izquierdo: equilibrio original
axes[0].plot(Qd, P, 'b-', linewidth=2.5, label=r'Demanda $Q_d = 300-5P$')
axes[0].plot(Qs_orig, P, 'r-', linewidth=2.5, label=r'Oferta original $Q_s = 40+3P$')
axes[0].scatter([Q_eq0], [P_eq0], color='green', s=150, zorder=5,
                label=f'Equilibrio: $P^*={P_eq0}$, $Q^*={Q_eq0}$')
axes[0].set_title('Sin impuesto', fontsize=13, fontweight='bold')
axes[0].set_xlabel('Cantidad $Q$'); axes[0].set_ylabel('Precio $P$')
axes[0].legend(fontsize=9); axes[0].grid(True, alpha=0.3)
axes[0].set_xlim(0, 320); axes[0].set_ylim(0, 65)

# Panel derecho: con impuesto
axes[1].plot(Qd, P, 'b-', linewidth=2.5, label=r'Demanda $Q_d = 300-5P$')
axes[1].plot(Qs_orig, P, 'r--', linewidth=1.5, alpha=0.5, label='Oferta original')
axes[1].plot(Qs_imp, P, 'r-', linewidth=2.5, label=r'Oferta + impuesto $t=8$')
axes[1].scatter([Qt], [Pc], color='darkred', s=150, zorder=5,
                label=f'Nuevo equilibrio: $P_c={Pc}$, $Q_t={Qt}$')
axes[1].scatter([Qt], [Pp], color='orange', s=100, marker='s', zorder=5,
                label=f'Precio productor $P_p={Pp}$')
axes[1].fill_between([0, Qt], [Pp, Pp], [Pc, Pc], alpha=0.3, color='purple',
                     label=f'Recaudación = S/ {t*Qt:.0f}')
axes[1].set_title('Con impuesto $t = 8$ soles/unidad', fontsize=13, fontweight='bold')
axes[1].set_xlabel('Cantidad $Q$'); axes[1].set_ylabel('Precio $P$')
axes[1].legend(fontsize=9); axes[1].grid(True, alpha=0.3)
axes[1].set_xlim(0, 320); axes[1].set_ylim(0, 65)

plt.suptitle('Efecto de un Impuesto por Unidad sobre el Mercado', fontsize=14, fontweight='bold')
plt.tight_layout()
plt.savefig('figuras/fig_c01_impuesto_unidad.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 1.4 — Maximización de Beneficio Cuadrático

> Empresa con $I(x) = 120x$ y $C(x) = 2x^2 + 20x + 500$ (miles de soles).  
> Función de beneficio: $\pi(x) = -2x^2 + 100x - 500$.  
> **Óptimo:** $x^* = 25$ unidades, $\pi(25) = 750$ miles de soles.

```python
import numpy as np
import matplotlib.pyplot as plt

x = np.linspace(0, 55, 400)
I = 120 * x
C = 2 * x**2 + 20 * x + 500
pi = -2 * x**2 + 100 * x - 500  # Beneficio = I - C

x_opt = 25
pi_max = 750
x1, x2 = 5.635, 44.365   # Raíces de pi(x) = 0

fig, axes = plt.subplots(1, 2, figsize=(14, 6))

# Panel izquierdo: I(x) y C(x)
axes[0].plot(x, I, 'b-', linewidth=2.5, label=r'Ingreso $I(x) = 120x$')
axes[0].plot(x, C, 'r-', linewidth=2.5, label=r'Costo $C(x) = 2x^2+20x+500$')
axes[0].fill_between(x, C, I, where=(I >= C), alpha=0.2, color='green', label='Zona de beneficio')
axes[0].fill_between(x, C, I, where=(I < C), alpha=0.2, color='red', label='Zona de pérdida')
axes[0].set_title('Ingreso y Costo Total', fontsize=13, fontweight='bold')
axes[0].set_xlabel('Producción $x$ (unidades)'); axes[0].set_ylabel('Miles de soles')
axes[0].legend(fontsize=9); axes[0].grid(True, alpha=0.3)

# Panel derecho: pi(x)
axes[1].plot(x, pi, 'g-', linewidth=2.5, label=r'Beneficio $\pi(x) = -2x^2+100x-500$')
axes[1].axhline(y=0, color='black', linewidth=1)
axes[1].scatter([x_opt], [pi_max], color='darkgreen', s=180, zorder=5,
                label=f'Máximo: $x^*={x_opt}$, $\\pi^*={pi_max}$')
axes[1].scatter([x1, x2], [0, 0], color='red', s=100, zorder=5,
                label=f'Equilibrios: $x_1={x1:.2f}$, $x_2={x2:.2f}$')
axes[1].fill_between(x, 0, pi, where=(pi >= 0), alpha=0.2, color='green')
axes[1].fill_between(x, 0, pi, where=(pi < 0), alpha=0.2, color='red')
axes[1].set_title('Función de Beneficio', fontsize=13, fontweight='bold')
axes[1].set_xlabel('Producción $x$ (unidades)'); axes[1].set_ylabel('Beneficio (miles de soles)')
axes[1].legend(fontsize=9); axes[1].grid(True, alpha=0.3)

plt.suptitle('Maximización de Beneficio Cuadrático', fontsize=14, fontweight='bold')
plt.tight_layout()
plt.savefig('figuras/fig_c01_beneficio_cuadratico.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 1.5 — Excedente del Consumidor y del Productor

> Oferta: $Q_s = P^2 - 2$, Demanda: $Q_d = 10 - P$. Calcular excedentes en el equilibrio de mercado.

```python
import numpy as np
import matplotlib.pyplot as plt
from scipy.optimize import fsolve

P = np.linspace(0, 10, 400)
Qd = 10 - P
Qs = P**2 - 2

# Equilibrio numérico
def market(P): return (10 - P) - (P**2 - 2)
P_eq = fsolve(market, 3)[0]
Q_eq = 10 - P_eq

# Rango de integración para excedentes
P_ec = np.linspace(P_eq, 10, 300)  # excedente consumidor: de P* a P_max
P_ep = np.linspace(np.sqrt(2), P_eq, 300)  # excedente productor

plt.figure(figsize=(10, 6))
plt.plot(Qd, P, 'b-', linewidth=2.5, label=r'Demanda $Q_d = 10 - P$')
plt.plot(np.maximum(Qs, 0), P, 'r-', linewidth=2.5, label=r'Oferta $Q_s = P^2 - 2$')
plt.scatter([Q_eq], [P_eq], color='green', s=160, zorder=5,
            label=f'Equilibrio: $P^*={P_eq:.2f}$, $Q^*={Q_eq:.2f}$')
plt.fill_betweenx(P_ec, 0, 10 - P_ec, alpha=0.3, color='blue',
                  label=f'Excedente Consumidor ≈ {0.5*(10-P_eq)*Q_eq:.1f}')
plt.fill_betweenx(P_ep, P_ep**2 - 2, Q_eq, alpha=0.3, color='red',
                  label='Excedente Productor')
plt.axhline(y=P_eq, color='green', linestyle='--', alpha=0.6)
plt.grid(True, alpha=0.3)
plt.xlabel('Cantidad $Q$', fontsize=12)
plt.ylabel('Precio $P$ (soles)', fontsize=12)
plt.title('Excedente del Consumidor y del Productor', fontsize=14, fontweight='bold')
plt.legend(fontsize=10)
plt.xlim(0, 12); plt.ylim(0, 10)
plt.tight_layout()
plt.savefig('figuras/fig_c01_excedentes.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 1.6 — Elasticidad Precio de la Demanda

> Demanda $Q = 500 - 10P$. Calcular la elasticidad en $P = 20$, $P = 25$ y $P = 30$, e identificar las zonas elástica, unitaria e inelástica.
>
> **Fórmula:** $\varepsilon = \frac{dQ}{dP} \cdot \frac{P}{Q}$. Con $Q = 500 - 10P$: $\varepsilon = -10 \cdot \frac{P}{500 - 10P}$.

```python
import numpy as np
import matplotlib.pyplot as plt

P = np.linspace(0.1, 49.9, 400)
Q = 500 - 10 * P
epsilon = -10 * P / Q   # Elasticidad-precio

puntos_P = [20, 25, 30]
puntos_eps = [-10 * p / (500 - 10 * p) for p in puntos_P]

fig, axes = plt.subplots(1, 2, figsize=(14, 6))

# Panel izquierdo: curva de demanda
axes[0].plot(Q, P, 'b-', linewidth=2.5, label=r'$Q_d = 500 - 10P$')
for p, e in zip(puntos_P, puntos_eps):
    q = 500 - 10 * p
    axes[0].scatter([q], [p], s=120, zorder=5, label=f'$P={p}$, $\\varepsilon={e:.2f}$')
axes[0].set_xlabel('Cantidad $Q$'); axes[0].set_ylabel('Precio $P$')
axes[0].set_title('Curva de Demanda Lineal', fontsize=13, fontweight='bold')
axes[0].legend(fontsize=10); axes[0].grid(True, alpha=0.3)
axes[0].set_xlim(0, 520); axes[0].set_ylim(0, 50)

# Panel derecho: elasticidad
axes[1].plot(P, np.abs(epsilon), 'r-', linewidth=2.5, label=r'$|\varepsilon(P)|$')
axes[1].axhline(y=1, color='green', linestyle='--', linewidth=2, label='$|\\varepsilon| = 1$ (unitaria)')
axes[1].fill_between(P, 0, np.abs(epsilon), where=(np.abs(epsilon) > 1),
                     alpha=0.2, color='blue', label='Elástica $|\\varepsilon|>1$')
axes[1].fill_between(P, 0, np.abs(epsilon), where=(np.abs(epsilon) <= 1),
                     alpha=0.2, color='orange', label='Inelástica $|\\varepsilon|<1$')
for p, e in zip(puntos_P, puntos_eps):
    axes[1].scatter([p], [abs(e)], s=120, zorder=5)
    axes[1].annotate(f'$P={p}$\n$|\\varepsilon|={abs(e):.2f}$',
                     xy=(p, abs(e)), xytext=(p+1, abs(e)+0.3), fontsize=9)
axes[1].set_xlabel('Precio $P$'); axes[1].set_ylabel('$|\\varepsilon|$')
axes[1].set_title('Elasticidad-Precio de la Demanda', fontsize=13, fontweight='bold')
axes[1].legend(fontsize=10); axes[1].grid(True, alpha=0.3)
axes[1].set_xlim(0, 50); axes[1].set_ylim(0, 6)

plt.suptitle('Análisis de Elasticidad — Demanda Lineal', fontsize=14, fontweight='bold')
plt.tight_layout()
plt.savefig('figuras/fig_c01_elasticidad.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

## 📘 Capítulo 2 — Límites y Continuidad

### Teoría

El **límite** de $f(x)$ cuando $x \to a$ (denotado $\lim_{x \to a} f(x) = L$) describe el comportamiento de la función al acercarse al punto $a$, independientemente del valor en $a$. La **continuidad** exige que $f(a)$ exista, el límite exista, y ambos coincidan.

---

### Ejemplo 2.1 — Límite Intuitivo: Cociente Incremental

> Visualizar cómo $\frac{f(x) - f(2)}{x - 2}$ con $f(x) = x^2$ se aproxima a $4$ cuando $x \to 2$.

```python
import numpy as np
import matplotlib.pyplot as plt

f = lambda x: x**2
a = 2
h_vals = np.array([1.0, 0.5, 0.1, 0.01])
cocientes = [(f(a + h) - f(a)) / h for h in h_vals]

x = np.linspace(0, 4, 400)
x_tang = np.linspace(0.5, 3.5, 100)
tang = 4 * (x_tang - 2) + 4   # Tangente en x=2: y = 4(x-2) + 4

plt.figure(figsize=(10, 6))
plt.plot(x, f(x), 'b-', linewidth=2.5, label=r'$f(x) = x^2$')
plt.plot(x_tang, tang, 'g--', linewidth=2, label='Recta tangente en $x=2$ (pendiente $= 4$)')
colores = ['#FF6B6B', '#FFA07A', '#FFD700', '#98FB98']
for h, coc, color in zip(h_vals, cocientes, colores):
    x_sec = np.linspace(1, a + h + 0.2, 100)
    sec = coc * (x_sec - a) + f(a)
    plt.plot(x_sec, sec, '-', color=color, alpha=0.7, linewidth=1.5,
             label=f'Secante $h={h}$, pendiente$={coc:.2f}$')
plt.scatter([a], [f(a)], color='red', s=150, zorder=5, label='Punto $x=2$')
plt.grid(True, alpha=0.3)
plt.xlabel('$x$', fontsize=12); plt.ylabel('$f(x)$', fontsize=12)
plt.title('Aproximación de la Derivada: Límite del Cociente Incremental', fontsize=13, fontweight='bold')
plt.legend(fontsize=9); plt.xlim(0, 4); plt.ylim(0, 16)
plt.tight_layout()
plt.savefig('figuras/fig_c02_limite_intuitivo.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 2.2 — Límite con Forma Indeterminada 0/0 (Factorización)

> Calcular $\lim_{x \to 3} \frac{x^2 - 9}{x - 3}$.  
> **Solución:** Factorizando: $\frac{(x-3)(x+3)}{x-3} = x + 3 \to 6$.

```python
import numpy as np
import matplotlib.pyplot as plt

f = lambda x: (x**2 - 9) / (x - 3)   # Forma indeterminada en x=3
g = lambda x: x + 3                   # Forma simplificada

x1 = np.linspace(0, 2.99, 200)
x2 = np.linspace(3.01, 7, 200)

plt.figure(figsize=(10, 6))
plt.plot(x1, f(x1), 'b-', linewidth=2.5, label=r'$f(x) = \dfrac{x^2-9}{x-3}$')
plt.plot(x2, f(x2), 'b-', linewidth=2.5)
plt.plot(np.concatenate([x1, x2]), g(np.concatenate([x1, x2])), 'r--',
         linewidth=1.5, alpha=0.6, label=r'Forma reducida $g(x)=x+3$')
plt.scatter([3], [6], facecolors='white', edgecolors='blue', s=150, zorder=5, linewidths=2,
            label=r'$x=3$ (punto excluido), límite $= 6$')
plt.axhline(y=6, color='green', linestyle=':', alpha=0.7, label='$L = 6$')
plt.axvline(x=3, color='gray', linestyle=':', alpha=0.5)
plt.grid(True, alpha=0.3)
plt.xlabel('$x$', fontsize=12); plt.ylabel('$f(x)$', fontsize=12)
plt.title(r'Límite con Forma Indeterminada: $\lim_{x\to3}\frac{x^2-9}{x-3}=6$',
          fontsize=13, fontweight='bold')
plt.legend(fontsize=10); plt.xlim(0, 7); plt.ylim(0, 12)
plt.tight_layout()
plt.savefig('figuras/fig_c02_limite_factorizacion.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 2.3 — Límites Laterales y Discontinuidad

> Función de precio por tramos:
> $p(x) = \begin{cases} 50 & x < 100 \\ 45 & x \geq 100 \end{cases}$
> Los límites laterales en $x=100$ no coinciden: discontinuidad de salto.

```python
import numpy as np
import matplotlib.pyplot as plt

x_izq = np.linspace(0, 99.99, 300)
x_der = np.linspace(100, 200, 300)
p_izq = np.full_like(x_izq, 50.0)
p_der = np.full_like(x_der, 45.0)

plt.figure(figsize=(10, 6))
plt.plot(x_izq, p_izq, 'b-', linewidth=2.5, label=r'$p(x)=50$ para $x<100$')
plt.plot(x_der, p_der, 'r-', linewidth=2.5, label=r'$p(x)=45$ para $x\geq 100$')
plt.scatter([100], [50], facecolors='white', edgecolors='blue', s=150, zorder=5,
            linewidths=2.5, label=r'Límite izquierdo $= 50$')
plt.scatter([100], [45], color='red', s=150, zorder=5,
            label=r'Límite derecho $= 45$ (valor de $p(100)$)')
plt.annotate('Discontinuidad\nde salto en $x=100$\n$\\Delta p = 5$',
             xy=(100, 47.5), xytext=(120, 48),
             arrowprops=dict(arrowstyle='->', color='black'), fontsize=10,
             bbox=dict(boxstyle='round,pad=0.3', facecolor='yellow', alpha=0.7))
plt.grid(True, alpha=0.3)
plt.xlabel('Cantidad $x$ (unidades)', fontsize=12)
plt.ylabel('Precio unitario $p(x)$ (soles)', fontsize=12)
plt.title('Límites Laterales — Función de Precio por Tramos', fontsize=13, fontweight='bold')
plt.legend(fontsize=10); plt.xlim(0, 200); plt.ylim(35, 60)
plt.tight_layout()
plt.savefig('figuras/fig_c02_limites_laterales.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 2.4 — Límite al Infinito y Asíntota Horizontal

> Función de costo medio $\overline{C}(x) = 5 + \frac{1200}{x}$. Determinar $\lim_{x \to \infty} \overline{C}(x)$.
>
> **Solución:** $\lim_{x \to \infty} \left(5 + \frac{1200}{x}\right) = 5$. Asíntota horizontal: $\overline{C} = 5$.

```python
import numpy as np
import matplotlib.pyplot as plt

x = np.linspace(1, 600, 500)
C_med = 5 + 1200 / x

plt.figure(figsize=(10, 6))
plt.plot(x, C_med, 'b-', linewidth=2.5, label=r'$\overline{C}(x) = 5 + \dfrac{1200}{x}$')
plt.axhline(y=5, color='red', linestyle='--', linewidth=2,
            label=r'Asíntota horizontal: $\overline{C} = 5$')
plt.annotate(r'$\lim_{x\to\infty}\overline{C}(x) = 5$',
             xy=(400, 5.2), fontsize=12, color='red',
             bbox=dict(boxstyle='round', facecolor='lightyellow', alpha=0.8))
plt.scatter([1200/5], [10], color='green', s=100, zorder=5,
            label='$x=240$: $\\overline{C}=10$ (doble del asíntota)')
plt.grid(True, alpha=0.3)
plt.xlabel('Producción $x$ (unidades)', fontsize=12)
plt.ylabel(r'Costo medio $\overline{C}(x)$ (soles/unidad)', fontsize=12)
plt.title('Límite al Infinito — Costo Medio con Asíntota Horizontal', fontsize=13, fontweight='bold')
plt.legend(fontsize=10); plt.xlim(0, 600); plt.ylim(0, 50)
plt.tight_layout()
plt.savefig('figuras/fig_c02_asintota_horizontal.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

## 📙 Capítulo 3 — La Derivada y Reglas de Derivación

### Teoría

La **derivada** $f'(x_0) = \lim_{h \to 0} \frac{f(x_0+h) - f(x_0)}{h}$ representa la tasa de cambio instantánea. Geométricamente, es la pendiente de la recta tangente. En economía: **costo marginal** $= C'(x)$, **ingreso marginal** $= I'(x)$.

---

### Ejemplo 3.1 — Tasa de Cambio Promedio del Ingreso

> $I(x) = 5x + 0.5x^2$. Calcular la tasa de cambio promedio de $x=10$ a $x=20$, y el ingreso marginal en $x=10$.
>
> **Resultado:** TCP$(10, 20) = 20$, $I'(10) = 15$ soles/helado.

```python
import numpy as np
import matplotlib.pyplot as plt

I = lambda x: 5*x + 0.5*x**2
I_prima = lambda x: 5 + x   # Derivada: I'(x) = 5 + x

x = np.linspace(0, 30, 400)
x0 = 10
tang_x = np.linspace(5, 20, 100)
tang_y = I_prima(x0) * (tang_x - x0) + I(x0)  # Recta tangente en x=10

plt.figure(figsize=(10, 6))
plt.plot(x, I(x), 'b-', linewidth=2.5, label=r'$I(x) = 5x + 0.5x^2$')
plt.plot(tang_x, tang_y, 'r--', linewidth=2,
         label=f"Tangente en $x={x0}$: pendiente $= I'(10) = {I_prima(x0)}$")
# Recta secante de x=10 a x=20
sec_x = np.array([10, 20])
sec_slope = (I(20) - I(10)) / (20 - 10)
sec_y = sec_slope * (sec_x - 10) + I(10)
plt.plot(sec_x, sec_y, 'g-', linewidth=2,
         label=f'Secante (TCP 10→20): pendiente $= {sec_slope:.0f}$')
plt.scatter([10, 20], [I(10), I(20)], color=['red', 'green'], s=120, zorder=5)
plt.grid(True, alpha=0.3)
plt.xlabel('Helados vendidos $x$', fontsize=12)
plt.ylabel('Ingreso $I(x)$ (soles)', fontsize=12)
plt.title('Tasa de Cambio Promedio vs. Instantánea del Ingreso', fontsize=13, fontweight='bold')
plt.legend(fontsize=10)
plt.tight_layout()
plt.savefig('figuras/fig_c03_tasa_cambio_ingreso.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 3.2 — Derivada por Definición: $f(x) = \sqrt{x}$

> Calcular $f'(4)$ para $f(x) = \sqrt{x}$ usando la definición de límite.
> **Resultado:** $f'(4) = \frac{1}{4} = 0.25$.

```python
import numpy as np
import matplotlib.pyplot as plt

f = lambda x: np.sqrt(x)
f_prima = lambda x: 0.5 / np.sqrt(x)

x = np.linspace(0.01, 10, 400)
x0 = 4
tang_x = np.linspace(1, 7, 100)
tang_y = f_prima(x0) * (tang_x - x0) + f(x0)

h_vals = [2.0, 1.0, 0.5, 0.1, 0.01]
approx = [(f(x0+h) - f(x0))/h for h in h_vals]

fig, axes = plt.subplots(1, 2, figsize=(14, 6))

axes[0].plot(x, f(x), 'b-', linewidth=2.5, label=r'$f(x)=\sqrt{x}$')
axes[0].plot(tang_x, tang_y, 'r--', linewidth=2,
             label=f"Tangente en $x={x0}$: pendiente $={f_prima(x0):.4f}$")
axes[0].scatter([x0], [f(x0)], color='red', s=150, zorder=5)
axes[0].set_xlabel('$x$'); axes[0].set_ylabel('$f(x)$')
axes[0].set_title(r'$f(x)=\sqrt{x}$ y Recta Tangente en $x=4$', fontsize=12, fontweight='bold')
axes[0].legend(fontsize=10); axes[0].grid(True, alpha=0.3)

axes[1].plot(h_vals, approx, 'ro-', linewidth=2, markersize=8, label='Cociente incremental')
axes[1].axhline(y=0.25, color='green', linestyle='--', linewidth=2, label="$f'(4) = 0.25$")
axes[1].set_xscale('log')
axes[1].set_xlabel('$h$ (escala logarítmica)'); axes[1].set_ylabel('Cociente incremental')
axes[1].set_title('Convergencia al Límite cuando $h \\to 0$', fontsize=12, fontweight='bold')
axes[1].legend(fontsize=10); axes[1].grid(True, alpha=0.3)

plt.suptitle(r'Derivada por Definición: $f(x)=\sqrt{x}$, $f\'(4)=1/4$',
             fontsize=13, fontweight='bold')
plt.tight_layout()
plt.savefig('figuras/fig_c03_derivada_definicion.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 3.3 — Regla de la Cadena: Función Compuesta de Costo

> $C(q) = \sqrt{2q^2 + 5q + 10}$. Calcular $C'(q)$ e interpretar en $q = 3$.
> **Resultado:** $C'(q) = \frac{4q + 5}{2\sqrt{2q^2+5q+10}}$. En $q=3$: $C'(3) \approx 1.29$ soles/unidad.

```python
import numpy as np
import matplotlib.pyplot as plt

C = lambda q: np.sqrt(2*q**2 + 5*q + 10)
C_prima = lambda q: (4*q + 5) / (2 * np.sqrt(2*q**2 + 5*q + 10))

q = np.linspace(0, 10, 400)
q0 = 3
tang_q = np.linspace(1, 6, 100)
tang_C = C_prima(q0) * (tang_q - q0) + C(q0)

fig, axes = plt.subplots(1, 2, figsize=(14, 6))

axes[0].plot(q, C(q), 'b-', linewidth=2.5, label=r'$C(q)=\sqrt{2q^2+5q+10}$')
axes[0].plot(tang_q, tang_C, 'r--', linewidth=2,
             label=f"Tangente en $q=3$: $C'(3)={C_prima(q0):.4f}$")
axes[0].scatter([q0], [C(q0)], color='red', s=150, zorder=5)
axes[0].set_xlabel('Cantidad $q$'); axes[0].set_ylabel('Costo $C(q)$ (soles)')
axes[0].set_title('Función de Costo (Regla de la Cadena)', fontsize=12, fontweight='bold')
axes[0].legend(fontsize=10); axes[0].grid(True, alpha=0.3)

axes[1].plot(q, C_prima(q), 'g-', linewidth=2.5,
             label=r"$C'(q)=\frac{4q+5}{2\sqrt{2q^2+5q+10}}$")
axes[1].scatter([q0], [C_prima(q0)], color='red', s=150, zorder=5,
                label=f"$C'(3) = {C_prima(q0):.4f}$")
axes[1].set_xlabel('Cantidad $q$'); axes[1].set_ylabel("Costo marginal $C'(q)$")
axes[1].set_title('Costo Marginal (Derivada)', fontsize=12, fontweight='bold')
axes[1].legend(fontsize=10); axes[1].grid(True, alpha=0.3)

plt.suptitle('Regla de la Cadena — Función de Costo Compuesta', fontsize=13, fontweight='bold')
plt.tight_layout()
plt.savefig('figuras/fig_c03_regla_cadena.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

## 📕 Capítulo 4 — Aplicaciones de la Derivada a los Negocios

### Teoría

Las aplicaciones de la derivada en negocios incluyen: **maximización de beneficios** (donde $\pi'(x^*)=0$ y $\pi''(x^*)<0$), **minimización de costos**, **análisis de elasticidad** y el **análisis gráfico completo** mediante primera y segunda derivada.

---

### Ejemplo 4.1 — Costo Marginal vs. Costo Incremental Exacto

> $C(x) = 0.1x^3 - 3x^2 + 60x + 200$. Comparar $C'(10)$ con $C(11) - C(10)$.
> **Resultado:** $C'(10) = 30$, $C(11)-C(10) = 30.1$ (error relativo: $0.33\%$).

```python
import numpy as np
import matplotlib.pyplot as plt

C = lambda x: 0.1*x**3 - 3*x**2 + 60*x + 200
C_prima = lambda x: 0.3*x**2 - 6*x + 60

x = np.linspace(0, 25, 400)
x0 = 10
tang_x = np.linspace(7, 14, 100)
tang_y = C_prima(x0) * (tang_x - x0) + C(x0)

print(f"C'(10)          = {C_prima(10):.4f}  (costo marginal)")
print(f"C(11) - C(10)   = {C(11)-C(10):.4f}  (costo incremental exacto)")
print(f"Diferencia      = {abs(C(11)-C(10)-C_prima(10)):.4f}")
print(f"Error relativo  = {abs(C(11)-C(10)-C_prima(10))/(C(11)-C(10))*100:.2f}%")

plt.figure(figsize=(10, 6))
plt.plot(x, C(x), 'b-', linewidth=2.5, label=r'$C(x)=0.1x^3-3x^2+60x+200$')
plt.plot(tang_x, tang_y, 'r--', linewidth=2,
         label=f"Tangente: $C'(10)={C_prima(10):.1f}$")
plt.plot([10, 11], [C(10), C(11)], 'g-o', linewidth=2.5, markersize=10,
         label=f'Incremento exacto: $\\Delta C = {C(11)-C(10):.1f}$')
plt.scatter([10], [C(10)], color='red', s=150, zorder=6)
plt.annotate(f'$\\Delta C = {C(11)-C(10):.1f}$\n$C\'(10) = {C_prima(10):.1f}$',
             xy=(11, C(11)), xytext=(13, C(10)+50),
             arrowprops=dict(arrowstyle='->', color='green'), fontsize=11,
             bbox=dict(boxstyle='round', facecolor='lightgreen', alpha=0.8))
plt.grid(True, alpha=0.3)
plt.xlabel('Producción $x$ (unidades)', fontsize=12)
plt.ylabel('Costo $C(x)$ (miles de soles)', fontsize=12)
plt.title('Costo Marginal vs. Costo Incremental Exacto', fontsize=13, fontweight='bold')
plt.legend(fontsize=10); plt.xlim(0, 25)
plt.tight_layout()
plt.savefig('figuras/fig_c04_marginal_vs_incremental.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 4.2 — Maximización del Beneficio con Segunda Derivada

> $\pi(x) = -x^3 + 12x^2 - 36x + 5$. Encontrar el máximo local usando la prueba de la segunda derivada.
> **Resultado:** $x^* = 6$ es máximo local ($\pi''(6) = -12 < 0$), $\pi(6) = 77$.

```python
import numpy as np
import matplotlib.pyplot as plt

pi = lambda x: -x**3 + 12*x**2 - 36*x + 5
pi1 = lambda x: -3*x**2 + 24*x - 36   # Primera derivada
pi2 = lambda x: -6*x + 24              # Segunda derivada

x = np.linspace(0, 10, 400)
# Puntos críticos: -3x^2 + 24x - 36 = 0 → x = 2, 6
x_crit = [2, 6]

fig, axes = plt.subplots(1, 3, figsize=(16, 5))

axes[0].plot(x, pi(x), 'b-', linewidth=2.5, label=r'$\pi(x) = -x^3+12x^2-36x+5$')
axes[0].axhline(y=0, color='black', linewidth=1)
for xc in x_crit:
    axes[0].scatter([xc], [pi(xc)], s=150, zorder=5)
    axes[0].annotate(f'$x={xc}$\n$\\pi={pi(xc):.0f}$', xy=(xc, pi(xc)),
                     xytext=(xc+0.3, pi(xc)+5), fontsize=9)
axes[0].fill_between(x, 0, pi(x), where=(pi(x) >= 0), alpha=0.15, color='green')
axes[0].fill_between(x, 0, pi(x), where=(pi(x) < 0), alpha=0.15, color='red')
axes[0].set_title(r'Función de Beneficio $\pi(x)$', fontsize=11, fontweight='bold')
axes[0].set_xlabel('$x$'); axes[0].set_ylabel('$\\pi(x)$')
axes[0].legend(fontsize=9); axes[0].grid(True, alpha=0.3)

axes[1].plot(x, pi1(x), 'r-', linewidth=2.5, label=r"$\pi'(x) = -3x^2+24x-36$")
axes[1].axhline(y=0, color='black', linewidth=1.5, linestyle='--')
for xc in x_crit:
    axes[1].scatter([xc], [0], s=150, zorder=5,
                    color='green' if pi2(xc) < 0 else 'red',
                    label=f"$x={xc}$: $\\pi''={pi2(xc):.0f}$ ({'Máx' if pi2(xc)<0 else 'Mín'})")
axes[1].fill_between(x, 0, pi1(x), where=(pi1(x) > 0), alpha=0.2, color='blue')
axes[1].fill_between(x, 0, pi1(x), where=(pi1(x) < 0), alpha=0.2, color='orange')
axes[1].set_title(r"Primera Derivada $\pi'(x)$", fontsize=11, fontweight='bold')
axes[1].set_xlabel('$x$'); axes[1].legend(fontsize=8); axes[1].grid(True, alpha=0.3)

axes[2].plot(x, pi2(x), 'g-', linewidth=2.5, label=r"$\pi''(x) = -6x+24$")
axes[2].axhline(y=0, color='black', linewidth=1.5, linestyle='--')
axes[2].scatter([4], [0], color='purple', s=150, zorder=5, label='Inflexión $x=4$')
axes[2].fill_between(x, 0, pi2(x), where=(pi2(x) > 0), alpha=0.2, color='cyan',
                     label='Cóncava arriba')
axes[2].fill_between(x, 0, pi2(x), where=(pi2(x) < 0), alpha=0.2, color='orange',
                     label='Cóncava abajo')
axes[2].set_title(r"Segunda Derivada $\pi''(x)$", fontsize=11, fontweight='bold')
axes[2].set_xlabel('$x$'); axes[2].legend(fontsize=9); axes[2].grid(True, alpha=0.3)

plt.suptitle('Análisis Completo de Beneficio con Primera y Segunda Derivada',
             fontsize=13, fontweight='bold')
plt.tight_layout()
plt.savefig('figuras/fig_c04_analisis_derivadas.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 4.3 — Costo Medio Mínimo

> $C(x) = x^3 - 6x^2 + 15x + 50$. Encontrar el nivel de producción que minimiza el costo medio $\overline{C}(x) = C(x)/x$.
> **Cond. necesaria:** $\overline{C}'(x) = 0 \Leftrightarrow C'(x) = \overline{C}(x)$ (CM = CMg).

```python
import numpy as np
import matplotlib.pyplot as plt
from scipy.optimize import minimize_scalar

C = lambda x: x**3 - 6*x**2 + 15*x + 50
C_med = lambda x: C(x) / x
C_prima = lambda x: 3*x**2 - 12*x + 15

x = np.linspace(0.5, 12, 400)
res = minimize_scalar(C_med, bounds=(1, 10), method='bounded')
x_opt = res.x
C_med_min = C_med(x_opt)

plt.figure(figsize=(10, 6))
plt.plot(x, C_med(x), 'b-', linewidth=2.5, label=r'$\overline{C}(x)=\frac{C(x)}{x}$')
plt.plot(x, C_prima(x), 'r--', linewidth=2, label=r"$C'(x) = 3x^2-12x+15$ (CMg)")
plt.scatter([x_opt], [C_med_min], color='green', s=180, zorder=5,
            label=f'Mínimo: $x^*={x_opt:.2f}$, $\\overline{{C}}^*={C_med_min:.2f}$')
plt.axvline(x=x_opt, color='green', linestyle=':', alpha=0.7)
plt.annotate('CMg = Cme\n(condición de mínimo)',
             xy=(x_opt, C_med_min), xytext=(x_opt+1.5, C_med_min+2),
             arrowprops=dict(arrowstyle='->', color='green'), fontsize=10,
             bbox=dict(boxstyle='round', facecolor='lightgreen', alpha=0.8))
plt.grid(True, alpha=0.3)
plt.xlabel('Producción $x$ (unidades)', fontsize=12)
plt.ylabel('Costo (soles/unidad)', fontsize=12)
plt.title('Minimización del Costo Medio: $CMg = C_{me}$', fontsize=13, fontweight='bold')
plt.legend(fontsize=10); plt.xlim(0.5, 12); plt.ylim(0, 80)
plt.tight_layout()
plt.savefig('figuras/fig_c04_costo_medio_minimo.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

## 📒 Capítulo 5 — Funciones Trascendentes y sus Aplicaciones

### Teoría

Las **funciones exponenciales** $f(x) = a^x$ y el **logaritmo natural** $\ln(x)$ son fundamentales en finanzas, biología y economía. La **capitalización continua** $A(t) = A_0 e^{rt}$ y el **modelo logístico** describen crecimiento con límite de capacidad.

---

### Ejemplo 5.1 — Valor Futuro y Valor Presente (Capitalización Continua)

> Capital $A_0 = 5{,}000$ soles al $8\%$ continuo. ¿Cuánto acumula en 6 años?  
> **Resultado:** $A(6) = 5000 \cdot e^{0.48} \approx S/\, 8{,}080.37$.

```python
import numpy as np
import matplotlib.pyplot as plt

A0 = 5000
r = 0.08
t = np.linspace(0, 20, 400)
A_cont = A0 * np.exp(r * t)           # Capitalización continua
A_anual = A0 * (1 + r) ** t           # Capitalización anual

t6 = 6
A_6 = A0 * np.exp(r * t6)

plt.figure(figsize=(10, 6))
plt.plot(t, A_cont, 'b-', linewidth=2.5, label=f'Continua: $A(t)={A0}e^{{0.08t}}$')
plt.plot(t, A_anual, 'r--', linewidth=2, label=f'Anual: $A(t)={A0}(1.08)^t$')
plt.scatter([t6], [A_6], color='green', s=150, zorder=5,
            label=f'$A(6) = S/\\, {A_6:,.2f}$')
plt.axhline(y=A0*2, color='gray', linestyle=':', alpha=0.7,
            label=f'Duplicación: $t_{{dup}}={np.log(2)/r:.1f}$ años')
plt.annotate(f'$A(6)={A_6:,.0f}$', xy=(t6, A_6), xytext=(t6+1, A_6-500),
             arrowprops=dict(arrowstyle='->', color='green'), fontsize=10)
plt.grid(True, alpha=0.3)
plt.xlabel('Tiempo $t$ (años)', fontsize=12)
plt.ylabel('Monto $A(t)$ (soles)', fontsize=12)
plt.title('Capitalización Continua vs. Anual — $r = 8\\%$', fontsize=13, fontweight='bold')
plt.legend(fontsize=10)
plt.tight_layout()
plt.savefig('figuras/fig_c05_capitalizacion.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 5.2 — Modelo Logístico de Crecimiento

> Una empresa tiene capacidad máxima de mercado $K = 10{,}000$ clientes. Parte con $N_0 = 500$ y crece a tasa $r = 0.3$.
> **Modelo:** $N(t) = \frac{K}{1 + \left(\frac{K - N_0}{N_0}\right)e^{-rt}}$.

```python
import numpy as np
import matplotlib.pyplot as plt

K = 10000    # Capacidad máxima
N0 = 500     # Clientes iniciales
r = 0.3      # Tasa de crecimiento

t = np.linspace(0, 30, 400)
N = K / (1 + ((K - N0) / N0) * np.exp(-r * t))
N_prima = r * N * (1 - N / K)   # Velocidad de crecimiento

t_inflexion = np.log((K - N0) / N0) / r

fig, axes = plt.subplots(1, 2, figsize=(14, 6))

axes[0].plot(t, N, 'b-', linewidth=2.5, label=r'$N(t)$ — Modelo Logístico')
axes[0].axhline(y=K, color='red', linestyle='--', linewidth=1.5,
                label=f'Capacidad máxima $K={K:,}$')
axes[0].axhline(y=K/2, color='gray', linestyle=':', alpha=0.7,
                label=f'$K/2={K//2:,}$ (inflexión)')
axes[0].scatter([t_inflexion], [K/2], color='green', s=150, zorder=5,
                label=f'Inflexión: $t={t_inflexion:.1f}$ años')
axes[0].set_xlabel('Tiempo $t$ (años)'); axes[0].set_ylabel('Número de clientes $N(t)$')
axes[0].set_title('Crecimiento Logístico de Clientes', fontsize=12, fontweight='bold')
axes[0].legend(fontsize=9); axes[0].grid(True, alpha=0.3)

axes[1].plot(t, N_prima, 'r-', linewidth=2.5, label=r"$N'(t) = rN(1-N/K)$")
axes[1].scatter([t_inflexion], [r*K/4], color='green', s=150, zorder=5,
                label=f'Máx. velocidad: $t={t_inflexion:.1f}$, $N\'={r*K/4:.0f}$ cl/año')
axes[1].axvline(x=t_inflexion, color='gray', linestyle=':', alpha=0.7)
axes[1].set_xlabel('Tiempo $t$ (años)'); axes[1].set_ylabel("Velocidad $N'(t)$ (clientes/año)")
axes[1].set_title('Velocidad de Crecimiento', fontsize=12, fontweight='bold')
axes[1].legend(fontsize=9); axes[1].grid(True, alpha=0.3)

plt.suptitle('Modelo Logístico de Crecimiento de Mercado', fontsize=13, fontweight='bold')
plt.tight_layout()
plt.savefig('figuras/fig_c05_logistico.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 5.3 — Aproximación Polinómica de Taylor (Función de Beneficio)

> $\pi(x) = \ln(x+1) - 0.1x$. Aproximar mediante polinomio de Taylor de 3er orden alrededor de $x=4$.

```python
import numpy as np
import matplotlib.pyplot as plt

x = np.linspace(-5, 30, 400)
pi = np.log(x + 1) - 0.1 * x

# Polinomio de Taylor de tercer orden alrededor de x=4
P3 = 1.20944 + 0.1*(x-4) - 0.02*(x-4)**2 + 0.0026667*(x-4)**3

plt.figure(figsize=(10, 6))
plt.plot(x, pi, 'b-', linewidth=2.5, label=r'$\pi(x)=\ln(x+1)-0.1x$ (función exacta)')
plt.plot(x, P3, 'r--', linewidth=2, label='Polinomio de Taylor de 3er orden en $x=4$')
plt.scatter(4, 1.20944, color='green', zorder=5, s=120, label='Punto de expansión $x=4$')
plt.scatter(5, 1.29176, color='blue', zorder=5, s=80, label='$\\pi(5)$ exacto')
plt.scatter(5, 1.29211, color='red', zorder=5, s=80, marker='x', label='$P_3(5)$ aproximado')
plt.grid(True, alpha=0.3)
plt.legend()
plt.title('Aproximación Polinómica de Taylor', fontsize=14, fontweight='bold')
plt.xlabel('Producción $x$ (miles)')
plt.ylabel('Beneficio $\\pi(x)$')
plt.xlim(-5, 30)
plt.ylim(0.5, 1.6)
plt.tight_layout()
plt.savefig('figuras/fig_c05_taylor.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

## 📓 Capítulo 6 — La Integral Indefinida

### Teoría

La **integral indefinida** $\int f(x)\,dx = F(x) + C$ es la antiderivada de $f$. Técnicas fundamentales: sustitución $u$, integración por partes $\int u\,dv = uv - \int v\,du$, y fracciones parciales para funciones racionales.

---

### Ejemplo 6.1 — Sustitución Básica: Función de Costo Marginal

> $C'(x) = \frac{2x}{\sqrt{x^2 + 9}}$. Encontrar $C(x)$ dado que $C(0) = 15$.  
> **Resultado:** $C(x) = 2\sqrt{x^2 + 9} + 9$.

```python
import numpy as np
import matplotlib.pyplot as plt

C_prima = lambda x: 2*x / np.sqrt(x**2 + 9)
C = lambda x: 2 * np.sqrt(x**2 + 9) + 9   # Verificar: C(0) = 2*3 + 9 = 15 ✓

x = np.linspace(0, 15, 400)

fig, axes = plt.subplots(1, 2, figsize=(13, 5))

axes[0].plot(x, C_prima(x), 'r-', linewidth=2.5,
             label=r"$C'(x)=\frac{2x}{\sqrt{x^2+9}}$")
axes[0].fill_between(x, 0, C_prima(x), alpha=0.2, color='red',
                     label='Área = incremento de costo')
axes[0].set_xlabel('Producción $x$'); axes[0].set_ylabel("Costo marginal $C'(x)$")
axes[0].set_title('Costo Marginal', fontsize=12, fontweight='bold')
axes[0].legend(fontsize=10); axes[0].grid(True, alpha=0.3)

axes[1].plot(x, C(x), 'b-', linewidth=2.5,
             label=r'$C(x) = 2\sqrt{x^2+9}+9$')
axes[1].scatter([0], [C(0)], color='red', s=150, zorder=5,
                label=f'Costo fijo: $C(0) = {C(0):.0f}$')
axes[1].set_xlabel('Producción $x$'); axes[1].set_ylabel('Costo total $C(x)$')
axes[1].set_title('Costo Total (Antiderivada)', fontsize=12, fontweight='bold')
axes[1].legend(fontsize=10); axes[1].grid(True, alpha=0.3)

plt.suptitle('Integración por Sustitución — Reconstrucción del Costo Total',
             fontsize=13, fontweight='bold')
plt.tight_layout()
plt.savefig('figuras/fig_c06_sustitucion_costo.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 6.2 — Integración por Partes: Acumulación de Capital

> $\int t e^{-0.05t}\,dt$. Aplicar integración por partes con $u = t$, $dv = e^{-0.05t}dt$.
> **Resultado:** $-20t e^{-0.05t} - 400 e^{-0.05t} + C$.

```python
import numpy as np
import matplotlib.pyplot as plt
from scipy.integrate import quad

# Función integrando: t * e^(-0.05t)
f = lambda t: t * np.exp(-0.05 * t)
F = lambda t: -20*t * np.exp(-0.05*t) - 400*np.exp(-0.05*t)  # Antiderivada

t = np.linspace(0, 50, 400)
T_max = 20
area, _ = quad(f, 0, T_max)

plt.figure(figsize=(10, 6))
plt.plot(t, f(t), 'b-', linewidth=2.5, label=r'$R(t) = t \cdot e^{-0.05t}$')
t_fill = np.linspace(0, T_max, 300)
plt.fill_between(t_fill, 0, f(t_fill), alpha=0.3, color='blue',
                 label=f'VP acumulado $[0,{T_max}]$ = {area:.2f}')
plt.axvline(x=T_max, color='green', linestyle='--', alpha=0.7)
plt.annotate(f'$\\int_0^{{{T_max}}} t e^{{-0.05t}}dt = {area:.2f}$',
             xy=(T_max/2, f(T_max/2)*0.6), fontsize=11, color='navy',
             bbox=dict(boxstyle='round', facecolor='lightblue', alpha=0.8),
             ha='center')
plt.grid(True, alpha=0.3)
plt.xlabel('Tiempo $t$ (años)', fontsize=12)
plt.ylabel('Flujo descontado $R(t)$', fontsize=12)
plt.title(r'Integración por Partes: $\int te^{-0.05t}\,dt$', fontsize=13, fontweight='bold')
plt.legend(fontsize=10)
plt.tight_layout()
plt.savefig('figuras/fig_c06_partes_capital.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

## 📔 Capítulo 7 — La Integral Definida y sus Aplicaciones

### Teoría

La **integral definida** $\int_a^b f(x)\,dx$ es el límite de sumas de Riemann. El **Teorema Fundamental del Cálculo** conecta integración y diferenciación: $\int_a^b f(x)\,dx = F(b) - F(a)$.

---

### Ejemplo 7.1 — Convergencia de Sumas de Riemann: $f(x) = x^2$ en $[0,1]$

> $S_n = \sum_{i=1}^n \left(\frac{i}{n}\right)^2 \cdot \frac{1}{n} = \frac{(n+1)(2n+1)}{6n^2} \to \frac{1}{3}$.

```python
import numpy as np
import matplotlib.pyplot as plt

def riemann_derecho(n):
    x_i = np.arange(1, n+1) / n
    return np.sum(x_i**2) / n

n_vals = np.arange(1, 201)
S_n = [riemann_derecho(n) for n in n_vals]
exacto = 1/3

fig, axes = plt.subplots(1, 2, figsize=(14, 5))

for n, color in [(4, 'skyblue'), (20, 'steelblue')]:
    x_i = np.arange(1, n+1) / n
    ax = axes[0] if n == 4 else axes[1]
    x_curva = np.linspace(0, 1, 300)
    ax.plot(x_curva, x_curva**2, 'b-', linewidth=2.5, label=r'$f(x)=x^2$')
    for i in range(n):
        xi = i / n
        height = (xi + 1/n)**2
        rect = plt.Rectangle((xi, 0), 1/n, height, facecolor=color,
                              edgecolor='navy', alpha=0.7)
        ax.add_patch(rect)
    S = riemann_derecho(n)
    ax.set_title(f'$n={n}$ rectángulos — $S_n = {S:.4f}$\n(exacto $= 1/3 \\approx {exacto:.4f}$)',
                 fontsize=11, fontweight='bold')
    ax.set_xlabel('$x$'); ax.set_ylabel('$f(x) = x^2$')
    ax.legend(fontsize=10); ax.grid(True, alpha=0.3)
    ax.set_xlim(0, 1); ax.set_ylim(0, 1.1)

plt.suptitle('Convergencia de Sumas de Riemann (Extremos Derechos)', fontsize=13, fontweight='bold')
plt.tight_layout()
plt.savefig('figuras/fig_c07_riemann_convergencia.png', dpi=150, bbox_inches='tight')
plt.show()

# Gráfica de convergencia
plt.figure(figsize=(9, 5))
plt.plot(n_vals, S_n, 'b-', linewidth=1.5, label='$S_n$ (Riemann)')
plt.axhline(y=exacto, color='red', linestyle='--', linewidth=2,
            label=f'Valor exacto $= 1/3 \\approx {exacto:.4f}$')
plt.xlabel('Número de subintervalos $n$', fontsize=12)
plt.ylabel('$S_n$', fontsize=12)
plt.title('Convergencia de la Suma de Riemann hacia $\\int_0^1 x^2\\,dx = 1/3$',
          fontsize=12, fontweight='bold')
plt.legend(fontsize=10); plt.grid(True, alpha=0.3)
plt.tight_layout()
plt.savefig('figuras/fig_c07_riemann_convergencia2.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 7.2 — Área entre una Parábola y una Recta

> Área acotada por $f(x) = x^2 + 1$ y $g(x) = 2x + 4$ en $[-1, 3]$.  
> **Resultado:** $A = \frac{32}{3} \approx 10.667$.

```python
import numpy as np
import matplotlib.pyplot as plt
from scipy.integrate import quad

f = lambda x: x**2 + 1
g = lambda x: 2*x + 4
h = lambda x: g(x) - f(x)   # Diferencia

x = np.linspace(-2, 5, 400)
x_int = np.linspace(-1, 3, 300)  # Intervalo de integración
area, _ = quad(h, -1, 3)

plt.figure(figsize=(10, 6))
plt.plot(x, f(x), 'b-', linewidth=2.5, label=r'$f(x) = x^2+1$ (parábola)')
plt.plot(x, g(x), 'r-', linewidth=2.5, label=r'$g(x) = 2x+4$ (recta)')
plt.fill_between(x_int, f(x_int), g(x_int), alpha=0.35, color='green',
                 label=f'Área $= \\frac{{32}}{{3}} \\approx {area:.3f}$')
plt.scatter([-1, 3], [f(-1), f(3)], color='purple', s=150, zorder=5,
            label='Intersecciones $x=-1$ y $x=3$')
plt.annotate(f'$A = \\int_{{-1}}^3 [g-f]\\,dx = {area:.3f}$',
             xy=(1, 5), fontsize=11,
             bbox=dict(boxstyle='round', facecolor='lightgreen', alpha=0.8))
plt.grid(True, alpha=0.3)
plt.xlabel('$x$', fontsize=12); plt.ylabel('$y$', fontsize=12)
plt.title('Área entre una Parábola y una Recta', fontsize=13, fontweight='bold')
plt.legend(fontsize=10); plt.xlim(-2, 5); plt.ylim(-1, 15)
plt.tight_layout()
plt.savefig('figuras/fig_c07_area_parabola_recta.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 7.3 — Excedente del Consumidor y del Productor

> $D(Q) = 200 - 2Q$, $O(Q) = 20 + Q$. Equilibrio en $P^* = 80$, $Q^* = 60$.  
> **Resultados:** $EC = 3{,}600$, $EP = 1{,}800$, Bienestar total $= 5{,}400$.

```python
import numpy as np
import matplotlib.pyplot as plt
from scipy.integrate import quad

D = lambda Q: 200 - 2*Q    # Demanda
O = lambda Q: 20 + Q       # Oferta
P_eq, Q_eq = 80, 60

Q_range = np.linspace(0, 100, 400)

EC, _ = quad(lambda Q: D(Q) - P_eq, 0, Q_eq)
EP, _ = quad(lambda Q: P_eq - O(Q), 0, Q_eq)

fig, axes = plt.subplots(1, 2, figsize=(14, 6))

for ax, titulo, show_ec, show_ep in [
    (axes[0], 'Excedente del Consumidor', True, False),
    (axes[1], 'Excedente del Productor', False, True)
]:
    ax.plot(D(Q_range), Q_range, 'b-', linewidth=2.5, label=r'Demanda $P=200-2Q$')
    ax.plot(O(Q_range), Q_range, 'r-', linewidth=2.5, label=r'Oferta $P=20+Q$')
    ax.axhline(y=Q_eq, color='green', linestyle='--', alpha=0.5)
    ax.axvline(x=P_eq, color='green', linestyle='--', alpha=0.5)
    ax.scatter([P_eq], [Q_eq], color='green', s=180, zorder=5,
               label=f'Equilibrio $(P^*={P_eq}, Q^*={Q_eq})$')
    if show_ec:
        Q_fill = np.linspace(0, Q_eq, 300)
        ax.fill_betweenx(Q_fill, P_eq, D(Q_fill), alpha=0.35, color='blue',
                         label=f'EC = S/ {EC:,.0f}')
    if show_ep:
        Q_fill = np.linspace(0, Q_eq, 300)
        ax.fill_betweenx(Q_fill, O(Q_fill), P_eq, alpha=0.35, color='red',
                         label=f'EP = S/ {EP:,.0f}')
    ax.set_xlabel('Precio $P$', fontsize=11); ax.set_ylabel('Cantidad $Q$', fontsize=11)
    ax.set_title(titulo, fontsize=12, fontweight='bold')
    ax.legend(fontsize=9); ax.grid(True, alpha=0.3)
    ax.set_xlim(0, 210); ax.set_ylim(0, 100)

plt.suptitle(f'Bienestar Total = EC + EP = {EC+EP:,.0f} soles', fontsize=13, fontweight='bold')
plt.tight_layout()
plt.savefig('figuras/fig_c07_excedentes.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 7.4 — Valor Presente de Flujos Continuos

> Proyecto con flujo $R(t) = 50{,}000 + 2{,}000t$ soles/año durante 10 años, $r = 8\%$ continuo.  
> **Resultado:** $VP \approx S/\, 372{,}850$. VPN $= VP - 350{,}000 \approx S/\, 22{,}850 > 0$ ✔

```python
import numpy as np
import matplotlib.pyplot as plt
from scipy.integrate import quad

R = lambda t: 50000 + 2000 * t
r = 0.08
T = 10
R_desc = lambda t: R(t) * np.exp(-r * t)   # Flujo descontado

t = np.linspace(0, T, 400)
VP, _ = quad(R_desc, 0, T)
inversion = 350000
VPN = VP - inversion

print(f"Valor Presente (VP) = S/ {VP:,.2f}")
print(f"Inversión inicial   = S/ {inversion:,}")
print(f"VPN                 = S/ {VPN:,.2f}  → {'VIABLE ✔' if VPN>0 else 'NO viable ✗'}")

plt.figure(figsize=(10, 6))
plt.plot(t, R(t), 'b-', linewidth=2.5, label=r'Flujo: $R(t)=50{,}000+2{,}000t$')
plt.plot(t, R_desc(t), 'r--', linewidth=2.5, label=r'Flujo descontado: $R(t)e^{-0.08t}$')
plt.fill_between(t, 0, R_desc(t), alpha=0.3, color='red',
                 label=f'VP = S/ {VP:,.0f}')
plt.axhline(y=inversion/T, color='gray', linestyle=':', alpha=0.7,
            label=f'Inversión/año: S/ {inversion/T:,.0f}')
plt.grid(True, alpha=0.3)
plt.xlabel('Tiempo $t$ (años)', fontsize=12)
plt.ylabel('Flujo de caja (soles/año)', fontsize=12)
plt.title(f'Valor Presente de Flujo Continuo Creciente\nVP = S/ {VP:,.0f}  |  VPN = S/ {VPN:,.0f}',
          fontsize=12, fontweight='bold')
plt.legend(fontsize=10)
plt.tight_layout()
plt.savefig('figuras/fig_c07_valor_presente.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 7.5 — Integral Impropia: Valor Presente a Perpetuidad

> $VP = \int_0^\infty R \cdot e^{-rt}\,dt = \frac{R}{r}$.  
> Con $R = 5{,}000$ soles/año y $r = 0.05$: $VP = S/\, 100{,}000$.

```python
import numpy as np
import matplotlib.pyplot as plt
from scipy.integrate import quad

R_constante = 5000
r = 0.05

f = lambda t: R_constante * np.exp(-r * t)
T_vals = [10, 20, 50, 100, 500]
VP_parcial = [quad(f, 0, T)[0] for T in T_vals]
VP_exacto = R_constante / r

t = np.linspace(0, 120, 500)

fig, axes = plt.subplots(1, 2, figsize=(14, 6))

axes[0].plot(t, f(t), 'b-', linewidth=2.5, label=r'$R(t) = 5000\,e^{-0.05t}$')
axes[0].fill_between(t, 0, f(t), alpha=0.3, color='blue',
                     label=f'VP total = S/ {VP_exacto:,.0f}')
axes[0].set_xlabel('Tiempo $t$ (años)'); axes[0].set_ylabel('Flujo descontado (soles/año)')
axes[0].set_title('Flujo de Caja Descontado a Perpetuidad', fontsize=12, fontweight='bold')
axes[0].legend(fontsize=10); axes[0].grid(True, alpha=0.3)

axes[1].semilogx(T_vals, VP_parcial, 'ro-', linewidth=2, markersize=10, label='$VP(0,T)$')
axes[1].axhline(y=VP_exacto, color='blue', linestyle='--', linewidth=2,
                label=f'$VP(\\infty) = R/r = S/\\, {VP_exacto:,.0f}$')
for T, vp in zip(T_vals, VP_parcial):
    axes[1].annotate(f'{vp/VP_exacto*100:.0f}%', xy=(T, vp), xytext=(T, vp-3000),
                     fontsize=9, ha='center')
axes[1].set_xlabel('Horizonte $T$ (escala logarítmica)'); axes[1].set_ylabel('Valor Presente acumulado')
axes[1].set_title('Convergencia del VP hacia la Perpetuidad', fontsize=12, fontweight='bold')
axes[1].legend(fontsize=10); axes[1].grid(True, alpha=0.3)

plt.suptitle(r'Integral Impropia: $VP = \int_0^\infty R e^{-rt}dt = R/r$',
             fontsize=13, fontweight='bold')
plt.tight_layout()
plt.savefig('figuras/fig_c07_perpetuidad.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

### Ejemplo 7.6 — Teorema del Valor Medio Integral: Costo Promedio

> $C(x) = x^2 + 4x + 10$ en $[2, 8]$. Encontrar el costo promedio $\bar{C}$.
> **Resultado:** $\bar{C} = \frac{1}{6}\int_2^8 C(x)\,dx = \frac{1}{6} \cdot [...]$

```python
import numpy as np
import matplotlib.pyplot as plt
from scipy.integrate import quad
from scipy.optimize import brentq

C = lambda x: x**2 + 4*x + 10
a, b = 2, 8
integral, _ = quad(C, a, b)
C_prom = integral / (b - a)

# Encontrar c donde C(c) = C_prom
c_val = brentq(lambda x: C(x) - C_prom, a, b)

x = np.linspace(0, 10, 400)
x_int = np.linspace(a, b, 300)

plt.figure(figsize=(10, 6))
plt.plot(x, C(x), 'b-', linewidth=2.5, label=r'$C(x) = x^2+4x+10$')
plt.fill_between(x_int, 0, C(x_int), alpha=0.2, color='blue',
                 label=f'Integral = {integral:.2f}')
plt.axhline(y=C_prom, color='red', linestyle='--', linewidth=2,
            label=f'Costo promedio $\\bar{{C}} = {C_prom:.2f}$')
plt.fill_between(x_int, 0, C_prom, alpha=0.2, color='red',
                 label=f'Rectángulo equivalente (área = {integral:.2f})')
plt.scatter([c_val], [C(c_val)], color='green', s=180, zorder=5,
            label=f'TVM: $C(c) = \\bar{{C}}$ en $c={c_val:.2f}$')
plt.annotate(f'$c = {c_val:.2f}$', xy=(c_val, C(c_val)),
             xytext=(c_val+0.5, C(c_val)+10), fontsize=10,
             arrowprops=dict(arrowstyle='->', color='green'))
plt.grid(True, alpha=0.3)
plt.xlabel('Producción $x$ (unidades)', fontsize=12)
plt.ylabel('Costo $C(x)$ (soles)', fontsize=12)
plt.title('Teorema del Valor Medio Integral — Costo Promedio', fontsize=13, fontweight='bold')
plt.legend(fontsize=10); plt.xlim(0, 10); plt.ylim(0, 100)
plt.tight_layout()
plt.savefig('figuras/fig_c07_valor_medio_costo.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

## 🎨 Convención de Estilo Gráfico

Todos los notebooks de este repositorio siguen la convención estética mostrada a continuación para garantizar visualizaciones uniformes y profesionales:

```python
import numpy as np
import matplotlib.pyplot as plt

# ── Parámetros de estilo globales (añadir al inicio de cada notebook) ──
plt.rcParams.update({
    'figure.dpi'        : 150,
    'figure.facecolor'  : 'white',
    'axes.facecolor'    : 'white',
    'axes.grid'         : True,
    'grid.alpha'        : 0.3,
    'axes.spines.top'   : False,
    'axes.spines.right' : False,
    'font.size'         : 11,
    'axes.titlesize'    : 13,
    'axes.labelsize'    : 12,
    'legend.fontsize'   : 10,
    'lines.linewidth'   : 2.5,
})

# ── Paleta de colores del libro ──
AZUL   = '#1E64B4'   # Curva principal / función exacta
ROJO   = '#C0392B'   # Aproximación / derivada
VERDE  = '#27AE60'   # Punto de equilibrio / solución
NARANJA = '#E67E22'  # Zona de pérdida / advertencia
GRIS   = '#7F8C8D'   # Asíntotas, referencias

# ── Template de figura (una sola gráfica) ──
fig, ax = plt.subplots(figsize=(10, 6))
ax.set_xlabel('Variable independiente', fontsize=12)
ax.set_ylabel('Variable dependiente', fontsize=12)
ax.set_title('Título del Ejemplo', fontsize=14, fontweight='bold')
ax.legend()
plt.tight_layout()
plt.savefig('figuras/fig_cap_nombre.png', dpi=150, bbox_inches='tight')
plt.show()
```

---

## 📚 Referencias

- Libro principal: *Matemática para los Negocios* (2026).  
- Stewart, J. (2016). *Cálculo de una Variable*. Cengage Learning.  
- Chiang, A. & Wainwright, K. (2006). *Métodos Fundamentales de Economía Matemática*. McGraw-Hill.  
- Simon, C. & Blume, L. (1994). *Mathematics for Economists*. W. W. Norton.

---

<p align="center">
  Desarrollado con ❤️ para estudiantes de Ciencias Económicas y Empresariales  
  <br>
  <i>«El cálculo es la gramática de la ciencia.» — Bertrand Russell</i>
</p>
