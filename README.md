# 🌦️ Weather Classification using CNN & Transfer Learning

This project classifies images of different weather conditions into **11 categories**:  
`dew, fogsmog, frost, glaze, hail, lightning, rain, rainbow, rime, sandstorm, snow`.

---

## 📂 Dataset
- Custom dataset stored in `./data/weather class/dataset/`
- Each folder corresponds to one weather category
- No predefined train/test split → split done using `validation_split` in TensorFlow

---

## 🧠 Models Used
1. **Custom CNN (Convolutional Neural Network)**  
   - 3 Conv2D layers + Dense layers  
   - Accuracy: ~17% (not great)

2. **MobileNetV2 (Transfer Learning)**  
   - Pretrained on ImageNet  
   - Fine-tuned for weather dataset  
   - Accuracy: ~80–85% after tuning  

---

## 📊 Results
| Model        | Accuracy |
|--------------|----------|
| Custom CNN   | ~17%     |
| MobileNetV2  | ~80–85%  |

---

## 🚀 How to Run
1. Clone the repository
   ```bash
   git clone https://github.com/Vision-Ali/Weather-Classification-CNN.git
   cd Weather-Classification-CNN
