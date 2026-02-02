# DEEP NEUTRAL NETWORK

#Visual Storytelling with Cross-Modal Attention Refinement

✔️ Overview

This project focuses on visual storytelling using multimodal learning, where both images and text are used together to predict the next element in a story sequence and is supported by a Notebook template.

The project introduces the idea of Cross-Modal Attention Refinement (CMAR) to improve alignment between visual and textual information, resulting in more coherent and context-aware story predictions.

The model learns to encode k-image caption pairs and generate the (k+1) th caption using:

•	CNN-based image encoder

•	Cross-Modal attention 

•	LSTM / Transformers

•	GRU


✔️ Key purposes:

•	Data loading and preprocessing

•	Model design and explanation

•	Training and evaluation workflows

•	Metric computation and result analysis



✔️ Project Focus

•	Visual storytelling

•	Image–text alignment

•	Multimodal reasoning

•	Attention-based models

•	Narrative prediction tasks.


📈 Loss Curves

The training script collects:

•	Train loss per epoch

•	Validation loss per epoch

These are plotted automatically:

•	plt.plot(train_losses)

•	plt.plot(val_losses)

✔️Evaluation Metrics Used:

•	BLUE

•	CIDE

•	Sequence-level alignment scores


CMAR:

Improving image-text correspondence, making it suitable for sequence modelling tasks without increasing training complexity.

DataSet Used:

Compatible with datasets containing sequences of images + captions (e.g. daniel3303/StoryReasoning).


✔️ Required Installation:

       •	Python 3.8+ versions

       •	PyTorch

       •	matplotlib

       •	numpy

       •	torchvision

       •	Transformers



 🤝 Contributing

Contributions from the community are highly appreciated.

Proposals including new attention architectures, advanced fusion strategies, or training optimizations are welcome. Please open an issue so we can discuss and plan the improvements together.


  📜 License
  

MIT License.





