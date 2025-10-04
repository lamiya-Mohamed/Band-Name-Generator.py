import streamlit as st

st.title("🎸 Band Name Generator")

st.write("Welcome to the Band Name Generator App!")

# Ask user for inputs
city = st.text_input("Which city did you grow up in?")
pet = st.text_input("What's the name of your pet?")

# Generate band name
if city and pet:
    band_name = f"{city} {pet} Band"
    st.success(f"Your band name could be: **{band_name}** 🎶")
