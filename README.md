# Projeto: test_detection_cars_ssd_mobilenet_v2

## 📌 Descrição
Implementação de um modelo de **detecção de carros** utilizando **SSD MobileNet V2**. O objetivo é detectar veículos em imagens ou vídeos de forma eficiente e em tempo real.

---

## 🔧 Tecnologias
- Python  
- TensorFlow / Keras  
- OpenCV  
- NumPy  

---

## 📂 Estrutura do Projeto
- **Carregamento do modelo**: utiliza pesos pré-treinados SSD MobileNet V2.  
- **Pré-processamento**: redimensionamento e normalização das imagens.  
- **Inferência**: geração de bounding boxes e classes previstas.  
- **Visualização**: uso do OpenCV para desenhar caixas e rótulos.  

---

## 📊 Resultados Esperados
- Detecção rápida e eficiente de carros em imagens/vídeos.  
- Modelo leve, adequado para aplicações em dispositivos de baixa potência.  
- Precisão balanceada para uso em sistemas de monitoramento ou IoT.  

---

## 🚀 Possíveis Extensões
- Treinar com dataset customizado.  
- Adaptar para detectar múltiplas classes (pessoas, motos, caminhões).  
- Exportar para **TensorFlow Lite** ou **ONNX** para uso em dispositivos móveis ou embarcados.  
