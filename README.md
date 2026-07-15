## Zachary Gallant

Software engineering graduate (Carleton University, 2026), based in Campbellton, New
Brunswick and open to remote work. I build backend-heavy web applications — mostly
Laravel and PHP, with Java and C/C++ from my systems and concurrency coursework.

**Backend** &nbsp;Laravel · PHP · Spring Boot · Java
**Frontend** &nbsp;Vue · Blade · Thymeleaf · TypeScript
**Infrastructure** &nbsp;Docker · Laravel Sail · GitHub Actions · Azure
**Systems** &nbsp;C · C++ · concurrency, IPC, scheduling

---

### Selected work

#### [SYSC4907 Capstone — driving simulator on real map data](https://github.com/CapstoneProjectForSysc4907/SYSC4907-Capstone-) · Java
Reconstructs real roads from Google Maps Roads API geometry and Street View imagery, then
runs a vehicle physics model over them with collision detection and a live HUD.
*Team of three — I built the Roads API caching layer and the Street View image loader,*
including in-flight request de-duplication that recovers cleanly when the API fails, plus
GUI work and its JUnit coverage.

#### GP Transmission — production Laravel site · live at [gptransmission.ca](https://gptransmission.ca)
Full site for a Campbellton, NB transmission shop: customer service-request flow with Mailgun
delivery, Dockerised development environment, GitHub Actions CI, and a PHPUnit suite.
128 commits over two years — my longest-running project. *Private repository; happy to
walk through the code on request.*

#### [ticket-system](https://github.com/Zach262626/ticket-system) · Laravel 12
Multi-tenant support desk. Per-tenant database isolation via `stancl/tenancy`, real-time
updates over Reverb WebSockets, queued email and broadcast workers on Horizon, all
containerised with Laravel Sail.

#### [Bookstore-WebApp](https://github.com/Josh-fuller/Bookstore-WebApp) · Java · Spring Boot
Spring Boot, JPA and Thymeleaf bookstore application. *Team of five — I built the
authentication system* (user model, repository, service-layer registration and
credential verification, and the auth controller) *and much of the integration test suite.*

#### Firefighting drone simulator · Java
Concurrent multi-subsystem simulation: a drone fleet, a scheduler, and a fire-incident
subsystem coordinating over UDP with a state-machine-driven drone lifecycle.
*Team of four — I implemented fault injection and recovery* (stuck-mid-flight, nozzle jam,
packet loss, corrupted messages) *and drone utilisation tracking.* *Private course
repository.*

#### [spring-address-book](https://github.com/Zach262626/spring-address-book) · Java · Spring Boot
REST and web controllers over JPA persistence, with GitHub Actions CI and continuous
deployment to Azure App Service.

#### [justinvest-access-control](https://github.com/Zach262626/justinvest-access-control) · Java
Role-based access control for a mock investment platform: five roles, time-of-day
permission rules, salted password hashing, and password-policy enforcement.

Also on my profile: a [Laravel + Vue real-time broadcasting app](https://github.com/Zach262626/broadcast-project),
and an [OS scheduler and memory simulator in C++](https://github.com/Zach262626/SYSC4001_A3_P1).

---

📍 Campbellton, New Brunswick &nbsp;·&nbsp; 🌐 Open to remote
