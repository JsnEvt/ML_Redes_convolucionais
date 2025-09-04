# 🐶🐱 Reconhecimento de Cães e Gatos com PyTorch

Projeto desenvolvido durante o curso **Deep Learning de A a Z com PyTorch e Python**, ministrado por **Jones Granatyr (Udemy)**.  
O objetivo é treinar e avaliar uma rede neural profunda capaz de classificar imagens em duas categorias: **cães** ou **gatos**.

---

## 🚀 Objetivos do Projeto
- Implementar uma **rede neural convolucional (CNN)** em **PyTorch**.  
- Treinar o modelo utilizando um dataset de imagens de cães e gatos.  
- Aplicar técnicas de **pré-processamento de imagens** e **data augmentation**.  
- Avaliar o desempenho do modelo em termos de acurácia e capacidade de generalização.  
- Fazer predições em imagens novas, simulando cenários reais de uso.

---

## 🧠 Principais Conceitos de Deep Learning Abordados
- **Torch e Torchvision** para construção e treinamento da CNN.  
- **Camadas convolucionais e pooling** para extração de características visuais.  
- **Funções de ativação (ReLU, Softmax, etc.)**.  
- **Treinamento supervisionado** com retropropagação e otimizadores (Adam, SGD).  
- **CrossEntropy Loss** para classificação binária.  
- **Treinamento em lotes (mini-batches)**.  
- **GPU acceleration (CUDA)** quando disponível.  

---

## ⚙️ Como Executar no VS Code

### 1️⃣ Clonar o repositório
```bash
git clone https://github.com/JsnEvt/ML_Redes_convolucionais.git
cd ML_Redes_convolucionais
```
1. Crie e ative um ambiente virtual (opcional, mas recomendado):
```bash
python -m venv venv
```
Ativar no Windows
```bash
venv\Scripts\activate
```
Ativar no Linux/Mac
```bash
source venv/bin/activate
```
Instale as dependências:
```bash
pip install -r requirements.txt
```
2. Abra no VS Code
 ```
 code .
 ```
3. Abra o arquivo e execute célula por céulula
 ```
 Redes Convolucionais - distincao entre caes e gatos.ipynb
 ```
   
## 📊 Resultados Esperados

O modelo atinge boa acurácia na classificação entre cães e gatos.

👨‍🏫 Créditos

Projeto baseado no curso Deep Learning de A a Z com PyTorch e Python de Jones Granatyr - Udemy
