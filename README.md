# pattern-finding-

finding dose name, dosage, address, manufacture from medical raw data

I have used regex to fetch various details from the paragraph.

Address - regex is based on pin code

Company name - All addresses contain company names in the starting. So I have fetched the

address and the previous string which company name.

License number - regex is based on License pattern which is M/xxx/xxxx

Dose - I have used filtration using “mg”

Drug name - Based on all medicine drug name patterns, i can see all drugs have IP in their name. So,

I have fetched it from “IP”.

Medicine name - Some medicine names include dose(power) and some medicine names need to
filter using custom code.
