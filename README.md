# proyecto PdM CESE2020

Se aplicará una máquina de estados para realizar el control de un robot móvil, 
se aplicará la modularización en archivos para separar la máquina de estados del hardware (sensores y actuadores).
Sensores: 	  Dos Sensores infrarrojos reflectivos (respuesta tipo On/OFF)
		          Pulsador
Actuadores: 	Driver de motores.  Dos Motores de CC.
Periféricos: 	GPIO, PWM



Breve descripción de cada estado

INICIO: 	Es el estado que tiene el sistema solo al iniciar. Es donde se inicializan y verifica todo lo necesario para el funcionamiento.
FOWARD: 	el robot no encuentra ningún obstáculo y avanza.
TURN_R: 	El robot encontró un obstáculo al frente y no detectó obstáculo a la derecha.
TURN_L: 	El robot encontró un obstáculo al frente y a la derecha.
STTOPED: 	El robot se encuentra detenido
