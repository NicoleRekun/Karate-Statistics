# Karate Match Winner Prediction

## Overview
This project aims to analyze the factors that impact the outcome of a karate match. By constructing a dataset with various technical, tactical, and physical variables, I aim to identify key contributors to winning a match.

## Dataset Description
The dataset includes multiple variables related to a karate match. The response variable is whether a fighter won (1) or lost (0).

### **Response Variable**
- **Winner (Binary):**
  - `0` - Lost
  - `1` - Won

### **Predictor Variables**
#### **Fighter Information**
- **First Name**: Fighter's first name
- **Last Name**: Fighter's last name
- **Gender**: Male or Female
- **Country**: Country the fighter represents
- **Colour**: Belt or uniform color
- **Age**: Fighter's age
- **Weight**: Fighter's weight category
- **Rank**: Karate world rank
- **Fighter Type**: Style preference (attack, defence, timing)

#### **Technical & Tactical Variables**
- **Number of Previous Tournaments Competed In**: Experience level
- **Warnings**: Number of warnings received
- **Senshu**: Whether the fighter secured the first-point advantage
- **Stance**: Fighter's dominant stance (orthodox or southpaw)
- **Total Points**: Total points scored in the match
- **Yuko**: Number of Yuko points scored (1 point - appointed by a hand technique)
- **Wazari**: Number of Wazari points scored (2 points - appointed by a kick technique to the body)
- **Ippon**: Number of Ippon points scored (3 points - appointed by a kick technique to the head or a takedown)
- **Number of Attempts**: Total number of attack attempts
- **Number of Successful Attempts**: Number of landed strikes

## Goals & Objectives
- Analyze which variables have the most impact on winning a match.
- Use statistical modelling or machine learning to predict match outcomes.
- Gain insights into the optimal fighting style and strategy for success.
