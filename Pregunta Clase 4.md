#Joan Carlo Gonzalez 1088322980#

*Tarea 3*

**¿ Cuales son las instrucciones de control de transferencia (CTI)?.**

<h2> Estas instrucciones mueven datos de una parte a otra del sistema; desde y hacia la memoria
principal, de y a los registros de datos, puertos de E/S y registros de segmentación.  
Las instrucciones de transferencia de datos son las siguientes:  </h2> 
<h2>  

+ MOV transfiere
+ XCHG intercambia
+ IN entrada
+ OUT salida
+ XLAT traduce usando una tabla
+ LEA carga la dirección efectiva
+ LDS carga el segmento de datos
+ LES carga el segmento extra
+ LAHF carga los indicadores en AH
+ SAHF guarda AH en los indicadores
+ PUSH FUENTE (sp) ¬ fuente
+ POP DESTINO destino ¬ (sp)

## Instrucciones de control de transferencia (CTI).
 Las instrucciones de control de tranferencia se conforman por instrucciones que modifican el **nPC**. (Next program Counter)**nPC** es un registro de 32 bits que contiene las dirección de la próxima instrucción a ejectutar. Las instrucciones de control de tranferencia son: 
 
 - Ramas condicionados **Branch** (**Bicc, FBfcc,CPccc**)
 - Llamados **Call and Link** (**CALL**)
 - Saltos **Jump and Link**(**JMPL**)
 - Retorno de excepciones **Return from Trap**(**RETT**)
 - Excepciones **Trap** (**TIcc**)
 
Las instrucciones de control de transferencia puedes ser categorizadas, acorde como se muestran en la tabla, además la dirección destino es calculada teniendo en cuenta (PC-relativo vs. register-indirect) y el tiempo relativo que toma la trasnferencia con respecto al (non delay,vs. delay vs. condicional-delay).
