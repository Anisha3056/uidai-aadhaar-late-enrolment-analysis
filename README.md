# uidai-aadhaar-late-enrolment-analysis
Data driven analysis of Aadhaar enrolment and update patterns in 2025 in India with focus on late enrolment in North East states

# Unlocking Societal Trends in Aadhaar Enrolment and Updates

This repository contains my submission for the UIDAI Data Hackathon 2026.
The project analyzes Aadhaar enrolment and update behavior across India
with a special focus on late Aadhaar enrolment in North Eastern states.

## Problem Statement
Late Aadhaar enrolment at age 18 and above is disproportionately higher in
North East India compared to the rest of the country.
This project aims to identify where these delays occur, quantify the gap,
and understand the structural and policy driven factors behind them.

## Key Findings
- Late enrolment ratio in North East India is 14.54 percent compared to
  2.06 percent in the rest of India
- Meghalaya and Assam together account for approximately 96 percent of
  late enrolments in the region
- Significant intra state inequality exists at the pincode level
- Predictable temporal peaks are observed in March, September, and December

## Methodology
- Integrated enrolment biometric and demographic datasets using full outer joins
- Cleaned and standardized data including fuzzy matching of state names
- Engineered analytical metrics such as late enrolment ratio and update gap
- Conducted spatial temporal and behavioral analysis
- Visualized insights using clear and interpretable charts

## Policy Context
Findings are interpreted in the context of real world policies including
the NRC legacy in Assam, district level vetting frameworks, and decentralized
verification models used in Meghalaya.

## Repository Structure
- notebook contains the full reproducible analysis
- report contains the final analytical report in PDF format
- data contains dataset description

## Tools Used
Python Pandas NumPy Matplotlib RapidFuzz

## Author
Tenali Anisha
