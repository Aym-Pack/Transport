# Wireframe Specifications - DafnckMachine v3.1

## Document Metadata
- **Document Type**: Wireframe Specifications
- **Version**: 3.1.0
- **Last Updated**: 2025-01-27
- **Status**: Template Ready
- **Related Documents**: 
  - [UX_Design_System.md](mdc:01_Machine/04_Documentation/Doc/Phase_3_Product_Definition_Design/UX_Design_System.md)
  - [User_Journey_Maps.json](mdc:01_Machine/04_Documentation/Doc/Phase_3_Product_Definition_Design/User_Journey_Maps.json)
  - [Responsive_Design_Guidelines.md](mdc:01_Machine/04_Documentation/Doc/Phase_3_Product_Definition_Design/Responsive_Design_Guidelines.md)

## Overview
This document provides comprehensive wireframe specifications for DafnckMachine v3.1, defining layout structures, content placement, functional element positioning, and interaction patterns across all key interfaces and user flows.

## Wireframe Methodology

### Design Approach
- **Mobile-First**: Start with mobile constraints, scale up to desktop
- **Content-First**: Prioritize content hierarchy and user goals
- **Progressive Enhancement**: Layer complexity based on device capabilities
- **Accessibility-Driven**: Ensure inclusive design from wireframe stage

### Fidelity Levels
- **Low-Fidelity**: Basic layout structure and content blocks
- **Medium-Fidelity**: Detailed component placement and sizing
- **High-Fidelity**: Precise specifications with interaction states

## Global Layout Framework

### Grid System
```
Desktop Grid (1440px):
├── Container: 1200px max-width, 120px margins
├── Columns: 12-column grid, 80px width, 20px gutters
├── Breakpoints: 1440px, 1024px, 768px, 320px
└── Vertical Rhythm: 8px base unit, 24px line height

Tablet Grid (768px):
├── Container: 728px, 20px margins
├── Columns: 8-column grid, 70px width, 20px gutters
└── Vertical Rhythm: 8px base unit, 24px line height

Mobile Grid (320px):
├── Container: 280px, 20px margins
├── Columns: 4-column grid, 55px width, 20px gutters
└── Vertical Rhythm: 8px base unit, 20px line height
```

### Layout Zones
- **Header Zone**: Global navigation and branding (64px height)
- **Content Zone**: Primary content area (flexible height)
- **Sidebar Zone**: Secondary navigation and tools (280px width)
- **Footer Zone**: Secondary links and information (120px height)

## Core Interface Wireframes

### 1. Landing Page Wireframe

#### Desktop Layout (1440px)
```
┌─────────────────────────────────────────────────────────────┐
│ Header [64px]                                               │
│ ┌─ Logo ─┐ ┌─ Navigation ──────┐ ┌─ CTA Button ─┐          │
│ │        │ │ Features Products │ │ Get Started  │          │
│ └────────┘ └───────────────────┘ └──────────────┘          │
├─────────────────────────────────────────────────────────────┤
│ Hero Section [600px]                                        │
│ ┌─────────────────────────────────────────────────────────┐ │
│ │ ┌─ Headline ──────────────────────────────────────────┐ │ │
│ │ │ AI-Powered Development Automation Platform          │ │ │
│ │ └─────────────────────────────────────────────────────┘ │ │
│ │ ┌─ Subheadline ───────────────────────────────────────┐ │ │
│ │ │ Transform your development workflow with            │ │ │
│ │ │ intelligent AI agents and automated processes      │ │ │
│ │ └─────────────────────────────────────────────────────┘ │ │
│ │ ┌─ Primary CTA ─┐ ┌─ Secondary CTA ─┐                  │ │
│ │ │ Start Free    │ │ Watch Demo      │                  │ │
│ │ │ Trial         │ │                 │                  │ │
│ │ └───────────────┘ └─────────────────┘                  │ │
│ └─────────────────────────────────────────────────────────┘ │
├─────────────────────────────────────────────────────────────┤
│ Features Section [800px]                                    │
│ ┌─ Section Title ─────────────────────────────────────────┐ │
│ │ Key Features & Capabilities                             │ │
│ └─────────────────────────────────────────────────────────┘ │
│ ┌─ Feature Grid ──────────────────────────────────────────┐ │
│ │ ┌─ Feature 1 ─┐ ┌─ Feature 2 ─┐ ┌─ Feature 3 ─┐        │ │
│ │ │ AI Agents   │ │ Automation  │ │ Integration │        │ │
│ │ │ [Icon]      │ │ [Icon]      │ │ [Icon]      │        │ │
│ │ │ Description │ │ Description │ │ Description │        │ │
│ │ └─────────────┘ └─────────────┘ └─────────────┘        │ │
│ └─────────────────────────────────────────────────────────┘ │
├─────────────────────────────────────────────────────────────┤
│ Social Proof Section [400px]                                │
│ ┌─ Testimonials ──────────────────────────────────────────┐ │
│ │ Customer quotes and success stories                     │ │
│ └─────────────────────────────────────────────────────────┘ │
├─────────────────────────────────────────────────────────────┤
│ Footer [120px]                                              │
│ ┌─ Links ─────┐ ┌─ Contact ───┐ ┌─ Social ────┐            │
│ │ About       │ │ Email       │ │ Twitter     │            │
│ │ Privacy     │ │ Phone       │ │ LinkedIn    │            │
│ └─────────────┘ └─────────────┘ └─────────────┘            │
└─────────────────────────────────────────────────────────────┘
```

#### Mobile Layout (320px)
```
┌─────────────────────────────┐
│ Header [56px]               │
│ ┌─ Logo ─┐ ┌─ Menu ─┐       │
│ │        │ │ ☰     │       │
│ └────────┘ └───────┘       │
├─────────────────────────────┤
│ Hero Section [400px]        │
│ ┌─ Headline ──────────────┐ │
│ │ AI-Powered Development  │ │
│ │ Automation Platform     │ │
│ └─────────────────────────┘ │
│ ┌─ Subheadline ───────────┐ │
│ │ Transform development   │ │
│ │ with intelligent AI     │ │
│ └─────────────────────────┘ │
│ ┌─ Primary CTA ───────────┐ │
│ │ Start Free Trial        │ │
│ └─────────────────────────┘ │
│ ┌─ Secondary CTA ─────────┐ │
│ │ Watch Demo              │ │
│ └─────────────────────────┘ │
├─────────────────────────────┤
│ Features Section [600px]    │
│ ┌─ Section Title ─────────┐ │
│ │ Key Features            │ │
│ └─────────────────────────┘ │
│ ┌─ Feature Stack ─────────┐ │
│ │ ┌─ Feature 1 ─────────┐ │ │
│ │ │ AI Agents [Icon]    │ │ │
│ │ │ Description         │ │ │
│ │ └─────────────────────┘ │ │
│ │ ┌─ Feature 2 ─────────┐ │ │
│ │ │ Automation [Icon]   │ │ │
│ │ │ Description         │ │ │
│ │ └─────────────────────┘ │ │
│ └─────────────────────────┘ │
└─────────────────────────────┘
```

### 2. Dashboard Wireframe

#### Desktop Layout (1440px)
```
┌─────────────────────────────────────────────────────────────┐
│ Header [64px]                                               │
│ ┌─ Logo ─┐ ┌─ Search ────┐ ┌─ Notifications ─┐ ┌─ Profile ─┐│
│ │        │ │             │ │ 🔔 (3)          │ │ Avatar    ││
│ └────────┘ └─────────────┘ └─────────────────┘ └───────────┘│
├─────────────────────────────────────────────────────────────┤
│ Main Content Area                                           │
│ ┌─ Sidebar [280px] ─┐ ┌─ Content Area ─────────────────────┐│
│ │ ┌─ Navigation ──┐ │ │ ┌─ Page Header ──────────────────┐ ││
│ │ │ Dashboard     │ │ │ │ Dashboard Overview             │ ││
│ │ │ Projects      │ │ │ │ ┌─ Breadcrumb ─┐ ┌─ Actions ─┐ │ ││
│ │ │ Agents        │ │ │ │ │ Home > Dash  │ │ + New     │ │ ││
│ │ │ Analytics     │ │ │ │ └──────────────┘ └───────────┘ │ ││
│ │ │ Settings      │ │ │ └────────────────────────────────┘ ││
│ │ └───────────────┘ │ │ ┌─ Metrics Cards ────────────────┐ ││
│ │ ┌─ Quick Actions ┐ │ │ │ ┌─ Card 1 ─┐ ┌─ Card 2 ─┐    │ ││
│ │ │ New Project   │ │ │ │ │ Active    │ │ Completed │    │ ││
│ │ │ Add Agent     │ │ │ │ │ Projects  │ │ Tasks     │    │ ││
│ │ │ View Reports  │ │ │ │ │ 12        │ │ 156       │    │ ││
│ │ └───────────────┘ │ │ │ └───────────┘ └───────────┘    │ ││
│ │ ┌─ Recent Items ─┐ │ │ └────────────────────────────────┘ ││
│ │ │ Project Alpha │ │ │ ┌─ Activity Feed ────────────────┐ ││
│ │ │ Agent Beta    │ │ │ │ ┌─ Activity Item ─────────────┐ │ ││
│ │ │ Report Gamma  │ │ │ │ │ Agent completed task X      │ │ ││
│ │ └───────────────┘ │ │ │ │ 2 minutes ago               │ │ ││
│ └───────────────────┘ │ │ └─────────────────────────────┘ │ ││
│                       │ │ ┌─ Project Status ────────────┐ │ ││
│                       │ │ │ ┌─ Project 1 ─────────────┐ │ ││
│                       │ │ │ │ Name: E-commerce App    │ │ ││
│                       │ │ │ │ Progress: [████████░░] │ │ ││
│                       │ │ │ │ Status: In Progress     │ │ ││
│                       │ │ │ └─────────────────────────┘ │ ││
│                       │ │ └─────────────────────────────┘ ││
│                       │ └─────────────────────────────────┘│
└─────────────────────────────────────────────────────────────┘
```

### 3. Project Management Interface

#### Desktop Layout (1440px)
```
┌─────────────────────────────────────────────────────────────┐
│ Header [64px] - Same as Dashboard                           │
├─────────────────────────────────────────────────────────────┤
│ Project Header [120px]                                      │
│ ┌─ Project Info ──────────────────────────────────────────┐ │
│ │ ┌─ Title ─────────────────┐ ┌─ Status ─┐ ┌─ Actions ──┐ │ │
│ │ │ E-commerce Platform     │ │ Active   │ │ Settings   │ │ │
│ │ │ Last updated: 2h ago    │ │          │ │ Export     │ │ │
│ │ └─────────────────────────┘ └──────────┘ └────────────┘ │ │
│ │ ┌─ Progress Bar ──────────────────────────────────────┐  │ │
│ │ │ Overall Progress: [████████████░░░░] 75%            │  │ │
│ │ └─────────────────────────────────────────────────────┘  │ │
│ └─────────────────────────────────────────────────────────┘ │
├─────────────────────────────────────────────────────────────┤
│ Main Content [Variable Height]                              │
│ ┌─ Tab Navigation ────────────────────────────────────────┐ │
│ │ [Tasks] [Agents] [Timeline] [Files] [Settings]         │ │
│ └─────────────────────────────────────────────────────────┘ │
│ ┌─ Tasks View ────────────────────────────────────────────┐ │
│ │ ┌─ Filters & Search ──────────────────────────────────┐ │ │
│ │ │ ┌─ Search ─────┐ ┌─ Filter ─┐ ┌─ Sort ──┐ ┌─ View ┐ │ │ │
│ │ │ │ Search tasks │ │ Status   │ │ Priority │ │ List  │ │ │ │
│ │ │ └──────────────┘ └──────────┘ └─────────┘ └───────┘ │ │ │
│ │ └─────────────────────────────────────────────────────┘ │ │
│ │ ┌─ Task List ─────────────────────────────────────────┐ │ │
│ │ │ ┌─ Task Item ─────────────────────────────────────┐ │ │ │
│ │ │ │ ☐ Implement user authentication                 │ │ │ │
│ │ │ │ Assigned: @auth-agent | Priority: High         │ │ │ │
│ │ │ │ Due: Tomorrow | Progress: [████░░] 60%         │ │ │ │
│ │ │ │ ┌─ Actions ─┐                                  │ │ │ │
│ │ │ │ │ Edit View │                                  │ │ │ │
│ │ │ │ └───────────┘                                  │ │ │ │
│ │ │ └─────────────────────────────────────────────────┘ │ │ │
│ │ │ ┌─ Task Item ─────────────────────────────────────┐ │ │ │
│ │ │ │ ✓ Setup database schema                         │ │ │ │
│ │ │ │ Assigned: @db-agent | Priority: Medium         │ │ │ │
│ │ │ │ Completed: Yesterday                            │ │ │ │
│ │ │ └─────────────────────────────────────────────────┘ │ │ │
│ │ └─────────────────────────────────────────────────────┘ │ │
│ └─────────────────────────────────────────────────────────┘ │
└─────────────────────────────────────────────────────────────┘
```

### 4. Agent Management Interface

#### Desktop Layout (1440px)
```
┌─────────────────────────────────────────────────────────────┐
│ Header [64px] - Same as Dashboard                           │
├─────────────────────────────────────────────────────────────┤
│ Agent Management Header [80px]                              │
│ ┌─ Page Title ────────────────────────────────────────────┐ │
│ │ AI Agent Management                                     │ │
│ │ ┌─ Add Agent ─┐ ┌─ Import ─┐ ┌─ Settings ─┐            │ │
│ │ │ + New Agent │ │ Import   │ │ Configure  │            │ │
│ │ └─────────────┘ └──────────┘ └────────────┘            │ │
│ └─────────────────────────────────────────────────────────┘ │
├─────────────────────────────────────────────────────────────┤
│ Agent Grid [Variable Height]                                │
│ ┌─ Agent Card ────────────────┐ ┌─ Agent Card ────────────┐ │
│ │ ┌─ Agent Avatar ──────────┐ │ │ ┌─ Agent Avatar ──────┐ │ │
│ │ │ 🤖                      │ │ │ │ 🤖                  │ │ │
│ │ └─────────────────────────┘ │ │ └─────────────────────┘ │ │
│ │ ┌─ Agent Info ────────────┐ │ │ ┌─ Agent Info ────────┐ │ │
│ │ │ Development Agent       │ │ │ │ Testing Agent       │ │ │
│ │ │ Status: Active          │ │ │ │ Status: Idle        │ │ │
│ │ │ Tasks: 3 active         │ │ │ │ Tasks: 0 active     │ │ │
│ │ │ Efficiency: 94%         │ │ │ │ Efficiency: 87%     │ │ │
│ │ └─────────────────────────┘ │ │ └─────────────────────┘ │ │
│ │ ┌─ Actions ───────────────┐ │ │ ┌─ Actions ───────────┐ │ │
│ │ │ Configure | Monitor     │ │ │ │ Configure | Monitor │ │ │
│ │ │ Pause | Logs           │ │ │ │ Activate | Logs     │ │ │
│ │ └─────────────────────────┘ │ │ └─────────────────────┘ │ │
│ └─────────────────────────────┘ └─────────────────────────┘ │
│ ┌─ Agent Performance Dashboard ──────────────────────────┐  │
│ │ ┌─ Metrics ───────────────────────────────────────────┐ │ │
│ │ │ Total Agents: 8 | Active: 5 | Efficiency: 91%     │ │ │
│ │ └─────────────────────────────────────────────────────┘ │ │
│ │ ┌─ Performance Chart ─────────────────────────────────┐ │ │
│ │ │ [Line chart showing agent performance over time]   │ │ │
│ │ └─────────────────────────────────────────────────────┘ │ │
│ └─────────────────────────────────────────────────────────┘ │
└─────────────────────────────────────────────────────────────┘
```

## Component Specifications

### Navigation Components

#### Primary Navigation
- **Height**: 64px (desktop), 56px (mobile)
- **Logo Area**: 200px width, left-aligned
- **Navigation Links**: Center-aligned, 16px font size
- **User Actions**: Right-aligned, 40px avatar size
- **Mobile**: Hamburger menu, slide-out drawer

#### Sidebar Navigation
- **Width**: 280px (desktop), full-width overlay (mobile)
- **Sections**: Primary nav, quick actions, recent items
- **Item Height**: 48px with 16px padding
- **Icons**: 24px size, 16px margin-right

### Content Components

#### Cards
- **Padding**: 24px all sides
- **Border Radius**: 8px
- **Shadow**: 0 2px 8px rgba(0,0,0,0.1)
- **Spacing**: 24px between cards

#### Forms
- **Input Height**: 48px
- **Label Spacing**: 8px above input
- **Field Spacing**: 24px between fields
- **Button Height**: 48px (primary), 40px (secondary)

#### Tables
- **Row Height**: 56px
- **Header Height**: 48px
- **Cell Padding**: 16px horizontal, 12px vertical
- **Zebra Striping**: Every other row

## Responsive Behavior

### Breakpoint Adaptations

#### Desktop to Tablet (1024px)
- Sidebar collapses to icons only
- Content area expands to full width
- Card grid reduces from 3 to 2 columns

#### Tablet to Mobile (768px)
- Sidebar becomes overlay
- Navigation becomes hamburger menu
- Cards stack in single column
- Tables become horizontally scrollable

### Touch Optimization
- **Minimum Touch Target**: 44px x 44px
- **Button Spacing**: 8px minimum between touch targets
- **Gesture Support**: Swipe navigation, pull-to-refresh
- **Hover States**: Converted to active states on touch

## Interaction States

### Button States
- **Default**: Base styling
- **Hover**: 10% darker background
- **Active**: 20% darker background
- **Disabled**: 50% opacity, no interaction
- **Loading**: Spinner overlay, disabled interaction

### Form States
- **Default**: Neutral border
- **Focus**: Primary color border, shadow
- **Error**: Red border, error message below
- **Success**: Green border, success indicator
- **Disabled**: Gray background, no interaction

### Navigation States
- **Default**: Base styling
- **Active**: Primary color background/text
- **Hover**: Light background highlight
- **Visited**: Subtle visual indicator

## Accessibility Considerations

### Keyboard Navigation
- **Tab Order**: Logical flow through interface
- **Focus Indicators**: Clear visual focus states
- **Skip Links**: Jump to main content
- **Keyboard Shortcuts**: Common actions accessible

### Screen Reader Support
- **Semantic Markup**: Proper heading hierarchy
- **ARIA Labels**: Descriptive labels for complex elements
- **Alt Text**: Meaningful descriptions for images
- **Live Regions**: Dynamic content announcements

### Visual Accessibility
- **Color Contrast**: 4.5:1 minimum ratio
- **Text Size**: 16px minimum for body text
- **Color Independence**: Information not conveyed by color alone
- **Motion Reduction**: Respect prefers-reduced-motion

## Implementation Notes

### Development Handoff
- **Measurements**: All dimensions in pixels or rem units
- **Spacing**: Consistent 8px grid system
- **Typography**: Defined font sizes and line heights
- **Colors**: Hex values and design token references

### Quality Assurance
- **Cross-browser Testing**: Chrome, Firefox, Safari, Edge
- **Device Testing**: iOS, Android, various screen sizes
- **Accessibility Testing**: Screen readers, keyboard navigation
- **Performance**: Optimize for fast loading and smooth interactions

---

**Note**: These wireframes serve as the foundation for visual design and development implementation. All measurements and specifications should be validated during the design and development process.

**Next Steps**:
1. Create high-fidelity visual designs based on these wireframes
2. Develop interactive prototypes for user testing
3. Validate layouts with actual content and data
4. Refine specifications based on technical constraints 