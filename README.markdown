# AgriCon Dataset

## Project Overview

The AgriCon Dataset is a research initiative aimed at understanding challenges and opportunities within the agricultural ecosystem in Iseyin-Ipapo Farm Settlement, Oyo State, Nigeria. The project focuses on small- and medium-scale farmers involved in crop production and post-harvest activities, who form the majority of the agricultural workforce in many African regions due to lower capital requirements and land ownership constraints.

## Project Objectives

The AgriCon project seeks to:
- Design a data-driven digital agriculture platform (AgriCon) to minimize post-harvest losses.
- Enhance market access and logistics coordination.
- Improve financial inclusion via mobile payments.
- Support digitally excluded farmers.
- Empower farmers with data-driven insights.

## Data Collection

- **Location**: Iseyin-Ipapo Farm Settlement, Oyo State (70% concentration in South West Nigeria, likely due to favorable agro-climatic conditions and survey outreach).
- **Method**: Direct field interviews and structured surveys.
- **Sample Size**: 20 farmers.
- **Tools**: Google Sheets, Excel, Python.
- **Languages**: English and Yoruba.
- **Privacy**: Anonymous responses.

## Team and Collaboration

The project was a collaborative effort between Product Managers and Data Analysts:
- **Product Managers**:
  - Designed survey questions.
  - Distributed surveys via WhatsApp, X (Twitter), and in-person at markets.
  - Assigned analysis tasks to the data team.
  - Identified potential partners (e.g., MTN, Kobo360) based on insights.
  - Drafted the Product Requirements Document (PRD).
- **Data Analysts**:
  - Cleaned and analyzed survey data.
  - Created visualizations (bar charts, pie charts, pivot tables) to reveal patterns in crop spoilage, storage needs, technology access, and willingness to pay.
  - Extracted key insights to guide product decisions.
  - Designed an interactive dashboard for clear communication of findings.

Regular feedback loops ensured alignment between analysis and business needs.

## Data Analysis Contributors

The following data analysts collaborated on the analysis, visualization, and interpretation of the survey data for AgriCon Nigeria:
- Odi Chibuzor Greg ([@gregodprogrammer](https://github.com/gregodprogrammer))
- Amankwe Amarachi Francisca ([@Anabelmara18](https://github.com/Anabelmara18))
- Amakor Euphemia Chima ([@euphemyaa](https://github.com/euphemyaa))
- Tina Rufai ([@folapella](https://github.com/folapella))
- Emmanuella Agyapong

Their contributions were key in uncovering actionable insights that guided product planning and feature prioritization.

## Key Insights & Analysis

### Farmer Demographics
- **Insight**: Majority are small- and medium-scale farmers due to limited capital and land constraints.
- **Recommendations**:
  - Tailor programs and app features to small- and medium-scale farmers.
  - Design affordable pricing models and support systems.
  - Include case studies and testimonials from similar-scale farmers.

### Regional Concentration
- **Insight**: 70% of respondents are in South West Nigeria.
- **Recommendations**:
  - Focus initial pilot programs and feature testing in the South West.

### Lack of Access to Services
- **Insight**: 78% lack access due to low awareness, inadequate extension agents, and trust issues.
- **Recommendations**:
  - Partner with cooperatives and extension agents.
  - Offer onboarding education (online/offline).
  - Launch community service centers.
  - Create an in-app "service marketplace" with trusted providers and ratings.

### Technology Access
- **Insight**: 75% own smartphones, but only 50% use the internet; strong preference for USSD.
- **Recommendations**:
  - Maintain dual accessibility (app + USSD).
  - Provide voice-based or pictorial content in local languages.
  - Develop internet-lite app versions for poor connectivity.

### Crop Prioritization
- **Insight**: Top crops are maize, cassava, and tomatoes, driven by diet, market demand, and climate.
- **Recommendations**:
  - Focus support on these crops with crop-specific bundles (e.g., planting calendars, AI disease detection).
  - Partner with input providers for seeds, fertilizers, and pest control.

### Infrastructure Challenges
- **Insight**: Over 60% lack access to cold rooms/processing plants; 51%+ spoilage rates due to poor electrification, capital, logistics, and limited public-private partnerships.
- **Recommendations**:
  - Offer micro-financing or cooperative leasing for shared equipment.
  - Partner with off-grid solar providers.
  - Map and connect farmers to existing infrastructure.
  - Collaborate with NGOs/government for rural infrastructure.
  - Provide mobile processing units.

### Regional Differences in Crop Cultivation
- **Insight**: Variations due to soil type, rainfall, market demands, and cultural preferences.
- **Recommendations**:
  - Customize advisory content by region, crop, and farmer scale.
  - Include agro-ecological zoning maps in the app.
  - Promote inter-regional knowledge-sharing groups.

### Desired App Features
- **Insight**: Preferred features include real-time availability, group bookings, USSD, and transport coordination; price forecasting less prioritized.
- **Recommendations**:
  - Build a live marketplace with stock, service, and weather/disease alerts.
  - Enable group bookings for bulk purchases or services.
  - Add an "Uber-for-agri-logistics" feature.
  - Bundle price forecasts subtly in decision-making tools.

### AI Recommendations & Premium Subscription
- **Insight**: Low AI adoption (19/37) due to lack of understanding or trust.
- **Recommendations**:
  - Explain AI outputs clearly with evidence of success.
  - Use in-app testimonials and case studies.
  - Bundle AI features in a free trial of premium subscription.
  - Simplify AI suggestion language and visualizations.

## Dataset Structure

The dataset is stored in an Excel file (`.xlsx`) with four sheets:
- **Farmers**: Demographic and operational data.
- **Growing crops**: Crop-specific information.
- **Lack of access**: Infrastructure and service gaps.
- **Useful app features**: Feature preferences.

## Implementation Recommendations

### Technology Implementation
- Mobile-first platform with USSD fallback.
- Voice-based interfaces for low-literacy users.
- Offline-capable features.

### Service Models
- Cooperative storage solutions.
- Shared equipment leasing.
- Community service centers.

### Educational Components
- Onboarding training modules.
- AI explanation systems.
- Testimonials and case studies.

### Partnerships
- Local cooperatives and extension agents.
- Input suppliers (seeds, fertilizers).
- Off-grid solar providers.
- Government/NGOs for infrastructure.

## Usage Guidelines

- **Purpose**: Internal research and development.
- **Region**: Initially focused on South West Nigeria.
- **Scaling**: Pilot programs recommended before expansion.
- **Privacy**: Maintain respondent anonymity.

## Conclusion

This project successfully provided data-driven insights to guide the development of AgriCon Nigeria’s mobile-first platform. Analysis of farmer survey responses identified critical challenges like high spoilage rates, lack of access to cold storage and markets, and limited digital tool usage. Visualizations and dashboards enabled prioritization of features like IoT-powered cold rooms, solar dryers, and USSD access. These insights are shaping a Product Requirements Document (PRD) to ensure AgriCon meets real farmer needs. The collaboration between data and product teams demonstrates the power of combining analytics with strategic planning for impactful, farmer-centered tech solutions.

## Contributing

Contributions to enhance the dataset or platform features are welcome. Please submit pull requests or open issues for discussion. To add contributors, use the `@all-contributors` bot or manually update the **Data Analysis Contributors** section with GitHub handles.

## License

This project is for internal use and development. Contact the project team for access or usage permissions.