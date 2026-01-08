A beautiful, professional label designer application built with Flutter and Supabase. Create, design, and manage custom labels for your business with an intuitive drag-and-drop interface.

✨ Features
🎨 Beautiful UI/UX Design
Modern, consistent design language across all screens

Professional gradient headers and shadow effects

Responsive layout for both mobile and web

Google Fonts Poppins typography

🏢 Business Management
Company Profile Management - Upload logo, edit company details

Multiple Users - Secure authentication with Supabase Auth

Cloud Storage - Store company logos and designs

🎯 Label Designer
Drag & Drop Interface - Intuitive element placement

Multiple Element Types:

📝 Text elements with dynamic variables ({{date}}, {{weight}}, {{amount}})

📱 QR Code generator

📊 Barcode generator

🏢 Company logo integration

Real-time Editing - Resize, reposition, edit elements

Pixel-perfect Grid System - Precise alignment

Zoom & Pan - Interactive canvas navigation

📁 Design Management
Save & Load Designs - Cloud storage for your label designs

Design Templates - Reuse and modify existing designs

Preview Mode - See labels with real dynamic data

Print Ready - Generate printable label formats



Usage Guide
1. Registration & Login
Create a new account with company details

Login with email/password

Secure authentication with Supabase Auth

2. Setup Company Profile
Upload company logo

Add company details (name, email, phone, address)

All data stored securely in Supabase

3. Create New Design
Click "New Design" from home screen

Set label dimensions (width & height)

Choose from common size templates

4. Design Your Label
Add Text Elements: Click text button, edit content and font size

Add QR Codes: Generate QR codes with dynamic data

Add Barcodes: Create barcodes for product tracking

Add Logo: Insert your company logo

Drag & Drop: Move elements freely on canvas

Resize Elements: Use resize handles or dialog

Layer Management: Elements can overlap

5. Dynamic Variables
Use these placeholders in text elements:

{{date}} - Current date

{{weight}} - Weight value

{{amount}} - Price amount

{{order}} - Order number

{{customer}} - Customer name

6. Save & Manage Designs
Save designs to cloud

View all your designs in "My Designs"

Reopen and edit existing designs

Preview with real data

7. Print & Export
Preview label with dynamic data filled

Print-ready format

Share functionality

🚀 Deployment
Android
bash
flutter build apk --release
flutter build appbundle --release
iOS
bash
flutter build ios --release
Web
bash
flutter build web --release
