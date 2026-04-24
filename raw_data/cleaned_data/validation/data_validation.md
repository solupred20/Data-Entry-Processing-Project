# Data Validation & Quality Checks

## Objective
Ensure data accuracy, completeness, and consistency after data entry and cleaning.

---

## Validation Rules

### 1. Missing Values
- No empty fields allowed (age, email, city)

### 2. Email Format
- Must contain "@" and ".com"

### 3. Phone Number
- Must be 11 digits
- Must start with 010, 011, or 012

### 4. Age Validation
- Age must be between 18 and 60

### 5. City Standardization
- Allowed values:
  - Cairo
  - Alexandria
  - Giza

---

## Errors Found in Raw Data

- Missing age (John Doe)
- Invalid email (sara@email)
- Missing city (Laila Hassan)
- Incorrect phone format

---

## Actions Taken

- Filled missing values
- Corrected email formats
- Standardized city names
- Fixed phone numbers

---

## Final Result

The cleaned dataset is accurate, consistent, and ready for use in data analysis or AI systems.

---

## QA Insight

Applying validation rules ensures high data quality and reduces errors in downstream systems.
