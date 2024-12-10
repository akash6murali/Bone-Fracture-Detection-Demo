# Bone Fracture Detection Using X-Ray Images

### Authors:
- **Anurag Sanjay Ghosh**  
- **Akash Murali**  

---

## Project Setup

### 1. Download Pre-trained Model Weights
Download the model weight files from the links below and place them in their respective folders under `modules/models`:

- **ResNet:** [Download Here](https://northeastern-my.sharepoint.com/my?id=%2Fpersonal%2Fmurali%5Fak%5Fnortheastern%5Fedu%2FDocuments%2FCS%205330%20Bone%20Fracture%20Detection%2FResnet)  
- **VGG:** [Download Here](https://northeastern-my.sharepoint.com/my?id=%2Fpersonal%2Fmurali%5Fak%5Fnortheastern%5Fedu%2FDocuments%2FCS%205330%20Bone%20Fracture%20Detection%2FVGG)  
- **YOLO:** [Download Here](https://northeastern-my.sharepoint.com/my?id=%2Fpersonal%2Fmurali%5Fak%5Fnortheastern%5Fedu%2FDocuments%2FCS%205330%20Bone%20Fracture%20Detection%2FYolo)  

---

### 2. Environment Setup
1. Install **Conda** (if not already installed).  
2. Create a new Python environment:  
   ```bash
   conda create -n demo python=3.9
3. activate the newly created environment using conda activate demo
4. Install the dependencies using ' pip install -r requirements.txt'
5. Execute the main.ipynb notebook cell by cell to run inferences on our model.