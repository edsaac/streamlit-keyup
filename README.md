# streamlit-keyup

If you're collecting text input from your users in your streamlit app, `st.text_input` works well -- as long as you're happy with
waiting to get the response when they're finished typing.

But, what if you want to get the input out, and do something with it every time they type a new key (AKA "on keyup")?

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://key-up.streamlitapp.com)

![filtering](https://user-images.githubusercontent.com/34405119/186949358-3b7c3dc7-ba52-42b0-9cf8-5aaee7c189ec.gif)


## Installation


`pip install streamlit-keyup`

## Usage

```python
from st_keyup import st_keyup

value = st_keyup("Enter a value")

# Notice that value updates with every keyup
st.write(value)
```
