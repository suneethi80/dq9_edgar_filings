
Extract required information from edgar filings

Background:
The purpose of the filings  is to protect investors by requiring detailed information about the securities to be provided prior to selling the securities.
The main challenge of working with these filings is the lack of a common document format. 

Goal: Use natural language processing (NLP) tools to extract required information from 424B filings obtained from the Electronic Data Gathering, Analysis, and Retrieval (EDGAR) system. In addition, the goal is to provide methods to extract information from any selected documents from EDGAR system.
There are a number of key features contained in these filings.
The fields that are covered are as follows:

issuer_name
security_description
cusip_id
isin_id
original_face_amount
maturity_date
coupon_type_code
cpn_pay_frq_code
is_callable

Tools used: Python, Natural Language Processing (NLP)