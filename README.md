# julia

## Investigate the Covid-19 dataset
<pre>The main purpose in this investigation is to find the spread of the pandemic in the world and find what are the countries which suffer most, and which managed to reduce this pandemic.
A SARS-like virus outbreak originating in Wuhan, China, is spreading into neighboring Asian countries, and as far afield as Australia, the US and Europe.
On 31 December 2019, the Chinese authorities reported a case of pneumonia with an unknown cause in Wuhan, Hubei province, to the World Health Organization (WHO)’s China Office. As more and more cases emerged, totaling 44 by 3 January, the country’s National Health Commission isolated the virus causing fever and flu-like symptoms and identified it as a novel coronavirus, now known to the WHO as 2019-nCoV.
The following dataset shows the numbers of spreading coronavirus across the globe.
Data can be found in: Covid-19 Dataset .
</pre>
Content:
<ul> 
	<li>Sno - Serial number</li>
	<li>Date - Date of the observation</li>
	<li>Province / State - Province or state of the observation</li>
	<li>Country - Country of observation</li>
	<li>Last Update - Recent update (not accurate in terms of time)</li>
	<li>Confirmed - Number of confirmed cases.</li>
	<li>Deaths - Number of death cases</li>
	<li>Recovered - Number of recovered cases.</li>
</ul>

 
Research Questions:
<ul>
<li>Q1: What is the first observation date?</li>
<li>Q2: What is the Active, Deaths, Recovered cases Percentage in the world.</li>
<li>Q3: Which countries were affected the most?</li>
<li>Q4: Which countries have the biggest number of deaths?</li>
<li>Q5: Which countries still in danger (Active) “Till the last date in the date set”</li>
<li>Q6: Which countries have the biggest number of recovered cases?</li>
</ul>

Conclusion:
<ul>
<li>	The Investigation shows that the pandemic reaches 226 different countries.</li>
<li>	We Found that The Active cases percentage in the world = 36.28 %</li>
<li>	The Deaths cases percentage in the world = 2.78 %</li>
<li>	The Recovered Percentage in the world = 60.93%</li>
<li>	Then we drew a pie chart which shows that the Recovered rate is much bigger than the Active rate and The Deaths, which is great.</li>
<li>	The Top affected Countries: US, India, Brazil.</li>
<li>	Top countries in Number of Deaths: US, Brazil, India.</li>
<li>	Top countries in Number of Active cases: US, UK, France.</li>
<li>	Top countries in Number of Recovered cases: India, Brazil, Russia.</li>
</ul>

### Then We focused on one country, Egypt:
<pre>
Data can be found in https://www.kaggle.com/bassemmustafa/covid19-egypt-cases
Egypt is one of the countries that is suffering from the pandemic and one of the top 10 countries in the death rate compared to the number of confirmed cases.
The first COVID-19 case reported was in February 2020 for a tourist, since that, number of confirmed cases reached 5895 cases with 406 deaths.
</pre>

Content:
<ul>
<li>	date - Observation Date.</li>
<li>	new_confirmed - New confirmed cases with COVID-19.</li>
<li>	new_deaths - New death cases by COVID-19.</li>
<li>	new_recovered - New recovered cases from COVID-19 that exit quarantine hospitals.</li>
<li>	new_pos_to_neg - New cases whose pcr results turned to negative for COVID-19. </li>
<li>	active_pos - Number of active positive cases.</li>
<li>	cases_in_hospital - Number of cases occupied in quarantine hospitals.</li>
<li>	total_confirmed - Total confirmed cases with COVID-19.</li>
<li>	total_deaths - Total death cases by COVID-19</li>
<li>	total_recovered - Total recovered cases from COVID-19 that exit quarantine hospitals.</li>
</ul>

Research Questions:
<ul>
<li>Q1: What is the Danger rate (Confirmed Cases) in Egypt? </li>
<li>Q2: The Deaths Rate in Egypt. </li>
<li>Q3: The Recovering Rate.</li>
<li>Q4: What is the rate of turning from Pos to Neg?</li>
<li>Q5: What is the difference between Confirmed cases and Recovered?</li>
<li>Q6: What is the difference between Deaths cases and Recovered?</li>
<li>Q7: What is the Hospital Status?</li>
</ul>

Conclusion:
<ul>
<li>This investigation discusses the status in Egypt from Mach to May- 2020.</li>
<li>The danger rate (Confirmed Cases) was enormously increased in this period.</li>
<li>The Recovered rate was increased in the half of May.</li>
<li>The rate of change from positive to negative was not stable. </li>
<li>And there is a huge difference between the recovered rate, which it is much lower and the Confirmed rate.
<li>The Recovered cases is bigger than the Death cases.</li>
<li>Then We investigate the Hospital status: The number of the cases who exit the hospital is low compared to the positive cases in hospitals.</li>
<li>There are Negative cases still in hospitals. </li>
</ul>

Links / Resources
<ul>
<li>Public Coronavirus dashboard</li>
<li>JHU Github Repo</li>
</ul>

<hr>

<pre>
The Programming Language Used 
<h3>Julia:</h3> 
o developed at MIT by Prof. Edelman’s group: 
 Alan Edelman, Jeff Bezanson, Stefan 
Karpinski, Viral B.   Shah o Released 8 years ago. o Stable release: 1.5.2 / 24 September 2020. 
 
Julia Advantages  
•	Functional Programming Language. 
•	high-level, high-performance, dynamic programming language. 
•	Free, open source software. 
•	Over 3,000 registered packages in wide range of domains. 
•	Interactive but high performance (fast): 
Julia is a compiled language, not interpreted that is one of the reasons that it performs faster than interpreted languages. However, unlike traditional compiled languages, Julia is not strictly statically typed. It uses JIT (Just In Time) compilation to infer the type of each individual variable in your code.  
 
The result is a dynamically-typed language that can be run from the command line like Python, but that can achieve comparable speeds to compiled languages like C and Go. 
•	Julia can run in Jupyter Notebook. 
•	Syntax: similar to Python / MATLAB / R. 
•	Julia, as a much newer language with a smaller user base, has far fewer packages available. 
 It is possible to run Python libraries in Julia (through 
the 	PyCall	 package), and C/Fortran libraries can be 
called and run directly from Julia code. 
•	it is a general-purpose language and can be used to write any application, many of its features are well suited for numerical analysis and computational science. 
 
Using Julia for Data Science and Machine Learning 
•	Julia is popular among data scientists and mathematicians. 
•	It shares features (such as 1-based array indexing and functional design) with mathematical and data software like Mathematica, and its syntax is closer to the way mathematicians are used to writing formulas.  
•	Julia also includes excellent support for parallelism and cloud computing, making it a good choice for big data projects. 
•	Julia is developing its own native machine learning libraries. 

</pre>


To download a Julia: https://julialang.org/downloads/

It is better to use anaconda.

You need to download Jupyter "It is in conda" and IJulia also. 

To add Pkg: - using Pkg
 	 - Pkg.add("Pkg")

