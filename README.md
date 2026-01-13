# Experimenting CNN Components
> A journey to understand what actually happens inside a Convolutional Neural Network.

I was confused about CNN components and wanted to actually **understand** them. So I built these experiments to answer the questions that bugged me.

## ❓ The Questions
* Does adding more layers always improve accuracy?
* How much do feature maps actually matter?
* What's the "optimal" architecture for MNIST?

## 🛠️ My Approach
* ✅ **Controlled experiments:** Changing only one variable at a time to isolate impact.
* ✅ **Reproducibility:** Used fixed seeds so you can get the same results.
* ✅ **Visual Analysis:** Clear documentation of training curves and results.
* ✅ **Honest Analysis:** Documenting what works and, more importantly, what doesn't.

## 🌟 What's Different Here?
I try to tested multiple configurations and documented surprises—**like why 2 layers sometimes beat 3!** I wanted to move beyond "just following along" to truly understanding the architecture.

## 📚 Acknowledgments
This work builds upon excellent tutorials and insights from:
- [How to Choose CNN Architecture - MNIST](https://www.kaggle.com/code/cdeotte/how-to-choose-cnn-architecture-mnist) by Chris Deotte
- [Convolutional Neural Network Tutorial](https://www.kaggle.com/code/kanncaa1/convolutional-neural-network-cnn-tutorial) by Kaan

---
⚠️ **Disclaimer:** This is a learning project. Some models may exhibit overfitting as the focus is on understanding the **relative impact** of components. Regularization techniques like dropout are explored in later sections.
