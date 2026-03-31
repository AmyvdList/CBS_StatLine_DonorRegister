# CBS_StatLine_DonorRegister
Visualisation of the CBS StatLine dataset “Donorregistratie; persoonskenmerken, 2014–2022”. 

**Summary** 
This analysis examines how donor registration choices in the Netherlands evolved between 2014 and 2022, with a focus on the 2021 transition to an opt-out system. While this policy increased the potential donor pool by automatically registering individuals without a recorded choice as having no objection, the key question is whether it also encouraged more people to actively record their own preference. The results show that the opt-out law did more than double the amount of donor registrations – it also increased public awareness and prompted active decision-making about organ donation. Importantly, the distribution of choices (in favor, neutral, against) remained relatively stable, suggesting that the law did not disproportionately mobilize a specific group (e.g., those against donation), but instead engaged the population broadly. 

**Donor Registry Dataset**
The Donor registry data can be downloaded as a csv file fom the StatLine databank of the CBS: *https://opendata.cbs.nl/#/CBS/nl/navigatieScherm/themaStatLine*.

Specifically the dataset to be downloaded is named "Donorregistratie; persoonskenmerken, 2014-2022" and can be found under section "Gezonheid and Welzijn" followed by "Donorregistratie": *https://opendata.cbs.nl/#/CBS/nl/dataset/82814NED/table?ts=1774702668634*.

**Data Description**
The dataset contains information on the number of individuals and their recorded preferences in the Dutch Donor Register between 2014 and 2022. A description of the variables is provided below:

Donorregistratie: the recorded choice in the donor register (e.g., consent, refusal, or decision delegated to others)
Persoonskenmerken: demographic characteristics of individuals, such as age group; selected for 'Totale bevolking van 12 jaar en ouder'.
Perioden: the year of registration (2014–2022)
Donorregister, vastgelegde keuze (x 1 000): the number of individuals (in thousands) with a given registration choice. 

**How to run the code** 
git clone <repo-url>
cd <repo-name>
pip install -r requirements.txt
jupyter notebook

Then:
Open the notebook and run all cells.

