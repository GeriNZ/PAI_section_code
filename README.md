# PAI Section Code

Optional Python notebooks that connect section concepts to runnable code. No previous coding experience is required: the code is supplied, with explanations and examples to explore at your own pace.

## Week 3: Where Am I?

Use **gradient ascent in PyTorch** to estimate a phone's location from the pings it receives from three Wi-Fi towers. The notebook follows the section exercise's numbers, scoring rule, and step size.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GeriNZ/PAI_section_code/blob/main/Week_3_Where_Am_I_Gradient_Ascent.ipynb)

### Get started

1. Click **Open in Colab** above and sign in to your Google account.
2. Choose **File → Save a copy in Drive** if you want to keep your changes.
3. Choose **Runtime → Run all**, or run each code cell from top to bottom using its play button.

Everything runs in your browser. No installation on your computer or GPU is needed. Your experiments do not change the original notebook in this repository.

### What you will see

- **Ask for the arrow:** PyTorch calculates the uphill slopes and takes the first hop.
- **Repeat the climb:** follow ten hops across the lawn and watch the score improve.
- **Explore:** optionally change the starting guess or step size and see what happens.

You can also [read the notebook and its saved charts on GitHub](Week_3_Where_Am_I_Gradient_Ascent.ipynb) without running the code.

## Week 5: Inside the Mystery 8

Train a small **784 → 4 → 1 neural network in PyTorch** to recognize 8s, then inspect what its hidden and output layers learned.

[![Open in Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/GeriNZ/PAI_section_code/blob/main/Week_5_Inside_the_Mystery_8.ipynb)

The notebook includes:

- Hidden-neuron weight maps before and after training.
- A picture's journey through the hidden activations and output calculation.
- Real digits that strongly activate each neuron.
- Output weights that support or oppose an “8” prediction.
- The section's three strategies for adding pixels, with the same starting image for comparison.

This notebook trains its own model with the section's small-network architecture. Its neuron roles, probabilities, and pixel counts may differ from the section demonstrations.

Open it in Colab and choose **Runtime → Run all**. MNIST downloads automatically when local files are unavailable; no GPU or local installation is needed. Locally, the notebook also recognizes the data in the repository's `minst` folder. Save a copy in Drive to keep your changes.

You can also [read the notebook and its saved charts on GitHub](Week_5_Inside_the_Mystery_8.ipynb).
