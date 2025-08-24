<div align="center">
  <h1>Tarea 2 – Computación Cuántica</h1>
  <p>
    Ingeniería Electrónica · Universidad Santo Tomás
    <br>
    <b>Didier Posse</b>
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
  <li><b>Superposicion:</b>
    
  </li>
  <li><b>Entrelazamiento:</b>
    
  </li>
  <li><b>Interfaz Cuantica:</b>
    
  </li>
  <li><b>Medicion Probabilistica:</b>
    
  </li>
  <li><b>Desafio de Decoherencia:</b>
    
  </li>
  <li><b>Tipos de Comunicacion:</b>
    
  </li>
  <li><b>Compuertas Cuanticas:</b>
    
  </li>
</ul>

<h2>Referencias</h2>
<ul>
  <li><a href="https://es.wikipedia.org/wiki/Computaci%C3%B3n_cu%C3%A1ntica">Wikipedia – Computación cuántica</a></li>
  <li><a href="https://aws.amazon.com/es/what-is/quantum-computing/">AWS – ¿Qué es la computación cuántica?</a></li>
  <li><a href="https://www.newscientist.com/article/2221707-timeline-a-brief-history-of-quantum-computing-from-1980-to-2100/">New Scientist – Timeline: A brief history of quantum computing from 1980 to 2100</a></li>
  <li><a href="https://www.futurelearn.com/info/blog/what-is-quantum-computing">FutureLearn – What is quantum computing? Essential concepts and uses</a></li>
</ul>
