# Supplement Master Database

Comprehensive database structure for tracking supplements, brands, and related data.

## Directory Structure

```
/data
├── brands.csv          # Brand information
├── products.csv        # Product details
├── ingredients.csv     # Base ingredients
├── proprietary.csv     # Proprietary formulations
├── categories.csv      # Category system
├── quality.csv         # Quality and COA data
├── combinations.csv    # Supplement combinations
├── delivery.csv        # Delivery systems
└── research.csv        # Research references
```

## File Structure

### brands.csv
- brand_id (3 letters: TNQ, NOW)
- name
- website
- quality_certifications
- manufacturing_standards
- country
- founding_year
- trademarks
- patents

### products.csv
- product_id (BRAND###)
- brand_id
- name
- primary_ingredient
- prop_forms
- dosage
- unit
- form
- serving_size
- categories
- certifications
- price
- size
- cost_per_serving
- price_tier
- image_url

[Additional file structures will be added in subsequent commits]

## Usage

1. Each CSV file contains specific data categories
2. Files are linked through ID fields
3. Follow the format in sample data
4. Maintain consistent units and naming

## Getting Started

1. Clone this repository
2. Follow data entry guidelines
3. Start with sample Toniqq data as reference
4. Maintain consistent formatting