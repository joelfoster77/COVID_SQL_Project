The excel document in this folder has PostgreSQL queries
for a COVID data analytics project.

The tables below outline the tables that were imported
into Postgre: covid, tests, demographics, and vaccines.


.csv	SQL Column Name Change	Data Type

covid	iso_code	character 3
covid	continent	character varying 50
covid	country	character varying 50
covid	date	date
covid	ttl_cases	bigint
covid	new_cases	bigint
covid	ttl_deaths	bigint
covid	new_deaths	bigint
covid	ttl_cases_permm	numeric
covid	new_cases_permm	numeric
covid	ttl_deaths_permm	numeric
covid	new_deaths_permm	numeric
		
		
tests	iso_code	character 3
tests	continent	character varying 50
tests	country	character varying 50
tests	date	date
tests	ttl_tests	bigint
tests	new_tests	bigint
tests	ttl_tests_per1k	numeric
tests	new_tests_per1k	numeric
tests	positive_rate	numeric
tests	tests_per_case	numeric
		
		
demographics	iso_code	character 3
demographics	continent	character varying 50
demographics	country	character varying 50
demographics	population_density	numeric
demographics	median_age	numeric
demographics	aged_65_older	numeric
demographics	aged_70_older	numeric
demographics	gdp_per_capita	numeric
demographics	extreme_poverty	numeric
demographics	cardiovasc_death_rate	numeric
demographics	diabetes_prevalence	numeric
demographics	female_smokers	numeric
demographics	male_smokers	numeric
demographics	hospital_beds_per_thousand	numeric
demographics	life_expectancy	numeric
demographics	human_development_index	numeric
demographics	population	bigint
		
		
vaccinations	country	character varying 50
vaccinations	iso_code	character 3
vaccinations	date	date
vaccinations	ttl_vax	bigint
vaccinations	ppl_vaxed	bigint
vaccinations	ppl_fully_vaxed	bigint
vaccinations	ttl_boosters	bigint
vaccinations	daily_vax	bigint
vaccinations	ttl_vax_per100	numeric
vaccinations	ppl_vaxed_per100	numeric
vaccinations	ppl_fully_vaxed_per100	numeric
vaccinations	ttl_boosters_per100	numeric
vaccinations	daily_vax_permm	numeric
vaccinations	daily_ppl_vaxed	bigint
vaccinations	daily_ppl_vaxed_per100	numeric
