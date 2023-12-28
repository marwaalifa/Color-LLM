# Colorgraphics

Colorgraphics is an assistant designed to provide color recommendations for
users who may find themselves at a creative impasse during the production of their products.

## Installation

Use the package manager [pip](https://pip.pypa.io/en/stable/) to use pip.

```bash
pip install google ai
```

## Usage

```python

# Library Usage
import google.generativeai as genai
import streamlit as st

# Generate by Hex Code Color Option
def hex_to_rgb(hex_code):

# Generate by Text To Find What's U Need
  if st.button("Generate Color Sugestion"):
        with st.spinner("Generating..."):
            response = model.generate_content(
                "give me color pallete sugestion for my product, product=  "
                + input_text
            )
            st.write(response.text)

# Random Color Picker
def generate_random_color():

# Last is Information Trends Color
st.subheader("About Color of the Years")
    st.write()


```

## Contributing

It is hoped that COLORGRAPHICS can facilitate the selection of colors that
match the user's style, simplify the work of color designers, and speed up the production process.

Please make sure to update tests as appropriate.
Hit me up On : {Insert Contact}

## License

[MIT](https://choosealicense.com/licenses/mit/)
