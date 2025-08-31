<div align="center">
  <h1>Tarea 2 – Computación Cuántica</h1>
  <p>
    Ingeniería Electrónica · Universidad Santo Tomás
    <br>
    <b>Didier Posse</b>
    <br>
    <em>Primer punto</em>
  </p>
</div>

<hr>

<h2>¿Qué es la Computación Cuántica?</h2>
<p>
La <b>computación cuántica</b> es un tipo de computación diferente a la computación clásica.  
En la computación clásica se usan <i>bits</i>, que son combinaciones de unos y ceros para resolver problemas, pero cada bit solo puede estar en un estado a la vez.  
En cambio, la computación cuántica utiliza los <b>qubits</b>, que también se basan en 0 y 1, pero con la diferencia de que pueden estar en ambos estados al mismo tiempo.  
Esto genera una nueva lógica con puertas lógicas distintas.
</p>
<p>
Los qubits se pueden representar como vectores. Como pueden estar en los dos estados posibles simultáneamente, se representan en un plano cartesiano llamado <b>esfera de Bloch</b>.  
En ella, el qubit se describe con los estados <i>|0⟩</i> y <i>|1⟩</i>, lo que permite calcular matemáticamente su estado y que no sea aleatorio.  
A esto se le llama <b>superposición cuántica</b>, es decir, estar en dos estados simultáneamente.
</p>

<hr>

<h2>Arquitectura de la Computación Cuántica</h2>
<p>Existen tres componentes principales en el hardware de las computadoras cuánticas:</p>

<ul>
  <li>
    <b>Plano de datos cuánticos:</b>  
    Es la parte principal, el núcleo de la computadora.  
    Se encarga de procesar mediante los qubits físicos y las puertas lógicas cuánticas.  
    También incluye las estructuras que mantienen estables los qubits para que funcionen correctamente.
  </li>
  <li>
    <b>Plano de control y medida:</b>  
    Transforma las señales digitales en analógicas, es decir, traduce del sistema clásico al cuántico.  
    De esta manera, los resultados se pueden interpretar y procesar en sistemas clásicos.
  </li>
  <li>
    <b>Procesador de control y procesador host:</b>  
    El procesador de control organiza las secuencias cuánticas y las envía al plano de control y medida.  
    El procesador host corresponde al usuario y al sistema operativo, que controlan el hardware mediante el software.
  </li>
</ul>

<p>
El <b>software</b> funciona de forma similar al clásico, pero con <b>algoritmos cuánticos</b> y circuitos cuánticos.  
Existen diferentes tipos de arquitecturas cuánticas:
</p>
<ul>
  <li>Arquitectura de superconductores</li>
  <li>Arquitectura de iones atrapados</li>
  <li>Arquitectura fotónica</li>
  <li>Arquitectura topológica</li>
</ul>

<hr>

<h2>Historia de la Computación Cuántica</h2>
<ol>
  <li><b>Década de 1980:</b>
    <ul>
        <li>Richard Feynman y David Deutsch plantean la idea de una computadora cuántica.</li>
        <li>Se definen los primeros modelos teóricos de computación cuántica.</li>
        <li>Nace el concepto de simulación cuántica para sistemas físicos.</li>
    </ul>
  </li>
  <li><b>Década de 1990:</b>
    <ul>
        <li>David Simon ideó una base para los algoritmos y Charles Bennett descubrió el teletransporte cuántico (1993).</li>
        <li>Shor desarrolla su algoritmo de factorización y rompe algunos sistemas de criptografía (1994).</li>
        <li>Grover propone su algoritmo de búsqueda de datos, un algoritmo probabilístico (1996).</li>
        <li>Se propagó el primer cúbit por medio de aminoácidos y se creó la primera máquina de 3 cúbits.</li>
    </ul>
  </li>
  <li><b>Década de 2000:</b>
    <ul>
        <li>Primeros experimentos con cúbits físicos en computadores de 5 a 12 cúbits.</li>
        <li>Se consiguen unir componentes cuánticos con superconductores y se crea el primer bus cuántico.</li>
        <li>Se consigue almacenar un cúbit en el núcleo del fósforo por 1,75 segundos.</li>
        <li>Se crea el primer procesador cuántico de estado sólido que busca datos y los opera.</li>
    </ul>
  </li>
  <li><b>Década de 2010:</b>
    <ul>
        <li>IBM anuncia y presenta el primer procesador cuántico estable y comercial.</li>
        <li>IBM presenta el primer ordenador cuántico de uso comercial con 20 cúbits.</li>
        <li>Surgen frameworks de programación cuántica (Qiskit, Cirq, Forest).</li>
    </ul>
  </li>
  <li><b>Década de 2020:</b>
    <ul>
        <li>Avances hacia la tolerancia a fallos y corrección de errores.</li>
        <li>Aplicaciones en optimización, nuevos materiales y criptografía post-cuántica.</li>
        <li>Expansión de servicios en la nube cuánticos (IBM, Amazon, Microsoft, Google).</li>
    </ul>
  </li>
</ol>

<h4>Ventajas</h4>
<ul>
  <li><b>Potencia en cálculos:</b> Los computadores cuánticos son más potentes que los clásicos por la capacidad de procesar grandes cantidades de datos simultáneamente.</li>
  <li><b>Optimización:</b> Gracias a la potencia de estas computadoras, ayudan a resolver de forma más eficiente los problemas de optimización como la planificación y la gestión logística.</li>
  <li><b>Avances tecnológicos:</b> Se espera que esta tecnología ayude a desarrollar nuevos materiales y herramientas, y que también potencie la IA logrando un aprendizaje más rápido y preciso.</li>
</ul>

<h4>Desventajas</h4>
<ul>
  <li><b>Fragilidad de los cúbits:</b> Los cúbits son muy sensibles al medio, pueden perder fácilmente su estado cuántico, por lo que aún no se ha logrado almacenar datos por largo tiempo.</li>
  <li><b>Cuidados con el hardware:</b> Debido a la fragilidad de los cúbits, se requiere un entorno estricto sin vibraciones y a temperaturas cercanas al cero absoluto.</li>
  <li><b>Seguridad:</b> Esta computación tiene la capacidad de vulnerar algoritmos de cifrado, lo cual la hace peligrosa y poco segura en algunos contextos.</li>
  <li><b>Costos:</b> El desarrollo y el mantenimiento de estos ordenadores son demasiado elevados, debido a la delicadeza de su funcionamiento y a la alta tecnología que utilizan.</li>
</ul>

<hr>

<h2>Principios fundamentales de la computación cuántica</h2>
<ul>
  <li><b>Superposición:</b>
    Es el principio fundamental en el que el cúbit (o electrón) puede estar en varios estados simultáneamente. 
    En el caso de la computación cuántica, estos estados pueden ser 0 y 1 a la vez.
  </li>
  <li><b>Entrelazamiento:</b>
    Es un fenómeno en el cual dos o más partículas están conectadas por sus estados. 
    Como las partículas están en superposición, al observar o medir una de ellas se obtiene un único estado, 
    y automáticamente la otra partícula adopta el otro estado posible, sin importar la distancia, ya que siguen conectadas.
  </li>
  <li><b>Interferencia cuántica:</b>
    Es un fenómeno en el cual las amplitudes de probabilidad de una partícula (onda) se combinan, es decir, se suman o restan. 
    Esto ocurre porque puede haber dos o más estados posibles en la partícula. 
    La interferencia puede ser constructiva (la probabilidad aumenta) o destructiva (la probabilidad disminuye).
  </li>
  <li><b>Medición probabilística:</b>
    Es la medición cuántica que se realiza para determinar el estado de un sistema cuántico. 
    Debido a la superposición, no se puede conocer el estado exacto de forma determinista, 
    por lo que se describe mediante una distribución de probabilidades.
  </li>
  <li><b>Desafío de decoherencia:</b>
    Este desafío ocurre cuando los sistemas pierden su coherencia cuántica, es decir, dejan de mantener sus propiedades cuánticas. 
    Esto genera errores en los cálculos y se debe principalmente a la interacción con el entorno, 
    ya que los sistemas cuánticos requieren condiciones muy rigurosas para funcionar correctamente.
  </li>
  <li><b>Tipos de comunicación cuántica:</b>
    <ul>
      <li>Distribución de claves cuánticas (QKD): Se utiliza para crear claves secretas imposibles de copiar sin ser detectadas.</li>
      <li>Teletransporte cuántico: Permite transmitir el estado cuántico de una partícula a otra distante usando entrelazamiento.</li>
      <li>Redes cuánticas: Son redes similares a internet, pero usan cúbits en lugar de bits.</li>
      <li>Criptografía post-cuántica: Algoritmos clásicos diseñados para resistir ataques de computadores cuánticos.</li>
    </ul>
  </li>
  <li><b>Compuertas cuánticas:</b>
    <h4>Compuertas single-cúbit</h4>
    <ul>
      <li>Hadamard (H): Genera superposición (|0⟩ → (|0⟩+|1⟩)/√2).</li>
      <li>Pauli-X (X): Equivalente a NOT clásico, cambia |0⟩ ↔ |1⟩.</li>
      <li>Pauli-Y (Y): Rota el estado en el eje Y de la esfera de Bloch.</li>
      <li>Pauli-Z (Z): Introduce un cambio de fase (cambia el signo de |1⟩).</li>
      <li>Fase (S): Rotación de 90° en fase.</li>
      <li>π/8 (T): rotación de 45° en fase.</li>
    </ul>
    <h4>Compuertas multi-cúbits</h4>
    <ul>
      <li>CNOT: Invierte el cúbit objetivo si el control es |1⟩.</li>
      <li>Toffoli (CCNOT): Generalización de CNOT con 2 controles y 1 objetivo.</li>
      <li>Fredkin (CSWAP): Hace un SWAP entre dos cúbits solo si el control es |1⟩.</li>
    </ul>
  </li>
</ul>

<hr>

<div align="center">
  <p><em>Segundo punto</em></p>
</div>

<hr>

<h2>¿Qué es la Computación Neuromórfica?</h2>
<p>
  La <b>computación neuromórfica</b> es un enfoque que busca imitar la forma en que funciona el cerebro humano.  
  Mientras que los computadores clásicos procesan información con una lógica secuencial y binaria, los sistemas neuromórficos intentan replicar las <b>redes neuronales biológicas</b>.  
  Esto permite que no solo procesen datos, sino que también logren <i>percepción, control motriz, integración multisensorial, aprendizaje y adaptación</i>.
</p>
<p>
  Este tipo de computación combina <b>biología, electrónica e informática</b>.  
  Su meta es diseñar circuitos y arquitecturas que reproduzcan las capacidades del cerebro, como ocurre en sistemas visuales, auditivos o de movimiento, pero llevados a un entorno tecnológico.  
  Así se busca avanzar en la creación de <b>robots inteligentes</b> que no solo tengan apariencia física, sino también capacidades cognitivas, adaptativas y evolutivas.
</p>

<hr>

<h2>Arquitectura de la Computación Neuromórfica</h2>
<p>
  La arquitectura neuromórfica se inspira en las <b>neuronas y sinapsis</b> del cerebro.  
  Se basa en <i>spiking neural networks (SNN)</i>, que son modelos de redes neuronales que transmiten información mediante <b>impulsos eléctricos</b> (spikes), al igual que el cerebro.  
</p>

<ul>
  <li>
    <b>Neuronas artificiales:</b> Representan nodos de procesamiento que simulan la función de las neuronas biológicas.
  </li>
  <li>
    <b>Sinapsis electrónicas:</b> Conexiones que transmiten señales entre neuronas y que pueden fortalecerse o debilitarse, imitando la <i>plasticidad sináptica</i>.
  </li>
  <li>
    <b>Procesamiento paralelo:</b> Millones de neuronas artificiales trabajan de forma simultánea, lo que hace más eficiente el reconocimiento de patrones y la adaptación.
  </li>
  <li>
    <b>Bajo consumo energético:</b> Los chips neuromórficos consumen muy poca energía comparados con procesadores clásicos, ya que trabajan por eventos (solo procesan cuando hay un estímulo).
  </li>
</ul>

<h4>¿Cómo funciona?</h4>
<p>
  El funcionamiento se da por medio de <b>eventos eléctricos discretos</b>.  
  Cuando un estímulo alcanza cierto umbral en una neurona artificial, esta "dispara" un pulso que viaja a través de la red.  
  Con la repetición, las conexiones se refuerzan o debilitan, reproduciendo el <b>aprendizaje sináptico</b> del cerebro humano.
</p>

<h4>Ventajas</h4>
<ul>
  <li>Procesamiento paralelo y en tiempo real.</li>
  <li>Bajo consumo energético.</li>
  <li>Alta capacidad de aprendizaje y adaptación.</li>
  <li>Útil para IA, visión artificial, robótica y sistemas autónomos.</li>
</ul>

<h4>Desventajas</h4>
<ul>
  <li>Tecnología aún en desarrollo, con pocos chips comerciales.</li>
  <li>Difícil de programar con modelos clásicos de software.</li>
  <li>Limitaciones en la escalabilidad de hardware.</li>
</ul>

<hr>

<h2>Hardware utilizado en la Computación Neuromórfica</h2>
<p>
  Algunos ejemplos de <b>hardware neuromórfico</b> son:
</p>
<ul>
  <li><b>IBM TrueNorth:</b> Primer chip neuromórfico con más de un millón de neuronas simuladas.</li>
  <li><b>Intel Loihi:</b> Chip diseñado para IA adaptativa, que aprende en tiempo real con muy bajo consumo de energía.</li>
  <li><b>BrainScaleS:</b> Proyecto europeo que simula redes neuronales a gran escala.</li>
  <li><b>SpiNNaker (Manchester):</b> Computadora neuromórfica que utiliza millones de procesadores ARM para simular el cerebro.</li>
</ul>

<hr>

<h2>Tipos de Computación Neuromórfica</h2>
<ul>
  <li><b>Digital:</b> Implementada con chips digitales tradicionales que simulan redes neuronales.</li>
  <li><b>Analógica:</b> Basada en circuitos analógicos que imitan de manera más realista los impulsos eléctricos del cerebro.</li>
  <li><b>Mixta:</b> Combinación de elementos digitales y analógicos, aprovechando las ventajas de ambos.</li>
</ul>

<hr>

<div align="center">
  <p><em>Tercer punto</em></p>
</div>

<hr>

<h2>¿Qué son los Ordenadores Biológicos?</h2>
<p>
  Un <b>ordenador biológico</b> es similar a los ordenadores neuromórficos, pero con una diferencia fundamental: en lugar de usar <i>componentes electrónicos</i>, 
  su funcionamiento se basa en <b>elementos biológicos</b> como células, neuronas, ADN y otras moléculas.  Estos sistemas buscan reproducir la <b>estructura y el
  comportamiento del cerebro humano</b>, logrando un procesamiento más natural y eficiente.
</p>
<p>
  El propósito de esta tecnología es <b>superar las limitaciones de los ordenadores clásicos</b>, ofreciendo mayor capacidad de almacenamiento, menor consumo energético
  y procesamiento masivo de datos en poco tiempo. Aunque todavía se encuentra en fases iniciales de desarrollo, comparte con los ordenadores neuromórficos la meta de
  crear sistemas de <i>cómputo más inteligentes, adaptativos y eficientes</i>.
</p>

<hr>

<h2>Arquitectura de los Ordenadores Biológicos</h2>
<p>
  La <b>arquitectura de los ordenadores biológicos</b> se basa en el uso de <b>moléculas orgánicas</b> como el ADN, el ARN, proteínas 
  o incluso <b>cultivos neuronales vivos</b> en lugar de los tradicionales transistores de silicio.  
  Este enfoque busca aprovechar la <b>capacidad natural de las células</b> para almacenar, procesar y transmitir información, 
  imitando los procesos biológicos que ocurren en organismos vivos.
</p>

<p>
  A diferencia de los ordenadores clásicos, cuya lógica se fundamenta en impulsos eléctricos y puertas lógicas binarias, 
  los <b>ordenadores biológicos</b> emplean <b>reacciones químicas, enlaces moleculares y señales celulares</b> como base de su funcionamiento.  
  Esto les permite realizar operaciones en paralelo, con un <b>bajo consumo energético</b> y en un <b>espacio extremadamente reducido</b>.
</p>

<p>
  Entre sus principales <b>tipos</b> podemos mencionar:
</p>
<ul>
  <li><b>Computación con ADN:</b> utiliza cadenas de ADN para resolver problemas matemáticos complejos mediante emparejamiento de bases y reacciones químicas.</li>
  <li><b>Computación con proteínas:</b> emplea proteínas y enzimas como unidades de almacenamiento y procesamiento de datos.</li>
  <li><b>Neurocomputación biológica:</b> trabaja con neuronas vivas en cultivo, que pueden generar conexiones sinápticas y <i>aprender</i> patrones de manera similar a un cerebro.</li>
</ul>

<p>
  A lo largo de la historia, destacan algunos <b>hitos importantes</b>:
</p>
<ul>
  <li><b>1994:</b> Leonard Adleman construyó el primer <i>ordenador de ADN</i>, resolviendo un problema matemático de caminos en grafos.</li>
  <li><b>Década de 2000:</b> avances en biología sintética permitieron diseñar <b>circuitos genéticos</b> capaces de tomar decisiones simples dentro de células vivas.</li>
  <li><b>Últimos años:</b> experimentos con <b>redes neuronales biológicas</b> lograron que cultivos de neuronas reconozcan patrones e incluso aprendan tareas sencillas, abriendo la puerta a la fusión entre biología y computación.</li>
</ul>

<hr>

<div align="center">
  <p><em>Cuarto punto</em></p>
</div>

<hr>

<h2>Arquitectura de la Computación Heterogénea</h2>
<p>
  Esta arquitectura se basa en un sistema de <b>multi-procesadores</b>, lo que significa que integra varios tipos de procesadores como <b>
  CPU, GPU, NPU o ASIC</b>. Cada uno cuenta con un <i>hardware especializado</i>, capaz de realizar tareas específicas y complementarse con los demás.
</p>
<p>
  Un ejemplo claro está en la <b>computación clásica</b>, donde la <b>CPU</b> se encarga de <i>trabajos robustos y específicos</i>, además de gestionar
  los datos de software y hardware. Por su parte, la <b>GPU</b> se especializa en el <i>procesamiento masivo en paralelo</i>, permitiendo ejecutar
  múltiples procesos de forma simultánea y eficiente.
</p>

<h4>Ventajas</h4>
<ul>
  <li><b>Mayor velocidad de procesamiento:</b> Permite ejecutar tareas en menos tiempo gracias a la distribución entre distintos procesadores.</li>
  <li><b>Mejor rendimiento en procesos exigentes:</b> Cada procesador se especializa en un tipo de tarea, logrando un desempeño más eficiente.</li>
  <li><b>Eficiencia energética:</b> Optimiza el consumo de energía al asignar la carga de trabajo al procesador más adecuado.</li>
  <li><b>Adaptabilidad:</b> Se ajusta a diferentes tipos de cargas y necesidades, desde cálculos en paralelo hasta gestión de datos.</li>
</ul>

<h4>Desventajas</h4>
<ul>
  <li><b>Complejidad en la programación:</b> Requiere un desarrollo de software más avanzado para coordinar los diferentes procesadores.</li>
  <li><b>Componentes especializados:</b> Necesita hardware específico y optimizado para cada tipo de tarea.</li>
  <li><b>Costos elevados:</b> El desarrollo, la integración y el mantenimiento son más caros que en una arquitectura tradicional.</li>
</ul>

<hr>

<h2>Historia de la Computación Heterogénea</h2>
<ol>
  <li><b>Década de 1990:</b>
    <ul>
        <li>Se empieza a usar la idea de juntar <b>CPU con coprocesadores</b> para cálculos científicos y gráficos.</li>
        <li>Las primeras <b>GPU programables</b> aparecen y se ve que sirven no solo para juegos, sino también para cálculos más complejos.</li>
    </ul>
  </li>
  <li><b>Década de 2000:</b>
    <ul>
        <li>Ya se ven sistemas donde <b>CPU y GPU trabajan juntos</b>. NVIDIA saca CUDA en 2006 y abre la puerta a usar GPUs en todo tipo de tareas.</li>
        <li>Se vuelve común en la <b>computación de alto rendimiento</b> porque acelera bastante los procesos.</li>
    </ul>
  </li>
  <li><b>Década de 2010:</b>
    <ul>
        <li>Empiezan a meter <b>ASICs y FPGAs</b> en servidores para tareas muy específicas.</li>
        <li>Los celulares y dispositivos empiezan a traer <b>chips para IA</b> además del procesador normal.</li>
    </ul>
  </li>
  <li><b>Década de 2020:</b>
    <ul>
        <li>La <b>heterogeneidad</b> ya se ve en todas partes: en PCs, móviles y hasta en supercomputadores.</li>
        <li>Ahora es normal que un mismo equipo tenga procesadores dedicados para <b>IA, gráficos o seguridad</b>.</li>
    </ul>
  </li>
</ol>

<hr>

<div align="center">
  <p><em>Cuarto punto</em></p>
</div>

<hr>

<h2>Arquitectura de la Computación de Borde</h2>
<p>
  Esta arquitectura se basa en el <b>procesamiento y almacenamiento de datos en el mismo dispositivo</b>. 
  Esto significa que, en lugar de enviar los datos a un <b>servidor</b> u <b>ordenador central</b> para ser procesados, 
  el <b>mismo dispositivo que mide esos datos</b> (como <i>sensores</i>, <i>dispositivos IoT</i>, <i>medidores</i>, etc.) 
  se encarga de <b>almacenar y procesar la información localmente</b>, generando una <b>respuesta inmediata</b> 
  según los datos recolectados.
</p>

<h4>Ventajas</h4>
<ul>
  <li><b>Baja latencia:</b> Reduce el tiempo de respuesta y la pérdida de datos al procesarlos más cerca del origen.</li>
  <li><b>Optimización del ancho de banda:</b> Disminuye el tráfico de datos en internet al filtrar y procesar localmente.</li>
  <li><b>Escalabilidad:</b> El sistema soporta múltiples dispositivos y grandes volúmenes de datos sin colapsar.</li>
  <li><b>Resiliencia:</b> Permite seguir funcionando incluso con limitaciones o interrupciones en la nube o el servidor central.</li>
</ul>

<h4>Desventajas</h4>
<ul>
  <li><b>Seguridad de los datos:</b> Es más difícil proteger la información al estar distribuida en múltiples dispositivos.</li>
  <li><b>Costos elevados:</b> Requiere implementar almacenamiento y procesamiento en muchos nodos en lugar de un único servidor.</li>
  <li><b>Complejidad en la gestión:</b> Coordinar, actualizar y mantener múltiples dispositivos distribuidos puede ser complicado.</li>
</ul>

<hr>

<h2>Historia de la Computación de Borde</h2>
<ol>
  <li><b>Década de 1990:</b>
    <ul>
        <li>Se empieza a notar la necesidad de <b>procesar datos cerca de donde se generan</b>, sobre todo en redes industriales.</li>
    </ul>
  </li>
  <li><b>Década de 2000:</b>
    <ul>
        <li>Con el crecimiento del <b>IoT</b> se ve que no es tan eficiente mandar todo a un servidor central.</li>
    </ul>
  </li>
  <li><b>Década de 2010:</b>
    <ul>
        <li>El concepto de <b>edge computing</b> se hace más conocido gracias a los <b>dispositivos inteligentes</b>.</li>
        <li>Se aplica en cosas como <b>autos autónomos, ciudades inteligentes y en la salud</b>.</li>
    </ul>
  </li>
  <li><b>Década de 2020:</b>
    <ul>
        <li>Se consolida como un complemento de la nube, ahora se habla de <b>cloud + edge</b>.</li>
        <li>Empresas como Amazon, Microsoft y Google ya ofrecen <b>servicios de edge</b> directamente.</li>
    </ul>
  </li>
</ol>

<hr>

<h2>Referencias</h2>
<ul>
  <li><a href="https://es.wikipedia.org/wiki/Computaci%C3%B3n_cu%C3%A1ntica">Wikipedia – Computación cuántica</a></li>
  <li><a href="https://aws.amazon.com/es/what-is/quantum-computing/">AWS – ¿Qué es la computación cuántica?</a></li>
  <li><a href="https://www.newscientist.com/article/2221707-timeline-a-brief-history-of-quantum-computing-from-1980-to-2100/">New Scientist – Timeline: A brief history of quantum computing from 1980 to 2100</a></li>
  <li><a href="https://www.futurelearn.com/info/blog/what-is-quantum-computing">FutureLearn – What is quantum computing? Essential concepts and uses</a></li>
  <li><a href="https://www.youtube.com/watch?v=iZ5I_P4XUWQ">YouTube – Introducción a la Computación Cuántica</a></li>
  <li><a href="https://www.spinquanta.com/news-detail/exploring-quantum-interference-key-concepts-explained">SpinQuanta – Interferencia cuántica: conceptos clave</a></li>
  <li><a href="https://www.spinquanta.com/news-detail/decoherence-in-quantum-computing-everything-you-need-to-know">SpinQuanta – Decoherencia en la computación cuántica</a></li>
  <li><a href="https://profmcruz.wordpress.com/wp-content/uploads/2017/08/quantum-computation-and-quantum-information-nielsen-chuang.pdf">Libro – Nielsen & Chuang: Quantum Computation and Quantum Information</a>
  <li><a href="https://es.wikipedia.org/wiki/Computaci%C3%B3n_neurom%C3%B3rfica">Wikipedia – Computación neuromórfica</a></li>
  <li><a href="https://www.ibm.com/blogs/research/2018/08/brain-inspired-computing/">IBM Research – Brain-inspired computing</a></li>
  <li><a href="https://newsroom.intel.com/editorials/loihi-neuromorphic-chip/">Intel – Loihi Neuromorphic Chip</a></li>
  <li><a href="https://www.sciencedirect.com/topics/computer-science/neuromorphic-computing">ScienceDirect – Neuromorphic Computing</a></li>
  <li><a href="https://www.xataka.com/investigacion/computacion-biologica-que-como-nos-esta-ayudando-a-resolver-algunos-grandes-retos-a-que-se-enfrenta-humanidad">Xataka – Computación biológica: cómo nos está      ayudando a resolver retos humanos</a></li>
  <li><a href="https://polytechnique-insights.com/en/columns/science/biocomputing-the-promise-of-biological-computingbrains/">Polytechnique Insights – Biocomputing: the promise of biological computing brains</a></li>
  <li><a href="https://en.wikipedia.org/wiki/Heterogeneous_computing">Wikipedia – Heterogeneous computing</a></li>
  <li><a href="https://phoenixnap.mx/glosario/computaci%C3%B3n-heterog%C3%A9nea">phoenixNAP – ¿Qué es la computación heterogénea?</a></li>
  <li><a href="https://es.wikipedia.org/wiki/Computaci%C3%B3n_frontera">Wikipedia – Computación frontera (Edge computing)</a></li>
  <li><a href="https://www.youtube.com/watch?v=JELW6zQdkJg&ab_channel=AlbertoLopezTECHTIPS">YouTube – Video (Alberto López TECHTIPS)</a></li>
</ul>
</ul>
