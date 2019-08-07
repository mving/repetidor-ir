# Repetidor-ir

El módulo receptor IR entrega en su salida una señal eléctrica cuya trama es copia fiel de la forma de onda 
generada por el mando a distancia accionado delante de él. Esta señal es aplicada al transistor inversor 
el cual adapta el nivel lógico para poder accionar el pin de reset del integrado 7555 el cual es un 555 de precisión. 
Este se encarga de re-generar una portadora de aproximadamente 40KHz sobre la cual se modula la señal recibida. 
Esta señal se aplica al transistor de salida el cual acciona el diodo emisor IR. El módulo receptor IR puede ser 
cualquiera de los utilizados en TV's o equipos de sonido. El foto diodo debe ser cualquiera de los usados en mandos 
a distancia. El circuito se alimenta de 5Vcc y puede ser alimentado a pilas o fuente.