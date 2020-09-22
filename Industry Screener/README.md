# Industry Screener for Company Fundamentals

I created this screener using the Eikon API and the dataquery library provided by Refinitiv.
A TRBC Industry (IndustryGroup, EconSector, Activity,etc.) code is provided as input,
and the output is a 6 graph dashboard to analyze how companies in an industry compare to the industry average or their peers over 5 years.

Data is pulled using the Eikon Data API from Refinitiv, and metrics such as 'Net Sales (USD)' ,  'Net Profit Margin (After-tax) (%)','Sales/Receivables','Gearing Ratio', 'Debt Ratio'
'EVA (USD)', 'EVA Margin (%)','EVA Momentum Sales (%)' are calculated over 5 years for an industry.
