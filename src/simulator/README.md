# FluoriVenger Simulator

## Overview

The FluoriVenger Simulator provides interactive tools to demonstrate filter performance, cost-benefit analysis, health impact, and business projections. Perfect for hackathon presentations, investor pitches, and stakeholder demonstrations.

## Components

### 1. Web-Based Interactive Simulator (`web_simulator.html`)

**Features:**
- 🔬 **Filter Performance Calculator** - Simulate fluoride removal over time
- 💰 **Cost-Benefit Analysis** - Compare costs with alternatives
- 🏥 **Health Impact Calculator** - Estimate cases prevented and savings
- 📈 **Business Growth Projections** - Model revenue and customer growth
- ⚖️ **Solution Comparison** - Side-by-side comparison with alternatives

**How to Use:**
1. Open `web_simulator.html` in any modern web browser
2. No installation or internet connection required
3. Navigate between tabs to explore different calculators
4. Adjust input parameters and click "Calculate" buttons
5. Results update instantly with visual metrics

**Perfect For:**
- Live demonstrations during hackathon presentations
- Interactive investor meetings
- Community engagement events
- Training sessions for sales teams
- Educational workshops

### 2. Python Simulator (`fluorivenger_simulator.py`)

**Features:**
- Comprehensive simulation engine
- Batch processing capabilities
- JSON export for data analysis
- Multiple scenario modeling (base case, optimistic, conservative)
- Detailed performance metrics

**How to Use:**

```bash
# Run the simulator
python fluorivenger_simulator.py

# This will generate three scenario files:
# - simulation_base_case.json
# - simulation_optimistic.json
# - simulation_conservative.json
```

**Programmatic Usage:**

```python
from fluorivenger_simulator import FluoriVengerSimulator

# Create simulator instance
simulator = FluoriVengerSimulator()

# Run filter performance simulation
filter_results = simulator.simulate_filter_performance(
    input_fluoride=10.0,
    days=180,
    daily_volume=20.0
)

# Calculate cost-benefit
cost_benefit = simulator.calculate_cost_benefit(
    household_size=5,
    years=5,
    input_fluoride=10.0
)

# Simulate health impact
health_impact = simulator.simulate_health_impact(
    households=10000,
    years=3
)

# Business growth projections
business = simulator.simulate_business_growth(
    years=5,
    initial_households=10000,
    growth_rate=1.5
)

# Kiosk operations
kiosk = simulator.simulate_kiosk_operations(
    daily_customers=200,
    months=12
)

# Generate comparison report
comparison = simulator.generate_comparison_report(
    input_fluoride=10.0,
    household_size=5
)

# Run full simulation
full_results = simulator.run_full_simulation(scenario="base_case")

# Export results
simulator.export_results(full_results, "my_simulation.json")

# Print summary
simulator.print_summary(full_results)
```

## Simulation Scenarios

### Base Case (Realistic)
- Input fluoride: 10 mg/L
- Initial customers: 10,000
- Growth rate: 50% annually
- Filter lifespan: 6-9 months

### Optimistic
- Input fluoride: 8 mg/L (easier to treat)
- Initial customers: 15,000
- Growth rate: 100% annually
- Filter lifespan: 9-12 months

### Conservative
- Input fluoride: 12 mg/L (harder to treat)
- Initial customers: 5,000
- Growth rate: 30% annually
- Filter lifespan: 4-6 months

## Key Metrics Calculated

### Filter Performance
- Fluoride removal efficiency (%)
- Output fluoride concentration (mg/L)
- Filter lifespan (days/months)
- WHO compliance status
- Cumulative volume processed

### Cost-Benefit Analysis
- FluoriVenger total cost
- Alternative costs (bottled water, RO, activated alumina)
- Medical costs avoided
- Total savings
- ROI (%)
- Payback period (months)

### Health Impact
- People reached
- Children protected
- Fluorosis cases prevented
- Healthcare cost savings
- Fluoride removed (tons)
- Environmental impact (plastic bottles avoided)

### Business Projections
- Customer growth (year-over-year)
- Revenue projections
- Gross profit
- Cumulative metrics
- Market penetration

### Kiosk Operations
- Daily/monthly customers
- Revenue and costs
- Profit margins
- Payback period
- ROI

## Sample Results

### Filter Performance (180 days, 10 mg/L input)
```
Initial Removal: 95.0%
After 180 days: 87.3%
Output Fluoride: 1.27 mg/L
Status: Good ✓
WHO Compliant: Yes
```

### Cost-Benefit (5 years, family of 5)
```
FluoriVenger Cost: KES 4,200
Bottled Water Cost: KES 182,500
Medical Costs Avoided: KES 45,000
Total Savings: KES 223,300
ROI: 5,217%
Payback: 1.1 months
```

### Health Impact (10,000 households, 3 years)
```
People Reached: 50,000
Children Protected: 20,000
Cases Prevented: 27,500
Healthcare Savings: KES 1.24 Billion
Fluoride Removed: 1.97 tons
```

### Business Growth (5 years, base case)
```
Year 1: 10,000 customers, KES 6M revenue
Year 2: 25,000 customers, KES 20M revenue
Year 3: 50,000 customers, KES 50M revenue
Year 4: 87,500 customers, KES 100M revenue
Year 5: 143,750 customers, KES 180M revenue
```

## Demonstration Tips

### For Hackathon Presentations
1. **Start with Web Simulator** - Show live calculations
2. **Use Real Numbers** - Input actual fluoride levels from Rift Valley
3. **Highlight Savings** - Emphasize 75-85% cost advantage
4. **Show Impact** - Demonstrate health outcomes at scale
5. **Compare Alternatives** - Use comparison tab to show competitive advantage

### For Investor Meetings
1. **Run Python Simulator** - Generate detailed reports
2. **Show Multiple Scenarios** - Base, optimistic, conservative
3. **Export to JSON** - Provide data for due diligence
4. **Emphasize ROI** - Both for customers and business
5. **Scale Projections** - Show path to profitability

### For Community Engagement
1. **Focus on Cost Savings** - Show monthly/yearly savings
2. **Health Benefits** - Emphasize children's protection
3. **Simple Language** - Use web simulator's visual interface
4. **Local Examples** - Use actual community data
5. **Interactive** - Let community members input their own numbers

## Technical Requirements

### Web Simulator
- Modern web browser (Chrome, Firefox, Safari, Edge)
- No internet connection required
- No installation needed
- Works on desktop, tablet, and mobile

### Python Simulator
- Python 3.7 or higher
- No external dependencies (uses only standard library)
- Cross-platform (Windows, Mac, Linux)

## Customization

### Adjusting Parameters

Edit the constants in `fluorivenger_simulator.py`:

```python
# Filter costs
FILTER_COST_HOUSEHOLD = 700  # KES
FILTER_COST_KIOSK = 5000  # KES

# Performance parameters
INITIAL_REMOVAL_EFFICIENCY = 0.95  # 95%
MIN_EFFICIENCY = 0.85  # 85%

# Health costs
MEDICAL_COST_FLUOROSIS = 15000  # KES per year
```

### Adding New Scenarios

```python
# Create custom scenario
custom_results = simulator.run_full_simulation(scenario="custom")

# Or manually set parameters
filter_perf = simulator.simulate_filter_performance(
    input_fluoride=15.0,  # High fluoride
    days=120,  # 4 months
    daily_volume=30.0  # Large household
)
```

## Data Export

### JSON Format
```json
{
  "scenario": "base_case",
  "timestamp": "2026-05-02T23:00:00",
  "filter_performance": { ... },
  "cost_benefit": { ... },
  "health_impact": { ... },
  "business_growth": { ... },
  "kiosk_operations": { ... },
  "comparison": { ... }
}
```

### Excel/CSV Export
Use Python's pandas library to convert JSON to Excel:

```python
import json
import pandas as pd

# Load simulation results
with open('simulation_base_case.json', 'r') as f:
    data = json.load(f)

# Convert to DataFrame and export
df = pd.DataFrame(data['business_growth'])
df.to_excel('business_projections.xlsx', index=False)
```

## Validation

All calculations are based on:
- Scientific literature on bone char filtration
- WHO water quality guidelines
- Kenya Bureau of Standards specifications
- Field data from pilot implementations
- Market research on alternative solutions

## Support

For questions or customization requests:
- Email: tech@fluorivenger.ke
- Documentation: See main project README.md
- Issues: Report via project repository

## License

MIT License - See LICENSE file in project root

---

**FluoriVenger Simulator** - Making Impact Measurable 📊✨