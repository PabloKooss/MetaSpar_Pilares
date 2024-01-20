
<h3>Actividad.</h3>

hacer un objeto 3D 
hacer un plane tracker
target tracker y plane tracker no se puede hacer al mismo tiempo

<h1>
  Plane tracker
</h1>

<image src="https://scontent.fmex26-1.fna.fbcdn.net/v/t39.2365-6/133356229_1275522526150659_7650537262237224681_n.jpg?_nc_cat=100&ccb=1-7&_nc_sid=e280be&_nc_ohc=VZm6Wm95JR8AX80S7v3&_nc_ht=scontent.fmex26-1.fna&oh=00_AfC_DQNwpYuZ9_WrFqHPJtppA_ybqpH5RN0D3JcUNyRm6A&oe=65C67EC0">

<p>
Utilice el rastreador de planos para crear un efecto mundial en Meta Spark Studio, colocando objetos 3D en los entornos de las personas.
Un rastreador de aviones encontrará una superficie horizontal en el mundo real, como del suelo a la mesa. Los objetos que son hijos del rastreador de aviones aparecerán cuando se detecte la superficie.
Solo puedes agregar un rastreador de avión a una escena, pero puedes hacer que varios objetos respondan al rastreador de avión. No se pueden utilizar un rastreador de avión y un rastreador de objetivos en la misma escena.
Los efectos de seguimiento del plano solo son visibles a través de la cámara en la parte posterior del dispositivo.
</p>

<h3>
  Agregar un rastreador de aviones
</h3>

<p>
  Para agregar un rastreador de aviones a su proyecto:
  
```psc
     Haga clic en + en la parte inferior del panel Escena.
     Seleccione Rastreador de aviones.
```

Debido a que los rastreadores de aviones solo funcionan a través de la cámara trasera, el video en el Simulador será reemplazado automáticamente por un video que muestra el mundo, en lugar de una persona.
Su ventana gráfica se verá así:
</p>

<img src="https://scontent.fmex26-1.fna.fbcdn.net/v/t39.2365-6/87529754_194508271622020_8020197245926244352_n.jpg?_nc_cat=105&ccb=1-7&_nc_sid=e280be&_nc_ohc=TnIrRi3QZsQAX8Iq_DM&_nc_oc=AQm-1iJVjbNjsBvP5hFLAxVNSkX8f50zyjPAIu-K8gZ6afaV8tzfpZwqAbh1gpEwCNE&_nc_ht=scontent.fmex26-1.fna&oh=00_AfDT2Hs1kICY-KLKSXDoT799tH45iihu4DU43iFYCtExGA&oe=65C683B0">

![imagen](https://github.com/PabloKooss/MetaSpar_Pilares/assets/128625936/681c5d9a-5716-457b-8b9e-08af01b05c3c)

![imagen](https://github.com/PabloKooss/MetaSpar_Pilares/assets/128625936/4e31025d-70cd-429e-8df6-b1b4de0caa5b)


![imagen](https://github.com/PabloKooss/MetaSpar_Pilares/assets/128625936/e95c2e38-09ef-4488-8a8f-3396ae212cbe)


<h3>Hacer que aparezca un objeto cuando se detecta una superficie</h3>
Para hacer que un objeto aparezca cuando la cámara detecta una superficie, todo lo que necesita hacer es convertir el objeto en hijo del rastreador de avión en el panel Escena. En Meta Spark Studio, cuando un objeto es hijo de otro objeto, responderá y asumirá cualquier cambio realizado en su objeto principal.
Para hacer esto, ya sea:

```psc
     Haga clic derecho en el rastreador de planos en el panel Escena y seleccione Objeto 3D.
     Arrastre un objeto desde el panel Activos o su escritorio, directamente al rastreador de planos en el panel Escena.
```

<h3>Propiedades del rastreador de planos</h3>

Cuando hayas seleccionado el rastreador de planos en el panel Escena, verás sus propiedades en el Inspector.
Capa
Haga clic en el menú desplegable junto a Capa para ajustar a qué capa está asignado el rastreador de planos.
Visible
Desmarque esta casilla para evitar que el rastreador de aviones y los niños aparezcan en la escena.
Autoencendido
Seleccione esta casilla para encontrar un avión en el espacio mundial tan pronto como se abra su efecto.
Transformaciones
No puedes cambiar las transformaciones de un rastreador de avión porque no es un objeto.
Habilitar para
Esto establece la visibilidad específica de la cámara. Para el rastreador de avión, Habilitar para se configura automáticamente en Cámara trasera y no se puede cambiar. Esto significa que el rastreador de aviones solo será visible en la cámara trasera de un dispositivo móvil.

<h3>
  Cambiar el tamaño, mover y rotar objetos mediante interacciones de pantalla
</h3>

Puede utilizar el Editor de parches para agregar fácilmente interactividad a los efectos que utilizan el rastreador de planos.
Debido a que los objetos que son hijos del rastreador de aviones aparecerán en una superficie del mundo real, es una buena idea darles a las personas la capacidad de cambiar el tamaño, mover y rotar el objeto mediante interacciones en la pantalla como toques y deslizamientos. Aprende cómo en esta guía


<H3>
  Agregar instrucciones a efectos con un rastreador de aviones
</H3>

Cuando agrega un rastreador de avión a un efecto, es una buena idea agregar una instrucción para que los usuarios sepan que el efecto debe verse a través de la cámara trasera. Puede utilizar el Editor de parches para hacer esto.

<h3>filtro Pablo</h3>

https://www.instagram.com/ar/732638822143973/?ch=ZGM0NDIxNjU1MzEzYzJkMmE3NTA0ZTQxNmY0N2U0NjI%3D
