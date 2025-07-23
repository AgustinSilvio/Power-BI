## Let's Connect :handshake:

<a href="https://www.linkedin.com/in/agustinsilviorojas/"><img src="https://img.shields.io/badge/linkedin-%230077B5.svg?&style=for-the-badge&logo=linkedin&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
<a href="mailto:silvioagustin12345@gmail.com"><img src="https://img.shields.io/badge/gmail-%23D14836.svg?&style=for-the-badge&logo=gmail&logoColor=white" /></a>&nbsp;&nbsp;&nbsp;&nbsp;
<a href="https://youtube.com/shorts/E4mJ0AFBq1Y?si=s4gy4ucUrY2BRd90"><img src="https://cdn2.iconfinder.com/data/icons/social-media-2285/512/1_Youtube_colored_svg-128.png" width="40"></a>
<a href="mailto:agustinsilviorojas@outlook.com.ar"><img src="https://cdn0.iconfinder.com/data/icons/logos-microsoft-office-365/128/Microsoft_Office-07-256.png" width="40"></a>
<hr>

# Power-BI
Este repositorio es para aportar algunos consejos de un reporte simulando un perfil de cartera con datos ficticios de forma anónima. Te invito a comentar y aportar tus propias recomendaciones.

> ⚠️ *Los datos y medidas han sido modificados con fines ilustrativos, por lo que los valores pueden no tener sentido real ya que el objetivo es simplemente ilustrativo..*


# Siniestros

Ejemplo de perfil de cartera de Siniestros. En este caso el producto es vida grupo. 

![desplegar opcion de mas filtros](https://github.com/user-attachments/assets/ec63ec6f-d1f2-401c-afed-9abb40d64a60)


## 🧩 Organización del Modelo

Una buena práctica es mantener **ordenadas las vistas de relaciones** para facilitar la comprensión del modelo de datos

<img width="919" height="555" alt="diagrama entidad relación" src="https://github.com/user-attachments/assets/4af30b03-e403-4faf-8ee8-61563ad52469" />



## Perfil Vida grupo
Es importante que haya un botón para limpiar los filtros y que se vea la fecha de la última actualización de la información.

Hay un cuadro de aclaraciones para que se sepa que consideraciones se deben tomar respecto a la información y otros dos botones que llevan a otras pagínas para ver otro análisis y gráficos.
El primer intervalo sirve para identificar aquellos casos en los que la suma asegurada fué cero, estaba vacio, null o simplemente no había un número, después de cambiar el formato a hace columna en power query para que sea formato número y específicamente sea moneda.

<img width="788" height="503" alt="perfiles de cartera Vida y Ap" src="https://github.com/user-attachments/assets/566dde7d-fe9f-4299-9660-f51c58927cef" />


# Percentiles
Por ejemplo además de elegir los intervalos de Suma asegurada según la prioridad y los montos de cada capa de contratos de reaseguro; Se puede hacer los intervalos según percentiles para la gestión.

<img width="894" height="503" alt="ramo incendio 1% y 5%" src="https://github.com/user-attachments/assets/43f3bb14-8979-477e-8a70-b69fcb5609c2" />


# Matriz Intervalos de SA e Intervalos de Edades

Usé el formato condicional de color de fuente para la medida de % y color de fondo para la medida de valor absoluto.
Se pueden seleccionar de forma dinámica ambos tipos de medida según lo que quiera ver el usuario.

![medidas dinamicas saldo deudor](https://github.com/user-attachments/assets/01449bb5-7de8-4f5a-8dc8-d63b5c961644)


# Matriz dinámica de siniestros
Incluso se puede seleccionar un campo de forma dinamica para la matriz.

<img width="893" height="501" alt="Siniestros VG perfil cartera" src="https://github.com/user-attachments/assets/9e7853c4-0ca3-490e-a419-6524f66b4dc1" />


## ✅ Recomendaciones Finales

- Mantener una estructura clara y navegable.
- Usar botones y filtros para mejorar la experiencia del usuario.
- Documentar las transformaciones y medidas utilizadas.

¡Muchas gracias!
