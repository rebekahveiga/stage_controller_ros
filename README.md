# Trabalho 1 - Robô Navegador 🤖

Grupo: Nicolle Ribeiro (132815) e Rebekah Veiga (132812)

# Mundo Stage Controller ROS:
A imagem a seguir representa o mundo que está sendo simulado no Stage Controller:

![Screenshot from 2023-05-23 22-46-48](https://github.com/rebekahveiga/stage_controller_ros/assets/61145169/7eb43b92-2a2c-40d6-b4ef-c1ab4911bac9)


# Construído com

- ROS 1
- Python 3

# Versão do ROS

- ROS Noetic Ninjemys

# Como Executar o ambiente do simulador Stage

1. Primeiro, execute este comando para ter acesso aos comandos ROS e atualizar o ambiente:

```plaintext
source /opt/ros/noetic/setup.bash
source ./devel/setup.bash
```
2. Inicie o ROS Core com o comando:

```
roscore
```

3. Para abrir o mundo, execute o seguinte comando:

```
rosrun stage_ros stageros src/stage_controller/world/create_hokuyo.world
```

4. Agora, para executar o script python de controle do robô, utilize o comando abaixo:

```plaintext
rosrun stage_controller stage_controller.py
```
5. Caso queira informações da posição do Robô, utilize o seguinte comando em outra aba do terminal:

```
rostopic echo /odom/n1
```

# Link Youtube Simulação▶️:

- 
