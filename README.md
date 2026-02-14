# 👥 Vendors Manpower Attendance & Salary System

An Excel-based attendance and salary management system for vendor-provided manpower (housekeeping, security guards, pantry staff) with automatic salary calculations, overtime tracking, and transparent billing.

## 📋 What This Does

**Solves the problem:** How to track vendor manpower attendance accurately, calculate salaries automatically, and generate transparent billing for multiple vendors across multiple locations.

**Key Benefits:**
- Track daily attendance for housekeeping, security, and support staff
- Automatically calculate salaries based on actual working days
- Monitor overtime hours and convert to billable days
- Generate monthly billing reports for each vendor
- Maintain complete audit trail for compliance

## 📸 View the File

**[Access Vendors Manpower Attendance System](https://excel.cloud.microsoft/open/onedrive/?docId=3B61701CAABF1310%21s4bb5ab51c44c439eaae4f75464c6a01a&driveId=3B61701CAABF1310)**

> **Password for all sheets: `123`**

## 📸 System Screenshots

### Attendance Data Entry & Summary
<img width="1281" height="865" alt="1" src="https://github.com/user-attachments/assets/460c51d9-84ad-4454-878e-5c988630d642" />

*Daily attendance entry form with automatic columns for each day, showing P, A, WO, HD, and partial shifts. Automatic calculations for Present, Absent, Weekly Offs, and Total Amount.*


### Master Configuration (Sheet Tool)
<img width="1278" height="859" alt="2" src="https://github.com/user-attachments/assets/620a4011-0f2b-471b-aedc-bdcc3e45323a" />

*Setup sheet with all designations, monthly salaries, vendor names, and office locations. All lookups reference this sheet automatically.*


### Detailed Attendance with Calculations
<img width="1280" height="862" alt="3" src="https://github.com/user-attachments/assets/5095ab24-96f8-48ed-a105-99c8c9d5ca9b" />

*Full month view with all daily attendances, working days calculation, OT tracking, and final salary amounts per employee.*


## ✨ Main Features

### 1. Daily Attendance Entry
- **P** = Present (full day)
- **P1-P8** = Partial shifts (1-8 hours worked)
- **A** = Absent
- **WO** = Weekly Off
- **HD** = Holiday
- Automatic Saturday/Sunday coloring

### 2. Multi-Vendor Support
- Track multiple vendors simultaneously
- Compare vendor performance
- Separate billing per vendor
- Vendor-wise attendance reports

### 3. Multiple Designations
- Housekeeping (HK)
- Cleaning Manager (CM)
- Security Guards (SG A, SG B)
- Pantry Boys
- Supervisors
- Easy to add more

### 4. Automatic Salary Calculations
- Per-day salary = Monthly Salary ÷ Days in Month
- Calculates total amount per employee
- Applies per-day rate to actual working days
- Updates automatically when salary rates change

### 5. Overtime Tracking
- Enter OT hours per shift (1-8 hours)
- Auto-converts to OT days (÷ 8-hour workday)
- Adds OT amount to final salary
- Tracks OT-heavy employees easily

### 6. Automatic Attendance Summary
- **Present Days**: Count of all P entries
- **Absent Days**: Count of A entries
- **Weekly Offs**: Count of WO entries
- **Holidays**: Count of HD entries
- **Total Working Days**: Sum of Present + WO + HD
- **Total Amount**: Salary calculation

### 7. Template System
- Reusable template for each month
- Copy-paste ready (no formula recreation)
- Works for single or multiple locations
- Easy backup for compliance

### 8. Master Configuration
- Designations with monthly salaries
- Vendor names and details
- Office locations/company names
- Attendance categories (HouseKeeping, Security, etc.)

## 🚀 How to Use

### Quick Start (3 Steps)

**Step 1: Set Up (One-Time - 10 Minutes)**
1. Download the file from the link above
2. Go to "Sheet Tool" tab
3. Add your designations, salaries, vendors, and office locations

**Step 2: Create Monthly Sheet (2 Minutes)**
1. Copy "Template File" sheet
2. Rename: `[Location] [Category] [Month-Year]` (e.g., "Viman Nagar HouseKeeping Feb-26")
3. Change Company Name (Cell A2) and Month (Cell U2)

**Step 3: Daily Entry (5 Minutes Per Day)**
1. Add employee: Vendor Name (Col B), Designation (Col D)
2. Enter daily attendance: P, P1-P8, A, WO, or HD
3. Enter OT hours if any
4. System calculates everything automatically

**End of Month:**
- View attendance summary
- Check total amount per employee
- Generate billing for each vendor
- Share reports with management

## 📊 What You'll See

### Example Output:
```
Employee: Raj Kumar
Designation: HouseKeeping
Vendor: Manpower Solution Pvt Ltd
Location: Viman Nagar
Month: February 2026

Per Day Salary: ₹625
Working Days: 22 days
Regular Salary: ₹13,750
OT Hours: 10 hours
OT Days: 1.25 days
OT Amount: ₹781.25

TOTAL AMOUNT: ₹14,531.25

Attendance Breakdown:
- Present Days: 20
- Absent Days: 1
- Weekly Offs: 2
- Holidays: 1
- Total Days: 24
```

### Monthly Summary Shows:
- Employee-wise salary calculations
- Attendance statistics
- OT hours and days
- Vendor-wise billing
- Location-wise breakdown
- Total payroll amount

## 💡 Key Benefits

✅ **90% Time Saving**: Reduce 2 hours → 12 minutes of calculation  
✅ **100% Accurate**: No manual calculation errors  
✅ **Transparent Billing**: Vendors see exactly what they earned  
✅ **Multi-Vendor Ready**: Compare and manage multiple vendors  
✅ **Scalable**: Works for 5 or 50+ employees  
✅ **Audit Compliant**: Complete daily attendance records  
✅ **OT Tracking**: Monitor overtime automatically  
✅ **Easy Entry**: Even non-technical staff can use  

## 🔧 Customization

### Add New Designations:
- Go to "Sheet Tool" tab
- Add designation name and monthly salary
- Auto-applies to all new sheets

### Change Salary Rates:
- Update in "Sheet Tool"
- All calculations update automatically
- Historical data remains unchanged

### Add New Vendors:
- "Sheet Tool" → Add vendor name
- Use in new monthly sheets
- Separate billing per vendor

### Add New Locations:
- "Sheet Tool" → Add office location
- Create sheets for each location
- Compare across locations

## 📈 Real-World Scenarios

**Scenario 1: Multi-Vendor Comparison**
```
Location: Viman Nagar
Month: Feb-26
Category: HouseKeeping

Vendor: Manpower Solution Pvt Ltd
- 5 employees, Average Attendance: 92%
- Total Payroll: ₹72,656

Vendor: VRC Force Pvt Ltd  
- 3 employees, Average Attendance: 95%
- Total Payroll: ₹43,594

⚠️ Manpower Solution has lower attendance rate
```

**Scenario 2: Overtime Tracking**
```
Month: Feb-26

Employees with OT:
- Raj Kumar: 15 hours OT = 1.875 days
- Priya Singh: 8 hours OT = 1 day
- Amit Patel: 0 hours OT

Total OT Cost: ₹2,847
Regular Payroll: ₹72,656
Total with OT: ₹75,503
```

## 💼 Technical Skills Demonstrated

- Excel advanced formulas (VLOOKUP, COUNTIF, SUM)
- Data validation and dropdown menus
- Conditional formatting
- Multi-sheet data management
- Automated salary calculations
- Overtime conversion logic
- HR/Payroll process design
- Audit-trail documentation
- User-friendly interface

## 📞 Contact

For customization or questions:
- [**GitHub**](https://github.com/heysubu)
- **Email**: suubhamghadge@gmail.com
- [**LinkedIn**](https://www.linkedin.com/in/subhamghadge/)

## 📄 License

MIT License - Free to use and modify

---

### 🌟 Project Stats

![Excel](https://img.shields.io/badge/Excel-Advanced-217346?logo=microsoft-excel)
![HR Management](https://img.shields.io/badge/HR-Management-blue)
![Multi--Vendor](https://img.shields.io/badge/Multi--Vendor-Support-orange)
![Payroll](https://img.shields.io/badge/Payroll-Automation-green)
![Status](https://img.shields.io/badge/Status-Active-brightgreen)

---

**👥 Simplify Manpower Management - Accurate, Transparent, Automated**

**⭐ If this helps your facility, please star this repository!**

**💬 Questions? Open an issue and I'll help you get started!**

**Password: 123** (all sheets)
