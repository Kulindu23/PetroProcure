# PetroProcure Workflow Management Module

Complete Bootstrap HTML interface for Workflow Collection Management in PetroProcure E-Procurement System.

## 📁 Files Created

1. **workflow-collection-active.html** - Active Blueprints view with workflow cards

## 🎨 Design Features

### Active Workflows View
- **3-State Tab Switching**: Active Blueprints / Pending Verifications / Archived
- **Category Filtering**: All / Tender Details / Tender Document / Tender Evaluation
- **Workflow Cards Grid**: Responsive 3-column layout
- **Card Hover Effects**: Lift animation with shadow
- **Status Badges**: Active (green), Pending (amber), Inactive (gray)
- **Define New Card**: Dashed border card with plus icon
- **Create Button**: Gradient indigo button (top-right)

### Workflow Cards Include:
- Category badge and process type
- Workflow name and description
- Logic nodes count
- Last version date
- Hover effects with border highlight

## 🚀 How to Run in VS Code

### Method 1: Live Server Extension (Recommended)

1. **Install Live Server Extension**
   - Open VS Code
   - Go to Extensions (Ctrl+Shift+X or Cmd+Shift+X)
   - Search for "Live Server" by Ritwick Dey
   - Click "Install"

2. **Open Your Project**
   - File → Open Folder
   - Select the folder containing the HTML files

3. **Launch Live Server**
   - Right-click on `workflow-collection-active.html`
   - Select "Open with Live Server"
   - Your browser will open at `http://127.0.0.1:5500/workflow-collection-active.html`

4. **Auto-Reload**
   - Any changes you make will automatically refresh in the browser

### Method 2: Direct Browser Opening

1. **Locate the File**
   - Navigate to your project folder in File Explorer/Finder

2. **Open in Browser**
   - Double-click `workflow-collection-active.html`
   - Or right-click → Open with → Choose your browser

## 📂 Project Structure

```
your-project-folder/
├── workflow-collection-active.html    # Active workflows view
├── product-category-list.html         # (Previously created)
├── product-category-details.html      # (Previously created)
├── product-category-create.html       # (Previously created)
├── product-category-edit.html         # (Previously created)
├── price-base-list.html              # (Previously created)
├── price-base-details.html           # (Previously created)
├── price-base-create.html            # (Previously created)
└── price-base-edit.html              # (Previously created)
```

## ✅ Features Implemented

### Navigation
- ✅ Fixed sidebar with expandable Workflow submenu
- ✅ Administrator card at bottom (LOGGED IN AS)
- ✅ Smooth expand/collapse animations
- ✅ Active state highlighting

### Content
- ✅ Status tab switcher (Active/Pending/Archived)
- ✅ Category filter buttons
- ✅ Workflow cards grid (responsive)
- ✅ Card hover animations
- ✅ Status badges (Active/Pending/Inactive)
- ✅ Define New workflow card
- ✅ Create Workflow button

### Design System
- **Colors**: Indigo primary, Emerald success, Amber warning
- **Typography**: Inter font family (300-900 weights)
- **Borders**: 1.5rem for cards, 0.75rem for buttons
- **Animations**: 300ms smooth transitions
- **Grid**: Auto-fill with minmax(380px, 1fr)

## 🎯 Key Components

### Workflow Card Structure:
```html
<div class="workflow-card">
    <span class="card-badge badge-active">ACTIVE</span>
    <div class="card-icon-container">
        <i class="bi bi-shield-check"></i>
    </div>
    <div class="card-category">DETAILS PROCESS</div>
    <h3 class="workflow-name">Workflow Name</h3>
    <p class="workflow-description">Description...</p>
    <div class="workflow-footer">
        <!-- Logic nodes & last version -->
    </div>
</div>
```

### Status Tab Switcher:
```html
<div class="status-tabs">
    <button class="status-tab active">Active Blueprints</button>
    <button class="status-tab">Pending Verifications</button>
    <button class="status-tab">Archived</button>
</div>
```

### Category Filter:
```html
<div class="category-filter">
    <button class="category-btn active">
        <i class="bi bi-grid-3x3"></i>
        All Categories
    </button>
    <!-- More category buttons -->
</div>
```

## 📋 Next Steps

The following pages will be created in the next session:
- Pending Verifications view
- Archived workflows view
- Workflow details pages (Active/Pending/Archived)
- Empty state screens

## 🔗 Navigation Links

- All workflow cards link to details page
- Sidebar menu items properly linked
- Create button ready for form page

## 💡 Tips for Development

1. **Keep all files in same folder** for proper navigation
2. **Use Live Server** for automatic refresh during development
3. **Check browser console** for any JavaScript errors
4. **Test responsive design** by resizing browser window
5. **Verify all icon classes** are correct (Bootstrap Icons 1.11.1)

## 🎨 Color Palette

```css
--primary-indigo: #4F46E5
--success-emerald: #10B981
--warning-amber: #F59E0B
--danger-rose: #F43F5E
--surface-bg: #F8FAFC
```

## 📱 Responsive Breakpoints

- Desktop: 992px and above (3 columns)
- Tablet: 768px - 991px (2 columns)
- Mobile: Below 768px (1 column)

---

**Ready to use!** Open `workflow-collection-active.html` in VS Code with Live Server and start exploring! 🚀
