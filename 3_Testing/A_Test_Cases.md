# Test Cases for Railway Crossing Logic Circuit

Below are four test cases designed to verify the correct operation of the railway crossing logic circuit, using the specified inputs and outputs. Each test case considers different combinations of sensor states and manual controls. For each case, the expected output is stated, and space is provided to record the actual output during testing.

---

## Test Case 1: No Train, No Obstruction

**Inputs:**

- Distant train presence: OFF
- Near train presence: OFF
- Gate obstruction detection: OFF
- Manual override controls: INACTIVE

**Expected Output:**

- Lights: OFF
- Bells: OFF
- Siren: OFF
- Gate: OPEN

**Actual Output:**
-

---

## Test Case 2: Train Approaching, No Obstruction

**Inputs:**

- Distant train presence: ON
- Near train presence: OFF
- Gate obstruction detection: OFF
- Manual override controls: INACTIVE

**Expected Output:**

- Lights: ON
- Bells: ON
- Siren: OFF
- Gate: CLOSE

**Actual Output:**
-

---

## Test Case 3: Train Approaching, Obstruction Detected

**Inputs:**

- Distant train presence: ON
- Near train presence: OFF
- Gate obstruction detection: ON
- Manual override controls: INACTIVE

**Expected Output:**

- Lights: ON
- Bells: ON
- Siren: ON
- Gate: OPEN

**Actual Output:**
-

---

## Test Case 4: Manual Override Activated

**Inputs:**

- Distant train presence: ON
- Near train presence: ON
- Gate obstruction detection: OFF
- Manual override controls: ACTIVE

**Expected Output:**

- Lights: As controlled by manual override
- Bells: As controlled by manual override
- Siren: As controlled by manual override
- Gate: As controlled by manual override

**Actual Output:**
-

---
