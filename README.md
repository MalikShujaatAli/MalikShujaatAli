# Malik Shujaat Ali

**Backend engineer.** I build systems, put them in production, and then keep them running — which is
where most of what I know actually came from.

Computer Science, UET Lahore (2026). Based in Lahore, Pakistan.

---

### Currently

Sole engineer on **[Nortixx](https://nortixx.com)** — a live multi-tenant B2B SaaS for US service
businesses. ASP.NET Core (.NET 10), EF Core over PostgreSQL, React 19 + TypeScript. ~93K lines of C#,
890+ commits and 148 migrations since April 2026. Multi-tenant isolation, signature-verified idempotent
webhooks, a durable outbox, subscription billing, and the on-call side of all of it.

Also producing AI-generated commercials at **Cinexcs Films**, where the engineering problem is getting
non-deterministic models to hold a specification across a whole batch.

---

### Selected work

**[Multimodal Emotion Recognition](https://github.com/MalikShujaatAli/EIMMAS_Backend_APIs)** · Python,
TensorFlow, FastAPI
Four microservices reading emotion from text, speech and facial expression. I trained all three models
(94.04% / 81.03% test accuracy, plus an audio BiLSTM) and served them with compiled graphs, TFLite
quantization and zero disk I/O. The repository also carries a **nine-phase rebuild log** documenting why
each earlier architecture was abandoned — that is the part worth reading.

**Azeem Style View** · C#, .NET 8, WinForms, ASP.NET Core MVC, SQLite *(private — client work)*
An offline-first shop management system delivered to a tailoring business. Prints Urdu receipts on a
thermal printer that has no Urdu font, by rendering the whole receipt as an ESC/POS raster bitmap. The
customer portal's public key can read no table directly; every read goes through a `SECURITY DEFINER`
procedure, and the PIN throttle is keyed by phone rather than IP because Pakistani carriers share
addresses behind CGNAT. 90 xUnit tests.

**[ASP.NET Core API suite](https://github.com/MalikShujaatAli?tab=repositories&q=API)** · .NET 8, EF Core,
SQL Server
Three services —
[authentication](https://github.com/MalikShujaatAli/Authentication-Microservice),
[job portal](https://github.com/MalikShujaatAli/JobPortalAPI),
[inventory](https://github.com/MalikShujaatAli/InventoryAPI) — built to get the details right rather than
to be large: revocable refresh tokens from a CSPRNG, zero clock skew on validation, price snapshots on
order lines so history does not move when prices do.

---

### Stack

**Daily:** C# · ASP.NET Core · Entity Framework Core · PostgreSQL · SQL Server · React · TypeScript
**Also:** Python · FastAPI · Docker · Dapper · Quartz.NET · xUnit · Testcontainers · SQLite · WPF · C++
**Machine learning:** TensorFlow · Keras · PyTorch · scikit-learn · OpenCV · HuggingFace Transformers

---

### A note on the READMEs here

Every repository on this profile says plainly what it is — production work, a learning project, or
coursework — and each one ends with its real limitations. A CRUD API described as enterprise-grade tells
you nothing; one that names the concurrency gap in its own stock-decrement path tells you what the author
actually understands. I would rather be read that way.

---

📧 [shujaatali12344@gmail.com](mailto:shujaatali12344@gmail.com) ·
💼 [LinkedIn](https://www.linkedin.com/in/malik-shujaat-ali) ·
🌐 [nortixx.com](https://nortixx.com)
