# Finding-the-Tourism-Sustainability-Communication-of-Indian-cities
Created a ranking of states tourism websites based on their tourism communication.

Methodology:

Step-1 Sustainable tourism dictionary development
1.	The first step (Objective clarification) allowed us to clearly define the aim of the dictionary which is to assess online sustainability communication of tourism destinations providing a tool for fast and systematic processing of large amounts of text.

"To develop a dictionary that helps assess the presence and emphasis of themes like nature, sustainability, and safety on tourism websites to make personalized travel recommendations."

2.	identification of categories and categorizing entries.   Sub-categories have been identified for each dimension to investigate and capture different aspects within the same category.
WM_project_categories.ipynb

Nature
Focuses on the natural attractions and outdoor experiences a state offers.
●	Sub-categories: Flora and Fauna, Landscapes, Adventure, Water Activities
●	Examples: Wildlife, national parks, mountains, beaches, rivers, hiking, camping
Sustainability Emphasizes eco-friendly practices and sustainable tourism efforts.
●	Sub-categories: Environmental Initiatives, Community Support, Eco-friendly Travel
●	Examples: Carbon-neutral, recycling, eco-tourism, local culture, renewable energy
Safety Covers information about how safe or accessible a destination is, often important for families or solo travelers.
●	Sub-categories: Health and Hygiene, Security, Family-Friendliness
●	Examples: Safety measures, clean, emergency services, family-friendly, safe trails
Culture & Heritage Highlights unique cultural aspects, historical sites, and local traditions.
●	Sub-categories: Historical Landmarks, Festivals, Local Traditions
●	Examples: Museums, heritage sites, festivals, traditional crafts, local foods
Adventure & Activities Focuses on thrill-seeking opportunities and sports.
●	Sub-categories: Extreme Sports, Outdoor Activities, Guided Experiences
●	Examples: Rafting, skydiving, mountain biking, scuba diving, safaris

Local Cuisine & Dining Covers food-related aspects, a key interest for many tourists.
●	Sub-categories: Regional Dishes, Food Tours, Specialty Markets
●	Examples: Street food, farm-to-table, wine tasting, regional dishes, food festivals
Accessibility Focuses on ease of travel for all types of tourists, including those with mobility needs.
●	Sub-categories: Transportation, Facilities for Disabled, Infrastructure
●	Examples: Accessible, public transport, ramps, walkways, visitor centers
Affordability Emphasizes budget-friendly travel options.
●	Sub-categories: Budget Accommodations, Affordable Dining, Deals and Discounts
●	Examples: Cheap, budget, affordable, discounts, hostels



3.	we identified the corpus on which the dictionary is developed. We adopted a set of documents that include textual content related to sustainable tourism
a.	a sustainable tourism dictionary (in Italian) previously developed by Marchi et al. (2021).....web content mining
b.	guidelines and indicators systems recognized at the international level,
c.	textual contents of the top 10 European tourism cities by the number of bed nights in 2019 (..... web scraping
Urls ready
Code almost ready  WM_crawler.ipynb
4.	we prepared the textual contents of the 10 European urban destinations for further analysis through the preprocessing operation (such as stop words removal, reduction of all words to lowercase).

After corpus
5.	validation of the dictionary entries. This study adopted the keyword-in-context (KWIC) method, which is an automatic system that allows the search of a particular keyword in the text and analyzes its local meaning in relation to a number of words immediately preceding and following it

