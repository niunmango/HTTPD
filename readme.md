# NGINX como load balancer frente a dos Apache
Archivos para una prueba de un servidor NGINX como proxy inverso para servir páginas de dos servidores Apache. En este ejemplo básico cada servidor Apache sirve una página diferente, en un entorno productivo habrá más servidores Apache todos ofreciendo la misma página. Para ejecutar, clonar el repositorio y una vez en el directorio ejecutar:

```bash
docker compose up -d
```