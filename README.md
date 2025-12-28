 Task-04: Image-to-Image Translation using cGAN (pix2pix)
ProDigy Infotech

Project Overview
This project demonstrates **image-to-image translation** using a **Conditional Generative Adversarial Network (cGAN)** known as **pix2pix**.

The pix2pix model learns a mapping from an **input image** to a **target image** using a conditional GAN framework.  
This implementation focuses on understanding the **architecture and workflow** of pix2pix rather than full training.

Objective
- To understand **Conditional GANs (cGANs)**
- To implement the **pix2pix architecture**
- To demonstrate **image-to-image translation**
- To visualize input, generated, and target images

What is pix2pix?
**pix2pix** is a supervised image-to-image translation model based on cGANs.

It consists of:
- **Generator (U-Net)**: Generates an output image from an input image
- **Discriminator (PatchGAN)**: Determines whether the generated image is real or fake when paired with the input image

The generator tries to fool the discriminator, while the discriminator tries to distinguish real from fake images.

---
 Technologies Used
- Python
- TensorFlow
- pix2pix (TensorFlow examples)
- Matplotlib
- NumPy

---

Project Structure
Task04_Pix2Pix_cGAN/
│
├── pix2pix.ipynb
├── README.md

---

How to Run the Project
1. Open **Google Colab**
2. Upload the notebook (`pix2pix.ipynb`)
3. Run all cells in order
4. Observe input, generated, and target images

---

How the Project Works
1. Clone TensorFlow’s official pix2pix implementation
2. Create a **custom paired dataset** using random images
3. Initialize the pix2pix **Generator** and **Discriminator**
4. Pass the input image through the generator
5. Visualize:
   - Input Image
   - Generated Image
   - Target Image

---

 Sample Output
The output displays three images side by side:
- **Input Image** (random image)
- **Generated Image** (output from generator)
- **Target Image** (expected output)

⚠️ Since the model is **not trained**, the generated image may appear dark or unclear.  
This is expected behavior and demonstrates the architecture rather than performance.

---

 Key Features
- Uses pix2pix cGAN architecture
- Demonstrates image-to-image translation pipeline
- Beginner-friendly implementation
- No dependency on unavailable datasets
- Clean visualization of results

---

 Future Enhancements
- Train the model on a real paired dataset
- Improve image quality with multiple training epochs
- Use real-world datasets like edges-to-photo
- Save and reload trained models

---

 Conclusion
This project successfully demonstrates the **pix2pix conditional GAN architecture** for image-to-image translation.  
Although the model is not fully trained, it clearly shows how a generator and discriminator interact in a cGAN framework.

This implementation is suitable for understanding the **core concepts of GAN-based image translation**.
Task-04 Submission  
ProDigy Infotech

