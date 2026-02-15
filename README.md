# 🌿 Plant-Species-Image-Classification

**Predicting plant images**

---

<p>This is the link in G-drive for my model.</p>
https://drive.google.com/drive/folders/1-LKnP17Iy454UdJpHO6-mjUqlewxKzl_?usp=sharing

## A. Project Overview

This project focuses on building an **image classification model** capable of identifying **20 different plant species** using images.  
The model was trained using **Google Teachable Machine**, leveraging **transfer learning** to efficiently classify plant images with high accuracy.

### Purpose of the Image Classification Model
- Automatically recognize plant species from images  
- Assist in plant identification and educational use  
- Demonstrate the practical application of machine learning for image classification  

---

## B. Plant Species Section

Below are the **20 plant species** used in the model.  
Each class contains **250 images** for training.

---

### 1. Areca Palm
<p align="center">
  <img src="images/frame_000196.jpg" width="300">
</p>
- **Common Name:** Areca Palm  
- **Scientific Name:** *Dypsis lutescens*  
- **Description:** A tropical palm with feathery, arching fronds commonly used as an indoor ornamental plant.

### 2. Begonias
<p align="center">
  <img src="images/Begonias.jpg" width="300">
</p>
- **Common Name:** Begonia  
- **Scientific Name:** *Begonia spp.*  
- **Description:** A flowering plant known for its colorful leaves and blooms, often grown indoors or in gardens.

### 3. Bougainvillea Plant
<p align="center">
  <img src="images/Bougainvillea.jpg" width="300">
</p>
- **Common Name:** Bougainvillea  
- **Scientific Name:** *Bougainvillea spp.*  
- **Description:** A climbing plant with vibrant, paper-like bracts commonly found in tropical climates.

### 4. Cacti
<p align="center">
  <img src="images/Cactus.jpg" width="300">
</p>
- **Common Name:** Cactus  
- **Scientific Name:** *Cactaceae family*  
- **Description:** A desert plant adapted to arid environments, characterized by thick stems and spines.

### 5. Crocus Plant
<p align="center">
  <img src="images/Crocus.jpg" width="300">
</p>
- **Common Name:** Crocus  
- **Scientific Name:** *Crocus spp.*  
- **Description:** A small flowering plant that blooms early in spring, known for its bright, cup-shaped flowers.

### 6. Crotons
<p align="center">
  <img src="images/Crotons.jpg" width="300">
</p>
- **Common Name:** Croton  
- **Scientific Name:** *Codiaeum variegatum*  
- **Description:** A decorative plant with colorful, variegated leaves often used indoors or outdoors.

### 7. Daylily
<p align="center">
  <img src="images/Daylily.jpg" width="300">
</p>
- **Common Name:** Daylily  
- **Scientific Name:** *Hemerocallis spp.*  
- **Description:** A flowering plant whose blooms typically last only one day, available in many colors.

### 8. Eryngium
<p align="center">
  <img src="images/Eryngium.jpg" width="300">
</p>
- **Common Name:** Sea Holly  
- **Scientific Name:** *Eryngium spp.*  
- **Description:** A spiky ornamental plant with blue or silver flowers, often used in floral arrangements.

### 9. Hibiscus
<p align="center">
  <img src="images/Hibiscus.jpg" width="300">
</p>
- **Common Name:** Hibiscus  
- **Scientific Name:** *Hibiscus rosa-sinensis*  
- **Description:** A tropical flowering plant known for its large, colorful blooms.

### 10. Jade Plant
<p align="center">
  <img src="images/Jade.jpg" width="300">
</p>
- **Common Name:** Jade Plant  
- **Scientific Name:** *Crassula ovata*  
- **Description:** A succulent plant with thick, glossy leaves, often associated with good luck.

### 11. Jasmine
<p align="center">
  <img src="images/Jasmine.jpg" width="300">
</p>
- **Common Name:** Jasmine  
- **Scientific Name:** *Jasminum spp.*  
- **Description:** A fragrant flowering plant commonly used in perfumes and teas.

### 12. Lantana
<p align="center">
  <img src="images/Lantana.jpg" width="300">
</p>
- **Common Name:** Lantana  
- **Scientific Name:** *Lantana camara*  
- **Description:** A hardy flowering plant with clusters of small, colorful flowers.

### 13. Marigolds
<p align="center">
  <img src="images/Marigolds.jpg" width="300">
</p>
- **Common Name:** Marigold  
- **Scientific Name:** *Tagetes spp.*  
- **Description:** A bright flowering plant commonly used in gardens and cultural events.

### 14. Monstera Dziurawa
<p align="center">
  <img src="images/Monstera Dziurawa.jpg" width="300">
</p>
- **Common Name:** Monstera  
- **Scientific Name:** *Monstera deliciosa*  
- **Description:** A popular houseplant with large, split leaves and a tropical appearance.

### 15. Peace Lily
<p align="center">
  <img src="images/Peace Lily.jpg" width="300">
</p>
- **Common Name:** Peace Lily  
- **Scientific Name:** *Spathiphyllum spp.*  
- **Description:** An indoor plant known for its white flowers and air-purifying qualities.

### 16. Snake Plant
<p align="center">
  <img src="images/Snake.jpg" width="300">
</p>
- **Common Name:** Snake Plant  
- **Scientific Name:** *Dracaena trifasciata*  
- **Description:** A low-maintenance indoor plant with upright, sword-like leaves.

### 17. Spider Plant
<p align="center">
  <img src="images/Spider Plant.jpg" width="300">
</p>
- **Common Name:** Spider Plant  
- **Scientific Name:** *Chlorophytum comosum*  
- **Description:** A fast-growing indoor plant with long, arching leaves and baby offshoots.

### 18. Ti Plant
<p align="center">
  <img src="images/images (9).jpg" width="300">
</p>
- **Common Name:** Ti Plant  
- **Scientific Name:** *Cordyline fruticosa*  
- **Description:** A tropical plant with colorful foliage often used as an ornamental plant.

### 19. Tulips
<p align="center">
  <img src="images/Tulips.jpg" width="300">
</p>
- **Common Name:** Tulip  
- **Scientific Name:** *Tulipa spp.*  
- **Description:** A spring-blooming flower known for its cup-shaped petals and vibrant colors.

### 20. Zinnia Plant
<p align="center">
  <img src="images/Zinnia.jpg" width="300">
</p>
- **Common Name:** Zinnia  
- **Scientific Name:** *Zinnia elegans*  
- **Description:** A bright, hardy flowering plant commonly used in gardens.

---

## C. Model Training Details

<p align="center">
  <img src="images/12.jpg" width="300">
</p>

| Parameter | Value |
|--------|------|
| Epochs | 50 |
| Batch Size | 32 |
| Learning Rate | Automatically optimized (Teachable Machine) |
| Number of Images per Class | 250 |
| Total Images | 5,000 |
| Model Type | Image Classification (Transfer Learning – MobileNet) |

---



## D. Model Evaluation

The model was evaluated using the following metrics:
- **Confusion Matrix**
- **Accuracy per Class**
- **Overall Model Accuracy**

<p align="center">
  <img src="images/1.jpg" width="300">
</p>

---

## E. Model Testing (Preview Results)

Below are **10 testing screenshots** taken from the **Teachable Machine Preview** section to demonstrate real-time classification performance.

<p align="center">
  <img src="images/2.jpg" width="300">
</p>
<p align="center">
  <img src="images/3.jpg" width="300">
</p>
<p align="center">
  <img src="images/4.jpg" width="300">
</p>
<p align="center">
  <img src="images/5.jpg" width="300">
</p>
<p align="center">
  <img src="images/6.jpg" width="300">
</p>
<p align="center">
  <img src="images/7.jpg" width="300">
</p>
<p align="center">
  <img src="images/8.jpg" width="300">
</p>
<p align="center">
  <img src="images/9.jpg" width="300">
</p>
<p align="center">
  <img src="images/10.jpg" width="300">
</p>
<p align="center">
  <img src="images/11.jpg" width="300">
</p>
---
