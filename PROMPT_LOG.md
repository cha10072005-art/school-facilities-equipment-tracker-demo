# Prompt Log - One Entry Per Prompt

## FR-01

- Prompt:
1. You are a helpful senior web developer.
2. Create a simple School Facilities and Equipment Concern Tracker for Medina College Ipil using HTML, CSS, and JavaScript in one file (index.html).
3. Users can submit a concern with category, location, item or facility name, date reported, and description. 
4. Require all fields and reject invalid or future dates.
5. Save submitted concerns using localStorage and display all saved records. 
6. Keep the records after a page refresh. Use embedded CSS and JavaScript. Do not use any libraries, frameworks, backend, database, or login features.
Add short comments, keep the design simple and clean, and tell me how to open and test it.


- Result:
Copilot created index.html with a concern form and saved concerns section.

- Verified:
All six test cases passed.



## FR-02: Filter Concerns by Category

**Prompt Used:**

Add a category filter to the Saved Concerns section of my existing School Facilities and Equipment Concern Tracker.

Allow users to filter saved concerns by category, including an option to display all concerns.

Keep the existing form, validation, localStorage functionality, and design unchanged.

Use only the existing index.html file. Do not use libraries or frameworks.

After implementing the feature, explain how I can test it.

**AI Tool:** GitHub Copilot Agent Mode

**File Modified:** index.html

**Feature Implemented:** Category filter with an All categories option.

**Testing:** [Testing: Successfully tested the category filter.
Electrical and Furniture categories displayed only their matching concerns.
The All categories option displayed all saved concerns.
Saved records remained available after refreshing the page.]

**Fixes Made:** [No fixes needed.]
