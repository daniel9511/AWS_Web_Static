# Despliegue de Sitio Web Estático en AWS

Este proyecto consiste en el despliegue de un sitio web estático en AWS utilizando servicios en la nube para garantizar su disponibilidad y acceso en línea.

## Descripción

El proyecto despliega un sitio web estático personalizado en la nube de AWS. Este sitio web contiene información sobre mi currículum y experiencia profesional, y está compuesto únicamente por un archivo `index.html`.

## URL del Sitio Web

El sitio web está desplegado en línea y es accesible a través de la siguiente URL:
[https://my-curriculum-daniel-cortes.xyz/](https://my-curriculum-daniel-cortes.xyz/)

## Servicios Utilizados

El despliegue del sitio web estático en AWS se realiza utilizando los siguientes servicios:

- **Amazon Route 53**: Se utiliza para la administración de los registros DNS y para asociar el nombre de dominio personalizado con el sitio web desplegado en AWS.

- **Amazon CloudFront**: Se utiliza como CDN (Content Delivery Network) para distribuir el contenido estático del sitio web de manera eficiente a nivel mundial, mejorando la velocidad de carga y la experiencia del usuario.

- **AWS Certificate Manager**: Se utiliza para gestionar los certificados SSL/TLS necesarios para habilitar HTTPS en el sitio web, garantizando la seguridad de la comunicación entre el navegador del usuario y el servidor web.

- **Amazon S3 Bucket**: Se utiliza para almacenar los archivos estáticos del sitio web, como HTML, CSS, JavaScript e imágenes. El bucket de S3 se configura para alojar el contenido del sitio web y se integra con CloudFront para la distribución global del contenido.

- **/index.html**: Contiene el contenido principal del sitio web.

![alt text](https://github.com/daniel9511/AWS_Web_Static/blob/main/Proyecto%20AWS%20Web%20Estatica.jpg)
