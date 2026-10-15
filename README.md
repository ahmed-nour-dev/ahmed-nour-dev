# Hi, I'm Ahmed 👋

**Laravel / PHP developer** at [IT-Gates](https://it-gates.com), based in Cairo, Egypt.

I build and maintain production Laravel applications, with a focus on backend architecture, database performance, and reliable deployments. I also write open source packages to solve problems I run into on real projects.

## 🔧 What I work on

- Backend architecture for large, modular Laravel applications
- Package development
- MySQL query and schema optimization, bulk imports and data migrations
- Deployment and production tooling
- Third-party integrations: Paymob (payments), VideoSDK and Agora (video)

## 📦 My packages

### [laravel-stream-backup](https://github.com/ahmed-nour-dev/laravel-stream-backup)

Streaming database backups for Laravel, with no temp files and flat memory usage, even on very large databases.

- Streams dumps directly to **S3 (multipart)**, **SFTP**, or **local disk**
- Supports **MySQL**, **PostgreSQL**, and **SQLite**
- **Atomic restores** using a shadow-table swap, so a failed restore never leaves the database half-written
- Built after hitting limits with existing backup packages on large databases

### [vi-validation](https://github.com/ahmed-nour-dev/vi-validation) · `ahmednour/validation`

A high-performance PHP validation library that is compatible with Laravel's validation rules.

- Compile a schema once and validate many rows, with optional native PHP code generation for hot paths
- Up to **94× faster than Laravel's validator** in its own benchmark suite (compiled to native PHP; 17–23× through the drop-in `FastValidator::make()` API)
- Streams large datasets (CSV, JSON, DB cursors) with constant memory
- Parity tests run the same cases through Laravel's real validator, and CI covers PHP 8.1–8.4 and Laravel 10–13
- Octane, Swoole and RoadRunner ready, with English and Arabic messages built in

```bash
composer require ahmednour/validation
```

### [eloquent-rag](https://github.com/ahmed-nour-dev/eloquent-rag) · `ahmednour/eloquent-rag` (beta)

Keeps your Eloquent models' RAG index correct on top of Laravel AI's embeddings and vector search, including when a document depends on data in *other* models.

- Model lifecycle sync, chunking, and rebuild tooling
- **Dependency tracking:** rename a category and every product whose document includes it is re-synced in bounded, coalesced queue batches
- Works with **MariaDB 11.7+** and **PostgreSQL + pgvector**
- Operations tooling: `rag:doctor`, `rag:verify`, `rag:rebuild`, and a `Rag::fake()` testing helper
- Beta, and not yet recommended for production

```bash
composer require ahmednour/eloquent-rag
```

## 🛠️ Tech stack

![PHP](https://img.shields.io/badge/PHP-777BB4?style=for-the-badge&logo=php&logoColor=white)
![Laravel](https://img.shields.io/badge/Laravel-FF2D20?style=for-the-badge&logo=laravel&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=for-the-badge&logo=mysql&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white)
![Vue.js](https://img.shields.io/badge/Vue.js-4FC08D?style=for-the-badge&logo=vuedotjs&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white)

## 📊 GitHub stats

![Ahmed's GitHub stats](https://github-readme-stats.vercel.app/api?username=ahmed-nour-dev&show_icons=true&theme=default)
![Top languages](https://github-readme-stats.vercel.app/api/top-langs/?username=ahmed-nour-dev&layout=compact)

## 🤝 Let's connect

- 💼 LinkedIn: [ahmed-nour-dev](https://www.linkedin.com/in/ahmed-nour-dev)
- 📦 Feedback and issues on my packages are always welcome
