# X-tract Expense Management (ServiceNow App)

X-tract is a custom **ServiceNow application** built to simplify expense tracking and categorization.  
It allows users to upload Excel/CSV files of expenses, automatically transform and load them into a custom table,  
and visualize insights through dashboards.

---

## 🚀 Features
- 📂 **File Import (Excel/CSV)** – Upload expenses and stage them in a custom import set table.  
- 🔄 **Transform Maps** – Map raw uploaded data (description, date, amount, category, payment method, etc.) into the target table.  
- 📊 **Expense Dashboard** – View categorized expenses, track totals, and analyze by date or category.  
- 🤖 **Potential AI Agent** – Can be extended with an AI chatbot to:  
  - Answer questions like *"What was my total expense last week?"*  
  - Automatically categorize payments based on description.  

---

## 🛠️ Technical Details
- Built entirely on **ServiceNow Studio** in a scoped application (`X-tract`).  
- Custom tables:  
  - `u_xtract_import_staging` – staging for imported data.  
  - `xtract_expense` – final expense records.  
- Transformation logic via **Transform Maps** + optional **onBefore/onAfter scripts**.  
- Extendable dashboards using **Performance Analytics (PA)**.  

---

## 📥 Installation
1. Download the latest **Update Set XML** from the Repo.  
2. In your ServiceNow instance, navigate to:  
3. Upload the XML file.  
4. Preview and Commit the update set.  
5. The app will be available in your application navigator under **X-tract**.

## 🧑‍💻 Author
**Dinessh V**  
- 📍 Chennai, India  
- 🔗 [LinkedIn](https://www.linkedin.com/in/dinessh-venkat-84065524a/)  
- 💻 [GitHub](https://github.com/Dinessh2815)

---

## ⚡ Future Enhancements
- AI-powered **chatbot assistant** for querying expenses.  
- NLP-based categorization of expenses.  
- Integration with external APIs (Google Sheets, payment apps).  
