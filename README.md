## Technologies Used

- **Next.js**: React framework for server-rendered applications.
- **React**: JavaScript library for building user interfaces.
- **Tailwind CSS**: Utility-first CSS framework for rapid UI development.
- **JSON**: Data storage and manipulation using JSON files.

## Folder Structure `inventory-task/`

- **pages/**: Next.js page components
  - `index.js`: Main page (Home)
  - **orders/**
    - `[id].js`: Dynamic order details page
    - `index.js`: Orders list page
  - `inventory.js`: Inventory management page
  - ... Other pages as per project requirements

- **components/**: React components
  - `OrderItem.js`: Component for rendering individual order items
  - ... Other components used across pages

- **data/**: JSON data files (orders.json, items.json, etc.)
  - `orders.json`
