# 📦 Stock Management System

A complete, **production-ready stock management dashboard** built with **HTML5**, **TailwindCSS**, and **Vanilla JavaScript**. No backend needed—all data stored locally in your browser!

## ✨ Features

✅ **Product Management** - Add, track, and delete products  
✅ **Multiple Inventories** - Support for main and sub-inventories  
✅ **Stock Taking** - Daily inventory counts with automatic calculations  
✅ **Transfer System** - Move stock between inventories with tracking  
✅ **Credit Management** - Track negative variations (debts) and mark as resolved  
✅ **Audit Trail** - Complete audit log of all system changes  
✅ **Reports & Portfolio** - Generate detailed stock reports and export to PDF  
✅ **Local Storage** - All data persists in your browser  

## 🚀 Quick Start

### **Online (No Installation)**
👉 **[Click here to use it online](https://your-username.github.io/stock-management-system)**

### **Or Download and Run Locally**

1. **Download** `index.html` from this repository
2. **Open** the file in any web browser (Chrome, Firefox, Safari, Edge)
3. **Start managing your stock!**

That's it! No installation, no server needed.

## 📊 How to Use

### **1. Create Inventories**
- Go to **🏪 Inventories** section
- Create Main and Sub inventories
- Link sub-inventories to mains

### **2. Add Products**
- Go to **📦 Products** section
- Add products to your inventories
- Select unit type (kg, liters, pcs, etc.)

### **3. Daily Stock Taking**
- Go to **📊 Stock Taking** section
- Select date and inventory
- Add all products with their counts
- Enter staff names (Chef, Cashier, Controller)
- Click **SAVE**

### **4. Stock Transfers**
- Use **↔️ Transfer** section to move stock between inventories
- All transfers are tracked and audited

### **5. Credit Management**
- **💳 Credit** section shows negative variations (debts)
- Mark debts as resolved
- Prevents double-counting of negative variations

### **6. Reports & Analysis**
- View all saved reports in **📑 Reports**
- Generate detailed portfolio analysis in **📈 Portfolio**
- Export reports to PDF

## 📋 Column Definitions

| Column | Meaning |
|--------|---------|
| **O** | Opening Stock (from previous count) |
| **A** | Added (new stock received) |
| **U** | Used (consumed/used) |
| **S** | Spoiled (damaged/expired) |
| **C/S** | Calculated Stock (O + A - U - S) |
| **P/S** | Physical Stock (what you counted) |
| **V** | Variation (P/S - C/S, shows discrepancies) |

## 🔒 Privacy & Security

✅ **All data stored locally** in your browser (IndexedDB/LocalStorage)  
✅ **No internet required** after initial load  
✅ **No accounts or logins** needed  
✅ **Your data is yours** - never sent to servers  
✅ **Completely private** - no tracking  

## 💡 Pro Tips

1. **Backup Your Data**
   - Regularly export reports to PDF or take screenshots
   - Browser data can be cleared accidentally

2. **Clear Debts Before Next Count**
   - Always resolve negative variations in the Credit section
   - You can't start a new count until debts are resolved

3. **Use Descriptive Names**
   - Inventory names: "Kitchen", "Storage Room", "Freezer"
   - Product names: "Chicken Breast (kg)", "Olive Oil (liters)"

4. **Check Audit Trail**
   - View all changes in **🔍 Audit** section
   - Helps track who made changes and when

5. **Track Transfers**
   - Use transfers to move stock between locations
   - All transfers are automatically adjusted in stock calculations

## 🎯 Workflow Example

**Daily Workflow:**

1. **Morning:** Go to Stock Taking
2. **Select today's date & inventory**
3. **Count each product** and enter physical stock
4. **Review variations** (differences between calculated and physical)
5. **Investigate large variations**
6. **Save the report**
7. **Check Credit section** for any debts that need attention
8. **Next day:** Repeat!

## 📱 Compatibility

Works on:
- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers (phones and tablets)

## 💾 Data Persistence

Your data is automatically saved in your browser's local storage. 

**To backup:**
- Export reports to PDF using the "PDF" button in reports
- Take screenshots of important data
- Note: Clearing browser data will delete everything

**To transfer to another device:**
- Currently no built-in sync (data is local only)
- You can manually copy data via browser DevTools console

## 🐛 Troubleshooting

**"Browser LocalStorage is full"**
- Delete old reports you don't need
- Use a different browser with more storage

**"Data disappeared"**
- Likely cleared browser cache/history
- Check if you cleared "Cookies and Cached Images"
- Consider backing up reports to PDF regularly

**"Can't add new stock count"**
- You may have unresolved debts from previous count
- Go to Credit section and mark them as resolved first

## 📄 License

Free to use and modify. Enjoy! 🎉

---

## 📞 Support

Have questions? Open an **Issue** on this repository or check the code comments.

---

**Made with ❤️ for better inventory management**
