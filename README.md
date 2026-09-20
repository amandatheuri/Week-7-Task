## 🧪 Week 7: Analytical Testing, KPI Validation & Dashboard Refinement

### 🎯 Objective
Systematically test, refine, and validate Week 6 analytical outputs, ensure absolute mathematical accuracy in Power BI DAX calculations, optimize visual usability, and validate cross-track dependencies with the Data Science team.

---

### 📋 Testing & Validation Summary
* **KPI Calculations Tested:** `No-Show Rate %` (48.5%), `Attendance Rate %` (46.3%), `Wasted Capacity %` (53.7%), `Lost Hours` (1,210 hrs).
* **Test Suite Execution:** 6 Test Scenarios executed; 3 visual/formatting defects identified and resolved; 100% pass rate achieved on re-test.
* **DAX Column Additions:** Created `Distance Tier` (`<5 km`, `5-15 km`, `>15 km`) and `Needs Urgent Outreach` operational flags.

---

### 🤝 Cross-Track Testing & Collaboration (Data Science & PM)
* **Data Science Alignment:** Validated that Analytics high-risk segment rules (`Booking Lead Days > 14`) directly align with Data Science Gradient Boosting error drivers and feature importance models.
* **Decision Support:** Confirmed that a 0.45 decision threshold in prediction models aligns with the dashboard's operational administrative queue.
* **Project Management:** Updated the central Issue Log and Risk Register with completed re-testing evidence.

---

### 🛠️ Key Dashboard Improvements (v2.pbix)
1. Reformatted SMS KPI card to display as a percentage (`45.8%`) with green callout alerts.
2. Replaced continuous decimal distance values in matrix visuals with discrete `Distance Tier` buckets.
3. Disabled non-sensical column totals on the operational high-risk table visual.
4. Verified end-to-end dynamic slicer cross-filtering across all canvas visuals.
