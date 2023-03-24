import numpy as np
import altair as alt
import pandas as pd
import streamlit as st

st.header('Walt Disney World Wait Time Help')


df = pd.read_csv('WDW_Data.csv')
df = df.sample(frac = 0.3)

import streamlit as st


st.write ('Which Magic Kingdom Attraction Would You Like To Ride')

wtp = st.checkbox('The Many Adventures of Winnie The Pooh')
sdwarfs = st.checkbox('Seven Dwarfs Mine Train')
sm = st.checkbox('Space Mountain')
tm = st.checkbox('Thunder Mountain')
thm = st.checkbox('The Haunted Mansion')
jc = st.checkbox('Jungle Cruise')
tmsw = st.checkbox('Tomorrowland Speedway')
poc = st.checkbox('Pirates of the Caribbean')
blsrs = st.checkbox('Buzz Lightyears Space Ranger Spin')
ppf = st.checkbox('Peter Pans Flight')

if wtp:
     st.write("Good News! This Ride Typically Has A Low Wait Time!")

if sdwarfs: 
     st.write("Unfortunately, This Ride Typically Has A High Wait Time")

if sm:
     st.write("Unfortunately, This Ride Typically Has A High Wait Time")

if tm: 
     st.write("This Ride Typically Has A Medium Wait Time")

if thm:
     st.write("This Ride Typically Has A Medium Wait Time")

if jc:
     st.write("Unfortunately, This Ride Typically Has A High Wait Time")

if tmsw: 
     st.write("Good News! This Ride Typically Has A Low Wait Time!")

if poc:
     st.write("Good News! This Ride Typically Has A Low Wait Time!")

if blsrs: 
     st.write("This Ride Typically Has A Medium Wait Time")

if ppf:
     st.write("Unfortunately, This Ride Typically Has A High Wait Time")
