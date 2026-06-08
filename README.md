Automation & AI Vulnerability Index (ISCO-08)

## 📌 Overview
This repository contains the dataset and automation probability coefficients used to construct a **weighted vulnerability index** for evaluating the impact of Artificial Intelligence and automation on labor markets. 

The data was specifically prepared and utilized for a scientific research study assessing and comparing the vulnerability of employment structures in the **Visegrad Group (V4: Czech Republic, Hungary, Poland, Slovakia) and Germany**.

## 🔬 Research Context
As artificial intelligence and automation technologies rapidly advance, different economies face varying degrees of disruption based on their occupational structures. This project translates recognized automation probabilities into an internationally comparable format (ISCO-08) to measure how susceptible the workforces of Germany and the V4 countries are to these technological shifts.

## 📊 Methodology
The core dataset maps the original probability of computerization/automation for various occupations-based on the seminal work by **Frey & Osborne (2017)** from the US SOC 2010 (Standard Occupational Classification) system to the **ISCO-08** (International Standard Classification of Occupations) framework. 

By harmonizing these classifications, we calculated the median probability of automation for different ISCO-08 occupational groups. These coefficients serve as the foundation for the weighted vulnerability index.

## 🗂 Data Structure
The primary dataset (`Automatization_isco-08.csv`) includes the conversion table and the following key metrics:
* **SOC 2010 Codes & Titles:** The original US occupational classifications.
* **ISCO-08 Codes & Titles:** The mapped international occupational classifications.
* **Probability:** The estimated probability of automation for the specific role (Frey & Osborne).
* **ISCO Group:** The broader occupational category under the ISCO-08 structure.
* **Probability (Median):** The calculated median vulnerability coefficient used for constructing the final index.

## 🚀 Usage
This dataset and the resulting coefficients can be used by researchers, labor economists, and data scientists to:
* Analyze the occupational structure and technological vulnerability of different countries or regions.
* Calculate weighted vulnerability indices based on national employment distributions.
