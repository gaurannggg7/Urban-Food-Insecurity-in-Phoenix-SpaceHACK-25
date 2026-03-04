🌍 SpaceHACK 2025 – Satellite-Driven Urban Agriculture Mapping

Track: Food Insecurity
Team #7

This project explores how satellite imaging and geospatial data layering can identify suitable locations for urban agricultural development in the Phoenix metropolitan area to address food insecurity.

📌 Problem Background

According to 2022 data:

12% of households in Maricopa County are food insecure

43% of food insecure households fall above the SNAP qualification threshold

Many residents experience:

Low income

Distance from supermarkets

Limited vehicle access

Existing government programs do not reach a large percentage of affected households, requiring alternative intervention strategies. 

SpaceHACK 2025 - Final Submissi…

🏪 Infrastructure Gap

While exploring existing food infrastructure, we found:

Out of 1,778 on-farm markets across the United States, only 2 are located in the Phoenix area

This highlights limited local access to farm markets and alternative fresh food sources. 

SpaceHACK 2025 - Final Submissi…

🛰 Our Approach

We developed a layered geospatial mapping system using satellite imagery and public datasets to identify potential sites for urban agriculture.

Key Datasets Used

USDA Food Access Research Atlas → Identify food desert boundaries

Census Data → Identify low-income & low vehicle access areas

USGS National Land Cover Database (NLCD) → Identify vacant/abandoned parcels

NDVI (Sentinel-2 Surface Reflectance) → Identify existing green spaces

NASA SMAP → Identify soil moisture suitability

OpenStreetMap → Base visualization layer

SpaceHACK 2025 - Final Submissi…

🌱 Urban Agriculture is Scarce

By comparing:

LCMS Land Use dataset

USDA Cropland Data Layer (CDL)

We observed that nearly all open land in Phoenix is already classified as cropland, meaning:

Urban agriculture in the form of community gardens, food forests, or micro-farms is largely missing and not captured in existing datasets.

This indicates a need to reclaim underutilized urban spaces for small-scale food production. 

SpaceHACK 2025 - Final Submissi…

🌾 Identifying Possible Cultivable Land

Using:

USGS/NLCD Land Cover (2019)

Sentinel-2 Surface Reflectance

NDVI analysis

We mapped:

Grassland / barren land

Low vegetation areas

Excluded active cropland

This revealed potential cultivable land within congested urban areas suitable for community-scale agriculture. 

SpaceHACK 2025 - Final Submissi…

📍 Correlation to Socioeconomic Data

When overlaying:

Low-income census tracts

Low food access regions

Vehicle access data

We found correlation between:

Identified cultivable zones

Populations experiencing food insecurity

This suggests strong potential for targeted intervention using satellite-informed land selection. 

SpaceHACK 2025 - Final Submissi…

🛠 Technical Implementation

Google Earth Engine API (hackathon-provided key)

Satellite datasets processed within Earth Engine

Analysis conducted in Google Colab

Layer visualization via OpenStreetMap

NDVI calculation for vegetation detection

SpaceHACK 2025 - Final Submissi…

🌆 Proposed Urban Agriculture Solutions
1️⃣ Community Gardens & Urban Farms

Open-access harvest areas

Volunteer or education program managed

Reduce cost barriers for fresh produce

Retain active farms

Encourage integration into master-planned communities

2️⃣ Farmers Markets

Repurpose abandoned buildings or barren land

Walking-distance fresh food access

SNAP Double Up Food Bucks incentives

3️⃣ Regenerative Urban Landscapes

Reuse & recycle food waste

Improve soil quality

Increase fresh food production in underutilized commercial zones

SpaceHACK 2025 - Final Submissi…

🌎 Impact Vision

Satellite imaging can:

Identify communities most in need

Pinpoint land suitable for intervention

Allow dynamic layer interchange for planning

Scale across U.S. cities or globally

SpaceHACK 2025 - Final Submissi…

👥 Team Members

Gaurang Mohan – Computer Science (BS), Data Science Minor

Shivani Chauhan – Data Science, Analytics & Engineering (MS)

Kadn Neal – Computer Science (Software Engineering) (BS)

Amoreena Ordonez – Data Science (Behavioral Sciences) (BS)

Christopher Kosko – Architecture (MS), Urban & Environmental Planning (MUEP)

SpaceHACK 2025 - Final Submissi…

🙏 Acknowledgments

Special thanks to:

Professor Chavez

Namig Abbasov

Kerri Rittschof

Jeremiah Pate

For their support throughout SpaceHACK 2025.
