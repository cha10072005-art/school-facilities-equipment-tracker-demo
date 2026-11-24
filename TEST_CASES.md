# FR-01 Test Cases
## School Facilities and Equipment Concern Tracker

| Test ID | Test Description | Expected Result | Actual Result | Status |
|---|---|---|---|---|
| TC-01 | Submit a concern with all fields completed | Concern is submitted successfully | Successful | PASS |
| TC-02 | Submit with an empty required field | System displays validation error | Validation works | PASS |
| TC-03 | Enter an invalid date | System rejects the date | Date rejected | PASS |
| TC-04 | Enter a future date | System rejects the date | Date rejected | PASS |
| TC-05 | Refresh the browser after submitting a concern | Saved concern remains displayed | Record remains | PASS |
| TC-06 | Submit multiple concerns | All saved concerns are displayed | Records displayed | PASS |



## FR-02: Filter Concerns by Category

| Test No. | Test Description | Expected Result | Actual Result | Status |
|---|---|---|---|---|
| TC-07 | Add an Electrical concern | Concern is saved and displayed | [PASS] | [PASS/FAIL] |
| TC-08 | Add a Furniture concern | Concern is saved and displayed | [PASS] | [PASS/FAIL] |
| TC-09 | Select Electrical category | Only Electrical concerns appear | [PASS] | [PASS/FAIL] |
| TC-10 | Select Furniture category | Only Furniture concerns appear | [PASS] | [PASS/FAIL] |
| TC-11 | Select All categories | All saved concerns appear | [PASS] | [PASS/FAIL] |
| TC-12 | Refresh the page | Saved concerns remain available | [PASS] | [PASS/FAIL] |
