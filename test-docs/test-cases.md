# ✅ Test Cases – Nx Console UI Bug

| TC ID     | Description                                | Steps                                                                 | Expected Result                        | Status |
|-----------|--------------------------------------------|-----------------------------------------------------------------------|----------------------------------------|--------|
| TC_UI_01  | Verify layout of target action buttons     | Open IntelliJ > Nx Console > Select any project > Check Targets pane | All buttons are aligned and clickable  | ❌ Fail |
| TC_UI_02  | Check interaction on overlapped buttons    | Hover and click `run`, `graph`, etc.                                 | Buttons should respond individually    | ❌ Fail |
| TC_UI_03  | Test resizing of Nx Console panel          | Drag and resize the panel width/height                                | Layout should adjust responsively      | ✅ Pass |
| TC_UI_04  | Verify in different IntelliJ themes        | Switch between light/dark themes                                     | Buttons remain properly aligned        | ❌ Fail |
| TC_UI_05  | Cross-IDE comparison (VS Code)             | Open same project in VS Code Nx Console                              | Buttons are properly spaced in VS Code | ✅ Pass |
