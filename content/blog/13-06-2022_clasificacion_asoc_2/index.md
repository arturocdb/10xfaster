---
author: Charlie Do Amaral
categories:
- Algoritmos
date: "2022-02-28"
draft: false
excerpt: Los algoritmos de clasificación son utilizados en minería de datos, sobre bases de   datos transaccionales, permiten encontrar de forma eficiente "conjuntos de items            frecuentes", los cuales sirven de base para generar reglas de asociación. 
layout: single
subtitle: Análisis de algoritmos de clasificación asociativa.
title: Clasificación Asociativa parte 2
---

## Casos de uso
### 1. Colocación de productos
Uno de los casos de uso más común de los algoritmos de asociación es el **"product placement"** o colocación de productos en estanterías.

**Objetivo**. Identificar artículos que los clienten compran conjuntamente.

**Solución**. Procesar los datos de las terminales de punto de venta proporcionados por scanners de códigos de barra.

**Ejemplo**. Si un cliente compra pañales, es muy probable que compre cerveza (no se sorprenda si vé las cervezas colocadas al lado de los pañales en su súper).

### 2. Promociones y ofertas
Si por ejemeplo se identifica una regla {impresora} -> {tóner}. 

- **Tóner en el consecuente**
  + => Puede determinarse cómo incrementar sus ventas
- **Impresora en el antecedente**
  + => Puede determinarse qué productos se verían afectados si dejamos de vender impresoras.
- **Impresora en el antecedente y Tóner en el consecuente**
  + => Puede utilizarse para ver qué prodcutos deberían venderse con impresoras para promocionar las ventas de tóner.

### 3. Gestión de inventarios.

**Problema**. Veamos el siguiente caso. Una empresa de reparación de electrodomésticos quiere anticipar la naturaleza de las reparaciones que tendrá que realizar y mantener a sus vehículos equipados con las piezas que permitan reducir el número de visitas a casa de sus clientes.

**Solución**. Procesar los datos sobre herrammientas y piezas utilizadas en reparaciones previas para descubrir patrones de co-ocurrencia.

## Oportunidades adicionales para el comercio minorista
Los algoritmos de asociación son una potente herramienta que le permitirá encontrar patrones en la forma de venta conjunta de sus productos, revelando las reglas y asociaciones ocultas que se producen a la hora del consumo, permitiéndole establecer estrategias efectivas para la disposición (layout) de sus productos y realizar promociones más exitosas.

La principal tarea de un minorista es comprender quiénes son las personas que realizan compras en la tienda y, con la ayuda de este conocimiento, influir en la cantidad y calidad de las compras. Para hacer esto, debe estudiar el comportamiento de los compradores e identificar modelos típicos.

El estudio de las cestas de la compra permite explorar e interpretar la demanda de los clientes, comprender la relación entre los productos y las reglas para realizar una compra. En esencia, el análisis ayuda al minorista a reconocer las necesidades del comprador y formar una oferta rentable para su cliente.

### Beneficios del análisis de la cesta de compra
Los 3 principales beneficios que recibe un minorista al estudiar la cesta de la compra de sus clientes:

1. **Fidelizar a los clientes**: el surtido siempre tiene los productos correctos y las tiendas de la cadena cumplen con las expectativas de los visitantes.
2. **Aumentar los márgenes del negocio**: suministramos bienes que se entregan bien y rápidamente.
3. **La máxima intersección de las necesidades del cliente y los productos** que son de interés comercial.

