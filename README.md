# Application Features

## Neighbourhood Healthcare Accessibility Index Search

### 1. Healthcare Accessibility Variation

This view examines variation in healthcare accessibility across Toronto’s census tracts.

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

# 🚍 Travel Catchments and Equity Analysis

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





# Data Sources

---

##  Geographic Boundary Data

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
