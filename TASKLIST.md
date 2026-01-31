# Task List

This file shows the current progress of all tasks in this project.
It is automatically updated by dev0 as tasks are completed.

---

## Phase 1

- [ ] ⏳ **Project Foundation & UI Setup**
  Initialize Next.js app with TypeScript and Tailwind CSS. Install Shadcn UI and configure the base layout (sidebar/navbar). Create the basic folder structure for the App Router.

- [ ] ⏳ **Database Schema & Prisma Setup**
  Set up Prisma with SQLite. Define models: 'Project' (name, url, repo), 'Deployment' (status, version, date), 'Financials' (mrr, cost), and 'Task' (description, isCompleted). Run initial migration.

## Phase 2

- [ ] ⏳ **Project CRUD Server Actions**
  Implement Server Actions for creating, reading, updating, and deleting Projects. Ensure proper Zod validation for inputs.

- [ ] ⏳ **Dashboard Project Grid UI**
  Create the main dashboard page displaying a grid of Project cards. Each card should show the project name, live URL link, and a status badge. Fetch data using the Server Actions created previously.

- [ ] ⏳ **Add/Edit Project Modal**
  Implement a Dialog component (Shadcn) containing a form to add a new project or edit an existing one. Connect form submission to the CRUD Server Actions.

- [ ] ⏳ **Project Details Page Layout**
  Create a dynamic route `/projects/[id]` to view specific project details. Layout should include tabs for 'Overview', 'Financials', and 'Tasks'.

## Phase 3

- [ ] ⏳ **Financials Tracking Implementation**
  Implement the Financials tab. Create a data table showing historical revenue/cost data. Add a summary card showing current Profit/Loss for the project.

- [ ] ⏳ **Project-Specific Task Manager**
  Build a simple todo list inside the Project Details view. Allow users to add tasks, toggle completion status, and delete tasks. Use optimistic UI updates.

- [ ] ⏳ **Deployment Status Simulation**
  Add a visual timeline or list in the Project Overview tab showing 'Deployment History'. For now, allow users to manually add a deployment record (Version, Status, Date).

- [ ] ⏳ **Global Dashboard Aggregates**
  Update the main dashboard to show aggregate metrics at the top: Total MRR across all apps, Total Monthly Costs, and Total Active Projects.

## Phase 4

- [ ] ⏳ **UI Polish & Loading States**
  Add React Suspense boundaries and Skeleton loaders for data fetching. Implement toast notifications for success/error states on all forms.

## Phase 5

- [ ] ⏳ **Documentation & Final Cleanup**
  Write internal documentation. Ensure all database seeds work correctly. Verify responsive behavior on mobile devices.

---

_Last updated by dev0 automation_
