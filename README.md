# Práctico Primer Parcial de SPD
![Tinkercad](./imagenes/at.png)


## Integrantes
- Juliana Gimena Grajeda

## Proyecto: Alarma de Incendios

### Descripción..
El siguiente programa busca simular el circuito de una alarma de incendios. El mismo categoriza la temperatura ambiente actual hasta dar con la temperatura promedio en la que se indica que podría haber un incendio, activando una señal con las luces led incluidas.

## Función Principal
~~C
void loop()
{
  lecturaDelSensor = analogRead(A0);
  temperatura = map(lecturaDelSensor,20,358,-40,125);
  int nivel = categorizar_temperatura(temperatura);
  manejar_botones(nivel); 
  
  if (bandera_alarma)
  {
    encender_alarma(nivel);
  }
  else
  {
    apagar_leds();
  }
}
~~

## Link al Proyecto
- [Click aquí para ser dirigido al proyecto](https://www.tinkercad.com/things/gUTzVkEOkP6-practico-primer-parcial/editel?sharecode=pjgnvAwwcNJcBiWY2Rh3e7YFxJmLNvZ8M6qPUQ6q05s)

