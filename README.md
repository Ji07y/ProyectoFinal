# ProyectoFinal
 
# Juego de Escapada con Agente ML-Agent

Bienvenido al juego de escapada, donde te enfrentarás a desafiantes escenarios controlados por agentes de inteligencia artificial entrenados con ML-Agent. El objetivo del juego es pasar de escenario en escenario, evitando a los agentes entrenados y buscando llaves para activar plataformas móviles que te permitirán avanzar hacia el siguiente nivel.

# Objetivo del Juego
Escapa de Agentes Entrenados: Los agentes de inteligencia artificial están entrenados para perseguirte. Deberás evitarlos mientras exploras los niveles.

Encuentra Llaves: Busca llaves escondidas en el entorno. Estas llaves son esenciales para activar las plataformas móviles que te llevarán al siguiente escenario.

Activa Plataformas Móviles: Una vez encuentres una llave, úsala para activar plataformas móviles estratégicamente ubicadas. Estas plataformas te ayudarán a superar obstáculos y avanzar en el juego.

# Cómo Jugar

Movimiento: Utiliza las teclas de dirección o el joystick para moverte por el entorno.
Buscar Llaves: Explora cada rincón para encontrar las llaves necesarias para avanzar.
Evitar Agentes: Mantén la distancia de los agentes entrenados para evitar ser atrapado.
Activar Plataformas Móviles: Usa las llaves para activar plataformas móviles y desbloquear el siguiente escenario.
Descripción del Script AgentController
Este script define el comportamiento del agente de inteligencia artificial en el juego. Aquí hay una breve descripción de sus funciones principales:

OnEpisodeBegin: Inicia cada episodio colocando al agente y al objetivo en posiciones aleatorias en el entorno.

CollectObservations: Recolecta observaciones del entorno, incluyendo la posición actual del agente y del objetivo, para el entrenamiento del modelo de ML-Agent.

OnActionReceived: Recibe acciones continuas del modelo entrenado y ajusta la posición del agente en consecuencia.

Heuristic: Proporciona una interfaz manual para controlar al agente, útil para pruebas y depuración.

OnTriggerEnter: Detecta colisiones cuando el agente toca objetos, como objetivos o paredes. Otorga recompensas o penalizaciones según la interacción.
