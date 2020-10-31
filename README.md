# aws-robomaker-tutorial

Este é um simples tutorial para configurar e executar uma similação na plataforma AWS RoboMaker da Amazon.

## Estrutura de Pastas

Para criar uma aplicação no RoboMaker um padrão estrutural de pastas deve ser sequido, neste link você encontrar mais detalhes.
[https://docs.aws.amazon.com/pt_br/robomaker/latest/dg/application-create-new.html](https://docs.aws.amazon.com/pt_br/robomaker/latest/dg/application-create-new.html)

### Comandos do terminal para criar a estrutura de pastas
```
mkdir -p robot_ws/src
```
```
cd robot_ws/src/
```
```
catkin_create_pkg robot_app std_msgs rospy
```
```
cd robot_app
```
```
mkdir -p launch scripts src/robot_app
```
```
touch src/robot_app/__init__.py
```
```
touch setup.py
```
Modifique o arquivo  **CMakeLists.txt** para o seu script e copie o conteúdo do arquivo **setup.py** deste repositório para o seu.

