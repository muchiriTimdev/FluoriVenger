# FluoriVenger Filter Cartridge Design Specifications

## 1. Filter Cartridge Assembly

### 1.1 Exploded View (Text Diagram)

```
                    ┌─────────────────────┐
                    │   INLET CAP         │
                    │   (1/2" BSP Thread) │
                    └──────────┬──────────┘
                               │
                    ┌──────────▼──────────┐
                    │  PRE-FILTER SCREEN  │
                    │  (100 mesh, SS304)  │
                    └──────────┬──────────┘
                               │
    ┌──────────────────────────▼──────────────────────────┐
    │                                                      │
    │              MAIN HOUSING (HDPE)                    │
    │              Height: 250mm                          │
    │              Diameter: 100mm                        │
    │              Wall Thickness: 5mm                    │
    │                                                      │
    │  ┌────────────────────────────────────────────┐   │
    │  │  Layer 1: COARSE GRAVEL (20mm)            │   │
    │  │  Particle size: 2-5mm                      │   │
    │  │  Function: Sediment removal                │   │
    │  └────────────────────────────────────────────┘   │
    │                                                      │
    │  ┌────────────────────────────────────────────┐   │
    │  │  Layer 2: BIO-MINERAL MIX (100mm)         │   │
    │  │  - 40% Bone Char (0.5-2mm)                │   │
    │  │  - 30% Activated Clay (0.1-0.5mm)         │   │
    │  │  - 20% Carbonized Maize Cob (1-3mm)       │   │
    │  │  - 10% Natural Binders                     │   │
    │  │  Function: Fluoride adsorption             │   │
    │  └────────────────────────────────────────────┘   │
    │                                                      │
    │  ┌────────────────────────────────────────────┐   │
    │  │  Layer 3: FINE SAND (50mm)                │   │
    │  │  Particle size: 0.5-1mm                    │   │
    │  │  Function: Polishing filtration            │   │
    │  └────────────────────────────────────────────┘   │
    │                                                      │
    │  ┌────────────────────────────────────────────┐   │
    │  │  Layer 4: SUPPORT GRAVEL (30mm)           │   │
    │  │  Particle size: 5-10mm                     │   │
    │  │  Function: Structural support              │   │
    │  └────────────────────────────────────────────┘   │
    │                                                      │
    │  ┌────────────────────────────────────────────┐   │
    │  │  PERFORATED BASE PLATE (5mm)              │   │
    │  │  Holes: 2mm diameter, 5mm spacing          │   │
    │  │  Material: HDPE                            │   │
    │  └────────────────────────────────────────────┘   │
    │                                                      │
    └──────────────────────────┬───────────────────────────┘
                               │
                    ┌──────────▼──────────┐
                    │   OUTLET CAP        │
                    │   (1/2" BSP Thread) │
                    │   + Sampling Port   │
                    └─────────────────────┘
```

### 1.2 Cross-Section View

```
                 INLET (Top)
                      ↓
    ════════════════════════════════════
    ║                                  ║
    ║  ▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓▓  ║  Pre-filter Screen
    ║                                  ║
    ║  ●●●●●●●●●●●●●●●●●●●●●●●●●●●  ║  Coarse Gravel
    ║  ●●●●●●●●●●●●●●●●●●●●●●●●●●●  ║  (20mm)
    ║                                  ║
    ║  ████████████████████████████  ║  Bio-Mineral Mix
    ║  ████████████████████████████  ║  - Bone Char
    ║  ████████████████████████████  ║  - Activated Clay
    ║  ████████████████████████████  ║  - Maize Cob Char
    ║  ████████████████████████████  ║  (100mm)
    ║                                  ║
    ║  ▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒  ║  Fine Sand
    ║  ▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒▒  ║  (50mm)
    ║                                  ║
    ║  ●●●●●●●●●●●●●●●●●●●●●●●●●●●  ║  Support Gravel
    ║  ●●●●●●●●●●●●●●●●●●●●●●●●●●●  ║  (30mm)
    ║                                  ║
    ║  ═══════════════════════════  ║  Perforated Base
    ║  ⊙ ⊙ ⊙ ⊙ ⊙ ⊙ ⊙ ⊙ ⊙ ⊙ ⊙ ⊙  ║  Plate
    ║                                  ║
    ════════════════════════════════════
                      ↓
                 OUTLET (Bottom)
```

### 1.3 Material Flow Diagram

```
RAW WATER INPUT
(Fluoride: 8-15 mg/L)
        ↓
┌───────────────────┐
│  PRE-FILTRATION   │ → Removes: Sediment, large particles
│  (Coarse Gravel)  │   Turbidity reduction: 50-70%
└────────┬──────────┘
         ↓
┌───────────────────┐
│  PRIMARY          │ → Removes: Fluoride (85-95%)
│  FILTRATION       │   Ion exchange with hydroxyapatite
│  (Bio-Mineral)    │   Adsorption on activated surfaces
└────────┬──────────┘
         ↓
┌───────────────────┐
│  POLISHING        │ → Removes: Fine particles, residual contaminants
│  (Fine Sand)      │   Final turbidity reduction
└────────┬──────────┘
         ↓
┌───────────────────┐
│  STRUCTURAL       │ → Supports filter media
│  SUPPORT          │   Prevents media migration
│  (Support Gravel) │   Ensures even flow distribution
└────────┬──────────┘
         ↓
TREATED WATER OUTPUT
(Fluoride: <1.5 mg/L)
```

## 2. Household System Configuration

### 2.1 Gravity-Fed System

```
                    WATER SOURCE
                    (Borehole/Well)
                          │
                          ↓
                    ┌─────────┐
                    │ Storage │
                    │  Tank   │
                    │ (50L)   │
                    └────┬────┘
                         │
                    ┌────▼────┐
                    │ Filter  │
                    │Cartridge│
                    │         │
                    └────┬────┘
                         │
                    ┌────▼────┐
                    │ Clean   │
                    │ Water   │
                    │Container│
                    │ (20L)   │
                    └─────────┘
                         │
                         ↓
                    CONSUMPTION

Flow Rate: 2-3 L/min
Pressure: Gravity (0.1-0.3 bar)
Height Difference: 1-2 meters
```

### 2.2 Pressure-Fed System (with Solar Pump)

```
    WATER SOURCE              SOLAR PANEL
    (Borehole)                (D&S Solar)
         │                         │
         │                         ↓
         │                    ┌─────────┐
         │                    │ Charge  │
         │                    │Controller│
         │                    └────┬────┘
         │                         │
         ↓                         ↓
    ┌─────────┐              ┌─────────┐
    │  Pump   │◄─────────────│ Battery │
    │ (Solar) │              │ (12V)   │
    └────┬────┘              └─────────┘
         │
         ↓
    ┌─────────┐
    │Pressure │
    │  Tank   │
    │ (100L)  │
    └────┬────┘
         │
         ↓
    ┌─────────┐
    │ Filter  │
    │Cartridge│
    └────┬────┘
         │
         ↓
    ┌─────────┐
    │  Tap    │
    └─────────┘

Flow Rate: 3-5 L/min
Pressure: 0.5-1.0 bar
Power: 50-100W solar
```

## 3. Community Kiosk System

### 3.1 Kiosk Layout

```
┌─────────────────────────────────────────────────────────┐
│                    KIOSK STRUCTURE                       │
│                    (3m x 2m x 2.5m)                     │
│                                                          │
│  ┌──────────┐  ┌──────────┐  ┌──────────┐            │
│  │  Solar   │  │  Solar   │  │  Solar   │            │
│  │  Panel   │  │  Panel   │  │  Panel   │            │
│  │  (300W)  │  │  (300W)  │  │  (300W)  │            │
│  └──────────┘  └──────────┘  └──────────┘            │
│                                                          │
│  ┌────────────────────────────────────────────────┐   │
│  │              ROOF (Corrugated Iron)            │   │
│  └────────────────────────────────────────────────┘   │
│                                                          │
│  ┌──────────────────────────────────────────────┐     │
│  │  INTERIOR LAYOUT                              │     │
│  │                                                │     │
│  │  ┌─────────┐    ┌─────────┐    ┌─────────┐  │     │
│  │  │ Storage │    │ Filter  │    │ Clean   │  │     │
│  │  │  Tank   │───▶│ System  │───▶│ Water   │  │     │
│  │  │ (500L)  │    │(Kiosk)  │    │  Tank   │  │     │
│  │  └─────────┘    └─────────┘    │ (200L)  │  │     │
│  │                                  └────┬────┘  │     │
│  │                                       │       │     │
│  │  ┌─────────┐    ┌─────────┐    ┌────▼────┐  │     │
│  │  │ Battery │    │  Pump   │    │  Taps   │  │     │
│  │  │ (24V)   │    │Control  │    │ (4x)    │  │     │
│  │  └─────────┘    └─────────┘    └─────────┘  │     │
│  │                                                │     │
│  │  ┌─────────────────────────────────────┐    │     │
│  │  │  IoT Monitoring System              │    │     │
│  │  │  - Fluoride sensors                 │    │     │
│  │  │  - Flow meters                      │    │     │
│  │  │  - GSM communication                │    │     │
│  │  └─────────────────────────────────────┘    │     │
│  │                                                │     │
│  └────────────────────────────────────────────────┘   │
│                                                          │
│  ┌────────────────────────────────────────────────┐   │
│  │         CUSTOMER SERVICE WINDOW                 │   │
│  └────────────────────────────────────────────────┘   │
│                                                          │
└─────────────────────────────────────────────────────────┘

Capacity: 200-500 jerrycans/day (4,000-10,000 L/day)
Power: 900W solar + 24V battery bank
Operators: 1-2 people
Operating Hours: 6am-8pm
```

### 3.2 Water Flow Schematic

```
BOREHOLE/WELL
      │
      ↓
┌─────────────┐
│ Solar Pump  │
│ (Submersible│
│  or Surface)│
└──────┬──────┘
       │
       ↓
┌─────────────┐
│  Storage    │
│   Tank      │
│  (500L)     │
└──────┬──────┘
       │
       ↓
┌─────────────┐
│ Pre-Filter  │
│ (50 micron) │
└──────┬──────┘
       │
       ↓
┌─────────────┐
│   Pump      │
│ (Pressure)  │
└──────┬──────┘
       │
       ↓
┌─────────────┐
│  Kiosk      │
│  Filter     │
│ Cartridge   │
│  (12L)      │
└──────┬──────┘
       │
       ↓
┌─────────────┐
│  Clean      │
│  Water      │
│  Tank       │
│  (200L)     │
└──────┬──────┘
       │
       ├──────┐
       │      │
       ↓      ↓
    ┌───┐  ┌───┐
    │Tap│  │Tap│  (4 taps total)
    │ 1 │  │ 2 │
    └───┘  └───┘

Flow Rate: 12-16 L/min
Pressure: 1.0-1.5 bar
Daily Capacity: 10,000 L
```

## 4. Manufacturing Process Flow

### 4.1 Material Preparation

```
BONE COLLECTION          CLAY MINING           MAIZE COB COLLECTION
(Abattoirs)              (Kajiado/Nakuru)      (Farms)
      │                        │                      │
      ↓                        ↓                      ↓
┌──────────┐            ┌──────────┐           ┌──────────┐
│ Cleaning │            │ Drying   │           │ Drying   │
│Degreasing│            │ Grinding │           │          │
└────┬─────┘            └────┬─────┘           └────┬─────┘
     │                       │                      │
     ↓                       ↓                      ↓
┌──────────┐            ┌──────────┐           ┌──────────┐
│Carbonize │            │  Acid    │           │Carbonize │
│600-800°C │            │Activation│           │400-500°C │
│ 4-6 hrs  │            │  90°C    │           │ 2-3 hrs  │
└────┬─────┘            └────┬─────┘           └────┬─────┘
     │                       │                      │
     ↓                       ↓                      ↓
┌──────────┐            ┌──────────┐           ┌──────────┐
│ Crushing │            │ Washing  │           │ Crushing │
│ Sieving  │            │ Drying   │           │ Sieving  │
│0.5-2mm   │            │0.1-0.5mm │           │ 1-3mm    │
└────┬─────┘            └────┬─────┘           └────┬─────┘
     │                       │                      │
     └───────────┬───────────┴──────────────────────┘
                 │
                 ↓
          ┌──────────┐
          │  MIXING  │
          │  40:30:20│
          │  + 10%   │
          │ Binders  │
          └────┬─────┘
               │
               ↓
          ┌──────────┐
          │CARTRIDGE │
          │ FILLING  │
          │ LAYERING │
          └────┬─────┘
               │
               ↓
          ┌──────────┐
          │ SEALING  │
          │ FITTING  │
          │ASSEMBLY  │
          └────┬─────┘
               │
               ↓
          ┌──────────┐
          │ QUALITY  │
          │ TESTING  │
          │ PACKAGING│
          └────┬─────┘
               │
               ↓
          FINISHED PRODUCT
```

### 4.2 Quality Control Checkpoints

```
RAW MATERIALS
      │
      ↓
┌─────────────┐
│   QC #1     │ → Particle size, moisture, purity
│ Raw Material│
└──────┬──────┘
       │
       ↓
PROCESSING
       │
       ↓
┌─────────────┐
│   QC #2     │ → Surface area, pH, carbon content
│ Processed   │
│  Material   │
└──────┬──────┘
       │
       ↓
MIXING
       │
       ↓
┌─────────────┐
│   QC #3     │ → Homogeneity, ratio verification
│   Mix       │
└──────┬──────┘
       │
       ↓
ASSEMBLY
       │
       ↓
┌─────────────┐
│   QC #4     │ → Layer integrity, compaction
│  Assembly   │
└──────┬──────┘
       │
       ↓
FINAL PRODUCT
       │
       ↓
┌─────────────┐
│   QC #5     │ → Fluoride removal test
│   Final     │   Flow rate test
│  Product    │   Leak test
└──────┬──────┘   Microbial test
       │
       ↓
PASS → PACKAGING → DISTRIBUTION
       │
FAIL → REWORK or REJECT
```

## 5. Chemical Process Diagrams

### 5.1 Fluoride Adsorption Mechanism

```
WATER WITH FLUORIDE
        │
        ↓
┌───────────────────────────────────────┐
│   BONE CHAR (Hydroxyapatite)         │
│   Ca₁₀(PO₄)₆(OH)₂                    │
│                                        │
│   Surface Sites:                      │
│   ≡Ca-OH  ≡Ca-OH  ≡Ca-OH            │
│      │       │       │                │
│      ↓       ↓       ↓                │
│   FLUORIDE IONS (F⁻) APPROACH        │
│      │       │       │                │
│      ↓       ↓       ↓                │
│   ION EXCHANGE OCCURS:                │
│   ≡Ca-OH + F⁻ → ≡Ca-F + OH⁻         │
│                                        │
│   RESULT:                             │
│   ≡Ca-F   ≡Ca-F   ≡Ca-F              │
│   (Fluoride bound to surface)         │
└───────────────────────────────────────┘
        │
        ↓
WATER WITH REDUCED FLUORIDE
```

### 5.2 Multi-Stage Filtration Process

```
INPUT WATER
Fluoride: 10 mg/L
Turbidity: 20 NTU
pH: 7.5
        │
        ↓
┌───────────────────┐
│  STAGE 1:         │
│  Coarse Gravel    │
│                   │
│  Removes:         │
│  - Sediment       │
│  - Large particles│
│                   │
│  Output:          │
│  Turbidity: 10 NTU│
└────────┬──────────┘
         ↓
┌───────────────────┐
│  STAGE 2:         │
│  Bio-Mineral Mix  │
│                   │
│  Mechanisms:      │
│  - Ion exchange   │
│  - Adsorption     │
│  - Precipitation  │
│                   │
│  Output:          │
│  Fluoride: 1.0 mg/L│
│  Turbidity: 5 NTU │
└────────┬──────────┘
         ↓
┌───────────────────┐
│  STAGE 3:         │
│  Fine Sand        │
│                   │
│  Removes:         │
│  - Fine particles │
│  - Residual       │
│    contaminants   │
│                   │
│  Output:          │
│  Turbidity: 1 NTU │
└────────┬──────────┘
         ↓
OUTPUT WATER
Fluoride: 1.0 mg/L
Turbidity: 1 NTU
pH: 7.3
Removal: 90%
```

## 6. Installation Diagrams

### 6.1 Household Installation Steps

```
STEP 1: SITE PREPARATION
┌─────────────────────┐
│  Select location:   │
│  - Near water source│
│  - Accessible       │
│  - Protected        │
│  - Level surface    │
└─────────────────────┘

STEP 2: MOUNTING
┌─────────────────────┐
│  Install bracket:   │
│  - Wall mount or    │
│  - Stand mount      │
│  - Height: 1-1.5m   │
│  - Secure firmly    │
└─────────────────────┘

STEP 3: PLUMBING
┌─────────────────────┐
│  Connect pipes:     │
│  - Input from source│
│  - Output to storage│
│  - Use 1/2" HDPE    │
│  - Seal connections │
└─────────────────────┘

STEP 4: TESTING
┌─────────────────────┐
│  Test system:       │
│  - Check for leaks  │
│  - Measure flow rate│
│  - Test water quality│
│  - Adjust as needed │
└─────────────────────┘

STEP 5: TRAINING
┌─────────────────────┐
│  Train user:        │
│  - Operation        │
│  - Maintenance      │
│  - Troubleshooting  │
│  - Contact info     │
└─────────────────────┘
```

### 6.2 Kiosk Installation Layout

```
SITE PLAN (Top View)

    N
    ↑

┌─────────────────────────────────────┐
│                                     │
│  ┌───────────────────────────┐    │
│  │      KIOSK STRUCTURE      │    │
│  │         (3m x 2m)         │    │
│  │                           │    │
│  │  ┌─────┐  ┌─────┐       │    │
│  │  │Tank │  │Filter│       │    │
│  │  │500L │  │System│       │    │
│  │  └─────┘  └─────┘       │    │
│  │                           │    │
│  │  ┌─────────────────┐    │    │
│  │  │  Service Window │    │    │
│  │  └─────────────────┘    │    │
│  └───────────────────────────┘    │
│                                     │
│  ┌─────────┐                       │
│  │ Solar   │                       │
│  │ Panels  │                       │
│  │ (Ground │                       │
│  │ Mount)  │                       │
│  └─────────┘                       │
│                                     │
│  ┌─────────┐                       │
│  │Borehole │                       │
│  │  Well   │                       │
│  └─────────┘                       │
│                                     │
│  Customer Queue Area               │
│  ═══════════════════               │
│                                     │
└─────────────────────────────────────┘

Dimensions: 10m x 8m plot
Access: 3m wide entrance
Drainage: Slope away from kiosk
Fencing: Optional perimeter fence
```

## 7. Maintenance Procedures

### 7.1 Monthly Maintenance Checklist

```
┌─────────────────────────────────────┐
│  MONTHLY MAINTENANCE CHECKLIST      │
├─────────────────────────────────────┤
│                                     │
│  □ Visual Inspection                │
│    - Check for leaks                │
│    - Inspect housing for cracks     │
│    - Check connections              │
│                                     │
│  □ Flow Rate Test                   │
│    - Measure flow rate              │
│    - Compare to baseline            │
│    - Document results               │
│                                     │
│  □ Water Quality Test               │
│    - Test fluoride levels           │
│    - Check pH                       │
│    - Measure turbidity              │
│                                     │
│  □ Pre-Filter Cleaning              │
│    - Remove pre-filter screen       │
│    - Clean with brush               │
│    - Rinse thoroughly               │
│    - Reinstall                      │
│                                     │
│  □ System Flush                     │
│    - Run water for 5 minutes        │
│    - Check for unusual color/odor   │
│    - Verify normal operation        │
│                                     │
│  □ Documentation                    │
│    - Record all measurements        │
│    - Note any issues                │
│    - Update maintenance log         │
│                                     │
└─────────────────────────────────────┘
```

### 7.2 Filter Replacement Procedure

```
STEP 1: PREPARATION
┌─────────────────────┐
│ - Shut off water    │
│ - Drain system      │
│ - Gather tools      │
│ - Prepare new filter│
└──────┬──────────────┘
       │
       ↓
STEP 2: REMOVAL
┌─────────────────────┐
│ - Disconnect inlet  │
│ - Disconnect outlet │
│ - Remove old filter │
│ - Inspect housing   │
└──────┬──────────────┘
       │
       ↓
STEP 3: INSTALLATION
┌─────────────────────┐
│ - Clean connections │
│ - Install new filter│
│ - Connect inlet     │
│ - Connect outlet    │
└──────┬──────────────┘
       │
       ↓
STEP 4: TESTING
┌─────────────────────┐
│ - Turn on water     │
│ - Check for leaks   │
│ - Flush system      │
│ - Test water quality│
└──────┬──────────────┘
       │
       ↓
STEP 5: DOCUMENTATION
┌─────────────────────┐
│ - Record date       │
│ - Note filter ID    │
│ - Update schedule   │
│ - Dispose old filter│
└─────────────────────┘
```

## 8. Troubleshooting Guide

### 8.1 Common Issues & Solutions

```
PROBLEM: Low Flow Rate
        │
        ↓
┌───────────────────────┐
│ Check:                │
│ 1. Pre-filter clogged?│──→ Clean pre-filter
│ 2. Filter saturated?  │──→ Replace filter
│ 3. Air lock?          │──→ Bleed system
│ 4. Low pressure?      │──→ Check pump/source
└───────────────────────┘

PROBLEM: High Fluoride Output
        │
        ↓
┌───────────────────────┐
│ Check:                │
│ 1. Filter exhausted?  │──→ Replace filter
│ 2. Bypass leak?       │──→ Check connections
│ 3. Wrong filter type? │──→ Verify specifications
│ 4. High input level?  │──→ Test input water
└───────────────────────┘

PROBLEM: Leaking
        │
        ↓
┌───────────────────────┐
│ Check:                │
│ 1. Loose connections? │──→ Tighten fittings
│ 2. Damaged O-rings?   │──→ Replace seals
│ 3. Cracked housing?   │──→ Replace cartridge
│ 4. Over-pressure?     │──→ Install regulator
└───────────────────────┘

PROBLEM: Cloudy Water
        │
        ↓
┌───────────────────────┐
│ Check:                │
│ 1. New filter?        │──→ Flush thoroughly
│ 2. Air bubbles?       │──→ Normal, will clear
│ 3. Bacterial growth?  │──→ Sanitize system
│ 4. Source quality?    │──→ Test input water
└───────────────────────┘
```

## 9. Performance Monitoring

### 9.1 Key Performance Indicators

```
┌─────────────────────────────────────────────┐
│  FILTER PERFORMANCE DASHBOARD               │
├─────────────────────────────────────────────┤
│                                             │
│  Fluoride Removal Efficiency                │
│  ████████████████████░░  90%               │
│  Target: >85%  Status: ✓ GOOD              │
│                                             │
│  Flow Rate                                  │
│  ██████████████░░░░░░░░  2.8 L/min         │
│  Target: 2-4 L/min  Status: ✓ GOOD         │
│                                             │
│  Filter Age                                 │
│  ████████████████████░░  145 days          │
│  Lifespan: 180 days  Status: ⚠ REPLACE SOON│
│                                             │
│  Water Quality (Output)                     │
│  Fluoride: 0.8 mg/L  ✓ (WHO: <1.5)        │
│  pH: 7.2  ✓ (Range: 6.5-8.5)              │
│  Turbidity: 1.5 NTU  ✓ (<5)               │
│                                             │
│  System Health                              │
│  Pressure: 1.2 bar  ✓ NORMAL               │
│  Leaks: None  ✓                            │
│  Last Maintenance: 15 days ago  ✓          │
│                                             │
└─────────────────────────────────────────────┘
```

## 10. Safety & Compliance

### 10.1 Safety Features

```
┌─────────────────────────────────────┐
│  SAFETY FEATURES                    │
├─────────────────────────────────────┤
│                                     │
│  1. Pressure Relief Valve           │
│     - Prevents over-pressure        │
│     - Set at 2.5 bar                │
│     - Auto-release                  │
│                                     │
│  2. Food-Grade Materials            │
│     - HDPE housing (BPA-free)       │
│     - Stainless steel fittings      │
│     - Non-toxic media               │
│                                     │
│  3. Tamper-Evident Seals            │
│     - Quality assurance             │
│     - Prevents contamination        │
│     - Warranty protection           │
│                                     │
│  4. Sampling Ports                  │
│     - Quality monitoring            │
│     - Easy testing                  │
│     - Compliance verification       │
│                                     │
│  5. Clear Labeling                  │
│     - Installation date             │
│     - Replacement schedule          │
│     - Contact information           │
│     - Safety warnings               │
│                                     │
└─────────────────────────────────────┘
```

---

**Document Version:** 1.0  
**Last Updated:** May 2026  
**Author:** FluoriVenger Design Team  
**Review Cycle:** Quarterly

For technical design inquiries, contact: design@fluorivenger.ke

## Notes

- All dimensions in millimeters unless otherwise specified
- Materials comply with Kenya Bureau of Standards (KEBS)
- Designs subject to continuous improvement
- CAD files available upon request
- Manufacturing tolerances: ±2mm for housing, ±5% for media quantities