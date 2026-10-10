> **Disclaimer:** The Stokly source code is private because it is an active commercial product. This repository exists strictly as a technical and architectural showcase.

# Stokly

Stokly is an offline-first desktop ERP and inventory management application designed for reliable daily operations, even without internet connectivity.

## Key Features

- **Offline-first architecture** for uninterrupted local operation and data access.
- **Automated PDF invoicing** for streamlined billing workflows.
- **Multi-tenant SQLAlchemy models** to support tenant-aware data isolation.
- **Custom PyQt6 reactive UI** tailored for desktop productivity.

## Tech Stack

- Python 3
- PyQt6
- SQLite
- SQLAlchemy

## Screenshots

_Insert application UI screenshots here (dashboard, inventory views, invoicing screens, etc.)._

## Architecture Overview

Stokly separates the local persistence layer and the GUI layer: SQLite/SQLAlchemy handle local data storage and domain modeling, while the PyQt6 interface manages user interaction and presentation.
