# P01: Database Design and Table Relationships

|                  |                                                |
| ---------------- | ---------------------------------------------- |
| **Status**       | 🚧 In progress                                  |
| **Started**      | 2026-10-06                                     |
| **Completed**    | -                                              |
| **Branch**       | `feature/database-relations`                   |
| **Pull request** | -                                              |

## Goal

Design and implement the database of **GameBook**, a gaming session booking application, focusing on table relationships with Eloquent: One-to-One, One-to-Many, Many-to-Many (with pivot data), and Has-Many-Through.

## Jobs

| Code | Job                      | Status         | Completed | Proof |
| ---- | ------------------------ | -------------- | --------- | ----- |
| J1   | Database design and ERD  | 🚧 In progress | -         | -     |
| J2   | Migrations               | 🚧 In progress | -         | -     |
| J3   | Models and relationships | 🚧 In progress | -         | -     |
| J4   | Seeders                  | 🚧 In progress | -         | -     |
| J5   | README                   | 🚧 In progress | -         | -     |

**Status legend:** ⏳ Planned · 🚧 In progress · ✅ Done · ⛔ Blocked

---

### J1: Database design and ERD
- **What:** 11 tables covering every relationship type.
- **Proof:** [`docs/database/erd.md`](erd.md)

### J2: Migrations
- **What:** Nine table migrations plus two pivot migrations (`game_station`, `addon_booking`), with foreign keys, cascade and restrict rules, and unique constraints.

### J3: Models and relationships
- **What:** Eight new models plus relationships added to `User`: `hasOne`, `hasMany`, `belongsTo`, `belongsToMany` (with `withPivot`), and `hasManyThrough`.

### J4: Seeders
- **What:** `DatabaseSeeder` creates platforms, stations, games, add-ons, two users with profiles, three bookings with payments, and two reviews.

### J5: README
- **What:** Root README with author details.

## Next

Update this file with proof links (commits) and mark each job as ✅ Done once it is pushed and verified. Later phases get their own file, for example `P02-crud-and-validation.md`.
