#echo "# Project-AI" >> README.md
#git init
#git add README.md
#git commit -m "first commit"
#git branch -M main
#git remote add origin https://github.com/adrikar19/Project-AI.git
#git push -u origin main


import streamlit as st
import time as t
import pandas as pd
import numpy as np

st.sidebar.title("LogIn")
st.sidebar.text_input("UserId")
st.sidebar.text_input("Password")
st.sidebar.button("submit")

st.title(":blue[Welcome to AI interview panel]")
st.header("header")
st.subheader("Please choose your topic of discussion")
st.info("Select one at a time")
st.warning("Do not click return")
st.write("Student name")
st.error("wrong")
st.success("correct")
st.markdown("proceed")
st.markdown("### again")
st.text("text")
st.caption("caption")
st.latex(r''' a^2+bx^3''')
st.checkbox("checkbox")
st.button("button")
st.radio("gender",["male","female","other"])
st.selectbox("select Branch",["CSE","EEE","ECE"])
st.multiselect("select subject",["C++","Java","HTML"])
st.select_slider("Grade",["A","B","C"])
st.slider("mark",0,100)
st.number_input("Age",0,30)
st.text_input("Name")
st.date_input("date of passing")
st.time_input("time of passing")
st.text_area("Hobby")
st.file_uploader("upload CV")
st.color_picker("color")
st.progress(90)
with st.spinner("wait"):
  t.sleep(2)
st.balloons()

col1, col2, Col3 = st.columns(3)

with col1:
    st.link_button(":rainbow[HR]", "Simulation of an HR Interviewer")
    st.link_button(":rainbow[Python]", "https://streamlit.io/gallery")
with col2:
    st.link_button(":rainbow[Java]", "https://streamlit.io/gallery")
    st.link_button(":rainbow[DotNet]", "https://streamlit.io/gallery")
with Col3:
    st.link_button(":rainbow[Css]", "https://streamlit.io/gallery")
    st.link_button(":rainbow[HTML]", "https://streamlit.io/gallery")



dataset=pd.dataframe(np.random.randn(50,2),columns=["x","y"])
st.pie_chart(dataset)

