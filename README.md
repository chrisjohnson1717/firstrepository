# Mission Statement

Having a healthy life is a fundamental aspiration for every person, and equitable physical access to healthcare is central to achieving it. With the adoption of the United Nations Sustainable Development Goals in 2015, Canada is working to ensure its people have well-maintained physical access to healthcare whenever and wherever it's needed. Of these interconnected SDGs, SDGs 3 (Good Health and Well-being), SDG 9 (Industry, Innovation and Infrastructure), and SDG 11 (Sustainable Cities and Communities) collectively contribute to physical access to healthcare in cities¹. Despite promising efforts to improve healthcare access in Canadian cities, significant barriers remain². Particularly for adults aged 65 and older. The structure and performance of both public and private transportation networks directly shape older adults' ability to access hospitals and healthcare facilities safely and efficiently.

In Toronto, the aging population is growing rapidly. According to the 2021 Census, approximately 477,000 residents are aged 65 and older. By 2041, this number is projected to exceed 719,000 — an increase of more than 50 percent, with the sharpest growth among those aged 75 and older³. Many older adults live with chronic conditions such as hypertension, diabetes, and chronic obstructive pulmonary disease, increasing their need for timely access to hospital services⁴. The app **CareReach Toronto** was developed to respond to this urgent demographic and infrastructural shift. The platform enables users to visualize the nearest available hospital bed and accessibility via sustainable transportation options, such as public transit and automobile travel. By integrating health infrastructure data with transportation accessibility metrics, CareReach Toronto empowers older adults to make informed decisions about access to healthcare during emergencies and for routine care.

Beyond individual users, CareReach Toronto generates actionable insights for urban and transportation planners. The platform provides neighbourhood-level accessibility scores, hospital bed-to-population ratios, and identifies 15-minute transit deserts across the city. It also reveals how access to sustainable transportation intersects with the age structure of census tracts, highlighting areas where vulnerable populations face disproportionate barriers. By interconnecting aging populations with sustainable transportation planning, CareReach Toronto advances equity-centered urban transport design and supports data-driven strategies that prioritize older and vulnerable communities, ensuring sustainable transport for everyone!

### References

¹ Cling, J.-P., & Delecourt, C. (2022). Interlinkages between the Sustainable Development Goals. *World Development Perspectives*, 25, 100398. https://doi.org/10.1016/j.wdp.2022.100398

² Patrick, K., & Laupacis, A. (2023). A focus on access to health care in Canada. *CMAJ: Canadian Medical Association Journal*, 195(3), E123–E124. https://doi.org/10.1503/cmaj.230040

³ Owusu, B., Bivins, B., Marseille, B. R., & Baptiste, D. (2023). Aging in place: Programs, challenges, and opportunities for promoting healthy aging for older adults. *Nursing Open*, 10(9), 5784–5786. https://doi.org/10.1002/nop2.1872

⁴ Statistics Canada. (2021). *Census of Population*.

⁵ Ontario Ministry of Health, IntelliHealth Ontario. (2024). *Healthy Aging in Toronto, at a glance*.

---

# Application Features

## Neighbourhood Healthcare Accessibility Index Search

### 1. Healthcare Accessibility Variation
This view examines variation in healthcare accessibility across Toronto's census tracts.
- The legend (top left) represents **hospital beds per person** in each tract.
- The histogram shows that **362 census tracts cannot reach a hospital bed within 15 minutes**, regardless of travel mode.
- This highlights significant spatial gaps in healthcare accessibility.

---

### 2. Neighbourhood-Based Filtering
Users can:
- Select any Toronto neighbourhood from the drop-down menu (bottom left)
- Click **Load** to filter census tracts within that neighbourhood
- View associated **public transit travel catchments**

This allows users to:
- Identify the most convenient hospital via public transit
- Click on hospitals to view:
  - Total staffed beds
  - Bed breakdown by department

---

### 3. Accessibility Score Summary
When a neighbourhood is selected, the dashboard simultaneously displays:
- Public transit accessibility score
- Automobile accessibility score
- Combined accessibility index
- Total population of the selected area

This enables quick comparison of transportation modes and healthcare access.

---

# Travel Catchments and Equity Analysis

## 1. Equity Assessment View
Users are first directed to the **Equity Assessment** view.

Key findings:
- Younger census tracts experience **33% higher healthcare accessibility** compared to older tracts.

When a neighbourhood is selected:
- Population aged 65+ is calculated
- Proportion of older adults relative to total population is displayed

This allows users to compare healthcare accessibility:
- Across neighbourhoods
- Within neighbourhoods
- In relation to older populations

---

## 2. Residential Travel Catchments
In the **Residences** section, users can:
- View public transit catchments
- View automobile catchments
- Compare reachable hospitals between:
  - Sustainable transportation (public transit)
  - Non-sustainable transportation (automobile)

---

## 3. Hospital-Based Catchments
In the **Hospitals** section, users can:
- Compare hospital service areas by travel mode
- Examine hospital bed-to-population ratios
- Assess differences between sustainable and non-sustainable catchments

This enables evaluation of transportation equity in healthcare access.

---

# Data Sources

## Geographic Boundary Data

### Toronto Municipal Boundary
Source: City of Toronto Open Data
https://open.toronto.ca/dataset/regional-municipal-boundary/

### Toronto Neighbourhood Boundaries
Source: ArcGIS Hub
https://hub.arcgis.com/datasets/uji::toronto-neighbourhoods/explore

### Census Tract Boundaries (2021)
Source: Statistics Canada
https://www12.statcan.gc.ca/census-recensement/2021/geo/sip-pis/boundary-limites/index2021-eng.cfm?year=21

---

## Population Data (Demand)

**Population by Census Tract**
Source: Statistics Canada
https://www150.statcan.gc.ca/t1/tbl1/en/tv.action?pid=9810001401&geocode=S0503535

---

## Hospital Bed Data (Supply)

**Hospital Beds Staffed**
Source: Canadian Institute for Health Information (CIHI)
https://www.cihi.ca/en/access-data-and-reports/data-tables?keyword=Hospital+Beds+Staffed&published_date=All&acronyms_databases=All&type_of_care=All&place_of_care=All&population_group=All&health_care_quality=All&health_conditions_outcomes=All&health_system_overview=All&sort_by=field_published_date_value&items_per_page=10

---

## Toronto GTFS Data
Source: Statistics Canada
https://www150.statcan.gc.ca/n1/pub/23-26-0003/232600032025001-eng.htm

