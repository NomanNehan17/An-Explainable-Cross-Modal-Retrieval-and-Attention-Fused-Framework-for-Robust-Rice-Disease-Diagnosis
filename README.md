# An Explainable Cross-Modal Retrieval and Attention-Fused Framework for Robust Rice Disease Diagnosis

## Author Information

### **Abdullah Al Noman**
Department of Computer Science and Engineering  
International Islamic University Chittagong  
Chittagong, Bangladesh  
📧 Email: *( nomanrooks@gmail.com)*

---

### **Chanda Rani Debi**
Computational Intelligence Lab  
Southeast University  
Dhaka, Bangladesh  
📧 Email: *(chandadebi892@gmail.com)*

---

### **Md. Khaliluzzaman**
Department of Computer Science and Engineering  
International Islamic University Chittagong  
Chittagong, Bangladesh  
📧 Email: *(khalil@iiuc.ac.bd)*

---

### **Ekramul Haque Tusher**
Department of Computer Science and Engineering  
International Islamic University Chittagong  
Chittagong, Bangladesh  
📧 Email: *(ehtusher018@gmail.com)*

---

### **Goh Kah Ong Michael** *(Corresponding Author)*
Center for Image and Vision Computing, COE for Artificial Intelligence  
Faculty of Information Science & Technology, Multimedia University  
Jalan Ayer Keroh Lama, Melaka, 75450, Malaysia  
📧 Email: <michael.goh@mmu.edu.my>

---
## Abstract
Rice leaf diseases significantly reduce global yields in regions with diverse climatic and soil conditions. Traditional diagnostic methods are labor-intensive, expert-dependent, and poorly scalable. Although deep convolutional neural networks have shown promise for automated disease recognition, existing approaches rely solely on visual data and neglect contextual agronomic knowledge. This article proposes an explainable cross-modal retrieval and attention-fused framework for robust rice disease diagnosis by combining CNN-based visual attention with structured agro-climatic environmental data. The architecture consists of two parallel streams. The visual branch leverages an ensemble of EfficientNet-B0, B3, and B5 backbones with multi-head attention to extract highly discriminative leaf features, generating a 4864-dimensional visual embedding. Concurrently, the numeric branch encodes structured agro-climatic parameters, including temperature, humidity, rainfall, and soil attributes, via a localized case-based tabular retrieval module and an embedding network into a 128-dimensional context vector. Both embeddings are fused into a 4992-dimensional joint feature space and classified through a multilayer perceptron (MLP). The framework was evaluated on a comprehensive multimodal dataset comprising 20,952 RGB rice leaf images spanning seven distinct classes (Healthy, Insect Damage, Leaf Scald, Rice Blast, Rice Leaf Folder, Rice Stripe, and Rice Tungro) mapped to underlying regional environmental records. Systematic hyperparameter evaluation indicates that the AdamW optimizer with a learning rate of 0.0001 yields a peak baseline accuracy of 96.00\%, outperforming alternative configurations. Under severe Gaussian blur and additive noise perturbations designed to simulate field-level sensor degradation, the model maintains a robust classification accuracy of 86.00\%. Grad-CAM and Grad-CAM++ visualizations confirm that the model's visual attention remains strictly localized on pathologically relevant symptomatic leaf regions. The results demonstrate that fusing visual features with structured environmental context substantially enhances diagnostic accuracy, generalization, and interpretability, offering a highly practical foundation for precision crop surveillance and sustainable global food security.
