# Corrección parcial primer corte

## 1.

$$x''+4x=5$$
$$x(0)=5 \ x'(0)=0$$
$$s^2x(s)-5s+4x(s)=\frac{5}{s}$$
$$x(s)(s^2+4=\frac{5}{s}+5s$$
$$x(s)=\frac{\frac{5}{s}+5s}{s^2+4}$$
$$s^2+4=0 \qquad s=\sqrt{-4}$$
$$x(s)=\frac{5+5s^2}{s(s^2+4)}=\frac{A}{s}+\frac{Bs+D}{s^2+4}$$
$$A(s^2+4)+Bs^2+Ds=5+5s^2$$
$$A+B=5$$
$$D=0 \qquad B=\frac{15}{4} \qquad A=\frac{5}{4}$$
$$\mathscr{L}^{-1} \left\lbrace x(s) \right\rbrace =\frac{5}{4}+\frac{15}{4}Cos(2t)$$


# SISTEMAS MECÁNICOS

$$Tasa \quad de \quad acumulación \frac{Masa}{Energía}=Flujo \quad de \frac{Masa}{Energía} Entrada - Flujo \quad de \frac{Masa}{Energía} Salida$$

### Resorte
Se asumen resortes lineales, la fuerza externa aplicada y el desplazamiento están relacionados por una constante de proporcionalidad.


![Gráfica de curva de resortes](https://blog.federnshop.com/wp-content/uploads/Federkennlinien_600px.jpg)

Figura 1. Representación de resortes, comportamiento de elongación contra fuerza aplicada.

![Ley de hook y formula de resortes](https://www.fisicalab.com/sites/all/files/contenidos/leyesnewton/fuerza-aplicada-sobre-muelle_0.png)

Figura 1. Ley de Hook y formula de resorte.

$$F=kx=K(x_{1}-x_{2})$$

### Amortiguador
Este tiene un comportamiento lineal, el cual es proporcional a la velocidad de desplazamiento del pistón dentro del cilindro.

Figura 3. Respresentación de amortiguador, comportamiento en su cambio de estado

El amortiguador aparte de llevar el analisis de cambio de posición en su carga, se ve afectado por una constante de fricción viscosa que representa la relación de la velocidad en este cambio de posición.
 
$$F=bx'=b(x'_{1}x'_{2}$$
Este mismo principio es utilizado para representar la fricción entre una masa y una superficie.

## Tipos de Fricción

### Fricción en seco
Es aquella que se presenta cuando un cuerpo con una superficie no lubricada se desliza sobre otra superficie no lubricada.
•Fricción estática
•Fricción por deslizamiento
•Fricción por rodamiento

Figura 4. Diagrama de cuerpo libre de una masa experimentado un momento de aceleración haciendo enfoque en las fricciones que experimenta en este fenomeno.

### Fricción por rodamiento
Esta fricción en es relativamente tolerante con el movimiento; ya que el par de fricción es muy pequeño, este se ubica especificamente entre las camisas internas y externas de un rodamiento donde se encuentran las esferas que de forma tangencial y sumado al lubricante con el que cuenten absorven toda la fricción entre las masas.


Diagrama de fuerzas de un rodamiento

Figura 5. Diagrama de cuerpo libre de un rodamiento.


## SISTEMAS MECÁNICOS - MASA-RESORTE-AMORTIGUADOR
Estos sistemas un conjunto de fenomenos físicos representados por los siguientes teoremas:
𝐹𝑅 = 𝑘2 ∗ 𝑥 → 𝐿𝑒𝑦 𝑑𝑒 𝐻𝑜𝑜𝑘𝑒
𝐹𝐹 = 𝑘1 ∗ 𝑣𝑚 → 𝐹𝑟𝑖𝑐𝑐𝑖ó𝑛 𝑣𝑖𝑠𝑐𝑜𝑠𝑎
𝐹 = 𝑚 ∗ 𝑎 → 𝐿𝑒𝑦𝑒𝑠 𝑑𝑒 𝑁𝑒𝑤𝑡𝑜𝑛









Figura 6.

Diagrama de cuerpo libre de masa



Análisis y planteamiento de ecuaciones de fuerzas:






💡**Ejemplo 1:**

## Vibración libre
•Aún aplicando entrada durante un intervalo de tiempo definido es posible provocar un comportamiento oscilatorio en la variable de salida del sistema
•Por ejemplo, en el caso de la suspensión si se aplica una fuerza constante durante un intervalo corto de tiempo y se retira dicho estímulo el sistema tiende a vibrar
•Este movimiento periódico se conoce como vibración libre

 Simular la solución de este sistema teniendo en cuenta que si se suben al carro 2 personas que en promedio pesan 80Kg y los siguientes valores.
• 𝑘 = 22500 𝑁𝑚
• 𝑏 = 2000 𝑁𝑠𝑚
• 𝑀 = 300 𝐾𝑔

💡**Aplicado al "Ejemplo 1":**



## SISTEMAS MECÁNICOS MÁS COMPLEJOS

Estos sistemas normalmente se pueden apreciar como sistemas mecánicos combinados donde las fuerzas se intercambian entre otras masas mediante apoyos solidos o dinamicos como lo son resortes o amortiguadores.

💡**Ejemplo 1:**

# Sistemas Rotacionales
Es un fenómeno mecánico pero la naturaleza del movimeinto cambia, ahora es movimiento angular.
Aplican leyes comparables al movimiento lineal
𝐹𝑅 = 𝑘 ∗ 𝜑 → 𝜑 𝑒𝑠 𝑎𝑛𝑔𝑢𝑙𝑜 𝑑𝑒 𝑡𝑜𝑟𝑠𝑖ó𝑛
𝐹𝐹 = 𝑏 ∗ 𝑑𝜑 / 𝑑𝑡 → 𝑑𝜑 / 𝑑𝑡   𝑒𝑠 𝑙𝑎 𝑣𝑒𝑙𝑜𝑐𝑖𝑑𝑎𝑑 𝑎𝑛𝑔𝑢𝑙𝑎𝑟
𝑇 = 𝐽 ∗ 𝑑𝜑2 /𝑑𝑡2 → 𝐽 𝑒𝑠 𝑒𝑙 𝑚𝑜𝑚𝑒𝑛𝑡𝑜 𝑑𝑒 𝑖𝑛𝑒𝑟𝑐𝑖𝑎



Figura 7. Sistema rotacional 

Diagrama de cuerpo libre

𝑇 − 𝐹𝑅 − 𝐹𝐹 = 𝐽 ∗ 𝛼 → 𝛼 𝑎𝑐𝑒𝑙𝑒𝑟𝑎𝑐𝑖ó𝑛 𝑎𝑛𝑔𝑢𝑙𝑎𝑟
𝑇 𝑡 − 𝐹𝐹 = 𝐽 ∗ 𝛼 → 𝛼 𝑎𝑐𝑒𝑙𝑒𝑟𝑎𝑐𝑖ó𝑛 𝑎𝑛𝑔𝑢𝑙𝑎𝑟
𝑇 𝑡 − 𝑘 ∗ 𝜃 𝑡 − 𝑏 ∗ 𝑑𝜃(𝑡)/𝑑𝑡 = 𝐽 ∗ 𝑑_{2}𝜃(𝑡)/𝑑𝑡_{2}

Análisis de fuerzas y planteamiento de ecuaciones



•Desarrollar un modelo para describer la posición angular de un sistema rocacional si el eje es rígido.


## GRADOS DE LIBERTAD

•Es el número mínimo de coordenadas independientes requeridas para especificar las posiciones de todos sus elementos
•Por ejemplo: en el caso del sistema de suspensión solo se necesita una coordenada (eje vertical) para especificar la posición, por lo tanto, es un sistema de un grado de libertad
•Desde el punto de vista del modelo es posible decir:
𝐷𝑂𝐹 = 𝑁ú𝑚𝑒𝑟𝑜 𝑒𝑐𝑢𝑎𝑐𝑖𝑜𝑛𝑒𝑠 𝑑𝑒 𝑚𝑜𝑣𝑖𝑚𝑖𝑒𝑛𝑡𝑜 − 𝑁ú𝑚𝑒𝑟𝑜 𝑒𝑐𝑢𝑎𝑐𝑖𝑜𝑛𝑒𝑠 𝑟𝑒𝑠𝑡𝑟𝑖𝑐𝑐𝑖ó𝑛


SOLUCIONAR LOS 3 EJEMPLOS PLANTEADOS


# SISTEMAS MECÁNICOS - TRABAJO, ENERGÍA Y POTENCIA
## Trabajo
>🔑 *Trabajo:* es una medida de la realización del esfuerzo (fuerza)
## Energía
>🔑 *Energía:* Capacidad para realizar y trabajo
### Tipos de energía
### Energía potencial
• En los sistemas mecánicos la energía potencial cambia de acuerdo a su posición (con respecto a una referencia)
• En los sistemas mecánicos los resortes y las masas almacenan energía potencial
• La energía potencial es equivalente al trabajo realizado por la fuerza externa


$$U=\int_{h}^{0} mg dx = mgh$$

Donde, 

U=Energía potencial

mgh=La capacidad de hacer trabajo está definida por la altura.

### Energía Cinética
• La energía cinética es debida a la velocidad
• Solamente los elementos de inercia pueden almacenar energía cinética
$$T=\frac{1}{2} mv^2$$ \qquad  T=\frac{1}{2} 𝐽𝜃^{2}$$
• Un cambio en la energía cinética es el trabajo realizado sobre una masa por la aplicación de una fuerza que acelera o desacelera

Cambio de energía cinética \quad $\triangle T=  \triangle W=\int_{x_{2}}^{x_{1}} F dx=\int_{t_{2}}^{t_{1}} F \frac{dx}{dt} dt$
$$=\int_{t_{2}}^{t_{1}} Fv dt=\int_{t_{2}}^{t_{1}} mv'v dt =\int_{v_{2}}^{v_{1}} mv dv $$
$$=frac{1}{2}mv_{2}^{2} - \frac{1}{2} mv_{1}^{2}$$

Cambio de energía cinética $ \triangle= \frac{1}{2} 𝐽𝜃_{2}^{2} - \frac{1}{2} 𝐽𝜃_1{1}^{2} $



 Fric
