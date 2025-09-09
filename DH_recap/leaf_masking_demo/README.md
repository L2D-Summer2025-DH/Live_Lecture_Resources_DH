## 📈 Data Handling Recap 🕥

### 🍀 Leaf Masking Demonstration:

Using the [OLID I dataset available _via_ Kaggle](https://www.kaggle.com/datasets/raiaone/olid-i?resource=download), this demonstration uses 5 healthy bitter gourd leaves, and 5 from plants subjected to a dewy mildew infection. The latter exhibit clear, brown necrotic lesions on their leaves, and the aim of this notebook is to show how with simple RGB- and HSV-based masking, we can:

- Reduce the background values down to pure black.
- Identify necrotic regions by using HSV (Hue, Saturation, Value) values and ranges.
- Mask and highlight these necrotic lesions, and replace them with pure red pixels, to highlight necrosis.

All the files you will need are in this folder, and should you need extra information, please watch the recap lecture recording, [linked on this playlist.](https://www.youtube.com/playlist?list=PLTRx90_S7dFsE3y_e1nBCo2VDOshgbwcS)

Please replace all paths as relevant to whether you are uploading the files and coding from a Codespace, or whether you're downloading them to your local machine, and coding using an IDE of your choice.

We encourage you to play around with the code cells, manipulate the output, and see if you can maybe enhance the masks even further from the parameters we included as standard, in this notebook. In this way, we hope you'll learn more about these techniques, and will hopefully be able to carry them over to your own datasets and work.

Happy coding!
