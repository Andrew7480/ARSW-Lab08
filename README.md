# ARSW-Lab08 Escalabilidad

## Integrantes
- Andres Cardozo
- Juan d Gomez

# Paso a Paso

## Escalabilidad horizontal


### Crear Security Groups

![alt text](image.png)


### Crear instancia base -  Verificar la instancia base

![alt text](image-1.png)

verificando:

![alt text](image-2.png)


###  Crear una AMI de la instancia base


![alt text](image-3.png)


### Crear Launch Template


![alt text](image-4.png)



## Alta disponibilidad con Load Balancer


### Crear Target Group

![alt text](image-5.png)



### Crear Application Load Balancer

![alt text](image-6.png)


### Crear Auto Scaling Group

![alt text](image-7.png)

 nuevas instancias creadas por el Auto Scaling Group:

![alt text](image-8.png)


### Verificar Target Group

![alt text](image-9.png)


### Probar el Load Balancer


![alt text](image-10.png)

![alt text](image-11.png)

