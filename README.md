# streamlit_reference

Here I will write some code that will help us to connect google colab with streamlit

!pip install streamlit
import streamlit as st
%%writefile app.py -> This will create new app.py if it exists then it will overwrite else creats the one and it is the executing file so it contains all business logic and model implementation
!wget -q -O - ipv4.icanhazip.com-> provides us the tunnel password and ipv4 address
! streamlit run app.py &  npx localtunnel --port 8501 -> provide us link of local host,network host
