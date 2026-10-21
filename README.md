# bic21203-lab4a-javascript
DANISH MUKHRIZ BIN MOHD ZULKERNAIN ISKANDAR AI250295 LAB 4A PRACTICE
# BIC21203 - Lab 4a: Client-Side Scripting (JavaScript)

- DANISH MUKHRIZ BIN MOHD ZULKERNAIN ISKANDAR
- AI250295

## Overview
This repository contains the solutions for Lab 4a, covering DOM manipulation, user input validation, and dynamic element generation using client-side JavaScript.

## How to Run & Expected Outputs

To run and verify the solutions, open the respective HTML file in any modern web browser (Google Chrome, Microsoft Edge, etc.)

### Question 1: Interactive Text Changer (`q1.html`)
1. Open `q1.html` in your browser.
2. **Initial Display:** The page shows the default heading/paragraph text: `"Welcome to my website!"` above the "Change Message" button.
3. Click the **"Change Message"** button.
4. **Expected Output:** The paragraph text immediately updates to `"Hello there!"` via DOM text content manipulation.

Expected Output:
Before:
<img width="175" height="80" alt="image" src="https://github.com/user-attachments/assets/55c068b9-088d-4a34-b024-2ece496ee664" />

After:
<img width="168" height="81" alt="image" src="https://github.com/user-attachments/assets/95469c6d-8894-4808-af38-bbabc5b0ffc5" />

---

### Question 2: Smart Number Validator (`q2.html`)
1. Open `q2.html` in your browser.
2. Enter a value into the input field and click the **"Check"** button.
3. **Expected Outputs based on test cases:**
   - **Input `< 10` (e.g., `5`):** Displays `"The number is lower than 10"`.
   - **Input `> 10` (e.g., `15`):** Displays `"The number is higher than 10"`.
   - **Input `== 10` (e.g., `10` or `10.0`):** Displays `"The number is equal to 10"`.
   - **Non-numeric input (e.g., `abc`):** Displays `"Please enter a valid number!"`.
   - **Empty / Whitespace input:** Displays `"Please enter a valid number!"`.

Expected Output:
<img width="289" height="67" alt="image" src="https://github.com/user-attachments/assets/b4b5b89c-f455-43d4-981b-3ea16acb980b" />

<img width="292" height="62" alt="image" src="https://github.com/user-attachments/assets/6fb28165-0b38-437b-b7c0-119fcff11521" />

<img width="279" height="71" alt="image" src="https://github.com/user-attachments/assets/45b20554-f546-49d0-9480-f6e84a1aa853" />

<img width="281" height="61" alt="image" src="https://github.com/user-attachments/assets/daab5793-6693-453f-b76a-5f1200899523" />

<img width="273" height="62" alt="image" src="https://github.com/user-attachments/assets/0fd440ef-756e-4c97-94d3-8602f8a866e2" />

<img width="277" height="59" alt="image" src="https://github.com/user-attachments/assets/6598562f-c4fe-4a07-9921-19459eea04da" />

---

### Question 3: Dynamic Number Generator (`q3.html`)
1. Open `q3.html` in your browser.
2. **Initial Display:** Only the **"Generate"** button is visible with an empty ordered list area.
3. Click the **"Generate"** button.
4. **Expected Output:** An ordered list (`<ol>`) dynamically populates with five list items (`<li>`) numbered sequentially:
   1. The number is 1
   2. The number is 2
   3. The number is 3
   4. The number is 4
   5. The number is 5
5. **Duplicate Prevention Verification:** Clicking the button repeatedly clears the previous list first, ensuring it consistently displays only five items without creating duplicates.

Expected Output:
<img width="205" height="124" alt="image" src="https://github.com/user-attachments/assets/61185873-fab2-4cb1-909b-3bc7bfc75946" />
