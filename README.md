# 🚴 EcoRider – Sistema de Alquiler de Bicicletas

EcoRider es una aplicación de consola en **Python** para gestionar el alquiler de bicicletas, calcular costos y aplicar descuentos/recargos según reglas del negocio.

---

## 🔧 Funcionalidades Principales

- Alquilar bicicletas (Estandar o Premium)
- Registrar múltiples alquileres antes del pago
- Consultar tarifas
- Calcular total con descuentos y recargos
- Validaciones para evitar errores del usuario
- Proceso de pago completo (incluye penalizaciones)

---

## 💵 Tarifas y Reglas

### Tarifas por minuto
| Tipo | Precio |
|------|--------|
| Estandar | 200$ |
| Premium  | 500$ |

### Descuentos
- 10% si → tiempo ≥ 60 min **y** pago con tarjeta  
- 15% si → pago con puntos **y** tiempo ≥ 10 min

### Recargos
- 5% fin de semana/feriado  
- 5000$ por retraso

---

## 🧩 Flujo del Sistema

1. **Alquilar bicicleta** (tipo + minutos)  
2. **Consultar tarifas**  
3. **Pagar**: suma total, aplica descuentos/recargos, muestra total final  
4. **Salir**

---

#**Developed by:**
##**Julian Aponte, Andres hidrobo, Mateo Martinez, Faiber Camacho**
