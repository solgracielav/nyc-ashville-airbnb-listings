# Airbnb Listings Demand Analysis – NYC & Asheville 🏙️🌄

This project explores the factors that influence Airbnb demand in two different U.S. cities:  
- **New York City**, a global tourism hub with intense market competition  
- **Asheville, North Carolina**, a regional destination known for its natural attractions and seasonal tourism

The goal is to understand what makes certain listings more appealing and visible to guests, and how those factors vary across different urban contexts.

> 🔒 **Note**: This repository contains **only the NYC portion** of the analysis, conducted by me, Sol Vloebergh. The Asheville portion, led by classmate, is described below but not included here out of respect for authorship and privacy.

---

## 📌 Objectives

- Identify which listing features (e.g., price, room type, location, availability) are associated with high demand.
- Build interpretable models to guide new or low-visibility hosts.
- Compare demand dynamics in two distinct markets: a saturated urban area (NYC) and a seasonal destination (Asheville).

---

## 📊 Tools Used

- **R** (R Markdown, dplyr, ggplot2, sf)
- **Tableau** (interactive maps and dashboards)
- **Statistical Modeling** (Logistic Regression)

---

## 🔍 Key Insights

### 🔷 NYC Analysis – *Sol Vloebergh*

- Listings with higher log-transformed prices are more likely to be in high demand.
- Shared and private rooms, compared to entire homes, are strongly associated with more review activity.
- Availability (days listed per year) has a small **negative** association with demand.
- Surprisingly, listings in tourist-heavy neighborhoods show **lower** odds of high demand—possibly due to saturation.

**Modeling:** Logistic regression revealed:
- `log_price`: OR = 1.50  
- `room_typeShared`: OR = 4.73  
- `near_tourist_area`: OR = 0.70 (30% less likely to be in high demand)

### 🔷 Asheville Analysis – *L.F.*

- Listings near natural attractions (e.g., Blue Ridge Parkway, Biltmore Estate) see higher review volume.
- Demand in Asheville is **seasonal**, peaking in spring and fall.
- Family-friendly amenities and proximity to local experiences correlate with higher visibility.

---

## 📁 Repository Structure

