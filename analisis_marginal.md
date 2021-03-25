# Analisis Marginal

### Enfoque tradicional
Ganancia Unitaria = Precio de Venta - Costo Unitario

<img src="https://render.githubusercontent.com/render/math?math=p_i">: precio de venta
<img src="https://render.githubusercontent.com/render/math?math=w_i">: costo variable unitario
- materia prima
- envases
- mano de obra
- gasto general de fabricacion
  - combustible
  - electricidad
  - regalias
- gasto general administracion comercializacion finanzas
  - comisiones de vendedores
  - impuestos
  - fletes
<img src="https://render.githubusercontent.com/render/math?math=Q_i">: volumen fisico de ventas
<img src="https://render.githubusercontent.com/render/math?math=F_i">: gastos fijos propios
no varian al variar el nivel de actividad
- alquiler
- publicidad
- cambio de estructura

gastos fijos
- ggf
  - sueldos no jornalizados
  - mdo indirecta
  - amortizaciones
  - seguros
  - gastos de mantenimiento
- ggacf
  - sueldos
    - telefono, luz
    - publicidad
    - alquiler

estos valores se definen para un periodo dado
son independientes entre si



### ventas de un producto
<img src="https://render.githubusercontent.com/render/math?math=V_i = p_i * Q_i">

### ventas para toda la empresa
<img src="https://render.githubusercontent.com/render/math?math=V = \sum_{i=1}^{n} V_i">


<img src="https://render.githubusercontent.com/render/math?math=w'_i"> : coeficiente de costo proporcional a los volumenes de ventas

<img src="https://render.githubusercontent.com/render/math?math=s_i">: coef de costo proporcional a la venta del producto

<img src="https://render.githubusercontent.com/render/math?math=J"> : coef de costo proporcional a las utilidades

### Costo total
<img src="https://render.githubusercontent.com/render/math?math=C = F + \sum_{i=1}^{n} w'_i Q_i + \sum_{i=1}^{n} s_i V_i">


### Utilidades operativas

U = V - C = \sum_{i=1}^{n} p_i Q_i - F - \sum_{i=1}^{n} w'_i Q_i - \sum_{i=1}^{n} s_i V_i

### Utilidades antes de impuestos

U_A = U + R

### Utilidad Neta

N = U_A - J U_A = (1-J)U_A

### Ecuacion fundamental
w_i = w'_i + s_i p_i
U = \sum^{n} (p_i-w_i)Q_i-F

### Utilidad marginal unitaria de un producto

e_i = p_i - w_i

U = \sum^n e_i Q_i - F


incremento de las utilidades de la empresa cuando se vende una unidad adicional
del producto

### Utilidad marginal de un producto

E_i = e_i Q_i = p_i Q_i - w_i Q_i = V_i W_i

V_i: ventas del producto
W_i: costo variable del producto


### Tasa de utilidad marginal del producto

m_i = \frac{e_i}{p_i}

Aumento de la utilidad por cada peso adicional vendido de un producto, siempre
que esa venta adicional se realice a precio constante, es decir que se realice
por variación de volumen.

Si la tasa m_i = 38 %, por cada 100$ adicionales vendidos del producto, se ganan
38$, siempre que esas ventas adicionales estén dadas por un incremento del
volumen físico, no por incremento de precio.

### Tasa de utilidad marginal de la empresa

m = \frac{E}{V}

E: utilidad marginal de la empresa
U = E - F

Aumento de la utilidad por cada peso adicional vendido, siempre que esa venta
adicional se realice a precio constante, es decir que se realice por variación
de volumen.


### Tasa de contribucion marginal de la emrpesa

m_{emp} = \frac{m_1 V_1 + m_2 V_2 + m_3 V_3}{V_1 V_2 V_3}

### Ecuacion de la empresa

utilidad incremental

\Delta U = V_1 \Delta p_1 + V_2 \Delta p_2 + E_1 \Delta Q_1 + E_2 \Delta Q_2 -
W_1 \Delta w_1 - W_2 \Delta w_w - F \Delta F

## Graficos

### equilibrio de un producto


### equilibrio unitario de un producto

u_i = p_i - c_i = p_i - w_i + \frac{F_i+F_e_i}{Q_i}

### equilibrio de la empresa


## Aplicaciones

### calidad de ventas

la tasa m mide la calidad de ventas

### costeo marginal

Un producto puede ser vendido por debajo del costo unitario y sin embargo estar
aportando positivamente a la utilidad marginal


### precio optimo

precio que maximiza la utilidad marginal aportada por el producto


### introduccion de un projecto

es viable si incrementa las utilidades

\Delta U = (p_n - w_n) Q_n - \Delta F_{n} > 0

el producto puede ser
- complementario
- sustitutivo

### eliminacion de un producto

conviene
1. si la utilidad marginal aportada por el producto es menor que los gastos
   fijos propios del producto

   E_i < F_i

  (p_i - w_i)Q_i < F_i

2. cuando absorbe algun insumo de MP o MOD critico
3. cuando se reemplace por otro prducto que sea mayor a E
4. cuando la inversion que se necesite para producir sea elevada o utilice
   activos que con otro producto tengan mayor rendimiento.

### eliminacion de un sucursal

el precio de compra debe ser inferior al costo variable de la fabricacion

p_i c_i < w'_i



# Matematica financiera

Capitalizacion: Incorporar los intereses devengados al capital inicial C

## Interes Simple

M = C + I = C + i * C * t = C * (1 + i * n)

VF = VA (1 + i * n)

n: cantidad de veces que se calcula el interes sobre el mismo capital C

i = i_N : tasa de interes

i_N : tasa nominal

i_p: tasa proporcional

i_p = i_N / n

## Interes Compuesto

al vencimientose reinvierte el Capital inicial + Intereses

VF = VA (1 + i)^n

n: cantidad de periodos de capitalizacion
m: cantidad de capitalizaciones por año
t: tiempo en años
n = mt

## Tasa Efectiva

tasa que capitaliza un solo periodo

TEA = (1+TNA/m)^m-1

## Tasa Real

f: tasa de inflacion

(1+i_{real}) = \frac{1+TEA}{1+f}

## Descuento Simple

Anticipo = Valor Nominal (1 - d * t)

Descuento = Valor Nominal * d * t

d: tasa de descuento

t: tiempo hasta el vencimiento del descuento

## Equivalencia entre i y d (tasa vencida y tasa adelantada) (tasa de interes y tasa de descuento) en descuento simple

i = \frac{d}{1 - d * t}

d = \frac{i}{1 + i * t}


## Descuento Compuesto

calculado para el periodo n

Anticipo_n = Valor Nominal (1 - d)^n


## Equivalencia entre i y d (tasa vencida y tasa adelantada) (tasa de interes y tasa de descuento) en descuento compuesto

i = \frac{d}{1 - d}

d = \frac{i}{1 + i}

## Renta

R: cuota (puede ser o no constante)

cuota 
- imposicion: cuando el objetivo es formar un capital
- amortizacion: cuando el objetivo es la extincion de la deuda

### Valor Actual de renta de pagos vencidos

VA = R (\frac{(1+i)^n-1}{i(1+i)^n})

R: cuota

la primer cuota se paga un periodo luego de comenzar la renta

### VA de renta de pagos anticipados

VA = R \frac{(1+i)^n-1}{i(1+i)^{n-1}}

la primer cuota se paga en el mismo periodo en que se comienza la renta

### Monto de renta de pagos vencidos

VF_{acum} = R \frac{(1+i)^n-1}{i}

### Monto de renta de pagos anticipados

VF_{acum} = R \frac{(1+i)-1}{i}(1+i)

## Amortizacion de prestamos

proceso en el cual se extingue la deuda

la cuota de amortizacion es el valor que se devuelve del prestamo

|periodo|Cuota a = Intereses + Cuota Amortizativa |Intereses|Cuota Amortizativa|Saldo o capital pendiente|

### Sistema Frances

La cuota que se paga al finalizado un periodo es constante

varian los intereses del periodo y la cuota de amortizacion

los intereses del periodo n se calculan sobre el saldo que se debe del periodo anterior n-1

la cuota de amortiacion es igual a los intereses + la cuota que se paga

se recibe el prestamo P en el periodo 0, en los periodos siguientes se paga la cuota R

R = P \frac{i(1+i)^n}{(1+i)^n-1}

R = I_j + A_j

I_j: interes de la deuda
A_j = A_1(1+i)^{j-1}

I_j = C_{j-1} * i

en este sistema, es constante


### Sistema Aleman

el prestamo P se devuelve en n amortizaciones constantes iguales R = P/n.

el interes se calcula sobre el saldo del periodo anterior por la tasa de interes

intereses pagados por periodo vencido
R_m = P / n + (p - \frac{P (m-1)}{n}) i

intereses pagados por periodo adelantado
R_m = P / n + (p - \frac{P m}{n}) i para m \neq 0

### Sistema Americano

1. al final de cada periodo se paga el interes simple de la deuda total
2. se depositan al final de cada periodo sumas constantes, que capitalizadas a interes compuesto, forman al final un capital igual a la deuda
3. al final del utlimo periodo se paga la totalidad de la deuda con el capital acumulado

intereses constantes

I_i = C_{i-1} * i


### Interes directo

R = P / n + i * P

### 
### 
### 

# Evaluacion de proyectos

## flujo de fondos descontados

### VAN - Valor Actual Neto
1. listar ingresos y egresos de caja la Vida util periodo por periodo
2. flujo de fondos neto periodo por periodo
3. Actualizar el Flujo de Fondos neto de acuerdo a la tasa elegida t

VAN = \sum^{n} \frac{I_i-E_i}{(1+t)^{i}}

los ingresos previstos, procedentes de la inversión inicial, son suficientes
para devolver el capital más los intereses de un préstamo a la tasa elegida t
anual, esta devolución sería en n cuotas anuales fijas.

O sea que la empresa podría haber tomado prestado C_0+Intereses, aplicado C_0 $
a la inversión e inmediatamente distribuir los Intereses restantes como ingresos
a los propietarios de la empresa; los ingresos de X$ por año procedentes de C_0
de la inversión bastarían para devolver el préstamo más los intereses a la tasa
t anual.

X son las cuotas del prestamo

- Reconoce explícitamente el VTD
- como los datos son FF se elimina la influencia de factores arbitrarios excepto
  en la determinación de los impuestos directos. Un proyecto con un FF
  determinado tiene, para una tasa dada, un solo VA.
- da indicación sobre la magnitud del beneficio que se obtiene de la inversión,
  lo que no sucede con la TIR. En el caso de tener que decidir sobre 2
  inversiones excluyentes, una de las cuales tiene una TIR = 50% sobre una
  inversión de 10 $ y otra que tiene una TIR = 30% sobre una inversión de 10.000
  $, el sistema de la tasa interna señalará la primera como más conveniente sin
  considerar la magnitud del ingreso que se obtiene en cada uno de los casos.

- No da indicación sobre el rendimiento que se obtiene de la inversión. Un mismo
  VA de 100 $ puede provenir de una inversión de 10 $ o de una inversión de
  10.000 $
- su comprensión no es inmediata, sino que requiere conocer el sistema y los
  conceptos que involucra (interés compuesto y VA de una suma futura).
- el control de los resultados reales que se obtengan de la inversión es
  dificultoso. Dado que no responde a registros contables, requiere un análisis
  laborioso

### TIR - Tasa Interna de Retorno

hace que VAN sea 0


- reconoce el VTD (dinero en futuro cercano vale + que en futuro lejano) ( Valor
  Tiempo del Dinero)
- como los datos son FF se elimina la influencia de factores arbitrarios
- la TIR es comparable directamente con el costo del capital de la empresa o con
  el interés del dinero vigente en el mercado

- presupone que los fondos ingresados se reinvierten a la tasa del proyecto
- la comprensión no es inmediata
- el resultado es laborioso

### Periodo de Recuperacion

El período de recuperación es el lapso en el cual el VA de los egresos E es
recuperado a través del VA de los ingresos I, a un tipo de interés i. El
período de recuperación t será aquel valor que satisfaga la ecuación:

\sum_{j=0}^{n} \frac{E_j}{(1+i)^j} = \sum_{j=0}^{t} \frac{I_j}{(1+i)^j}

n: cantidad de periodos a tener en cuenta

- reconoce el VTD
- como los datos son FF se elimina la influencia de factores arbitrarios excepto
  en la determinación de los impuestos directos. Un proyecto con un FF
  determinado tiene, para una tasa dada, un solo VA.
- indica durante cuanto tiempo se arriesga el dinero invertido
- constituye una evaluación muy útil cuando, debido a inestabilidad o
  incertidumbre, resulta dificultoso pronosticar resultados para años lejanos

- no da indicación acerca de los ingresos obtenidos una vez terminado el período
  de reembolso
- no da indicación sobre la magnitud del beneficio que se obtiene de la inversión
- no da indicación respecto del rendimiento que se obtiene de la inversión

## consideraciones

## casos especiales

1. Cuando es diferente la duración de los equipos de cada proyecto
2. Cuando es distinto el monto de la inversión de cada proyecto
3. Caso en que el método de la tasa interna y el VA discrepan
4. Evaluación de desinversiones (según criterios de RMg, TIR y VA)








# flujo de fondos
El Flujo de Fondos es la registración de todos los movimientos de egresos e
ingresos EN EFECTIVO en el momento que se producen

No incluyen conceptos de pagos/ventas a crédito, ni devengados de ninguna
naturaleza.

Generalmente en la Evaluación Económica de Proyectos de Inversión el Flujo de
Fondos es siempre ex-ante.

1. Determinar el monto de la inversión que requiere la puesta en marcha del
   proyecto.
2. Estimar la secuencia temporal en la cual se integrará esa inversión.
3. Constituir el elemento de análisis donde se aplican los índices y
   metodologías de evaluación y comparación de proyectos.

| Periodo                                         | 0 | 1 | 2 | n |
| Ingresos Marginales                             |   | X | X | X |
| Venta de activos del proyecto al Valor Residual |   |   |   | X |
| Venta de Capital de Trabajo al Valor Residual   |   |   |   | X |
| Total Ingresos                                  |   | X | X | X |
|-------------------------------------------------+---+---+---+---|
| Egresos Marginales                              |   | X | X | X |
| Compra de Activos                               | X |   |   |   |
| Capital de Trabajo                              | X |   |   |   |
| Impuestos (su valor marginal)                   | X | X | X | X |
| Total Egresos                                   | X | X | X | X |
|-------------------------------------------------+---+---+---+---|
| Resultado del Flujo de Fondos                   | X | X | X | X |


# Capital de Trabajo = Fondo de Maniobra

K_T = Activo_{corriente} - Pasivo_{corriente}

K_T = Patrimonio Neto + Pasivo_{no corriente} - Activo_{no corriente}


# indices

## nivel de riesgo

### periodo de recuperacion

cantidad de periodos + resultado neto acumulado / resultado neto del periodo

### periodo de recuperacion con actualizacion
### Maxima exposicion

Es el máximo valor negativo acumulado del flujo de fondos

### IVA Indice de valor actual

IVA = VAN / ME

ME: Maxima exposicion actualizado con la tasa i

beneficio de x$ por cada $1 arriesgado


## rentabilidad

tasa de acutalizacion i


### VAN Valor Actual Neto

VF = VA (1+i)^{n}

para una sucecion de valores futuros, el valor actual de la sucecion se lo llama valor actual neto y es:

VAN = VF_0 + VF_1 / (1+i) + VF_2 / (1+i)^2 + ... + VF_n / (1+i)^n

### TIR
### IVA 

# EPI
## Moneda constante
- Bajos niveles de inflación y/o
- Horizontes de análisis no muy largos (menos de 2 años) y/o
- No se preveen distorsiones PRECIOS/COSTOS relativos entre
  los distintos componentes de INGRESOS / EGRESOS

(1 + i_{real}) = (1 + I_{Costo Dinero})  / (1 + F_{inflacion})

# Marketing

## analisis

### 5C (estrategico)
- clientes: Qué necesidades satisfacemos?
  - varios tipos de clientes
- compañia: Qué fortalezas y debilidades tenemos?
  - mision
  - vision
  - foda
- competencia: Con quiénes competimos?
  - foda
  - tipo de mercado
    - muchos competidores o no
- colaboradores: Con quiénes colaboramos?
- contexto: Cuál es el contexto? (Cultural / Legal / Límites tecnológicos)

### 4P (operativo)
- producto: cuál es mi producto?
- plaza: dónde se podrá encontrar?
  - directo
  - corto
  - largo
  - distribuidor
- promocion: cómo llegará a conocerse?
  - avobe the line
  - below the line
  - vapor marketing
- precio: cuánto costará?

ciclo de vida del producto

diseño
introduccion
crecimiento
madurez
declinacion

matriz bcg (vaca perro estrella incognita)

### 7P (de retencion)
4P + 
- personas
- entorno
- procesos



## segmentacion de mercado
Un segmento es un grupo de consumidores que debe responder de forma similar a un conjunto determinado de esfuerzos de marketing

un segmento debe ser;
- medible
- accesible
- sustancial: de dimension adecuada
- homogeneo: facil de indentificar y con caracteristicas comunes

segmentacion:
- ingresos
- region
- conducta

## oferta demanda

Cantidad Demandada: Es la cantidad de un bien que los compradores quieren y pueden comprar.

Ley de la Demanda:  Manteniendo todo lo demás constante, la cantidad demandada de un bien disminuye cuando sube su precio.


Cantidad ofertada: Es la cantidad de un bien que los vendedores quieren y pueden vender.

Ley de la Oferta:  Manteniendo todo lo demás constante, la cantidad ofrecida de un bien aumenta cuando sube su precio.


# Costos
## std

nivel de actividad: si el centro productivo interviene en la fabricacion de varios productos, estos se tienen en cuenta para calcular el nivel de actividad del centro.

alfa, beta: si un producto pasa por varios centros productivos, a la hora de calcular los GGF (fijos y/o variables), se tienen en cuenta los alfa o beta de los centros que intervienen. Cada alfa o beta va multiplicado por el std de MOD del centro para el producto en cuestion

### por absorcion
costo unitario = MP_{std} * std_{MP} + MOD_{std} * std_{MOD} + GGFTot_{prop+prorr} * std_{MOD}

MP_{std}: cantidad de MP std utilizada para el producto en cuestion
std_{MP}: costo std de MP
MOD_{std}: cantidad de MOD std utilizada para el prod
std_{MOD}: costo std de MOD
GGFTot_{prop+prorr}: BETA, gastos fijos y variables std, propios y prorrateados divido el nivel de actividad utilizado por el Centro productivo que interviene en la produccion del producto en cuestion


### directo
costo unitario = MP_{std} * std_{MP} + MOD_{std} * std_{MOD} + GGFV_{prop+prorr} * std_{MOD}

GGFV_{prop+prorr}: ALFA, gastos vatriables std

## ABC

Activity based costing

asignar costos segun consumo de recursos

balde de costos de actividad, cada actividad tiene su valde de costos

1. identificar y definir actividades (y sus pools) y desarrollar un diccionario de actividades
2. tracear, rastrear, asignar costos a actividades
3. calcular cuotas de actividades
4. asignar costos a objetos de costos
5. informar


ej:
actividades
- procesar unidades en maq
- procesar unidades en mano
- preparar equipos
- manejar materiales
- diseño de productos
- construccion de planta

# Finanzas

# Contabilidad      

financiero
- liquidez
- efectivo disponible de inmediato

economico
- solvencia
- conjunto de bienes del patrimonio
