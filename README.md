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
![esquema de amortiguador](https://dademuchconnection.wordpress.com/wp-content/uploads/2017/07/null80.png).
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



### SISTEMAS MECÁNICOS MÁS COMPLEJOS

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

$$T=\frac{1}{2} mv^2 \qquad  T=\frac{1}{2} 𝐽𝜃^{2}$$

• Un cambio en la energía cinética es el trabajo realizado sobre una masa por la aplicación de una fuerza que acelera o desacelera

Cambio de energía cinética  $\triangle T=  \triangle W=\int_{x_{2}}^{x_{1}} F dx=\int_{t_{2}}^{t_{1}} F \frac{dx}{dt} dt$
$$=\int_{t_{2}}^{t_{1}} Fv dt=\int_{t_{2}}^{t_{1}} mv'v dt =\int_{v_{2}}^{v_{1}} mv dv $$
$$=frac{1}{2}mv_{2}^{2} - \frac{1}{2} mv_{1}^{2}$$      
>El signo en la ecuación no importa.

Cambio de energía cinética: $\triangle=\frac{1}{2} 𝐽𝜃_{2}^{2} - \frac{1}{2} 𝐽𝜃_1{1}^{2} $
>Caso rotacional

## POTENCIA
La potencia indica la realización del trabajo que varia con respecto al tiempo

$$Potencia=P=\frac{dW}{dt}$$
$$Potencia media = \frac{trabajo realizado(t_{2}-t_{1}) segundos}{(t_{2}-t_{1})segundos}$$

## Aplicando los conceptos a elementos mecánicos
### Energía potencial a un resorte
•Es el trabajo neto hecho sobre él por las fuerzas que actúan en sus extremos cuando es comprimido o estirado

$$U=\int_{x}^{0} F dx = \int_{x}^{0} kx dx =\frac{1}{2}kx^2$$

•De forma general el cambio de energía sería:

$$\triangle U=\int_{x_{2}}^{x_{1}} F dx = \int_{x_{2}}^{x_{1}} kx dx =\frac{1}{2}kx_2^2 - \frac{1}{2}kx_1^2 $$

### Potencia en un resorte 

• Potencia requerida para estirar o comprimir un resorte
$$P=\frac{dW}{dt}=\frac{F dx}{dt} = Fx'=kxx'$$

• Sabiendo que $U=\frac{1}{2} kx^2$

>Energía potencial en un resorte


$$P=kxx'=U'$$

### Potencia en una masa

• La potencia requerida para acelerar una masa en línea
recta

$$P=\frac{dW}{dt}=\frac{F dx}{dt} = Fx'=mx''x'$$

• Sabiendo que $T=\frac{1}{2} mv^2$
>Energía potencial en un resorte

$$P==mx''x'=mv''v'=T'$$

### Energía disipada
• La energía disipada en un amortiguador corresponde al trabajo neto realizado sobre este

$$\triangle W=\int_{x_{1}}^{x_{2}}Fdx=\int_{x_{1}}^{x_{2}}bx'dx=b\int_{t_{1}}^{t_{2}} x' \frac{dx}{dt}dt=b\int_{t_{1}}^{t_{2}} x'^2dt$$
>No importa signo de la velocidad

## Potencia disipada en amortiguador
•La potencia disipada en el amortiguador de cilindro es:
$$P=\frac{dW}{dt}=\frac{Fdx}{dt}=Fx'$$
•Sabiendo que \qquad F=bx'
$$P=bx'^{2}

## Método de energía para obtener las ecuaciones de movimiento
### Conservación de energía
•Es posible obtener el modelo matemático considerando que la energía total de un sistema permanece igual si ninguna energía entra o sale del sistema.
•En los sistemas mecánicos la fricción disipa energía en forma de calor.
•Los sistemas que ni incluyen fricción se denominan sistemas conservativos.

### Sistema conservativo
• Toda la energía (cinética y potencial) sale del sistema enforma de trabajo mecánico. No se disipa energía.
$$\triangle(T+U)=\triangle W$$

>Trabajo neto fuerza externa

• Si no entra energía externa entonces

$$\triangle(T+U)=0 \qquad \to T+U=Constante $$

💡**Ejemplo Horizontal:**

Si no hay fricción es conservativo

•Por lo tanto
$$T+U=\frac {1}{2}mx'^2 + \frac {1}{2}kx^2=constante$$

•Al derivarla energía total
$$\frac (T+U)=mx'x''+kxx'=(mx''+kx)x'=0$$
$$mx''+kx=0$$
 
💡**Ejemplo Vertical:**

• En el caso vertical, se debe tomar en cuenta la energía debida a la posición inicial

$$U_{0}=mgx^{0}+\frac{1}{2}k\delta^{2}$$

• Si está en equilibrio entonces

$$k\delta=mg$$
>Delta el cambio de posición debido a la posición inicial

$$U=mg(x_{0}-x)+\frac{1}{2}k(\delta+x)^2$$
$$mgx_{0}+mgx+\frac{1}{2}k\delta^{2}+k\delta x +\frac{1}{2}kx^2$$
$$mgx_{0}+\frac{1}{2}k\delta^2-(mg-k\delta)x+\frac{1}{2}kx^2$$
$$U=U_0+\frac{1}{2}kx^2$$

• La energía cinética , $\qquad T=\frac{1}{2}mx'^2$
$$T+U=\frac{1}{2}mx'^2+U_0+\frac{1}{2}kx^2=Constante$$
>energía total

• Derivando se obtiene la ecuación de movimiento
$$\frac{d}{dx}(T+U)=mx'x''+kxx'=0$$
$$(mx''+kx)x'=0$$

$$mx''+kx=0$$


💡**Ejemplo Rotacional:**

•El cilindrono se desliza(conservativo)

$$J \frac{1}{2}mR^2$$
$$x=R\theta$$
$$T+U=\frac{1}{2}mx'^2+\frac{1}{2}J\theta^2+\frac{1}{2}kx^2=constante$$

$$\frac{3}{4}mx'^2+\frac{1}{2}kx^2=Constante$$
$$\frac{3}{2}mx'x''+kxx'=0$$
$$(mx''+\frac{2}{3}kx)x'=0$$
$$mx''+\frac{2}{3}kx=0$$

$$Energía cinética=T=\frac{1}{2}mx'^2+\frac{1}{2}J\theta^2$$

$$Energía potencial=U=\frac{1}{2}kx^2$$

>Para el movimiento rotacional: $$\qquad x=R\theta$$

$$\theta''+\frac{2k}{3m}\theta=0$$

>COMENTARIOS DE CLASE

>•Se recomienda su uso en sistemas simples, ya que en sistemás donde hay interacción de elementos más difíciles se deben tener en establecer todas las energías que intervienen.

>•Para sistemas muy complejos es mejor usar leyes de Newton.

>•Para usar el enfoque de energía existe un método más completo basado en las ideas de Lagrange.

## Conversión de movimiento Translacional - Rotacional

![]()

Figura 1. Casos frecuentes 

$$J=\frac{W}{g}(\frac{L}{2\Pi})^2  \qquad J=Mr^2=\frac{W}{g}r^2$$

## Trenes  de engranajes, palancas y bandas

$$r_1N_2=r_2N_1 \qquad \theta _1r_1=\theta_2r_2 \qquad T_1\theta_1=T_2\theta_2 $$

$$\frac{T_1}{T_2}=\frac{N_1}{N_2}=\frac{\theta_2}{\theta_1}$$


💡**Ejemplo Par transmisión por engranajes:**

$$T(t)=J_1\frac{d^2\theta_1(t)}{dt^2}+B_1\frac{d\theta_1(t)}{dt}+T_1(t)$$

$$T_1(t)=\frac{N1}{N2} T_2(t)=(\frac{N_1}{N_2})^2 J_2\frac{d^2\theta_1(t)}{dt^2}+(\frac{N_1}{N_2})^2 B_2\frac{d\theta_1(t)}{dt}$$

Inercia: $(\frac{N_1}{N_2})^2J_2$ 

Desplazamiento  angular: $\frac{N_1}{N_2}\theta_2$

Coeficiente de fricción viscosa: $(\frac{N_1}{N_2})^2B_2$

Velocidad angular: $\frac{N_1}{N_2}\gamma^2$

Par: $\frac{N_1}{N_2}T_2$

$$T_2(t)=J_2\frac{d^2\theta_2(t)}{dt^2}+B_2\frac{d\theta_2(t)}{dt}$$

>Reflejar las ecuaciones hasta el torque de origen

$$T(t)=J_le\frac{d^2\theta_1(t)}{dt^2}+B_le\frac{d\theta_1(t)}{dt}$$
$$J_le=J_l+(\frac{N_1}{N_2})^2J_2$$
$$ B_le=B_1+(\frac{N_1}{N_2})^2 B_2$$

### Palancas
$$\frac{f_1}{f_2}=\frac{l_2}{l_1}=\frac{x_2}{x_1}$$

💡**Ejemplo Palanca:**

### Bandas
💡**Ejemplo Bandas:**
$$Tm-T1-Bm\frac{d\theta}{dt}=Jm\frac{d^2\theta}{dt^2}$$
$$t_1=Mr^2\frac{d^2\theta}{dt^2}$$
$$Tm-Mr^2\frac{d^2\theta}{dt^2}-Bm\frac{d\theta}{dt}=Jm\frac{d^2\theta}{dt^2}$$
$$\theta=\frac{y}{r}$$


$$Tm-Mr\frac{d^y}{dt^2}-\frac{Bm}{r}\frac{dy}{dt}=\frac{Jm}{r}\frac{d^2y}{dt^2}$$

>RESUMEN DE CLASE
>•El modelamiento de los sistemas mecánicos requiere la aplicación de modelo del fenómeno físico

>•El modelo de ecuaciones diferenciales permitirá describir el movimiento en el dominio del tiempo para cualquier instante de tiempo

>•El movimiento lineal y el movimiento rotacional son comparables y los fenomenos físicos que se presentan son similares

>•Los modelos de movimiento rotacional y lineal pueden ser iguales sin embargo, describen dos tipos de fenómenos totalmente diferentes


# SISTEMAS ELÉCTRICOS
## Redes RLC
Estos son los circuitos que contienen: (R), Resistencias; (L), Inductancias; (C), Condensadores.

𝐸𝑙 𝑓𝑒𝑛ó𝑚𝑒𝑛𝑜 𝑓í𝑠𝑖𝑐𝑜 𝑞𝑢𝑒 𝑚𝑜𝑑𝑒𝑙𝑎 𝑒𝑠𝑡𝑒 𝑐𝑜𝑚𝑝𝑜𝑟𝑡𝑎𝑚𝑖𝑒𝑛𝑡𝑜 𝑒𝑠 𝑙𝑎𝑠 𝑙𝑒𝑦𝑒𝑠 𝑑𝑒 𝑘𝑖𝑟𝑐ℎ𝑜𝑓𝑓 para el circuito

$$𝑅=\frac{𝑣(𝑡)}{𝑖(𝑡)} \qquad → 𝐿𝑒𝑦 \quad 𝑑𝑒 \quad 𝑂ℎ𝑚$$
$$𝑖(𝑡) = 𝐶 \frac{𝑑𝑣 (𝑡)}{𝑑𝑡} \qquad → 𝐶𝑎𝑟𝑔𝑎 \quad 𝑑𝑒 \quad 𝑢𝑛 \quad 𝑐𝑜𝑛𝑑𝑒𝑛𝑠𝑎𝑑𝑜𝑟$$
$$𝑣(𝑡) = 𝐿\frac{𝑑𝑖 (𝑡)}{𝑑𝑡} \qquad → 𝐶𝑎𝑟𝑔𝑎 \quad 𝑑𝑒 \quad 𝑢𝑛 \quad 𝑖𝑛𝑑𝑢𝑐𝑡𝑜𝑟$$


💡**Ejemplo RLC:**

>Aplicando Leyes de kirchoff

$$-u+v_R+v_L+V_C=0$$
$$-u+i(t)*R+L\frac{di(t)}{dt}+y(t)=0$$

>Aún no esta en términos de la variable "y".

>Recordar que la corriente que se pide despejar en el ejercicio es la corriente en el condensador asi que:

$$i(t)=C(\frac{dy(t)}{dt}$$


$$-u(t)+C(\frac{dy(t)}{dt})*R+L\frac{d}{dt}(C\frac{dt(y)}{dt})+y(t)=0$$
$$-u(t)+RC\frac{dy(t)}{dt}+LC\frac{d^2y(t)}{dt^2}+y(t)=0$$


>Ejercicio

Obtener el modelo para el circuito de la figura:




💡**Ejemplo Ejercicio:**

## Aplicando nodos
>Aplicando la ley de corrientes de Kirchoff

$$i_u-i_1-i_c=0$$
$$i_u(t)-\frac{V_AB}{0.5}-2\frac{dy(t)}{dt}=0$$
$$V_AB=ic*1+y(t)$$
$$V_AB=2\frac{dy(t)}{dt}+y(t)$$

$$u(t)-\frac{2}{0.5}\frac{dy(t)}{dt}-\frac{1}{0.5}y(t)-2\frac{dy(t)}{dt}=0$$
$$u(t)-6\frac{dy(t)}{dt}-2y(t)=0$$

>Ejercicio

Obtener el modelo para el circuito de la figura:


💡**Ejemplo Ejercicio:**

## Circuitos con amplificadores operacionales
### Amplificador no inversor
•Se utilizan leyes de Kirchoffy el modelo simplificado del amplificador operacional.


•La tension enambas entradas del amplificadorson iguales $V+=V-$
•La corrientea las entradas del amplificadores 0.
•La impedanciade entrada es muy grande
•La impedanciade salidaes muy pequeña

💡**Ejemplo:**

$$i_2-i_1=0$$
$$\frac{e_o-e_i)}{R_2}-\frac{e_i}{R1}=0$$
$$\frac{e_o}{R_2}=e_i(\frac{1}{R_2} +\frac{1}{R_1})$$
$$e_o=e_i(1+\frac{R_2}{R_1}$$

### Amplificadores con elementos almacenadores de energía
$$i_1-i_2-i_3=0$$
$$\frac{e_i-e'}{R_1}-\frac{e'-e_o}{R_2}-C\frac{d(e'-e_o}{dt}=0$$
$$e'=0$$

$$\frac{e_i}{R_1}-\frac{-e_o}{R_2}-C\frac{d(-e_o}{dt}=0$$
$$\frac{e_i}{R_1}=-\frac{e_o}{R_2}-C\frac{d(e_o)}{dt}

>Ejercicio

Obtener el modelo para el circuito de la figura:



# SISTEMAS HIDRAULICOS
En sistemas industriales de tanques es deseable mantener flujo o nivel constante.

## Sistemas de tanques
𝑞𝑖 , 𝑞𝑜; 𝐹𝑙𝑢𝑗𝑜𝑠 𝑑𝑒 𝑒𝑛𝑡𝑟𝑎𝑑𝑎 𝑦 𝑠𝑎𝑙𝑖𝑑𝑎 𝑑𝑒 𝑙í𝑞𝑢𝑖𝑑𝑜
𝑅1; 𝑅𝑒𝑠𝑖𝑠𝑡𝑒𝑛𝑐𝑖𝑎 𝑎𝑙 𝑓𝑙𝑢𝑗𝑜
𝐴1; Á𝑟𝑒𝑎 𝑡𝑟𝑎𝑛𝑠𝑣𝑒𝑟𝑠𝑎𝑙 𝑑𝑒𝑙 𝑡𝑎𝑛𝑞𝑢𝑒
ℎ1; 𝑁𝑖𝑣𝑒𝑙 𝑑𝑒 𝑙í𝑞𝑢𝑖𝑑𝑜 𝑒𝑛 𝑒𝑙 𝑡𝑎𝑛𝑞𝑢𝑒


•Flujo de salida del tanque
$$𝑞1=\frac{ℎ1}{𝑅1}$$


•Intercambiode energía
$$𝐴1\frac{𝑑ℎ1}{𝑑𝑡}= 𝑞𝑖 − 𝑞1$$

## Modelo de un tanque

•Modelo 𝑞𝑖 como entrada y ℎ1 como salida

$$𝑞_1=\frac{ℎ_1}{𝑅_1}$$

$$𝐴_1\frac{𝑑ℎ_1}{𝑑𝑡}= 𝑞_𝑖 − 𝑞_1$$

$$A_1\frac{dh_1}{dt}=q_i\frac{h_1}{R_1}$$

•Modelo 𝑞𝑖 como entrada y ℎ1 como salida

$$𝑞_1=\frac{ℎ_1}{𝑅_1}$$

$$𝐴_1\frac{𝑑ℎ_1}{𝑑𝑡}= 𝑞_𝑖 − 𝑞_1$$

$$h_1=q_1*R_1$$

$$R_1A_1\frac{dq_1}{dt}=q_i-q_1$$

### Modelo de 2 tanques en serie


>Ejercicio

Obtener el modelo para el sistema de la figura:

### Modelo de 2 tanques interconectados

$$𝑞_1 =\frac{ℎ_1 − ℎ_2}{𝑅1} \qquad 𝑞_2 =\frac{ℎ_2}{𝑅_2}$$
$$𝐴_1\frac{𝑑ℎ_1}{𝑑𝑡}= (𝑞_𝑖 − 𝑞_1) \qquad 𝐴_2\frac{𝑑ℎ_2}{𝑑𝑡}= (𝑞_1 − 𝑞_2)$$


💡**Ejemplo con q1 como salida:**

$$R_2A_2\frac{dq_2}{dt}=(q_1-q_2)$$
$$R_2A_2\frac{dq_2}{dt}+q_2=q_1$$

$$A_1\frac{dh_1}{dt}=(q_i-R_2A_2\frac{dq_2}{dt}+q_2)$$
$$R_1q_1+h_2=h_1$$

$$R_1(R_2A_2\frac{dq_2}{dt}+q_2)+R_2q_2=h_1$$
$$A_1\frac{d(R_1(R_2A_2\frac{dq_2}{dt}+q_2)+R_2q_2)}{dt}=(q_i-R_2A_2\frac{dq_2}{dt}+q_2)$$

>Modelo resultante

$$A_1R_1R_2A_2\frac{d^2q_2}{dt^2}+(A_1R_1+A_1R_2+R_2A_2)\frac{dq_2}{dt}-q_2=q_i$$

>Ejercicio

Desarrollar el modelo de h_2 como salida
