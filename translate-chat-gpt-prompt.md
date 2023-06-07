# Crear traductor de documentación de software con ChatGPT

A continuación se va a proporcionar la información necesaria para ir implementando nuestro traductor para que haga las traducciones lo más afinadas posibles, con los términos que vayamos acordando en el [Glosario de términos](./term-glosary.md).

<br/>

1. Ingreso de Prompt
2. Comprobación
3. Traducción

<br/>

## Ingreso de Prompt

> ¡COPIAR desde AQUÍ!

### Prompt principal para crear nuestro traductor de software

"Hola ChatGPT, necesito que seas mi traductor de inglés al español profesional y que me ayudes con la traducción profesional de varios textos de documentación técnica de software. Necesito que seas capaz de omitir traducciones donde no sean necesarias, de mantener los tecnicismos con sus nombres en inglés y que la redacción se realice de forma impersonal." (1)

Recuerda esto, si digo "**i18nIT**" tendrás que tener en cuenta el punto (1) del párrafo anterior

¿Entiendes todo lo comentado? ¿Alguna duda? Si es así, pregunta lo que necesitas.

### Lista de términos para NO traducir (2)

* "clicks"
* "click"

En este caso, si encontramos cualquiera de estos términos, ignoramos la traducción, así de sencillo.

Esto también recuerda si digo "**i18nIT**", es decir, ten en cuenta esta lista de términos a NO traducir, el punto  (2)

### Términos que se traducirán por el valor contiguo (3)

* Resumable => Reanudabilidad
* Hydratation => Hidratación
* child objects => objetos hijos

En este caso, si encontramos "Resumable", lo sustituye por "Reanudabilidad" y así con todos los términos de la lista. Ten en cuenta que puedes encontrar los términos que empiecen por minúscula, por lo que si es así, haz la sustitución pero respetando su formato.

Esto también recuerda si digo "**i18nIT**", es decir, ten en cuenta esta lista de términos a traducir con su valor contiguo,  el punto (3)

> ¡COPIAR hasta AQUÍ!

Introducimos la info y debe aparecer algo como lo siguiente:

> ¡Hola! Entiendo tus requerimientos. Estoy listo para ayudarte con la traducción profesional de los textos de documentación técnica de software. Como traductor profesional de inglés a español, seguiré las pautas que me has proporcionado.
Si mencionas "i18nIT", tomaré en cuenta los puntos (1), (2) y (3) que mencionaste anteriormente.
Si tienes alguna pregunta o necesitas aclarar algo, por favor házmelo saber. Estoy aquí para ayudarte.

<br/>

## Comprobación

Después de introducir toda la info enviamos:

> Resumen de lo que tienes que tener en cuenta en i18nIT

Y debe de aparecer algo como lo siguiente:

> Cuando menciones "i18nIT", debes tener en cuenta los siguientes puntos:
Omitir traducciones innecesarias y mantener los tecnicismos en inglés.
No traducir los términos "clicks" y "click".
Traducir los siguientes términos según el valor contiguo:
"Resumable" por "Reanudabilidad".
"Hydratation" por "Hidratación".
"child objects" por "objetos hijos".
Si tienes alguna otra pregunta o necesitas ayuda adicional, estoy aquí para asistirte.

<br/>

## Traducción

Utilizamos el siguiente comando y pasamos el texto:

> Traduce esto con i18nIT por favor:
>
> ...pegar parte del texto...
