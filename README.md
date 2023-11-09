<p align="left">
    &nbsp中文&nbsp ｜ <a href="README_en.md">English</a>
</p>
<br>

> **warning**
> 
> **CareGPT(原名CareLlama) 为MPU的医疗大语言模型IvyGPT的分支，其存在意义是探索医疗数据、医疗LLM训练与部署相关的工作研究。**

<div align="center">
  <a href="https://github.com/WangRongsheng/CareGPT">
    <img src="./assets/images/caregpt.jpg" alt="Logo" height="280">
  </a>

  <p align="center">
    <h3> CareGPT (关怀GPT)：医疗LLM，开源驱动，共创健康未来 </h3>
    <p align="center">
      <em>资源整合 / 开源模型 / 丰富数据 / 高效部署 </em>
    </p>
    <p align="center">
      <a href='https://github.com/WangRongsheng/CareLlama'>
            <img src='https://img.shields.io/badge/Project-Page-Green'>
      </a>
      <a href='https://github.com/WangRongsheng/CareLlama'>
            <img src='https://img.shields.io/badge/Paper-Arxiv-red'>
      </a>
      <a href="#">
        <img alt="GitHub Contributors" src="https://colab.research.google.com/assets/colab-badge.svg" />
      </a>
      <a href='https://huggingface.co/wangrongsheng'>
        <img src='https://img.shields.io/badge/%F0%9F%A4%97%20Hugging%20Face-Spaces-blue'>
      </a>
      </br>
      <a href="https://github.com/WangRongsheng/CareLlama/graphs/contributors">
        <img alt="GitHub Contributors" src="https://img.shields.io/github/contributors/WangRongsheng/CareLlama" />
      </a>
      <a href="https://github.com/WangRongsheng/CareLlama/issues">
        <img alt="Issues" src="https://img.shields.io/github/issues/WangRongsheng/CareLlama?color=0088ff" />
      </a>
      <a href="https://github.com/WangRongsheng/CareLlama/pulls">
        <img alt="GitHub pull requests" src="https://img.shields.io/github/issues-pr/WangRongsheng/CareLlama?color=0088ff" />
      </a>
      <a href=href="https://github.com/WangRongsheng/CareLlama/stargazers">
        <img src="https://img.shields.io/github/stars/WangRongsheng/CareLlama?color=ccf">
      </a>
      <a href=href="https://github.com/WangRongsheng/CareLlama">
        <img src="https://img.shields.io/github/repo-size/WangRongsheng/CareLlama.svg?style=flat-square">
      </a>
      </br>
      <a href=href="https://github.com/WangRongsheng/CareLlama">
        <img src="https://visitor-badge.laobi.icu/badge?page_id=https://github.com/WangRongsheng/CareLlama">
      </a>
      <a href=href="https://github.com/WangRongsheng/CareLlama">
        <img src="https://img.shields.io/github/last-commit/WangRongsheng/CareLlama">
      </a>
      <a href="https://github.com/WangRongsheng/CareLlama/blob/main/LICENSE">
        <img alt="GitHub Contributors" src="https://img.shields.io/badge/License-CC%20BY--NC--SA%204.0-lightgrey.svg" />
      </a>
  </p>
</div>

<!--center><kbd><img src="./docs/images/usage.png" height="550px"/></kbd></center-->

<p align="center">
      <a href="#"><strong>视频教程</strong></a>
      <a href="https://github.com/WangRongsheng/CareLlama/tree/main#5gradio%E9%83%A8%E7%BD%B2"><strong>安装部署</strong></a>
      <a href="https://huggingface.co/spaces/wangrongsheng/CareLlama"><strong>在线体验</strong></a>
</p>

![](./assets/images/hx.png)

⚡Características:

Se agregó la implementación de ajuste de ChatGPT y recomendó amigos con créditos para realizar experimentos de ajuste en ChatGPT;
Admite el modelo de ajuste de implementación ChatGPT-Next-Web ;
Admite modelos de ajuste fino de implementación de Gradio ;
Admite entrenamiento de modelos de serie completa LLaMA y LLaMA-2;
Admite LoRA y QLoRA, incluida la posterior capacitación de aprendizaje reforzado de PPO y DPO;
Admite preguntas y respuestas combinadas con modelos y base de conocimientos;
Información de material de orientación médica de código abierto para más de 60 departamentos hospitalarios ;
Se desarrolló una herramienta para respaldar la destilación de datos médicos del modelo GPT-4/ChatGPT , que puede generar por lotes diversos datos para crear una base de conocimientos y realizar ajustes;
Agrega una gran cantidad de LLM médicos de código abierto, datos médicos para capacitación de LLM, datos de implementación de LLM, evaluación de LLM y compilación de recursos de LLM relacionados;
Participamos en la evaluación de la lista CMB de LLM médicos - IvyGPT . En la prueba, estábamos por delante de ChatGPT y varios LLM médicos de código abierto;
Contamos con múltiples LLM médicos de código abierto capacitados en diferentes LLM básicos basados ​​en nuestros propios conjuntos de datos. Puede descargarlos directamente para experimentar;
🎁Conjunto de datos 
Datos previos al entrenamiento 
LLM-Pretrain-FineTune/data_pretrain
MédicoGPT/preentrenamiento
zyj
TCM-Ancient-Books (casi 700 textos antiguos de medicina china)
Datos de entrenamiento supervisados 
icliniq-10k(es)
HealthCareMagic-100k(es)
ShenNong_TCM_Dataset
✅ ChatMed_Consult_Dataset
Datos-de-diálogo-médico-chino
cMedQA2
✅ Huatuo-26M
cMedQA2
webMedQA
PubMedQA
CMCQA
✅ QiZhenGPT
✅ LLM-Pretrain-FineTune/data_sft
Sistema de diálogo médico
IMCS-V2
CHIP-MDCFNPC
MedDG
✅ HuatuoGPT-sft-datos-v1
MédicoGPT/ajuste fino
✅ shibing624/médico
medAlpaca/datos
✅Zhongjing /sft
diálogo_medico
huatuo_enciclopedia_qa
Med-ChatGLM/datos
CMB
GenMedGPT-5k(es)
Alpaca-CoT(general)
✅ DISCO-Med-SFT
Datos de entrenamiento de recompensa 
GPT médico/recompensa
Zhongjing/rw
comparación_gpt4_data
HH-RLHF
Ultrafeedback
🗜️Capacitación de proceso completo 
1. Instalar dependencias 
conda create -n llm python=3.11
conda activate llm
python -m pip install -r requirements.txt
Descarga del modelo LLaMA: https://blog.csdn.net/u014297502/article/details/129829677
# 转为HF格式
python -m transformers.models.llama.convert_llama_weights_to_hf \
    --input_dir path_to_llama_weights --model_size 7B --output_dir path_to_llama_model
Descarga del modelo LLaMA-2: https://huggingface.co/meta-llama
2.Configuración de datos 
Configuración del conjunto de datos, formato de datos PT, SFT, RW
3. Configuración de entrenamiento 
Parámetros e instrucciones de entrenamiento.
4. Configuración de inferencia 
Parámetros e instrucciones de inferencia.
5.Implementación de Gradio 
Instrucciones de implementación de Gradio
6. Implementación de ChatGPT-Next-Web
Siguientes instrucciones de implementación
💫Experiencia práctica 
En CareGPT, la segmentación de palabras chinas no se agrega ni se reentrena al modelo de segmentación de palabras, pero el efecto sigue siendo prometedor;
Todo el proceso de formación de LLM incluye: formación previa, ajuste fino supervisado, modelo de recompensa y aprendizaje reforzado. En la mayoría de los casos, el ajuste fino supervisado puede satisfacer sus propias necesidades ;
Cuando la potencia informática es suficiente, se recomienda utilizar datos médicos y datos de corpus generales para la capacitación , de modo que el modelo no solo pueda tener capacitación y aprendizaje médicos, sino que también mantenga capacidades generales (como seguir instrucciones);
No espere que un LLM médico pueda satisfacer todas las necesidades. Un enfoque razonable puede ser una base de conocimientos actualizada en tiempo real + un LLM médico ajustado (como ChatLaw );
La serie de modelos BLOOMZ se entrenó utilizando el corpus PILE, que contiene varios textos médicos, incluidos PubMed Central, PubMed Abstractsetc. Estos valiosos textos han enriquecido enormemente el sistema de conocimiento médico del modelo BLOOMZ, por lo que muchos proyectos de código abierto darán prioridad a BLOOMZ como modelo base para el ajuste médico;
(2023.08.26) ChatGPT está entrenado en base a Code GPT. ¿Usaremos CodeLLaMA para ajustar las tareas posteriores para lograr mejores resultados que el ajuste fino en LLaMA-1/2?
La combinación de nuestro trabajo reciente con muchos trabajos publicados recientemente demuestra: en la era LLM, la 质量 > 数量verdad de los datos, como: ¡ Menos es más! Entregado a Qingyuan && Caspian | Uso de 200 datos para ajustar el modelo, superando MiniGPT-4 ! , los datos SFT a gran escala debilitarán el LLM de tareas posteriores o perderán ICL, CoT y otras capacidades;
Para los modelos verticales, tal vez deberíamos prestar más atención al proceso PT en lugar de recopilar millones de datos SFT para capacitación. Nuestra sugerencia es 大规模预训练+小规模监督微调=超强的LLM模型;
Aún no se ha abierto un buen LLM médico previamente capacitado en la comunidad de código abierto, y espero que alguien pueda complementar ese trabajo;
¿La capacitación previa puede infundir conocimiento, mientras que el ajuste fino supervisado solo activa las capacidades del dominio (no puede centrarse en el conocimiento)? ¿El conocimiento previo a la capacitación debería reflejar el conocimiento de ajuste supervisado? ¿Las decenas de GB de conocimiento del corpus pre-entrenado se verán abrumadas por el conocimiento del modelo original pre-entrenado de billones de tokens?
El entrenamiento previo secundario de una gran cantidad de datos requiere comparar varios tipos de otros datos: (1) Una vez completado el entrenamiento del modelo de lenguaje, se han determinado las partes responsables de cada área de los parámetros. que no está disponible durante el entrenamiento previo, los parámetros aumentarán. Los cambios de amplitud causan la pérdida de toda la capacidad del modelo de lenguaje; (2) Para el entrenamiento previo secundario de datos a gran escala, de 5 a 10 veces los datos en el original la capacitación previa debe agregarse, mezclarse y capacitarse en conjunto;
La fase de ajuste de la instrucción no puede llevar a cabo demasiadas rondas de capacitación: (1) Entrenar múltiples EPOCH en una pequeña cantidad de datos puede causar cambios en áreas clave del lenguaje, lo que lleva a la falla de todo el modelo; (2) Multa de instrucción -ajuste para mejoras de tareas específicas. Para garantizar que las áreas clave de las capacidades del lenguaje del modelo no se ajusten significativamente, es necesario agregar datos de ajuste fino de instrucción general o datos de preentrenamiento;
Los datos de entrenamiento deben controlar estrictamente el ruido: (1) Si aparece una pequeña cantidad de datos de ruido continuo en los datos previos al entrenamiento, como repetición continua de palabras, secuencias sin palabras, etc., puede provocar ajustes en dimensiones específicas, lo que provocará el PPL general del modelo fluctúa significativamente; (2) Si hay una gran cantidad de fragmentos de instrucción en las instrucciones de ajuste fino supervisadas que no coinciden con el modelo de lenguaje grande original, también puede hacer que el modelo ajuste dimensiones específicas, reduciendo así significativamente el rendimiento general del modelo;
Al ajustar un modelo grande con datos mixtos de múltiples capacidades, aparecerá: alto conflicto de recursos y baja ganancia de recursos, por lo que mezclar diferentes datos para el ajuste fino requiere ciertas habilidades de ingeniería;
En términos generales, existe una diferencia de rendimiento no despreciable entre lora y el ajuste completo (por ejemplo, LoRA da como resultado un rendimiento entre un 4% y un 6% menor en comparación con el ajuste fino completo );
Importante

¡ Todos son bienvenidos a agregar nuevas experiencias a ISSUE !

11, 12, 13 La metodología proviene del modelo de 13 mil millones de lenguajes grandes. ¡Cambiar solo un peso perderá por completo la capacidad del lenguaje! Las últimas investigaciones del Laboratorio de Procesamiento del Lenguaje Natural de la Universidad de Fudan .

14 Metodología de cómo las habilidades en modelos de lenguaje grandes se ven afectadas por la composición de datos de ajuste supervisado

🧰Modelo de código abierto 
escenario	Introducción a las pesas	enlace de descarga	Características	modelo base	método de ajuste fino	conjunto de datos
🌟Supervisión y puesta a punto	Los datos de diálogo de varios turnos se entrenan en base a LLaMA2-7b-Chat	⚙️CareLlama2-7b-chat-sft-multi , 🧰CareLlama2-7b-multi	Excelentes habilidades de conversación en varios turnos.	LLaMA2-7b-Chat	QLoRA	milímetros
Supervisar el ajuste	Se entrenan datos ricos y eficientes del diálogo médico-paciente en base a LLaMA2-7b-Chat	⚙️CareLlama2-7b-chat-sft-med	Excelentes capacidades de diagnóstico de enfermedades del paciente.	LLaMA2-7b-Chat	QLoRA	mmm
Supervisar el ajuste	Los datos mixtos se entrenan en base a LLaMA-7b.	⚙️CareLlama1-7b-merge	Mejores habilidades de conversación médica.	Llama-7b	lora	mmmmm
Supervisar el ajuste	Los datos mixtos se entrenan en base a LLaMA2-7b-Chat.	⚙️CareLlama2-7b-merge , 🧰CareLlama2-7b-merge-mix	Mejores habilidades de conversación médica.	LLaMA2-7b-Chat	QLoRA	mmmmm
DPO		⚙️CareLlama2-7b-merge-dpo				rlhh
Supervisar el ajuste	Se entrenan más datos mixtos basados ​​en LLaMA2-7b-Chat	⚙️CareLlama2-7b-super , 🧰CareLlama2-7b-super-mix	Mejores habilidades de conversación médica.	LLaMA2-7b-Chat	QLoRA	mm,ls,ks,mc,sra,qz,hm
Supervisar el ajuste	Los datos de diálogo de varios turnos se entrenan en base a Baichuan-13B-Chat	⚙️Baichuan-13B-Chat-sft-multi	Excelentes habilidades de conversación en varios turnos.	Baichuan-13B-Chat	QLoRA	milímetros
Supervisar el ajuste	Los datos de la conversación mixta se entrenan en base a Baichuan-13B-Chat	⚙️Baichuan-13B-Chat-sft-merge	Mejores habilidades de diálogo médico-paciente	Baichuan-13B-Chat	QLoRA	mmmmm
Supervisar el ajuste	Los datos de la conversación mixta se entrenan en base a Baichuan-13B-Chat	⚙️Baichuan-13B-Chat-sft-super , 🧰Baichuan-13B-Chat-sft-super-mix	Mejores habilidades de diálogo médico-paciente	Baichuan-13B-Chat	QLoRA	mm,ls,ks,mc,sra,qz,hm
🌟Supervisión y puesta a punto	Los datos de diálogo de múltiples turnos se entrenan en base a QWen-7B	🧰carellm	Excelentes habilidades de conversación en varios turnos.	QWen-7B	QLoRA	milímetros
Supervisar el ajuste	Los datos de conversaciones de varios turnos se entrenan en función de QWen-14B-Chat	⚙️careqwen-14B-Chat-sft-multi	Excelentes habilidades de conversación en varios turnos.	QWen-14B-Chat	QLoRA	milímetros
Supervisar el ajuste	Los datos de diálogo de varios turnos se entrenan en base a InternLM-20B-Chat	⚙️careinternlm-20B-Chat-sft-multi , 🧰careinternlm-20B-Chat-sft-multi-mix	Excelentes habilidades de conversación en varios turnos.	PasanteLM-20B-Chat	QLoRA	milímetros
🌟Supervisión y puesta a punto	Los datos del diálogo de rondas múltiples se entrenan en base a Baichuan2-13B-Chat	⚙️Baichuan2-13B-Chat-sft-multi , 🧰Baichuan2-13B-Chat-sft-multi-mix	Excelentes habilidades de conversación en varios turnos.	Baichuan2-13B-Chat	QLoRA	milímetros
Cómo utilizar :

Descargue el modelo base correspondiente;
Si es LLaMA se convertirá a formato HF , si es LLaMA-2 y la descarga es en formato HF no se requiere conversión;
Descargue los pesos que desea cargar arriba;
Comience a usar nuestro modelo basado en la configuración de inferencia ;
💯Evaluación del modelo 
Modelo	Institución	Puntaje
ShuKunGPT	Tecnología Shukun	64,44
GPT-4	AbiertoAI	58,37
Baichuan2-53B	Inteligencia de Baichuan	45,69
ChatGLM2-6B	Espectro de sabiduría IA	44,91
Baichuan-13B-chat	Inteligencia de Baichuan	41,63
IvyGPT (Baichuan2-13B+10W)	Universidad Politécnica de Macao	38,54
ChatGPT	AbiertoAI	38.09
IvyGPT (Baichuan-13B+10W)	Universidad Politécnica de Macao	34,60
ChatGLM3-6B	Espectro de sabiduría IA	33,76
HuatuoGPT (BLOOMZ)	La Universidad China de Hong Kong (Shenzhen)	31.38
IvyGPT (Qwen-7B+PT-WiNGPT3.2 mil millones+10W)	Universidad Politécnica de Macao	28.26
MédicoGPT	-	26,45
ChatMed-Consulta	Universidad Normal del Este de China	21.71
Bentsao	Instituto de Tecnología de Harbin	21.25
ChatGLM-Med	Instituto de Tecnología de Harbin	20.67
IvyGPT (LLaMA-2-7B+220W)	Universidad Politécnica de Macao	18.55
DoctorGLM	Universidad Tecnológica de Shanghai	7.63
BianQue-2	Universidad Normal del Este de China	7.26
Modelo	Tasa de no alucinaciones
ERNIE-Bot	69,33%
Baichuan2-53B	68,22%
ChatGLM-Pro	61,33%
GPT-4-0613	53,11%
QWen-14B-Chat	46,89%
Baichuan2-13B-Chat	42,44%
Baichuan2-7B-Chat	40,67%
GPT3.5-turbo-0613	39,33%
ChatGLM2-6B	34,89%
Base Baichuan2-13B	33,78%
Baichuan-13B-Chat	31,33%
Base Baichuan-13B	25,33%
Base Baichuan2-7B	25,33%
Base Baichuan-7B	22,22%
Referenciado desde: 2310.03368.pdf

📳Presentación de resultados 


Ver más demostraciones
🍰Descargo de responsabilidad 
Los recursos relacionados con este proyecto son únicamente para investigación académica y están estrictamente prohibidos para uso comercial. Cuando utilice piezas que incluyan código de terceros, siga estrictamente el acuerdo de código abierto correspondiente. El contenido generado por el modelo se ve afectado por factores como el cálculo del modelo, la aleatoriedad y la pérdida de precisión de la cuantificación, y este proyecto no puede garantizar su precisión. Incluso si el resultado del modelo de este proyecto se ajusta a hechos médicos, no puede utilizarse como base para un diagnóstico médico real. Este proyecto no asume ninguna responsabilidad legal por el contenido generado por el modelo, ni es responsable de las pérdidas que puedan surgir del uso de recursos relacionados y resultados de producción.

🥂Referencia del proyecto 
Este trabajo fue completado por Wang Rongsheng, Zhou Ruizhe y Chen Haoming, estudiantes de maestría de la Facultad de Ciencias Aplicadas de la Universidad Politécnica de Macao, y los supervisores fueron el profesor asociado Tan Tao y el profesor asociado Wang Yapeng.

Si utiliza el modelo, datos o código de este proyecto, por favor declare la siguiente referencia:

@misc{wang2023caregpt,
      title={CareGPT: Medical LLM, Open Source Driven for a Healthy Future}, 
      author={Rongsheng Wang, Ruizhe Zhou, Haoming Chen, Yapeng Wang, Tao Tan},
      year={2023},
      publisher = {GitHub},
      journal = {GitHub repository},
      howpublished = {\url{https://github.com/WangRongsheng/CareGPT}},
}
@article{wang2023ivygpt,
  title={IvyGPT: InteractiVe Chinese pathwaY language model in medical domain},
  author={Wang, Rongsheng and Duan, Yaofei and Lam, ChanTong and Chen, Jiexi and Xu, Jiangsheng and Chen, Haoming and Liu, Xiaohong and Pang, Patrick Cheong-Iao and Tan, Tao},
  journal={arXiv preprint arXiv:2307.10512},
  year={2023}
}
@Misc{llama-factory,
  title = {LLaMA Factory},
  author = {hiyouga},
  howpublished = {\url{https://github.com/hiyouga/LLaMA-Factory}},
  year = {2023}
}
Este proyecto ha sido incluido en Heart of the Machine SOTA-CareGPT .



🔔Licencia 
Este repositorio tiene la licencia MIT , consulte los términos de la licencia.

🎗️Apoyo de patrocinio 
Si cree que este proyecto es útil para usted y está dispuesto a apoyar nuestro trabajo, puede hacerlo de las siguientes maneras ( déjenos su ID de WeChat ):

	
Su apoyo será nuestra motivación para continuar explorando LLM, y todo el apoyo se utilizará para las tareas de implementación de inferencia de modelos .

📚Referencia del proyecto 
Maestría en Medicina 
https://github.com/llSourcell/DoctorGPT
https://github.com/facebookresearch/llama-recipes
https://github.com/Kent0n-Li/ChatDoctor
https://github.com/michael-wzhu/ShenNong-TCM-LLM
https://github.com/michael-wzhu/ChatMed
https://github.com/SCIR-HI/Huatuo-Llama-Med-Chinese
https://github.com/SCIR-HI/Med-ChatGLM
https://github.com/xionghonglin/DoctorGLM
https://github.com/MediaBrain-SJTU/MING
https://github.com/CMKRG/QiZhenGPT
https://github.com/NLPxiaoxu/LLM-Pretrain-FineTune
https://github.com/scutcyr/BianQue
https://github.com/thomas-yanxin/Sunsimiao
https://github.com/kbressem/medAlpaca
https://github.com/FreedomIntelligence/HuatuoGPT
https://github.com/shibing624/MedicalGPT
https://github.com/chaoyi-wu/PMC-LLaMA
https://github.com/parischang/CMLM-ZhongJing
https://github.com/SupritYoung/Zhongjing
https://github.com/openmedlab/PULSE
https://github.com/FudanDISC/DISC-MedLLM
https://github.com/Zlasejd/HuangDI
https://github.com/2020MEAI/TCMLLM
https://github.com/PharMolix/OpenBioMed
https://huggingface.co/Writer/palmyra-med-20b
https://github.com/taininghealth/WiNGPT2
https://github.com/DUTIR-BioNLP/Taiyi-LLM
https://github.com/TONYCHANBB/HealGPT
https://github.com/som-shahlab/Clinfo.AI
https://github.com/DUTIR-BioNLP/Taiyi-LLM
Revisar LLM 
https://github.com/FreedomIntelligence/CMB
Experiencia LLM 
https://medical.chat-data.com/
http://med.fudan-disc.com/
https://www.huatuogpt.cn/
https://huggingface.co/spaces/wangrongsheng/CareLlama
( contraseña ) https://huggingface.co/spaces/fb700/chatglm-fitness-RLHF
http://heal-gpt.cn/
Tecnología Sensetime-Dayi: https://chat.sensetime.com/
iFlytek-iFlytek Xiaoyi: búsqueda y uso de pequeños programas
https://www.cinfo.ai/
Ali Tongyi Renxin: https://tongyi.aliyun.com/renxin
Implementar LLM 
https://github.com/a16z-infra/llama2-chatbot
https://github.com/liltom-eth/llama2-webui
https://github.com/soulteary/docker-llama2-chat
https://huggingface.co/spaces/LinkSoul/Chinese-Llama-2-7b
https://github.com/mushan0x0/AI0x0.com
https://github.com/Yidadaa/ChatGPT-Next-Web
https://github.com/sunner/ChatALL
https://github.com/chatchat-space/Langchain-Chatchat
https://github.com/wenda-LLM/wenda
https://github.com/xusenlinzy/api-for-open-llm
https://github.com/yuanjie-ai/ChatLLM
https://github.com/labring/FastGPT
https://github.com/vllm-project/vllm
https://github.com/dataelement/bisheng
https://github.com/lobehub/lobe-chat
https://github.com/purton-tech/bionicgpt
https://github.com/Chainlit/chainlit
https://github.com/arc53/DocsGPT
https://vercel.com/templates/ai
https://github.com/ollama-webui/ollama-webui
https://github.com/huggingface/chat-ui
https://github.com/xusenlinzy/api-for-open-llm
Producción de datos LLM 
https://github.com/yanqiangmiffy/GoGPT-Instruction
https://github.com/wpydcr/LLM-Kit
https://github.com/huang1332/finetune_dataset_maker
https://github.com/tresColorFr/LLMforDialogDataGenerate
https://github.com/alibaba/data-juicer
https://github.com/duanyu/LabelFast
Recursos de maestría en Derecho 
https://github.com/onejune2018/Awesome-Medical-Healthcare-Dataset-For-LLM
https://github.com/WangRongsheng/MedQA-ChatGLM
https://github.com/hiyouga/LLaMA-Efficient-Tuning
https://github.com/WangRongsheng/Use-LLMs-in-Colab
https://github.com/HqWu-HITCS/Awesome-Chinese-LLM
https://github.com/LearnPrompt/LLMs-cookbook
https://github.com/liucongg/ChatGPTBook
https://github.com/EvilPsyCHo/train_custom_LLM
LLM multimodal 
https://github.com/QwenLM/Qwen-VL
https://github.com/haotian-liu/LLaVA
https://github.com/kyegomez/Med-PaLM
https://github.com/williamliujl/Qilin-Med-VL
Descargar LLM 
https://huggingface.co/
https://modelscope.cn/
https://aliendao.cn/
https://hf-mirror.com/


Acerca de
🌞 CareGPT (CareGPT) es un modelo de lenguaje médico a gran escala que, al mismo tiempo, integra docenas de conjuntos de datos de ajuste médico disponibles públicamente y modelos de lenguaje médico a gran escala abiertos disponibles, incluida la capacitación, evaluación e implementación de LLM para promover la Se desarrolla un rápido desarrollo de la LLM médica. LLM médico, código abierto impulsado por un futuro saludable.

Temas
llama gpto baichuan modelos de lenguaje grande llama2 llm medico
Recursos
Léame
Licencia
licencia MIT
 Actividad
Estrellas
 87 estrellas
Vigilantes
 4 mirando
tenedores
 14 tenedores
Repositorio de informes
Idiomas
Pitón
99,9%
 
CSS
0,1%
Pie de página
© 2023 GitHub, Inc.
Navegación de pie de página
Términos
Privacidad
Seguridad
Estado
Documentos
Contacto GitHub
Precios
API
Capacitación
Blog
Acerca de
