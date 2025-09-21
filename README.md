# 🧠 Desafio: Criação de uma Base de Dados e Treinamento da Rede YOLO

Este projeto tem como objetivo aplicar os conceitos de **detecção de objetos** utilizando a rede **YOLO (You Only Look Once)**. A proposta envolve a criação ou uso de uma base de dados rotulada, seguida do treinamento da rede com pelo menos **duas classes novas**, utilizando **transfer learning**.

---

## 🎯 Descrição do Desafio

- Criar ou utilizar uma base de dados com imagens rotuladas.
- Treinar a rede YOLO com **duas novas classes** além das já existentes.
- Utilizar **transfer learning** para reaproveitar pesos pré-treinados.
- Gerar resultados visuais de detecção em imagens.

---

## 🗂️ Fontes e Ferramentas Sugeridas

| Recurso | Finalidade |
|--------|------------|
| http://labelme.csail.mit.edu/Release3.0/ | Rotulagem manual de imagens |
| https://pjreddie.com/darknet/yolo/ | Rede original YOLO para treinamento local |
| https://cocodataset.org/#home | Base de dados pública com imagens já rotuladas |
| [Google Colab](https://colab.research.google.com/) | Ambienteinamento com GPU |
| https://colab.research.google.com/drive/1lTGZsfMaGUpBG4inDIQwIJVW476ibXk_#scrollTo=j0t221djS1Gk | Exemplo de uso de YOLO com transfer learning |

---

## 🛠️ Requisitos do Projeto

- Utilizar pelo menos **duas classes novas** para detecção.
- Aplicar **transfer learning** com pesos pré-treinados.
- Gerar resultados visuais com bounding boxes.
- Documentar o processo e resultados.

---

## 🧪 Sugestão de Fluxo de Trabalho

1. **Escolha da base de dados**  
   - Usar imagens rotuladas do COCO ou outro dataset pronto.

2. **Configuração do ambiente**  
   - Utilizar Google Colab para facilitar o uso de GPU.

3. **Treinamento com YOLO**  
   - Aplicar transfer learning com pesos pré-treinados.
   - Ajustar o modelo para as novas classes.

4. **Avaliação e visualização**  
   - Testar o modelo com imagens de validação.
   - Gerar imagens com detecções visuais.

---

## 📚 Aprendizados Esperados

- Como preparar uma base de dados para detecção de objetos.
- Como aplicar transfer learning com YOLO.
- Como utilizar ferramentas como LabelMe, COCO e Colab.
- Como interpretar os resultados de detecção.

---

## 📌 Observações

- O uso de imagens rotuladas do COCO é permitido para facilitar o desafio.
- O projeto pode ser executado inteiramente no Colab, sem necessidade de hardware local.
- A entrega deve conter evidências do treinamento e da detecção com as novas classes.

---

## 👨‍💻 Autor

Joel Ferreira Heanna Dos Reis  
Analista de Suporte a Aplicações  
São Paulo, Brasil
