# 🧠 Pydantic Practice Repository

This repository contains hands-on practice and examples using **Pydantic** for data validation, serialization, and model design in Python.

It covers core concepts required for building robust APIs (especially with FastAPI).

---

## 📂 Project Structure

```
.
├── pydantic_tutorials.py
├── Feild_validator.py
├── model_validator.py
├── Computed_fields.py
├── Nested_model.py
├── Serialization.py
├── patients.json
```

---

## 📌 Topics Covered

### 🔹 1. Basic Pydantic Model

📄 `pydantic_tutorials.py`

* Creating basic models
* Type validation (int, str, Email, URL)
* Optional fields
* Example:

  * User/Patient data validation
  * Insert & update functions

👉 See file: 

---

### 🔹 2. Field Validators

📄 `Feild_validator.py`

* Custom validation using `@field_validator`
* Domain-based email validation
* Data transformation (e.g., name → uppercase)

👉 See file: 

---

### 🔹 3. Model Validator

📄 `model_validator.py`

* Cross-field validation using `@model_validator`
* Business logic:

  * If age > 60 → emergency contact required

👉 See file: 

---

### 🔹 4. Computed Fields

📄 `Computed_fields.py`

* Automatically calculated fields using `@computed_field`
* Example:

  * BMI calculation from height & weight

👉 See file: 

---

### 🔹 5. Nested Models

📄 `Nested_model.py`

* Model inside another model
* Structured data validation
* Access nested fields easily

👉 See file: 

---

### 🔹 6. Serialization

📄 `Serialization.py`

* Convert model → dictionary (`model_dump`)
* Convert model → JSON (`model_dump_json`)

👉 See file: 

---

### 🔹 7. Sample Dataset

📄 `patients.json`

* Sample patient records
* Includes:

  * BMI
  * Health verdict (Underweight, Normal, etc.)

👉 See file: 

---

## 🚀 Key Concepts Learned

* Data validation using Pydantic
* Field-level validation
* Model-level validation
* Computed/derived fields
* Nested data structures
* Serialization & JSON conversion

---

## ⚙️ How to Run

1. Activate virtual environment:

```bash
myenv\Scripts\activate
```

2. Run any file:

```bash
python file_name.py
```

Example:

```bash
python model_validator.py
```

---

## 📦 Requirements

Install dependencies:

```bash
pip install pydantic
pip install "pydantic[email]"
```



