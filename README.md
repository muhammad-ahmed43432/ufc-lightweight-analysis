🥊 UFC Lightweight Fight Data Analysis


📌 Project Overview
This project is a data analysis of UFC Lightweight division fights using Python and Pandas. The goal is to explore fighter performance and extract insights from raw fight statistics such as strikes, knockdowns, takedowns, control time, and submissions.

📊 Dataset Description
The dataset contains UFC fight-level data where each row represents a fight between two fighters.
It includes:


Fighter names (f1_name, f2_name)


Weight class (weight_class)


Physical attributes (age, height)


Striking stats (significant strikes, total strikes)


Grappling stats (takedowns, submissions, reversals)


Control time


Knockdowns


Fight result information



🎯 Objectives


Filter only Lightweight division fights


Count total fights per fighter


Identify winners using fight performance statistics


Calculate wins per fighter


Compare top fighters:


Khabib Nurmagomedov


Islam Makhachev


Conor McGregor


Charles Oliveira


Ilia Topuria





🧠 Approach
1. Filtering Data


Selected Lightweight fights using string matching on weight_class


2. Feature-Based Winner Logic


Created a simple scoring system using fight statistics:


Strikes


Knockdowns


Takedowns


Submissions


Control time




Compared both fighters' scores to determine a winner for analysis purposes


3. Fighter Analysis


Combined both fighter columns to count total fight participation


Calculated total wins using derived winner column


Compared key fighters in Lightweight division



📈 Key Insights


Islam Makhachev shows the highest Lightweight wins in this dataset.


Khabib Nurmagomedov remains undefeated in Lightweight fights.


Charles Oliveira has strong performance due to high activity and submissions.


Conor McGregor has limited Lightweight participation in this dataset.


Ilia Topuria has very few Lightweight fights recorded.



🛠️ Tools Used


Python


Pandas


Google Colab
