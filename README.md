# CodeWeavex.NET — Demo Edition

**CodeWeavex** synchronizes SQL Server database schemas with C# model classes.  
It compares both structures, detects differences, and generates safe SQL scripts to keep your database fully aligned with your code.  
Includes metadata handling, JSON/XML schema export, HTML reporting, and full constraint synchronization.

---

## ⚙️ Current Edition: Demo

This is the **Demo Edition** of CodeWeavex.  
It is provided for testing and feedback purposes.  
The goal is to gather user impressions and improve the final product before releasing the **Full (commercial) Edition**.

### 🔒 Limitations in this demo
- Maximum of **2 tables** can be synchronized  
- **Record deletion** is disabled  

All other features are fully functional.

---

## 🚀 What CodeWeavex Does

1. Reads your database model from C# classes using attributes such as `[FieldMetadata]` and `[IndexMetadata]`  
2. Reads the actual structure directly from SQL Server  
3. Compares both schemas and identifies all structural differences (tables, columns, keys, indexes, constraints)  
4. Generates safe SQL scripts to synchronize the database with the model  
5. Optionally executes the synchronization automatically  
6. Produces a detailed **HTML report** showing all differences and actions performed  
7. Can **export any database schema** to a standalone HTML document for review or documentation  
8. Can **export differences between model and database** to **JSON** or **XML** formats for automation or audit purposes  
9. Demonstrates record operations (insert and update) through the included **Sample** program

---

## 🧩 Sample Program

Each release of CodeWeavex includes a **Sample Console Application** that demonstrates how to use the DLL.  
It shows schema synchronization, record creation, and updates in action.

Run the sample, explore the generated SQL and reports, and see how CodeWeavex automates the process.

---

## 🧠 Requirements

- **.NET 8.0**  
- **SQL Server 2016** or newer  
- **Windows 10+**
- **Microsoft SQL Server (any edition) **

---

## 🧰 Getting Started

1. **Clone this repository** or download the latest ZIP from the [Releases](../../releases) section  
2. The repository includes the full source code of the **Sample** program, showing how to use CodeWeavex  
3. The **CodeWeavex.Core.dll** (Demo Edition) is provided as a precompiled binary  
4. Open the solution in **Visual Studio 2022**  
5. Run the **CodeWeavex.Sample** project to explore schema synchronization, record creation, and updates  

---

## 💡 Feedback Wanted

This demo is an early version — your feedback will directly shape the **Full Edition**, which will include:
- Unlimited tables  
- Record deletion  
- Advanced configuration and logging  
- PostgreSQL support *(planned)*  

If you find issues or have suggestions, please open a GitHub issue or share your thoughts.

---

## ⚖️ License

CodeWeavex is proprietary software.  
All rights reserved © 2025 FZC.  
Redistribution, modification, or commercial use without explicit consent is prohibited.
