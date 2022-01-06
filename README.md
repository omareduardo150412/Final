# Final
Prueba FInal

Usar Docker

1.- En donde esta el proyecto ingresar la ruta en su cmd o powershell -> .\mvnw.cmd clean package
2.- Poner -> docker build -t rest-paises:v1 .
3.- crear la network con -> docker network create springcloud
4.- Corremos la imagen -> docker run -p 8002:8002 --name rest-paises -network springcloud rest-paises:v1

