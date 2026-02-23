# MUT Platform - Interactive Mockups

Professional mockups for the MUT Financial Management Platform, designed specifically for creative agencies managing projects, budgets, and cash flow.

## Design System

- **Style**: Dark wireframe design with structural clarity
- **Colors**: Dark backgrounds with high contrast borders and minimal shadows
- **Charts**: D3.js for interactive data visualization
- **Responsive**: Optimized for desktop viewing
- **Made by**: [Tyn Studio](https://tynstudio.com) - *a calm studio for bold ideas*

## Viewing the Mockups

### Option 1: Local File Browser
Simply open `index.html` in your web browser to see all mockups linked from a central hub.

### Option 2: Direct Access
Open any individual mockup file directly:
- `dashboard.html`
- `projects.html`
- `project-detail.html`
- `project-create.html`
- `cash-flow.html`
- `recurring-expenses.html`

### Option 3: Local Server (Recommended)
For best experience with all features:

```bash
# Navigate to the mockup folder
cd mockup

# Start a simple HTTP server (Python 3)
python3 -m http.server 8000

# Or with Node.js
npx http-server -p 8000
```

Then open: `http://localhost:8000`

## Mockup Overview

### 1. Dashboard (dashboard.html)
**Purpose**: Financial command center for executives

**Key Features**:
- Revenue, expenses, and profit metrics for current month
- Pipeline value of pending proposals
- 6-month revenue & expenses trend chart
- Project distribution by service type
- Active projects table with progress
- Pending proposals overview
- Area budget status tracking

**Target User**: CEO, Administration

---

### 2. Cash Flow Forecast (cash-flow.html)
**Purpose**: 6-month financial projection (THE KILLER FEATURE)

**Key Features**:
- Projected income with confirmed vs. pending breakdown
- Net cash flow calculations (best case, realistic, conservative)
- Interactive scenario selector (50%, 60%, 80% probability)
- 6-month visualization with income, expenses, and net flow
- Upcoming income by project with confirmation status
- Upcoming expenses by category
- Monthly breakdown table with cumulative cash position

**Target User**: CEO, CFO, Administration

**Why It's Special**: Shows "what if we land these 3 projects?" in real-time

---

### 3. Projects List (projects.html)
**Purpose**: Overview of all projects across all statuses

**Key Features**:
- Summary cards: active projects, pending approval, completed, avg profit margin
- Filter by status, service type, and client
- Complete project table with:
  - Status badges (In Progress, Proposal, Completed, Cancelled)
  - Budget vs. actual cost
  - Profit calculations
  - Progress bars
- Clickable rows to project detail

**Target User**: All team members

---

### 4. Project Detail (project-detail.html)
**Purpose**: Deep dive into a specific project

**Key Features**:
- Project information card (client, dates, service type, progress)
- Financial summary (value, costs, profit, margin, income received)
- Income schedule with payment milestones
- Visual payment timeline
- Budget vs. actual spending chart
- Activity log (payments, updates, expenses)
- Tabbed interface (Income Schedule, Budget, Expenses, Timeline)

**Target User**: Project Managers, Producers, Finance Team

---

### 5. Create Project Budget (project-create.html)
**Purpose**: New project budget workflow

**Key Features**:
- 4-step progress indicator
- Project details form (client, service type, dates)
- Budget builder with expandable categories
- Line-item budget with quantity, unit cost, totals
- Category subtotals (Pre-Production, Production, Post-Production, Overhead)
- Profit margin calculator
- Auto-calculate client quote from cost + margin
- Template support ("Use Template" button)

**Target User**: Producers, Creative Directors, Sales Team

---

### 6. Recurring Expenses (recurring-expenses.html)
**Purpose**: Manage ongoing operational costs

**Key Features**:
- Monthly expense total with annual projection
- Expense distribution donut chart
- Expenses by area (department allocation)
- Complete recurring expenses table:
  - Salaries, operations, software, equipment
  - Frequency (monthly, quarterly, annually)
  - Next payment date
  - Status (active/inactive)
- Add new expense modal
- Category and area filters

**Target User**: Administration, Area Managers

---

## Design Features

### Navigation
- Consistent sidebar navigation across all pages
- Logo with company name
- Organized sections (Main, Financial, Management)
- Active state highlighting

### Visual Elements
- **Stat Cards**: Large numbers with trends and progress bars
- **Badges**: Color-coded status indicators
- **Progress Bars**: Visual representation of completion/spending
- **Charts**: D3.js-powered interactive visualizations
- **Tables**: Sortable, hoverable rows with inline actions
- **Cards**: Modular content containers with headers

### Color Coding
- **Accent (Purple/Blue)**: Primary actions, in-progress items
- **Success (Green)**: Completed, on-track, positive metrics
- **Warning (Orange)**: Needs attention, pending items
- **Danger (Red)**: Over budget, cancelled, expenses
- **Neutral (Gray)**: Inactive, general information

## File Structure

```
mockup/
├── index.html                 # Landing page with all mockup links
├── dashboard.html            # Main dashboard
├── cash-flow.html            # Cash flow forecast
├── projects.html             # Projects list
├── project-detail.html       # Single project detail
├── project-create.html       # Create new project budget
├── recurring-expenses.html   # Recurring expenses management
├── styles.css                # Shared stylesheet
└── README.md                 # This file
```

## Dependencies

- **D3.js v7**: Loaded from CDN for charts
- **Mut.avif**: Company logo (referenced from parent directory)

## Browser Compatibility

Tested and optimized for:
- Chrome 90+
- Firefox 88+
- Safari 14+
- Edge 90+

## Presentation Tips

### For Client Pitch:

1. **Start with Dashboard** - Show the overview, emphasize "everything at a glance"
2. **Show Cash Flow Forecast** - The killer feature showing predictive analysis
3. **Walk through Project Creation** - Demonstrate the budget builder workflow
4. **Deep Dive into Project Detail** - Show payment milestones and tracking
5. **Show Recurring Expenses** - Demonstrate operational cost management
6. **Return to Dashboard** - Close the loop on how it all connects

### Key Talking Points:

- **"What if we land these projects?"** - Cash flow forecast answers this instantly
- **"From proposal to profit"** - Complete project lifecycle tracking
- **"Every area owns their budget"** - Collaborative financial management
- **"Real-time, not end-of-month"** - Live financial visibility
- **"Built for creative agencies"** - Not generic accounting software

## Future Enhancements (Not in Mockups)

These features can be shown as "coming soon" or "phase 2":
- Client CRM module
- Team management
- Time tracking
- Invoice generation
- Financial reports export
- Mobile app
- Integrations (QuickBooks, Stripe, etc.)
- Role-based permissions detail
- Email notifications

## Technical Notes

- Pure HTML/CSS with minimal JavaScript
- Only JS used for D3.js charts and interactive features
- No framework dependencies for fast loading
- Fully self-contained files
- Wireframe-style design for clear structure presentation
- Easy to modify and customize

## Questions?

These mockups demonstrate the core MVP functionality for the 6-10 month development timeline. They can be adjusted based on client feedback during the pitch.

---

**Built for MUT - 2026**
**Made by [Tyn Studio](https://tynstudio.com)** - *a calm studio for bold ideas*
