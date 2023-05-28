---
title: Топлинни машини
categories: [Physics]
tags: [gas, thermodynamics, applied]
math: true
mermaid: true
---

# 1. Топлинна машина - машина, извършваща механична работа чрез топлинен трансфер

# 2. Цикъл на Карно

# 3. Устройство на топлинна машина

stateDiagram
    Нагревател --> Газ: Qₜ
    Газ --> Охладител: Q꜀
    Газ --> А

- Коефициент на Полезно Действие (КПД) - $$\eta$$

$$
А = Q_T - Q_C
\eta = \frac{A}{Q_T} = \frac{Q_T - Q_C}{Q_T} = \left(1 - \frac{Q_C}{Q_T}\right) %
$$

> КПД е винаги по-малко от 100%
{: .prompt-warning }
