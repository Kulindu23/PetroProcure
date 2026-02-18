# Product Category Management Module

Complete Bootstrap HTML interfaces for Product Category Management in PetroProcure.

## 📁 Files Included

1. **product-category-list.html** - Collection view with filtering and search
2. **product-category-details.html** - Detailed view with linked products inventory  
3. **product-category-create.html** - Create new category form
4. **product-category-edit.html** - Edit existing category form

## 🎨 Design Features

- **Responsive Grid**: 3-column layout (1 column on mobile)
- **Sticky Filter Bar**: Glassmorphism effect with backdrop blur
- **Status Filtering**: All / Active / Inactive tabs
- **Real-time Search**: Search by name or description
- **Hover Effects**: Cards lift and show edit icon on hover
- **Smooth Animations**: 500ms transitions with fade-in effects

## 🔗 Navigation Flow

```
product-category-list.html
    ├─→ product-category-create.html → [Submit] → product-category-list.html
    └─→ product-category-details.html
            └─→ product-category-edit.html → [Submit] → product-category-details.html
```

## 🚀 Quick Start

1. Extract all files to your project folder
2. Open `product-category-list.html` in VS Code
3. Right-click → "Open with Live Server"
4. The sidebar will be open by default with hamburger menu available

## ⚙️ Key Features

### List View
- Filter by status (All/Active/Inactive)
- Search categories in real-time
- Click cards to view details
- Hover to see edit icon

### Details View  
- Category information sidebar
- Active/Inactive product counters
- Comprehensive product inventory tables
- Price base tags with info buttons
- View specification buttons

### Create/Edit Forms
- Required field validation
- Active/Inactive toggle
- Product counter display (edit mode)
- Deactivation warning when active products exist

## 🎯 Technical Specs

- **Bootstrap**: 5.3.2
- **Icons**: Bootstrap Icons 1.11.1
- **Fonts**: Inter (300-900 weights)
- **Colors**: Indigo primary, Emerald success, Amber warning
- **Animations**: All transitions 500ms duration

## 📱 Responsive Design

- **Desktop**: Full layout with 3-column grid
- **Tablet**: 2-column grid
- **Mobile**: Single column, collapsible sidebar

Enjoy building with PetroProcure! 🚀
