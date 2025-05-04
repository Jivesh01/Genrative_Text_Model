# � Generative Text Model

This project generates coherent paragraphs on specific topics using **GPT-2**.

---

## � Setup

### � Option 1: Automatic Setup

```bash
zsh setup_text_generation.sh
```

### � Option 2: Manual Setup

```bash
python3 -m venv venv
source venv/bin/activate
pip install -r requirements.txt
```

---

## � How to Use

1. Launch Jupyter Notebook:

```bash
jupyter notebook
```

2. Open `main.ipynb`

3. Change the **prompt** text in the notebook to your desired topic.

4. Run the cells to generate new paragraphs.

---

## �️ Features

- Uses GPT-2 from Hugging Face Transformers.
- Easy-to-edit prompt inside notebook.
- Generates up to 200 tokens in one shot.

---

## � License

MIT License

