# отклонение от этого порядка ведет к ошибкам

conda create -n mlagents python=3.10.12 && conda activate mlagents

git clone https://github.com/Unity-Technologies/ml-agents.git

cd /path/to/ml-agents

pip3 install torch -f https://download.pytorch.org/whl/torch_stable.html

pip3 install -e ./ml-agents-envs

pip3 install -e ./ml-agents



импорт package.json из com.unity.ml-agents.extensions и com.unity.ml-agents

Проблемы с пакетами InputSystem --- добавил com.unity.inputsystem через git URL

импорт ML-Agents из project/assets в ассеты

The type or namespace name 'Recorder' does not exist in the namespace 'UnityEditor' --- установил Recorder

The type or namespace name 'Newtonsoft' could not be found --- тоже установил пакет через Package Manager (com.unity.nuget.newtonsoft-json)



mlagents-learn config/ppo/3DBall.yaml --run-id=first3DBall

tensorboard --logdir results


![Training Process](https://raw.githubusercontent.com/pav3l-abramov/AI_and_ML/main/lab4/8QqJ4aUvPyY.jpg)

![Result](https://raw.githubusercontent.com/pav3l-abramov/AI_and_ML/main/lab4/Sx3faOhVfzo.jpg)
