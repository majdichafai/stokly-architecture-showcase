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

<img width="1920" height="1080" alt="Capture d&#39;écran 2026-09-17 155002" src="https://github.com/user-attachments/assets/a76f8721-798e-49c7-a75a-b1b37e56dfa7" />

<img width="1919" height="1044" alt="Capture d&#39;écran 2026-07-26 144258" src="https://github.com/user-attachments/assets/f0f5e5b5-3f16-4efd-870b-f32586e84f49" />
<img width="1919" height="1048" alt="Capture d&#39;écran 2026-08-05 220203" src="https://github.com/user-attachments/assets/fc009239-36e3-4af8-aec5-c629e026055d" />
<img width="1919" height="1049" alt="Capture d&#39;écran 2026-08-05 220149" src="https://github.com/user-attachments/assets/70412c8b-ce5b-456b-9e4d-cf9f03ebe57a" />
<img width="1918" height="1048" alt="Capture d&#39;écran 2026-08-05 220136" src="https://github.com/user-attachments/assets/5df53c6a-7145-4618-b688-1710c264571d" />
<img width="1919" height="1049" alt="Capture d&#39;écran 2026-08-05 220035" src="https://github.com/user-attachments/assets/ba37940c-881f-4cd8-9e2b-05eaa5a6d9ac" />
<img width="1919" height="1049" alt="Capture d&#39;écran 2026-08-05 220015" src="https://github.com/user-attachments/assets/7edeb4b2-d588-4901-b881-f911bed3086e" />
<img width="1919" height="1047" alt="Capture d&#39;écran 2026-08-05 215953" src="https://github.com/user-attachments/assets/87581a17-4e48-40f3-8e58-075baa1e4dd6" />
<img width="1919" height="1049" alt="Capture d&#39;écran 2026-08-05 215847" src="https://github.com/user-attachments/assets/75257576-d195-4df2-9025-eaf56b5b8e63" />
<img width="1919" height="1047" alt="Capture d&#39;écran 2026-08-05 215822" src="https://github.com/user-attachments/assets/57573fa8-c8b5-41ac-8c1e-114ec32efd42" />
<img width="1919" height="1046" alt="Capture d&#39;écran 2026-08-05 215755" src="https://github.com/user-attachments/assets/8c5e0aa9-253c-4b32-9d61-9a37a09ca1f1" />




## Architecture Overview

Stokly separates the local persistence layer and the GUI layer: SQLite/SQLAlchemy handle local data storage and domain modeling, while the PyQt6 interface manages user interaction and presentation.
