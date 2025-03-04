# Algo_Deliverable3

This project involves training a deep learning model using TensorFlow/Keras. The model processes textual inputs and functional ratings to make predictions.

## Key Components
- **Preprocessing**: Text tokenization, sequence padding, and one-hot encoding.
- **Model Architecture**: Multi-input neural network with embedding layers for text inputs.
- **Training**: Optimized with batch processing and validation split.

## Common Issues & Fixes
1. **Embedding Layer Error (`indices out of bounds`)**  
   - Ensure `input_dim` in the Embedding layer is `>= max(X_text) + 1`.
   - Properly fit the tokenizer before converting text to sequences.

2. **Mismatch in Sequence Length**  
   - Use `pad_sequences` to maintain consistent input shape.

## Repository
- Hugging Face Repository: `[Provide Link]`
- Dataset Source: `[Provide Source]`

## How to Run
1. Install dependencies:

2. 2. Train the model:
model.fit(...)
