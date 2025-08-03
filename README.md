As a part-time hotel manager, I developed this system to streamline employee scheduling and wage tracking in daily operations.

This system is a staff scheduling and payroll management tool designed for hotels or small to medium-sized businesses. It features a graphical user interface (GUI) built with tkinter and tkcalendar, allowing for interactive operation. Administrators can select dates via a calendar, assign work shifts (e.g., cleaner or receptionist), choose full-day or half-day shifts, and automatically calculate daily and weekly wages for each employee.

The system also supports exporting daily reports and payroll summaries as CSV files, making it convenient for management and record-keeping. With a visually appealing interface, date filtering, and name-based sorting, the system is ideal for daily scheduling, attendance tracking, and performance evaluation.
<img width="1312" height="813" alt="image" src="https://github.com/user-attachments/assets/e3ed693c-1fa5-4968-ac11-c2e97329c16e" />

<img width="373" height="650" alt="image" src="https://github.com/user-attachments/assets/a465cfb9-6f36-4540-afbb-b53c9b422a94" />
<img width="134" height="150" alt="image" src="https://github.com/user-attachments/assets/1f7966c0-b533-4bb8-8dea-ac1c3b295004" />


* 项目简介
* 技术栈
* 功能亮点
* 解决的实际问题
* 使用方法（可选）

---

## 🏨 Hotel Employee Work Schedule System

### 酒店员工工作排班与工资统计系统

### 📌 Project Introduction | 项目简介

> As a part-time hotel manager, I developed this system to streamline employee scheduling and wage tracking in daily operations.
> 作为一名兼职酒店经理，我开发了本系统用于简化日常的员工排班与工资管理流程，特别适用于酒店或中小型企业。

This is a staff scheduling and payroll management tool with a graphical user interface (GUI), built using Python’s `tkinter` and `tkcalendar` libraries. It allows administrators to interactively assign work, select shifts, calculate salaries, and export reports.

本系统基于 Python 的 `tkinter` 和 `tkcalendar` 库实现图形界面（GUI），管理员可以通过交互式界面完成员工排班、选择班次、工资计算，并可导出相关报表。

---

### 🛠 Tech Stack | 技术栈

| 分类         | 技术 / 工具                  | 描述             |
| ---------- | ------------------------ | -------------- |
| 👨‍💻 编程语言 | Python                   | 主体编程语言         |
| 📦 GUI框架   | `tkinter`, `tkcalendar`  | 实现交互式用户界面与日历控件 |
| 🗃 数据存储    | SQLite3                  | 用于存储员工、排班与工资数据 |
| 📊 报表导出    | `csv` 标准库                | 导出日报表、工资统计表    |
| 📁 项目管理    | Git + GitHub             | 版本控制与远程协作      |
| 💻 开发环境    | VS Code / macOS Terminal | 开发平台与终端环境      |

---

### ✅ Features | 功能亮点

* 📅 **Calendar-based Scheduling**
  基于日历选择，为指定日期添加排班记录

* 👤 **Employee Role Assignment**
  支持为员工分配“清洁工（cleaner）”或“接待员（receptionist）”角色

* 🕒 **Shift Options (Full-day or Half-day)**
  每日支持“全班（\$120/cleaner, \$150/receptionist）”或“半天（按比例计算）”

* 💰 **Auto Salary Calculation**
  自动计算每位员工每天、每周工资

* 📤 **CSV Report Export**
  一键导出日报表、工资总表，便于管理与归档

* 🎨 **Clean and Interactive GUI**
  图形界面直观，支持日期筛选与员工姓名排序

---

### 🎯 Solved Problems | 本系统解决了哪些实际需求？

| 问题/需求             | 解决方式                         |
| ----------------- | ---------------------------- |
| 排班混乱，手工统计工资繁琐     | 提供可视化排班界面，自动计算每天/每周工资        |
| 不同角色员工工资不同，按日结算复杂 | 系统根据角色和班次自动核算对应工资            |
| 无法统一管理工作记录、导出历史数据 | 可导出 `.csv` 文件，用于管理层查看历史记录和备份 |
| 需快速查找某员工某日排班或工资信息 | 提供员工列表与日期筛选功能，快速定位相关数据       |

---

### 🚀 Quick Start | 快速上手

```bash
# 克隆项目
git clone https://github.com/cc883015/Hotel_Employee_Work_Schedule_System.git
cd Hotel_Employee_Work_Schedule_System

# 启动主程序
python3 work_schedule_app.py
```

> 推荐使用 Python 3.9+，并确保本地支持 `tkinter` 和 `tkcalendar`。

---

### 📁 文件结构说明（可选）

```
├── work_schedule_app.py        # 主程序文件
├── work_schedule.db            # SQLite 数据库
├── images/                     # 界面用图标资源（可选）
├── exports/                    # 导出的 CSV 报表
├── README.md                   # 项目说明
```

---

