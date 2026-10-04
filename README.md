# Robot Autoequilibrado

Robot autoequilibrado de dos ruedas desarrollado utilizando Arduino Uno, sensor MPU6050, controlador de motores L298N y motores DC.

El sistema emplea un controlador PID para ajustar continuamente la velocidad y dirección de los motores en función de la inclinación detectada por el sensor, permitiendo mantener el equilibrio dinámico del robot.

## Componentes

- Arduino Uno
- Sensor MPU6050
- Driver de motores L298N
- 2 motores DC con reductora
- Ruedas
- Estructura mecánica
- Fuente de alimentación

## Funcionamiento

El MPU6050 mide la inclinación y el movimiento del robot.  
Estos datos son procesados por el Arduino Uno, que utiliza un controlador PID para calcular la corrección necesaria.

La salida del PID controla el driver L298N, que ajusta la velocidad y dirección de los motores para mantener el robot en posición de equilibrio.

Flujo general del sistema:

`MPU6050 → Arduino Uno → Control PID → L298N → Motores DC`

## Parámetros PID

- Kp = 60
- Ki = 70
- Kd = 1.4
- Setpoint = 173

## Librerías utilizadas

- PID_v1
- LMotorController
- I2Cdev
- MPU6050_6Axis_MotionApps20
- Wire

## Código

El código principal del proyecto se encuentra en:

`self_balancing_robot.ino`

## Documentación

El informe completo del proyecto, incluyendo diseño, componentes, montaje, pruebas y conclusiones, está disponible aquí:

[Ver informe del proyecto](docs/Project_Report.pdf)

## Autores

- Victor Gabriel Curiel Gonzalez
- Hernan Gabriel Espinola Fleitas
- Ximena Lujan Quenhan Riveros

Universidad Nacional de Asunción  
Facultad de Ingeniería  
Ingeniería Mecatrónica

## Licencia

Este proyecto está distribuido bajo la licencia MIT.
