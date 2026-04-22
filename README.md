# SAP ABAP Support & Web Development Portfolio

A modern, dynamic portfolio website showcasing enterprise SAP ABAP development services, web solutions, and real-time support ticket tracking.

## 🎯 Features

- **Real SAP Logo** - Official SAP branding with animated effects
- **Dynamic Service Panels** - Animated code windows showing real dev examples
  - UI/UX Design (CSS)
  - Web Development (React)
  - App Development (React Native)
  - E-Commerce (Node.js)
  - SAP ABAP Support

- **Live Ticket Tracker** - Real-world SAP support tickets managed in real-time
  - Auto-generated ticket IDs (SAP-001, SAP-002, etc.)
  - Status tracking (Open, In Progress, Resolved)
  - Live statistics dashboard
  - Filterable by status

- **Dynamic Admin Panel** - Update portfolio content without touching code
  - Manage projects (add/edit/delete)
  - Manage SAP support tickets
  - Update "About Us" statistics in real-time
  - Password protected (default: `admin2025`)

- **Real Team Testimonials**
  - Panchanana Dash - CEO & Founder
  - Vivek Tungaria - Founder & Director, SAP ABAP Expert

- **Real-Time Data Persistence** - All changes saved to browser localStorage

## 🚀 Getting Started

1. Open `index.html` in your browser
2. Click the **⚡ Admin** button (top right)
3. Enter password: `*********`
4. Manage projects, tickets, and team stats

## 📊 Admin Panel Features

### Projects Management
- Add/Edit/Delete projects
- Organize by category (Web Design, App, E-Commerce, Branding, SAP)
- Add tech stack, links, images, and descriptions

### SAP Ticket Tracker
- Create real-world support tickets
- Track status (Open → In Progress → Resolved)
- Add tags (ALV Report, Smartforms, Module Pool, etc.)
- Auto-generated ticket IDs
- Live statistics (Total, Resolved, In Progress, Open)

### About Us Statistics
- Customize team metrics
- Edit labels, values, and suffixes
- Add/remove custom statistics
- Real-time updates on website

## 🔐 Security

- Admin panel password protected
- Change password in code: `const ADMIN_PASSWORD = 'admin2025';`
- All data stored in browser localStorage (client-side only)

## 💾 Data Storage

- **Projects**: `dc_projects` (localStorage)
- **Tickets**: `dc_tickets` (localStorage)
- **About Stats**: `dc_about_stats` (localStorage)

## 🛠 Tech Stack

- HTML5 / CSS3 (Vanilla)
- JavaScript (ES6+)
- Custom animations (CSS + JS)
- Responsive design (mobile-friendly)

## 📝 Notes

- No fake data - everything is real and client-driven
- Update credentials and company info before going live
- Change email, social links, and contact info in footer
- Customize color scheme via CSS variables (`:root`)

## 🎨 Customization

### Change Admin Password
Edit line in script section:
```javascript
const ADMIN_PASSWORD = 'admin2025';
```

### Update Colors
Modify CSS variables at top of `<style>`:
```css
:root {
  --sap-blue: #0078d7;
  --gold: #f0a500;
  /* etc */
}
```

### Update Company Info
- Footer logo: `DevCraft` (change as needed)
- Contact email: `hello@devcraft.studio`
- Social links in footer

---

**Made with ❤️ for enterprise solutions**

© 2025 DevCraft Studio. All rights reserved.
