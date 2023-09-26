import streamlit as st

# Create a widget group
with st.expander("Click to expand"):
    st.write("This content is hidden by default.")
    name = st.text_input("Enter your name:")
    age = st.slider("Select your age:", 0, 100, 25)
    submit_button = st.button("Submit")

# Perform actions based on user input
if submit_button:
    st.write(f"Hello, {name}! You are {age} years old.")
