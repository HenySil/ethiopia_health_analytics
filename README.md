# Ethiopia Health Analytics Project  
**Advanced Analysis of World Bank Health Indicators for Ethiopia**  
 

# Overview  
This project analyzes Ethiopia's key health indicators using World Bank data (2015-2023). It features:  
- Comparative analysis: with regional peers (Kenya, Tanzania, Uganda, Rwanda, Sudan)  
- Machine learning forecasts: (ARIMA models) for 2024-2029  
- Interactive dashboard: built with Plotly Dash  
- Actionable insights for health policy optimization  

*Key Indicators Analyzed*:  

| Code            | Indicator                          | Relevance for Ethiopia               |  
|-----------------|------------------------------------|--------------------------------------|  
| `SH.DYN.MORT`   | Under-5 mortality rate             | High mortality (45/1000 live births) |  
| `SP.DYN.LE00.IN`| Life expectancy at birth           | Low average (67.8 years)             |  
| `SH.XPD.CHEX.GD.ZS` | Health expenditure (% GDP)     | Critical funding gap (5.5% vs WHO 7%)|  
| `SH.IMM.IDPT`   | DPT immunization coverage          | Prevents infectious diseases         |  
| `SH.STA.MALN.ZS`| Undernourishment prevalence        | Affects 21% of population            |  

# Installation  
1. **Clone repository**:  
```bash
git clone https://github.com/HenySil/ethiopia_health_analytics.git  
cd ethiopia-health-analytics  
