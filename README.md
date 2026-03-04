# Personal_Money_Tracker
💰 Personal Money Tracker UI

A clean, modern, and gamified daily expense tracking dashboard designed to help users control spending, monitor daily limits, and earn bonus rewards for disciplined money management.

📌 Project Overview

Personal Money Tracker UI is a web/mobile responsive finance dashboard that:

Tracks daily expenses

Enforces a fixed daily limit (₹100)

Maintains a carry-forward bonus balance

Provides real-time spending alerts

Visualizes progress with color-coded indicators

Automatically resets daily spending

This project focuses on simplicity, motivation, and financial discipline through an intuitive and minimal interface.

🧠 Core Concept

The dashboard is designed to feel like:

A productivity habit tracker

A gamified money management system

A reward-based spending control app

The UI prioritizes:

Minimal clutter

Clean typography

Soft financial theme

Smooth card-based layout

Micro-animations for better engagement

🎨 Design System
Theme

Soft modern UI

Light mode with subtle green accents

Financial productivity style

Clean white background with soft gradients

UI Elements

Rounded corners (12–16px radius)

Soft shadows

Financial theme icons

Smooth animated progress bars

Toast-style animated notifications

📱 Main Screen Layout
1️⃣ Header Section

App Name: Personal Money Tracker

Subtitle: Smart daily spending control

Auto-updating date display

2️⃣ Daily Summary Card (Highlight Card)

Displays:

💰 Daily Limit: ₹100

💸 Spent Today

🟢 Remaining Limit

⭐ Bonus Balance

Includes:

Dynamic progress bar

Color-coded percentage indicator

🎯 Progress Color System
Usage %	Color
0–50%	Green
50–75%	Yellow
75–90%	Orange
90–100%	Red
Above 100%	Dark Red + warning animation
3️⃣ Add Expense Section

Amount input field (₹)

Optional note field

“Add Expense” button

Quick-add buttons:

₹10

₹20

₹50

₹100

4️⃣ Notifications Panel

Displays real-time alerts:

✅ 50% limit reached

⚠️ 75% warning

🔴 90% alert

🚨 100% reached

❌ Limit crossed

⭐ Bonus increased

🔻 Bonus decreased

⚠️ Bonus negative warning

Notifications use animated toast-style popups.

5️⃣ Daily Log Section

Scrollable list showing:

Time of expense

Amount

Optional note

Running total

Features:

Date separators

Visual divider between days

Auto-reset indicator for new day

🔄 System Logic
📌 Daily Rules

Daily spending limit = ₹100

Spending resets automatically at midnight

Bonus balance carries forward

💡 Bonus System

If total spent < ₹100
→ Remaining amount added to bonus at day end

If total spent > ₹100
→ Extra amount deducted immediately from bonus

Bonus can go negative
→ Red warning indicator displayed

🔔 Notifications Logic

Trigger alerts at:

50% usage

75% usage

90% usage

100% usage

When crossing the limit

When bonus increases

When bonus decreases

When bonus becomes negative

🟢 Initial State

On first load:

Daily spending = ₹0
Bonus balance = ₹0
Today’s limit = ₹100

Display message:

“Money tracker activated. Your daily limit is ₹100. Please enter your first expense.”

🚀 Key Features

Real-time spending updates

Visual spending progress

Automatic daily reset

Reward-based bonus system

Persistent daily log

Responsive web/mobile design

Clean and minimal user interface
