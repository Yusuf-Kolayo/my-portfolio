# Senior Full-Stack Engineer
**Laravel | Flutter | Production Systems**

I architect and maintain systems handling financial transactions, field operations, and multi-tenant workflows for thousands of active users.

---

## Technical Expertise

**Backend (Laravel/PHP)**
- Multi-tenant architecture with dynamic database connections per tenant
- Approval workflow engine with state machines and authority-based routing
- Financial transaction processing with ACID compliance and audit trails
- Query optimization: eager loading, index design, N+1 elimination
- Firebase Cloud Messaging integration for real-time notifications
- Payment gateway integrations (Flutterwave) with webhook handling
- Granular RBAC with route-level permissions and middleware chains
- Schema design: composite keys, foreign key constraints, soft deletes, JSON columns

**Mobile (Flutter/Dart)**
- Cross-platform apps (iOS/Android) with 5K+ active installations
- Riverpod for state management with provider composition
- Offline-first: local SQLite cache with background sync
- WebView integration for OAuth flows and payment processing
- FCM push notifications with background message handling
- PDF generation from widgets, screenshot capture, Share API integration
- Service layer pattern with proper error propagation and retry logic

**Architecture**
- Multi-tenant SaaS with tenant isolation at database and cache layers
- Event-driven workflows with before/after snapshots for rollback
- Automated billing cycles with proration and reconciliation
- Document generation pipeline (bills, receipts, statements)
- Job queue processing with failed job handling and retry strategies

---

## Production Impact

Systems I've built serve municipal waste service operations across multiple locations:

- Payment processing with transaction verification and balance tracking
- Multi-level approval workflows with authority delegation
- Automated monthly billing cycles with proration logic
- Mobile field apps with offline operation and sync
- Job scheduling with GPS tracking and photo evidence
- Real-time push notifications for payment confirmations
- Export pipelines for financial reporting and analytics

These systems process real transactions where data integrity and uptime are critical.

---

## Stack

**Backend**: PHP 8+, Laravel 10+, MySQL 8+, Eloquent ORM, Firebase Admin SDK, Guzzle  
**Mobile**: Flutter 3+, Dart 3+, Riverpod, FCM, WebView, PDF/Image libraries  
**Tools**: Git, Composer, VS Code, Postman, MySQL Workbench  
**Patterns**: Multi-tenancy, Service Layer, Repository, Factory, Observer, DI

---

## Engineering Principles

**Data Integrity First**  
Database transactions, foreign key constraints, before/after snapshots, comprehensive audit trails.

**Performance at Scale**  
Eager loading, proper indexing, query analysis, caching strategies, background job processing.

**Defensive Programming**  
Authorization checks at every layer, input validation, SQL injection prevention, graceful error handling.

**Maintainable Code**  
Clear naming, logical abstractions, inline documentation for complex logic, migration rollback plans.

**Real-World UX**  
Offline capability, poor network handling, immediate feedback, no silent failures.

---

## Development Approach

**Pre-Development**  
Map business workflows, design state machines, define database schema, document API contracts.

**During Development**  
Test financial paths thoroughly, wrap critical operations in transactions, log strategically, optimize queries early.

**Deployment**  
Verify backups, stage rollouts, monitor error rates, profile performance, iterate based on metrics.

---

## Currently Exploring

Event-driven microservices, Laravel queue optimization, Flutter performance profiling, database sharding.

---

## Open to Opportunities

Looking for roles involving:
- Backend systems requiring scale and complexity
- Mobile apps with real business impact
- Teams that prioritize reliability and code quality
- Technical challenges with measurable outcomes

**Contact**: Available via GitHub or LinkedIn.

---

*Production systems engineer. I build things that work.*
