# Club App - Smart Table Ordering System

# Project Makefile

# Sprint Duration: 3 Weeks (Nov 10-28, 2025)

# =============================================================================

# PROJECT CONFIGURATION

# =============================================================================

PROJECT_NAME := Club-App-Smart-Table-Ordering
SPRINT_START := 2025-11-10
SPRINT_END := 2025-11-28
TEAM_MEMBERS := Maranatha Chrispine Elijah Praise Philimon Timothy-Zikani Timothy-Wongani

# =============================================================================

# WEEK 1 TASKS (Nov 10-14)

# =============================================================================

.PHONY: task-1 task-2 task-6 task-7 week-1

task-1: # UX Research & Requirement Validation
@echo "Task 1: UX Research & Requirement Validation"
@echo "Duration: 3 days (Nov 10-12)"
@echo "Team: Timothy Msiska, Elijah Mhango"
@echo "Deliverables: UX research summary, user personas, requirements confirmation"
@echo "Status: ✅ Ready"

task-2: # User Journey Mapping
@echo "Task 2: User Journey Mapping (Customer & Staff flows)"
@echo "Duration: 3 days (Nov 11-13)"
@echo "Team: Praise Khonje, Maranatha Ndege"
@echo "Deliverables: Visual maps for user flow"
@echo "Status: ✅ Ready"

task-6: # DFD Level 0
@echo "Task 6: Data Flow Diagram - Level 0 (System Overview)"
@echo "Duration: 2 days (Nov 12-13)"
@echo "Team: Timothy Wongani Mphande, Philimon Katambo"
@echo "Deliverables: Context diagram showing main entities and data flows"
@echo "Status: ✅ Ready"

task-7: # DFD Level 1
@echo "Task 7: Data Flow Diagram - Level 1 (Major Processes)"
@echo "Duration: 4 days (Nov 14-17)"
@echo "Team: Timothy Wongani, Maranatha Ndege"
@echo "Deliverables: DFD Level 1 with labeled processes and data stores"
@echo "Status: ✅ Ready"

week-1: task-1 task-2 task-6 task-7

# =============================================================================

# WEEK 2 TASKS (Nov 17-21)

# =============================================================================

.PHONY: task-3 task-4 task-5 task-8 week-2

task-3: # UI Wireframes
@echo "Task 3: UI Wireframes (Low-Fidelity)"
@echo "Duration: 3 days (Nov 13-15)"
@echo "Team: Chrispine Dzimbiri (Lead), Praise Khonje"
@echo "Deliverables: Figma wireframes for all app modules"
@echo "Status: 🔄 In Progress"

task-4: # UI Wireframes Review
@echo "Task 4: UI Wireframes Review & Adjustments"
@echo "Duration: 2 days (Nov 16-17)"
@echo "Team: All members"
@echo "Deliverables: Updated approved wireframes"
@echo "Status: ⏳ Pending"

task-5: # High-Fidelity Mockups
@echo "Task 5: High-Fidelity UI Mockups"
@echo "Duration: 3 days (Nov 18-20)"
@echo "Team: Chrispine Dzimbiri, Elijah Mhango"
@echo "Deliverables: Final design mockups in Figma or Adobe XD"
@echo "Status: ⏳ Pending"

task-8: # DFD Level 2
@echo "Task 8: Data Flow Diagram - Level 2 (Detailed Subprocesses)"
@echo "Duration: 4 days (Nov 18-21)"
@echo "Team: Philimon Katambo, Timothy Msiska"
@echo "Deliverables: DFD Level 2 diagrams with detailed data paths"
@echo "Status: ⏳ Pending"

week-2: task-3 task-4 task-5 task-8

# =============================================================================

# WEEK 3 TASKS (Nov 24-28)

# =============================================================================

.PHONY: task-9 task-10 task-11 week-3

task-9: # Data Dictionary
@echo "Task 9: Data Dictionary & Process Documentation"
@echo "Duration: 3 days (Nov 21-23)"
@echo "Team: Maranatha Ndege, Elijah Mhango"
@echo "Deliverables: Data dictionary and process table"
@echo "Status: ⏳ Pending"

task-10: # Prototype Integration
@echo "Task 10: UI/UX Prototype Integration & Demo Prep"
@echo "Duration: 3 days (Nov 24-26)"
@echo "Team: Chrispine Dzimbiri, Praise Khonje, Timothy Msiska"
@echo "Deliverables: Interactive prototype demo and walkthrough slides"
@echo "Status: ⏳ Pending"

task-11: # Final Review
@echo "Task 11: Final Review & Submission"
@echo "Duration: 2 days (Nov 27-28)"
@echo "Team: All members"
@echo "Deliverables: Final UI/UX files, DFDs, documentation, presentation deck"
@echo "Status: ⏳ Pending"

week-3: task-9 task-10 task-11

# =============================================================================

# PROJECT MANAGEMENT TARGETS

# =============================================================================

.PHONY: all timeline status clean help

all: week-1 week-2 week-3
@echo ""
@echo "🎯 All tasks scheduled for $(SPRINT_START) to $(SPRINT_END)"

timeline:
@echo "📅 PROJECT TIMELINE: $(PROJECT_NAME)"
@echo "=========================================="
@echo ""
@echo "WEEK 1: Nov 10-14"
@echo "┌─────────────────────────────────────────────────────────────┐"
@echo "│ Task 1: UX Research [████████████] │"
@echo "│ Task 2: User Journey Mapping [████████████] │"
@echo "│ Task 6: DFD Level 0 [████] │"
@echo "│ Task 7: DFD Level 1 [████████] │"
@echo "└─────────────────────────────────────────────────────────────┘"
@echo ""
@echo "WEEK 2: Nov 17-21"
@echo "┌─────────────────────────────────────────────────────────────┐"
@echo "│ Task 3: UI Wireframes [████████████] │"
@echo "│ Task 4: Wireframe Review [████] │"
@echo "│ Task 5: Hi-Fi Mockups [████████████] │"
@echo "│ Task 8: DFD Level 2 [████████████] │"
@echo "└─────────────────────────────────────────────────────────────┘"
@echo ""
@echo "WEEK 3: Nov 24-28"
@echo "┌─────────────────────────────────────────────────────────────┐"
@echo "│ Task 9: Data Dictionary [████████████] │"
@echo "│ Task 10: Prototype Integration [████████████] │"
@echo "│ Task 11: Final Review [████] │"
@echo "└─────────────────────────────────────────────────────────────┘"

status:
@echo "📊 PROJECT STATUS: $(PROJECT_NAME)"
@echo "=========================================="
@echo "Sprint: $(SPRINT_START) to $(SPRINT_END)"
@echo "Team Members: $(TEAM_MEMBERS)"
@echo ""
@echo "WEEK 1 (Nov 10-14):"
@echo " ✅ Task 1: UX Research (Nov 10-12)"
@echo " ✅ Task 2: User Journey Mapping (Nov 11-13)"
@echo " ✅ Task 6: DFD Level 0 (Nov 12-13)"
@echo " ✅ Task 7: DFD Level 1 (Nov 14-17)"
@echo ""
@echo "WEEK 2 (Nov 17-21):"
@echo " 🔄 Task 3: UI Wireframes (Nov 13-15)"
@echo " ⏳ Task 4: Wireframe Review (Nov 16-17)"
@echo " ⏳ Task 5: Hi-Fi Mockups (Nov 18-20)"
@echo " ⏳ Task 8: DFD Level 2 (Nov 18-21)"
@echo ""
@echo "WEEK 3 (Nov 24-28):"
@echo " ⏳ Task 9: Data Dictionary (Nov 21-23)"
@echo " ⏳ Task 10: Prototype Integration (Nov 24-26)"
@echo " ⏳ Task 11: Final Review (Nov 27-28)"

clean:
@echo "🧹 Cleaning project status..."
@echo "Reset all task statuses to pending"

help:
@echo "Club App - Smart Table Ordering System Makefile"
@echo ""
@echo "Available targets:"
@echo " all - Run all tasks (sequential)"
@echo " timeline - Show visual project timeline"
@echo " status - Show current project status"
@echo " week-1 - Run Week 1 tasks"
@echo " week-2 - Run Week 2 tasks"
@echo " week-3 - Run Week 3 tasks"
@echo " task-[1-11] - Run specific task"
@echo " clean - Reset project status"
@echo " help - Show this help message"
@echo ""
@echo "Example: make timeline status"

# =============================================================================

# DEFAULT TARGET

# =============================================================================

.DEFAULT_GOAL := help

VISUALISED TABLE

| <span style="color:#2563eb">Task</span>                              | <span style="color:#dc2626">Duration</span> | <span style="color:#059669">Start</span>  | <span style="color:#ea580c">End</span>    | <span style="color:#7c3aed">Key Members</span>               | <span style="color:#9333ea">Dependencies</span> | <span style="color:#dc2626">Key Deliverables</span>            |
| -------------------------------------------------------------------- | ------------------------------------------- | ----------------------------------------- | ----------------------------------------- | ------------------------------------------------------------ | ----------------------------------------------- | -------------------------------------------------------------- |
| <span style="color:#2563eb">**1. UX Research & Validation**</span>   | <span style="color:#dc2626">3 days</span>   | <span style="color:#059669">Nov 10</span> | <span style="color:#ea580c">Nov 12</span> | <span style="color:#7c3aed">Msiska, Elijah</span>            | <span style="color:#9333ea">None</span>         | <span style="color:#dc2626">User personas, requirements</span> |
| <span style="color:#2563eb">**2. User Journey Mapping**</span>       | <span style="color:#dc2626">3 days</span>   | <span style="color:#059669">Nov 11</span> | <span style="color:#ea580c">Nov 13</span> | <span style="color:#7c3aed">Praise, Maranatha</span>         | <span style="color:#9333ea">Task 1</span>       | <span style="color:#dc2626">User flow maps</span>              |
| <span style="color:#2563eb">**3. UI Wireframes (Low-Fi)**</span>     | <span style="color:#dc2626">3 days</span>   | <span style="color:#059669">Nov 13</span> | <span style="color:#ea580c">Nov 15</span> | <span style="color:#7c3aed">Chrispine, Praise</span>         | <span style="color:#9333ea">Task 2</span>       | <span style="color:#dc2626">Figma wireframes</span>            |
| <span style="color:#2563eb">**4. UI Wireframes Review**</span>       | <span style="color:#dc2626">2 days</span>   | <span style="color:#059669">Nov 16</span> | <span style="color:#ea580c">Nov 17</span> | <span style="color:#7c3aed">All members</span>               | <span style="color:#9333ea">Task 3</span>       | <span style="color:#dc2626">Approved wireframes</span>         |
| <span style="color:#2563eb">**5. High-Fidelity Mockups**</span>      | <span style="color:#dc2626">3 days</span>   | <span style="color:#059669">Nov 18</span> | <span style="color:#ea580c">Nov 20</span> | <span style="color:#7c3aed">Chrispine, Elijah</span>         | <span style="color:#9333ea">Task 4</span>       | <span style="color:#dc2626">Final design mockups</span>        |
| <span style="color:#2563eb">**6. DFD Level 0 (Overview)**</span>     | <span style="color:#dc2626">2 days</span>   | <span style="color:#059669">Nov 12</span> | <span style="color:#ea580c">Nov 13</span> | <span style="color:#7c3aed">Mphande, Philimon</span>         | <span style="color:#9333ea">Task 1</span>       | <span style="color:#dc2626">Context diagram</span>             |
| <span style="color:#2563eb">**7. DFD Level 1 (Processes)**</span>    | <span style="color:#dc2626">4 days</span>   | <span style="color:#059669">Nov 14</span> | <span style="color:#ea580c">Nov 17</span> | <span style="color:#7c3aed">Mphande, Maranatha</span>        | <span style="color:#9333ea">Task 6</span>       | <span style="color:#dc2626">Level 1 DFD</span>                 |
| <span style="color:#2563eb">**8. DFD Level 2 (Subprocesses)**</span> | <span style="color:#dc2626">4 days</span>   | <span style="color:#059669">Nov 18</span> | <span style="color:#ea580c">Nov 21</span> | <span style="color:#7c3aed">Philimon, Msiska</span>          | <span style="color:#9333ea">Task 7</span>       | <span style="color:#dc2626">Level 2 DFD</span>                 |
| <span style="color:#2563eb">**9. Data Dictionary**</span>            | <span style="color:#dc2626">3 days</span>   | <span style="color:#059669">Nov 21</span> | <span style="color:#ea580c">Nov 23</span> | <span style="color:#7c3aed">Maranatha, Elijah</span>         | <span style="color:#9333ea">Task 8</span>       | <span style="color:#dc2626">Data dictionary</span>             |
| <span style="color:#2563eb">**10. Prototype Integration**</span>     | <span style="color:#dc2626">3 days</span>   | <span style="color:#059669">Nov 24</span> | <span style="color:#ea580c">Nov 26</span> | <span style="color:#7c3aed">Chrispine, Praise, Msiska</span> | <span style="color:#9333ea">Tasks 5,9</span>    | <span style="color:#dc2626">Interactive prototype</span>       |
| <span style="color:#2563eb">**11. Final Review & Submission**</span> | <span style="color:#dc2626">2 days</span>   | <span style="color:#059669">Nov 27</span> | <span style="color:#ea580c">Nov 28</span> | <span style="color:#7c3aed">All members</span>               | <span style="color:#9333ea">All tasks</span>    | <span style="color:#dc2626">Final deliverables</span>          |

Color Legend:
🔵 Blue (#2563eb): Task names - Primary activities

🔴 Red (#dc2626): Duration & Deliverables - Time and output focused

🟢 Green (#059669): Start dates - Beginning of activities

🟠 Orange (#ea580c): End dates - Completion points

🟣 Purple (#7c3aed): Team members - People resources

🟣 Light Purple (#9333ea): Dependencies - Task relationships
