# PyPuma

# Acerca del proyecto

PyPuma es un proyecto del semillero de investigacion Tecnología de materiales emisores de luz dirigido por el docente Germán Aníbal Méndez Merchán de la Universidad Catolica de Colombia el cual busca hacer uso del programa Pointwise Unconstrained Minimization Approach (P.U.M.A.) con el fin de en solucionar la estimación del espesor y las constantes ópticas de películas delgadas utilizando únicamente datos de transmisión.

Este programa se usa con la finalidad de hallar valores óptimos para transmitancia, parámetros ópticos, índice de absorción y propiedades intrínsecas de las capas físicas usadas para el desarrollo de un OLED como el grosor y el material. Obteniendo resultados fiables de la simulación con todos estos parámetros, se buscan condiciones especiales y especificas que satisfagan el comportamiento deseado, además de buscar una optimización en los recursos económicos y físicos para el desarrollo del OLED. Sin embargo, la versión libre tiene muy pocos materiales implementados, así como carencia de opciones a la hora de realizar la simulación, es por este motivo que se busca modificar y agregar funcionalidades a este software que permitan hallar parámetros óptimos para una posterior prueba de laboratorio.

Se recurre a este lenguaje de programación para el desarrollo del proyecto, dado que el software P.U.M.A. esta implementado en C lo que lo hace bastante complejo de modificar y analizar. Sin embargo, esto más allá de representar una desventaja, es una ventaja, puesto que la flexibilidad y facilidad para manejar Python favorece la implementación de funcionalidades requeridas para las pruebas y manejabilidad del software, debido a que Python también cuenta con un apartado y librerías específicamente diseñadas para el desarrollo de interfaces de usuario graficas permitiéndonos manejar PUMA de una forma más dinámica y sencilla.

# Google Colaboratory

Google colaboratory, o por su abreviatura “colab” es una herramienta desarrollada por Google, la cual dispone de múltiples unidades de hardware que están a disposición de los usuarios. Dicha herramienta es de uso gratuito, sin embargo, posee un factor limitante: las unidades de hardware disponibles. Según estas unidades de hardware, se prestará el servicio con mayor o menor limitación. También influye otro factor, el uso constante y arduo de esta plataforma, desencadenara en algunas limitaciones para el usuario, es decir, que el uso es proporcional a las limitaciones impuestas, para garantizar el acceso a usuarios que requieran de procesos mas simples. Los programas desarrollados en Google Colab pueden ser almacenados en diversos espacios: Google Drive, GitHub, Documentos de Google u Hojas de Calculo de Google. Google Colab dispone de modelos GPU como Nvidia K80, T4, P4 y P100. El usuario no puede escoger el modelo de GPU que se usara en su proyecto, por tanto, este es escogido de manera arbitraria y aleatoria por Google Colab. Sin embargo, hay una opción para garantizar las unidades más rápidas y para ello es necesaria una suscripción premium a la plataforma.

# Google Colaboratory y PyPuma

El uso de esta herramienta durante el desarrollo del proyecto se destaca en dos aspectos importantes. El primero, es la facilidad que ofrece al trabajar en Python, esto es un factor crucial, debido a que podemos usar P.U.M.A en la nube por lo que podemos realizar pruebas necesarias para asegurar los resultados óptimos esperados de forma remota y de forma gratuita.

En segundo lugar, se usa esta herramienta para cubrir una deficiencia que tiene P.U.M.A., pues este no cuenta con una interfaz gráfica, y debido a la facilidad que ofrece Google Colab para enlazar tanto el software base con python, ventaja que nos  ha permitido un avance considerable en las funcionalidades a realizar. El mayor obstáculo que se ha presentado a causa de Google Colab es su factor limitante puesto que la realización de pruebas genera un considerable 

#Referencias

Google. (s.f.). Google. Obtenido de Google Colaboratory: https://research.google.com/colaboratory/intl/es/faq.html
Montero, A. F. (2013). Python 3 al descubierto. Mexico: Alfaomega Grupo Editor, S.A. de C.V.
State University of Campinas AND University of Sao Paulo. (s.f.). Pointwise Unconstrained Minimization Approach. Obtenido de Pointwise Unconstrained Minimization Approach: https://www.ime.usp.br/~egbirgin/puma/
 Challenger-Pérez, Ivet, & Díaz-Ricardo, Yanet, & Becerra-García, Roberto Antonio (2014). El lenguaje de programación Python. Ciencias Holguín, XX(2),1-13.[fecha de Consulta 20 de Agosto de 2021]. ISSN: . Disponible en:   https://www.redalyc.org/articulo.oa?id=181531232001 (Montero, 2013)
