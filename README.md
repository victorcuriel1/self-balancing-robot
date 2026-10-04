# Robot Autoequilibrado

Robot autoequilibrado de dos ruedas desarrollado utilizando Arduino Uno, sensor MPU6050, controlador de motores L298N y motores DC.

El sistema utiliza un controlador PID para ajustar la velocidad de los motores según la inclinación del robot y mantener el equilibrio dinámico.

## Componentes

- Arduino Uno
- Sensor MPU6050
- Driver de motores L298N
- 2 motores DC con reductora

## Parámetros PID

Kp = 60  
Ki = 70  
Kd = 1.4  
Setpoint = 173

## Librerías utilizadas

- PID_v1
- LMotorController
- I2Cdev
- MPU6050_6Axis_MotionApps20
- Wire

## Documentación

El informe completo del proyecto está disponible aquí:

[Ver informe del proyecto](docs/Informe_P1.pdf)

## Autores

- Victor Gabriel Curiel Gonzalez
- Hernan Gabriel Espinola Fleitas
- Ximena Lujan Quenhan Riveros

Universidad Nacional de Asunción  
Facultad de Ingeniería  
Ingeniería Mecatrónica

## Licencia

MIT License
