<div align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/a/a8/Microsoft_Azure_Logo.svg/1280px-Microsoft_Azure_Logo.svg.png"></div>

Bienvenido al primer post de este repositorio, empezarémos hablando un poco acerca de la nube de Azure, en esta parte, hablarémos únicamente acerca de algunos términos importantes que te serán
de gran utilidad a lo largo de los siguientes posts.

<h1> Qué es computación en la nube </h1>

Computación en la nube prácticamente te permite adquirir piezas de hardware (pero no limitado a) para uso personal o empresarial, este hardware, como es rentado una de sus ventajas es que no tienes
que hacer grandes pagos por este ni tampoco necesitas conocimientos de mantenimiento del mismo, ya que este hardware es mantenido por la empresa o lugar donde lo estés rentando, a su vez, únicamente 
pagas **por lo que usas**, es decir, es elástico por lo que si un día requieres muy poca fuerza de procesamiento pagas únicamente por esa fuerza de procesamiento que utilizarás y puedes ir aumentando 
progresivamente, si así lo deseas, tu fuerza de procesamiento e ir pagando por esos aumentos, teniendo así un mayor control tanto de tu presupuesto como de tu tiempo invertido en lo que más te importa
en este caso, la programación.

<h1> Tipo de servicio en la nube </h1>

Pero, como es que las empresas pueden ofrecer grandes cantidades de hardware a una demanda tan creciente como lo viene siendo en los últimos años?
Fácil. Para que las empresas puedan ofrecer este tipo de servicios se basan en en diferentes tipos de modelos que se ajustan a tus necesidades,
algunos de estos son "**Vm,Containers & Serverless Computing**". Veamos a detalle cada uno de estos.

<h2>VM's</h2>

Los VM's o "Virtual Machines" son a pocas palabras, computadoras virtuales que usan un hipervisor para dividir las capacidades del hardware físico en 
varias computadoras virtuales (aisladas y seguras) para uso personal o empresarial.

Cada VM incluye su propio S.O y Hardware que puedes utilizar e instalar cualquier software que ocupes para hacer las tareas que ocupes que corran en la nube. La diferencia, de este tipo de VM a tu computadora
es que el Harware es proveido por tu provedor de la nube, el cuál está alojado en alguno de sus muchos datacenters a lo largo del planeta.

<h3>Glosario</h3>

1. Hipervisor: Es un tipo de software de tipo capa (si, como las cebollas) que permiten realizar una virtualización del hardware físico y al mismo tiempo, utilizar diferentes sistemas operativos en una misma computadora.
Piensalo así, cuando sacas una cebolla del refrigerador primero tienes una capa dura, seca y fría, se podría decir, que esa capa es desechable, lo mismo para con las VM, en esa capa, es el área de trabajo del usuario, el cuál
cuando ya no la ocupe puede deshecharla fácilmente y rápido; debajo de esa capa tenemos una capa un poco mas limpia y que no está seca (hablando en términos de cebollas) se puede hacer la comparación con el hipervisor, esta capa
es la encargada de proteger el núcleo o centro de la cebolla, y finalmente tenemos el núcleo de la cebolla la cuál se compara con el hardware físico que está en los datacenters de tu proveedor.

2. Datacenter: Un datacenter es un lugar en alguna parte del planeta (o de la galaxia) en la cuál se encuentra en groso modo, grandes cantidades de hardware almacenado que está trabajando 24/7
Puedes pensarlo como un callcenter, un único lugar donde se encuentran muchas personas atendiendo llamadas.

<h2>Containers</h2>

Estos son muy similares a las VM's sin embargo, estos no requieren un sistema operativo, este tipo de soluciones lo que hace es que la aplicación que quieres correr y todas sus dependencias, se insertan en un tipo de contenedor y cuando el programa es ejecutado es justo cuando el contenedor manda información e instrucciones al hardware de la computadora, por lo que es útil a la hora de ahorrar recursos ya que no ocupamos un sistema operativo.

<h2> Serverless computing </h2>

Este tipo de modelo se basa en que puedas correr tu aplicación sin que tengas la preocupación de actualizar, configurar, crear y mantener un servidor, la idea, es que tu aplicación se fragmente en varias funciones que, corran cuando sean activadas o "llamadas" por algún evento, este tipo de modelo es ideal para tareas que quieras que sean automáticas.


<h1>Fuentes</h1>
1. Bulens, H., 2019. Azure Fundamentals. 1st ed. HENDRIK BULENS, pp.1-3.

