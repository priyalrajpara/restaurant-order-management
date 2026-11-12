# Restaurant Order Management System

A lightweight browser-based tool for managing restaurant orders and kitchen workflow.

## Features

- View order counts, statuses, and completed-order revenue on a dashboard.
- Create orders from a categorized menu; totals include 5% tax.
- Manage menu items and track orders through the kitchen using a FIFO queue.
- Search and filter order history. Orders and menu data are saved in browser `localStorage`.

## Running

This project uses plain JavaScript and CSS and has no build step. The current repository does not include an HTML entry page, so the interface cannot be launched from this checkout alone.

## Project files

- `js/app.js` — user interface and order workflow
- `js/linkedlist.js` — order list
- `js/queue.js` — kitchen waiting queue
- `js/storage.js` — browser storage and default menu
- `css/style.css` — application styles

Licensed under the MIT License; see [LICENSE](LICENSE).
