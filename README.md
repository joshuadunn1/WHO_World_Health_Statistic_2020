# World-Health-Statistics-2020-Geoanalysis
This is a dataset obtained from Kaggle (https://www.kaggle.com/datasets/utkarshxy/who-worldhealth-statistics-2020-complete) and contains recent health statistics of the world.

# Data Preperation and Cleaning

1. The data was saved as multiple csv files so the files were concatenated using **Power Query**, saved as STATS_COMBINED.csv.
2. I then had to organise each health statistic indicator into its own columns, using a pivot table

### Reference for DATASET
This dataset covers the most recent and updated health statistics of the world (countries recognized by WHO- all), BUT the data could not be directly used as the major indicator of various subtopics in the dataset was mixed so I have filtered based on various indicators and hence, divided into subcategories. I know so many datasets seem overwhelming, but I will be giving the various categories they belong to and what they represent so do not worry!)

The dataset was filtered to increase user readability and create amazing and beautiful visualizations and EDA’s.
Listed below will be the various datasets (named csv’s) and what they represent under their categories.  

**Pasted From:** https://www.kaggle.com/datasets/utkarshxy/who-worldhealth-statistics-2020-complete

**Life expectancy and Healthy life expectancy**  
lifeExpectancyAtBirth.csv -> Life expectancy at birth, country wise mentioned in age (years).  
HALElifeExpectancyAtBirth.csv -> Healthy life expectancy (HALE) at birth, country wise mentioned in age(years).csv  
WHOregionLifeExpectancAtBirth.csv -> Life expectancy at birth, Region wise mentioned in age (years).  
HAleWHOregionLifeExpectancy.csv -> Healthy life expectancy at birth, region wise mentioned in age(years).  
%HaleInLifeExpectancy.csv -> Healthy life and life expectancy at birth with the % of HALE in life expectancy.  

**Maternal mortality**  
Data from 2014 to 2019 indicate that approximately 81% of all births globally took place in the presence of skilled health personnel, an increase from 64% in the 2000–2006 period  
maternalMortalityRatio.csv-> Maternal mortality ratio per 100,000 births  
birthAttendedBySkilledPersonal.csv-> Births attended by skilled personals (percentile)  

**Newborn and child mortality**  
infantMortalityRate.csv-> Probability of dying between birth and age 1 per 1000 live births.  
neonatalMortalityRate.csv -> Probability of children dying in the first 28 days of life.  
under5MortalityRate.csv- > Probability of children dying below the age of 5 per 1000 live births.  

**Communicable Diseases**  
incedenceOfMalaria.csv-> Malaria incidence per 1000 population at risk  
incedenceOfTuberculosis.csv-> Incidence of TB per 100,000 population per year.  
hepatitusBsurfaceAntigen.csv -> Hepatitis B surface antigen (HBsAg) prevalence among children under 5 years)  
interventionAgianstNTD's.csv -> Reported number of people requiring interventions against NTDs.  
newHivInfections.csv ->New HIV infections per 1000 uninfected population  

**Noncommunicable diseases and mental health**  
30-70cancerChdEtc.csv -> Probability of dying between the age of 30 and exact age of 70 from any of the cardiovascular disease, cancer, diabetes, or chronic respiratory disease.  
crudeSuicideRates.csv -> Crude suicide rates per 100,000 population  

**Substance abuse**  
AlcoholSubstanceAbuse.csv -> Total (recorded + unrecorded) alcohol per capita (15 +) consumption’s  

**Road Traffic Injuries**  
roadTrafficDeaths.csv -> Estimated road traffic death rate per 100,000 population  

**Sexual and reproductive health**  
reproductiveAgeWomen.csv -> Married or in-union women of reproductive age who have their need for family planning satisfied with modern methods (%)  
adolescentBirthRate.csv -> Adolescent birth rate per 1000 women aged 15-19 years  

**Achieve universal health coverage (UHC) including financial risk protection**  
uhcCoverage.csv ->UHC index of service coverage (SCI)  
dataAvailibilityForUhc.csv ->Data availability of UHC index of essential service coverage (%)  
population10%SDG3.8.2.csv ->Population with household expenditures on health greater than 10% of total household expenditure or income (SDG indicator 3.8.2) (%)  
population25%SDG3.8.2.csv -> Population with household expenditures on health greater than 25% of total household expenditure or income (SDG indicator 3.8.2) (%)  

**Mortality from environment pollution**  
airPollutionDeathRate.csv -> Ambient and household air pollution attributable death rate per 100,00 population and the same data with age-standardized.  
mortalityRateUnsafeWash.csv -> Mortality rate attributed to exposure to unsafe WASH services per 100,000 population SDG3.9.2  
mortalityRatePoisoning.csv -> Mortality rate attributed to unintentional poisoning per 100,000 population  

**Tobacco control**  
tobaccoAge15.csv ->Prevalence of current tobacco use among persons aged 15 years and older (age- standardized rate)  

**Health Workforce**  
medicalDoctors.csv -> Medical doctors per 10,000 population.  
nursingAndMidwife.csv -> Nursing and midwifery personnel per 10,000 population.  
Dentists.csv -> Dentists available per 10,000 population  
Pharmacists.csv -> Pharmacists per 10,000 population  

**Eliminate violence Against women and girls**  
eliminateViolenceAgainstWomen.csv -> Proportion of ever-partnered women and girls aged 15-49 years subjected to physical and/or sexual violence by a current or former intimate partner in previous 12 months.  

**Drinking Water**  
basicDrinkingWaterServices.csv ->Population using at least basic drinking water services (%)  

**Sanitation and Hygiene**  
atLeastBasicSanitizationServices.csv - > Population using at least basic sanitation services (%)  
safelySanitization.csv -> Population using safe sanitation services (%)  
basicHandWashing.csv -> Population with basic handwashing facilities at home (%)  

**Clean household energy**  
cleanFuelAndTech.csv -> Proportion of population with primary reliance on clean fuels and technologies (%)  
