# Lab Mandatory 01

1. Branch Strategy Simulation
- Trunk Based Development
  Siguiendo el desarrollo basado en troncos genere la estructura de mi proyecto, generando una feature y generando un pull request para integrar con main
![image](https://github.com/LuisGutierrezRdz/lab-mandaroty01/assets/115661340/803ff9d2-f812-4d5d-a21b-cbe15e7d728b)
![image](https://github.com/LuisGutierrezRdz/lab-mandaroty01/assets/115661340/5ab37b0f-2b4b-46e1-993b-d60b6e40ab78)
  Para poder documentar el laboratorio genere otra feature con respectivo pull request para agregar el README.md
  ![image](https://github.com/LuisGutierrezRdz/lab-mandaroty01/assets/115661340/90f93773-f47d-4a96-b197-45831b430791)
 
- GitFlow
  Moviendonos a uso de gitFlow, generamos la ramas dev y qa
  
![image](https://github.com/LuisGutierrezRdz/lab-mandaroty01/assets/115661340/19bdda8e-7ced-4b03-8fda-77b80477b86f)

Voy a crear dos features que salgan de dev, una para generar un controlador que devuelva un Hello World y otro para Saludar (feature/hello y feature/greeting)

![image](https://github.com/LuisGutierrezRdz/lab-mandaroty01/assets/115661340/dfb4fee9-5082-4b08-be1e-4f453251a62a)

Una vez pasado el cambio a qa, simulamos que esa feature se probará y esperamos el VoBo para pase a PROD (main)

2. Conflict Resolution and Merging

- Tenemos la feature/greeting que salio al mismo tiempo de dev, como la feature/hello ya fue mezclada va tener conflictos, solucionamos y generamos el PR para mezclar en dev

![image](https://github.com/LuisGutierrezRdz/lab-mandaroty01/assets/115661340/7120a6a6-2571-4fb5-8138-f1452026ed7f)
![image](https://github.com/LuisGutierrezRdz/lab-mandaroty01/assets/115661340/a0b9481e-2e27-4155-a0e8-dea71b47b45b)

3. Pull Request and Code Review Simulation

Se va generar un PR para pasar los cambios de feature/greeting a qa