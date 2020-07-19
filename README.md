# Trabajo-de-investigacion_2
Trabajo de investigación-Segundo parcial

### Cloud computing con Node-Red

### Planteamiento del problema.

En el siguiente informe se dará a conocer las respuestas a las preguntas más recurrentes con respecto al la plataforma de FRED. Actualmente estamos sufriendo una transformación en la que los dispositivos se comunican con dispositivos, y dichas comunicaciones están creando nuevos modelos de negocio, productos y compañías. Aquí es donde aparece el concepto de Cloud Computing, ya que las PaaS funcionan sobre entornos Cloud. La Computación en la Nube se encuentra dentro de las Tecnologías Verdes, que hacen un uso eficiente de los recursos computacionales minimizando el impacto ambiental, maximizando su viabilidad económica, asegurando deberes sociales y promoviendo el reciclaje computacional. En los últimos años la información se ha convertido en uno de los recursos más valiosos para la economía y la vida cotidiana. Es por esto, que el poseerla es algo sumamente importante. Es necesario, que este esté disponible en cualquier momento o lugar de manera rápida, que sea fácil de compartir y que se pueda adaptar a nuestros requerimientos. Aquí se tratarán aspectos generales del tema, como la definición, tipos y características principales. Además, se presentarán ventajas y desventajas, de modo que cada quien pueda comprobar la eficiencia del Cloud Computing en la plataforma de FRED.

### Objetivo General.

El presente trabajo tiene como objetivo o propósito general conocer el funcionamiento, del Cloud computing en FRED utilizando Node-Red, identificando sus características principales y el uso de esta.

### Objetivos específicos 

Explicar el significado de Cloud Computing. Explicar: ¿En qué consiste el Cloud Computing?

Conocer las ventajas y desventajas de Cloud computing en la plataforma de FRED.

Ejecutar un ejemplo elaborado en FRED que consulte el clima en un servicio remoto, así mismo explicar el funcionamiento de este.

Identificar las principales características de SaaS, PaaS e IaaS.

### Estado del Arte.

### Concepto de Cloud Computing

Hace muchos años ya se introdujeron conceptos de Cloud Computing esto por John McCarthy en 1960, quien dijo en un discurso que “Algún día la computación podrá ser organizada como un servicio público” y haciendo una comparación con lo ocurrido en la distribución eléctrica a comienzos del siglo XX donde las grandes empresas tenían su propio generador de energía, ahora las empresas grandes constan de sus servidores, clúster o supercomputadoras [1]

Según la IEEE Computer Society define al Cloud Computing como: “Un paradigma en el cual la información permanente es almacenada en servidores en Internet y colocada (“cache”) temporalmente en clientes que incluyen computadoras de escritorio, centros de entrenamiento, tablets, notebooks, laptops, y dispositivos portátiles, etc.” [1] y según el autor: La computación en nube es un modelo de procesamiento de información en el que las capacidades de computación administrados centralmente son entregados como servicios, en una función de las necesidades, a través de la red a una variedad de dispositivos de cara al usuario. [1]Cloud Computing es la evolución de un conjunto de tecnologías que afectan al enfoque de las organizaciones y empresas en la construcción de sus infraestructuras de TI. Al igual que ha sucedido con la evolución de la Web, con la Web 2.0 y la Web Semántica, la computación en nube no incorpora nuevas tecnologías. Se han unido tecnologías potentes e innovadoras, para construir este nuevo modelo y arquitectura de la Web. En las últimas décadas los procesos de deslocalización e internacionalización de las grandes empresas, unidos a la explosión en el uso la de tecnologías de información y procesamiento de datos, han hecho que las necesidades de cómputo de las grandes empresas y organizaciones hayan crecido a un ritmo superior al que lo hacía la capacidad de cálculo de los ordenadores personales. Por este motivo, y para satisfacer las necesidades de los sistemas de computación más exigentes, se ha producido una interesante evolución de las arquitecturas de cálculo, basada fundamentalmente en la ejecución simultánea de procesos en múltiples equipos informáticos. [2]


En otras palabras, la definición de cloud computing es ofrecer servicios a través de la conectividad y gran escala de Internet. La computación en la nube democratiza el acceso a recursos de software de nivel internacional, pues es una aplicación de software que atiende a diversos clientes. Eso proporciona a las empresas mayor flexibilidad en relación a sus datos e informaciones, que se pueden acceder en cualquier lugar y hora, siendo esencial para empresas con sedes alrededor del mundo o en distintos ambientes de trabajo. Con un mínimo de gestión, todos los elementos de software de la computación en la nube pueden ser dimensionados bajo demanda, solo se necesita conexión a Internet.

### Internet of Things.

El término “Internet de las Cosas” (IoT) fue empleado por primera vez en 1999 por el pionero británico Kevin Ashton para describir un sistema en el cual los objetos del mundo físico se podían conectar a Internet por medio de sensores. En marzo de 2015, el Comité de Arquitectura de Internet (IAB) dio a conocer un documento para guiar la creación de redes de objetos inteligentes (RFC 7452),39 que describe un marco de cuatro modelos de comunicación comunes que utilizan los dispositivos de la IoT. En la discusión siguiente se presenta este marco y se explican las principales características de cada modelo. Las aplicaciones de IoT (Internet of Things) se han propagado de manera considerable en el sector industrial y su tecnología se ha utilizado durante décadas. Una de las características comunes de IoT es que los objetos deben estar “instrumentados”, interconectados y ser procesados de manera inteligente en cualquier lugar, cualquier momento, de cualquier forma y cualquier modo. La mayoría de las aplicaciones verticales de internet de las cosas utilizan normalmente tecnologías del nivel de red y una plataforma middleware del nivel aplicación tales como redes cableadas o inalámbricas estándares, DBMS, frameworks de seguridad, webs basadas en middlewares de nivel 3, PaaS (platform as a service) multiusuario, interfaces SOA (service-oriented architecture), etc. [1]

El Internet de las cosas (IoT) se puede definir como una red altamente interconectada de entidades heterogéneas, tales como, etiquetas, sensores, dispositivos embebidos, dispositivos portátiles, etc., que interactúan y se comunican entre sí en tiempo real. IoT revolucionará la manera en que las personas y las organizaciones interactúan con el mundo físico, la interacción con dispositivos domésticos, automóviles, plantas industriales, etc., sufrirá grandes modificaciones. También permitirá que muchos servicios como salud, educación y gestión de recursos, puedan ser mejorados para comodidad del cliente. [3]

Las tecnologías que soportan IoT, son muy amplias y su evolución constante. Debido a la revolución de internet que ha llevado a la interconexión entre las personas en una escala sin precedentes. Acelerando de esta manera la revolución que será la interconexión de los objetos para crear un entorno inteligente. Solo en el 2011, 9 millones de dispositivos se encontraban interconectados a nivel mundial, generando como expectativa la interconexión de 24 mil millones de dispositivos en el 2020. [4]



