<p align="center">
  <img src="https://komarev.com/ghpvc/?username=ziyadmansy&label=Profile%20views&color=0e75b6&style=flat" alt="ziyadmansy" />
</p>

<h1 align="center">Hi 👋, I'm Ziyad Mansy</h1>

<h3 align="center">
Senior Mobile Software Engineer specializing in Flutter, with 5+ years shipping production mobile apps across fintech, healthcare, transportation, HR, and real estate for clients in the US, UK, and Saudi Arabia — built on clean architecture, offline-first design, and CI/CD from day one. Led a 3-engineer team on a SAMA-licensed BNPL platform (100K+ downloads, zero critical security incidents) and shipped AI-powered features for an enterprise UK real estate platform used by Reapit and Connells. Currently building US fleet-operations software, where I took a stalled product from 9 months without a release to a HIPAA-compliant launch on both app stores in one month. Five independently published apps on Google Play. Author of two research papers on LLM-guided software testing — one published as an independent preprint, the other under review at an ICSE-colocated conference.
</h3>
<br/>

- 🎓 Currently applying to PhD programs in Computer Science / Software Engineering, with a research focus on software testing, program analysis, and LLM-guided testing tools
- 🔭 Building the offline-first navigation system for Naveera Tech's Driver App — fleet-operations software for NEMT, paratransit, and freight fleets
- 🧪 Researching LLM-guided fuzzing and differential testing (see Research section below)

<h2 align="left">🔬 Research</h2>

### Coverage-Free Fuzzing: LLM-Guided Refinement of Grammar-Based Test Generators
*Independent research preprint, 2026*

Designed and built a fully black-box fuzzing pipeline that uses an LLM to iteratively refine a grammar-based Hypothesis strategy for the **cJSON** C parser — using only parser-level feedback (acceptance rate, structural diversity, rejection signatures), with **no coverage instrumentation**. Every LLM-authored proposal is AST-sandboxed and validated before it ever touches the target binary.

**Key results (15 seeded runs per arm):**
- Raised mean input acceptance rate from **58.2% → 97.1%** vs. a static grammar-only baseline (exact permutation test, p ≈ 1.29×10⁻⁸)
- Generalized the *unmodified* pipeline to a second target (**parson**) to test portability
- Ran a feedback-signal ablation isolating which proxy signals actually drive improvement
- Fully reproducible: seeded runs, environment/provenance manifests, and open-sourced harnesses

<p>
<a href="https://doi.org/10.5281/zenodo.22556343" target="_blank"><img alt="DOI" src="https://zenodo.org/badge/DOI/10.5281/zenodo.22556343.svg" /></a>
<a href="https://github.com/ziyadmansy/agentic-grammar-fuzzing" target="_blank"><img alt="Github" src="https://img.shields.io/badge/Github-View%20on%20github-lightgrey?style=for-the-badge&logo=github" /></a>
</p>

**Stack:** Python, Hypothesis, OpenAI API, ANTLR grammars, AddressSanitizer/UBSan

### Beyond Sanitizers: LLM-Guided Refinement for Differential JSON Deserialization Testing in Dart
*Under review, AST 2027 (ICSE-colocated)*

Built an LLM-guided differential testing pipeline comparing four Dart/Flutter JSON deserialization libraries against each other, surfacing silent data-corruption bugs that crash-only fuzzing can't catch — because nothing crashes, the output is just wrong.

**Key results:**
- Tested across 43,336 generated records
- Found silent data-corruption behavior in 3 of 4 libraries, at a 5.7% mismatch rate

<p>
<a href="https://doi.org/10.5281/zenodo.22555795" target="_blank"><img alt="DOI" src="https://zenodo.org/badge/DOI/10.5281/zenodo.22555795.svg" /></a>
</p>

<h2 align="left">📱 Apps</h2>

- 👨‍💻 Most proud iOS apps on the App Store:
  - [**Naveera Driver**](https://apps.apple.com/us/app/naveera-driver/id6769880111) — Driver app for Naveera's fleet-operations platform (NEMT/paratransit/freight); full in-app navigation and offline-mode support.
  - [**MADFU**](https://apps.apple.com/us/app/madfu-shop-today-pay-later/id1658723268) — Sharia-compliant BNPL fintech platform for the Saudi market; interest-free installments, merchant integrations, and rewards.
  - [**PropertyBox**](https://apps.apple.com/eg/app/propertybox/id1660237557) — AI-powered real estate platform for the UK market; listing image enhancement, AI-generated descriptions, and EPC-related workflows.
  - [**Numa**](https://play.google.com/store/apps/details?id=com.cardlessBanki.app) — Fintech app supporting freelancers with secure digital financial services.
  - [**Tahara**](https://apps.apple.com/us/app/tahara-%D8%B7%D9%87%D8%A7%D8%B1%D8%A9/id6446452995) — Women's health platform ranked #2 in Health & Fitness on the Saudi App Store.
  - [**GetN**](https://apps.apple.com/eg/developer/getn-for-digital-content/id1659276865) — Ride-hailing app in the style of Uber/Careem.
  - [**Talmaro-ESS**](https://apps.apple.com/us/app/talmaro-ess/id1484374387) — Enterprise HR management platform for attendance, payroll, and leave.
  - [**Soul Gym**](https://apps.apple.com/us/developer/mohamed-youssef/id1320109692) — Gym app with personalized workouts and progress tracking.

- 👨‍💻 Most proud Android apps on Google Play:
  - [**Naveera Driver**](https://play.google.com/store/apps/details?id=tech.naveera.driver&hl=en) — Driver app for Naveera's fleet-operations platform (NEMT/paratransit/freight); full in-app navigation and offline-mode support.
  - [**MADFU**](https://play.google.com/store/apps/details?id=com.sa.app.madfuser) — Sharia-compliant BNPL fintech platform for the Saudi market; interest-free installments, merchant integrations, and rewards.
  - [**PropertyBox**](https://play.google.com/store/apps/details?id=io.propertybox.propertybox2_app) — AI-powered real estate platform for the UK market; listing image enhancement, AI-generated descriptions, and EPC-related workflows.
  - [**Numa**](https://play.google.com/store/apps/details?id=com.cardlessBanki.app) — Fintech app supporting freelancers with secure digital financial services.
  - [**Tahara**](https://play.google.com/store/apps/details?id=com.tahara.tahara_app) — Women's health platform ranked #2 in Health & Fitness on the Saudi App Store.
  - [**Talmaro-ESS**](https://play.google.com/store/apps/details?id=com.onecliquesystems.one_click_app) — Enterprise HR management platform for attendance, payroll, and leave.
  - [**Piety of Hearts**](https://play.google.com/store/apps/details?id=com.ziyadmansy.pietyofHearts) — 9-language Islamic lifestyle app; sole developer, 1K+ downloads, 4.9★ (38 reviews).
  - [**Soul Gym**](https://play.google.com/store/apps/details?id=com.soulgymegypt.soulgym) — Gym app with personalized workouts and progress tracking.
  - [**My personal apps**](https://bit.ly/ZiyadApps) — Full portfolio of independently published apps.

- 📄 Full experience: [**Online CV**](https://bit.ly/ziyadmansycv)
- 📫 Reach me via [**LinkedIn**](https://www.linkedin.com/in/ziyadmansy/) or [**Mail**](mailto:ziyadmohammad37@gmail.com)

<hr>

<h2 align="left">Languages and Tools</h2>
<p>
<img alt="Flutter" src="https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white">
<img alt="Dart" src="https://img.shields.io/badge/Dart-0175C2?style=for-the-badge&logo=dart&logoColor=white">
<img alt="Kotlin" src="https://img.shields.io/badge/Kotlin-B125EA?style=for-the-badge&logo=kotlin&logoColor=white">
<img alt="Swift" src="https://img.shields.io/badge/Swift-F05138?style=for-the-badge&logo=swift&logoColor=white">
<img alt="Java" src="https://img.shields.io/badge/Java-007396?style=for-the-badge&logo=openjdk&logoColor=white">
<img alt="C" src="https://img.shields.io/badge/C-A8B9CC?style=for-the-badge&logo=c&logoColor=black">
<img alt="Python" src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white">
<img alt="JavaScript" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black">
<img alt="Xcode" src="https://img.shields.io/badge/xcode-7F52FF?style=for-the-badge&logo=xcode&logoColor=white">
<img alt="Android Studio" src="https://img.shields.io/badge/android studio-00DE7A?style=for-the-badge&logo=android&logoColor=white">
<img alt="SQLite" src="https://img.shields.io/badge/SQLite-07405E?style=for-the-badge&logo=sqlite&logoColor=white">
<img alt="Git" src="https://img.shields.io/badge/-git-red?style=for-the-badge&logo=git&logoColor=white">
<img alt="GitHub" src="https://img.shields.io/badge/-GitHub-black?style=for-the-badge&logo=github&logoColor=white">
<img alt="Figma" src="https://img.shields.io/badge/Figma-F24E1E?style=for-the-badge&logo=figma&logoColor=white">
</p>

<h2 align="left">Connect</h2>
<p>
<a href="mailto:ziyadmohammad37@gmail.com" target="_blank"><img align="center" src="https://img.shields.io/badge/Gmail-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Gmail"/></a>
<a href="https://www.linkedin.com/in/ziyadmansy/" target="_blank"><img align="center" src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"/></a>
<a href="https://stackoverflow.com/users/14139092" target="_blank"><img align="center" src="https://aleen42.github.io/badges/src/stackoverflow.svg" alt="Stack Overflow" height="28"/></a>
<a href="https://www.hackerrank.com/ziyadmohammad37" target="_blank"><img align="center" src="https://img.shields.io/badge/-Hackerrank-2EC866?style=for-the-badge&logo=HackerRank&logoColor=white" alt="HackerRank"/></a>
<a href="https://codeforces.com/profile/ziyad_mansy" target="_blank"><img align="center" src="https://img.shields.io/badge/Codeforces-445f9d?style=for-the-badge&logo=Codeforces&logoColor=white" alt="Codeforces"/></a>
</p>

<h2>Portfolio</h2>

### Naveera Tech — Senior Mobile Software Engineer *(Current)*
Naveera builds fleet-operations software (routing, dispatch, driver app, billing, computer vision) for NEMT, paratransit, and freight/field-service fleets across the US — founded by former fleet operators out of Colorado and Arizona.

- Took over a stalled platform after 9 months without a production release; shipped the Driver and Client Flutter apps to the App Store and Google Play within one month of joining, delivering HIPAA-compliant workflows.
- Built the driver app's full in-app navigation system, handling live routing and turn-by-turn guidance for drivers on active trips.
- Implemented an offline-first architecture so dispatch, navigation, and trip data stay reliable without connectivity and reconcile automatically on reconnect — critical for drivers in low-signal areas.
- Contributed to dispatch/routing and billing modules, supporting the end-to-end trip lifecycle from scheduling to invoicing.

<p><a href="https://play.google.com/store/apps/details?id=tech.naveera.driver&hl=en" target="_blank"><img alt="Google Play" src="https://img.shields.io/badge/Get%20it%20on%20google%20play-blue.svg?style=for-the-badge&logo=google-play" /></a> <a href="https://apps.apple.com/us/app/naveera-driver/id6769880111" target="_blank"><img alt="App Store" src="https://img.shields.io/badge/Get%20it%20on%20app%20store-black.svg?style=for-the-badge&logo=app-store&logoColor=white" /></a></p>

<hr>

### Focal Agent — Senior Mobile Software Engineer *(Concurrent with Naveera Tech)*
One of 8 senior engineers building PropertyBox, an AI-powered real estate platform for the UK market, serving enterprise clients including Reapit and Connells.

- Built AI-powered features including photo enhancement, automated property description generation, and direct social media publishing of AI-generated content.
- Led Flutter Web development alongside Android and iOS, migrated the web application into a production-ready mobile app, and built automated Azure Pipelines CI/CD for cross-platform deployments.
- Delivered campaign management and EPC compliance features aligned with UK regulatory requirements.
- Led internal AI knowledge-sharing sessions, helping engineering teams adopt AI-assisted development workflows.

<p><a href="https://play.google.com/store/apps/details?id=io.propertybox.propertybox2_app" target="_blank"><img alt="Google Play" src="https://img.shields.io/badge/Get%20it%20on%20google%20play-blue.svg?style=for-the-badge&logo=google-play" /></a> <a href="https://apps.apple.com/eg/app/propertybox/id1660237557" target="_blank"><img alt="App Store" src="https://img.shields.io/badge/Get%20it%20on%20app%20store-black.svg?style=for-the-badge&logo=app-store&logoColor=white" /></a></p>

<hr>

### Madfu — Lead Mobile Software Engineer
Led a 3-engineer Flutter team delivering the MADFU consumer app and a merchant POS application for a Sharia-compliant BNPL platform, serving 100K+ downloads in the Saudi market.

- Owned architecture and delivery of core financial features — installment plans, merchant integrations, payment flows, and POS integrations — for a platform granted a consumer financing permit by SAMA (Saudi Central Bank), maintaining zero critical security incidents.
- Introduced mandatory PR reviews, a shared component library, and TDD practices, establishing engineering standards that hadn't previously existed on the team.

<p><a href="https://play.google.com/store/apps/details?id=com.sa.app.madfuser" target="_blank"><img alt="Google Play" src="https://img.shields.io/badge/Get%20it%20on%20google%20play-blue.svg?style=for-the-badge&logo=google-play" /></a> <a href="https://apps.apple.com/us/app/madfu-shop-today-pay-later/id1658723268" target="_blank"><img alt="App Store" src="https://img.shields.io/badge/Get%20it%20on%20app%20store-black.svg?style=for-the-badge&logo=app-store&logoColor=white" /></a></p>

<hr>

### Tahara — Senior Mobile Software Engineer
Built core features for Tahara, a women's health and wellbeing platform, in collaboration with the Assas IT Solutions team and Inovola outsource partners.

- 100K+ downloads and a 4.5★ rating across 1.19K reviews — reached #2 in Health & Fitness on the Saudi App Store.
- Built the menstrual cycle tracking module (cycle calculations, pie-chart visualizations) and a full pregnancy calendar tracking week-by-week progression.

<p><a href="https://play.google.com/store/apps/details?id=com.tahara.tahara_app" target="_blank"><img alt="Google Play" src="https://img.shields.io/badge/Get%20it%20on%20google%20play-blue.svg?style=for-the-badge&logo=google-play" /></a> <a href="https://apps.apple.com/us/app/tahara-%D8%B7%D9%87%D8%A7%D8%B1%D8%A9/id6446452995" target="_blank"><img alt="App Store" src="https://img.shields.io/badge/Get%20it%20on%20app%20store-black.svg?style=for-the-badge&logo=app-store&logoColor=white" /></a></p>

<hr>

### Talmaro-ESS — Founding Mobile Software Engineer
Built Talmaro-ESS, an enterprise HR management platform, from the ground up for Android, iOS, and Huawei AppGallery — covering attendance, payroll, leave management, and team approval workflows.

- 10K+ downloads across three store ecosystems, with clients including Baba Roma.
- Managed production releases across all three stores as the founding mobile engineer on the project.

<p><a href="https://play.google.com/store/apps/details?id=com.onecliquesystems.one_click_app&hl=en&gl=US" target="_blank"><img alt="Google Play" src="https://img.shields.io/badge/Get%20it%20on%20google%20play-blue.svg?style=for-the-badge&logo=google-play" /></a> <a href="https://apps.apple.com/us/app/talmaro-ess/id1484374387" target="_blank"><img alt="App Store" src="https://img.shields.io/badge/Get%20it%20on%20app%20store-black.svg?style=for-the-badge&logo=app-store&logoColor=white" /></a></p>

<hr>

### Numa
Built pivotal features for the Numa mobile banking app — secure login, transaction tracking, and budgeting tools — for a global fintech product supporting freelancers and self-employed professionals.

- Facilitated 10,000+ users and over $300,000 in transactions on the platform.
- Used API integration and secure data storage to support Numa's global customer base.

<p><a href="https://play.google.com/store/apps/details?id=com.cardlessBanki.app" target="_blank"><img alt="Google Play" src="https://img.shields.io/badge/Get%20it%20on%20google%20play-blue.svg?style=for-the-badge&logo=google-play" /></a> <a href="https://apps.apple.com/gb/app/use-numa/id6444899716" target="_blank"><img alt="App Store" src="https://img.shields.io/badge/Get%20it%20on%20app%20store-black.svg?style=for-the-badge&logo=app-store&logoColor=white" /></a></p>

<hr>

### GetN — Driver & Rider Apps
Built and launched two companion apps, GetN Client and GetN Driver, for a ride-hailing platform in the style of Uber/Careem — published on both the App Store and Google Play.

<p><a href="https://play.google.com/store/apps/developer?id=GetN&hl=pl&gl=US" target="_blank"><img alt="Google Play" src="https://img.shields.io/badge/Get%20it%20on%20google%20play-blue.svg?style=for-the-badge&logo=google-play" /></a> <a href="https://apps.apple.com/eg/developer/getn-for-digital-content/id1659276865" target="_blank"><img alt="App Store" src="https://img.shields.io/badge/Get%20it%20on%20app%20store-black.svg?style=for-the-badge&logo=app-store&logoColor=white" /></a></p>

<hr>

<h2 align="left">🎮 Independent Projects</h2>

### Piety of Hearts *(Flutter)*
9-language Islamic lifestyle app — sole developer, owning architecture, localization, and publishing end-to-end. Azkar, Dua, Hadith, and an electronic Islamic rosary. 1K+ downloads, 4.9★ (38 reviews).
<p><a href="https://play.google.com/store/apps/details?id=com.ziyadmansy.pietyofHearts" target="_blank"><img alt="Google Play" src="https://img.shields.io/badge/Get%20it%20on%20google%20play-blue.svg?style=for-the-badge&logo=google-play" /></a></p>

### Furniture Home *(Flutter & Unity 3D — Graduation Project)*
Lets users browse and preview furniture and architectural designs in virtual reality. Originally built as my B.Sc. graduation project, *Modern Home Furniture in Virtual Reality* (graded A+).
<p><a href="https://play.google.com/store/apps/details?id=com.ziyadmansy.furniture_app_demo" target="_blank"><img alt="Google Play" src="https://img.shields.io/badge/Get%20it%20on%20google%20play-blue.svg?style=for-the-badge&logo=google-play" /></a></p>

### 3D Furniture Simulator *(Native Android — Java)*
A native Android app for visualizing and arranging 3D furniture models — built independently, outside the Flutter stack, to explore native Android 3D rendering.
<p><a href="https://play.google.com/store/apps/details?id=com.ziyadmansy.a9dsimulator" target="_blank"><img alt="Google Play" src="https://img.shields.io/badge/Get%20it%20on%20google%20play-blue.svg?style=for-the-badge&logo=google-play" /></a></p>

### BOBA Colors *(Native Android)*
Educational coloring and drawing game for kids — alphabets, numbers, shapes, and colors, with glow-coloring pages for family play.
<p><a href="https://play.google.com/store/apps/details?id=com.ziyadmansy.BOBAColors" target="_blank"><img alt="Google Play" src="https://img.shields.io/badge/Get%20it%20on%20google%20play-blue.svg?style=for-the-badge&logo=google-play" /></a></p>

### Flying Bird *(Native Android)*
A simple, relaxing obstacle-flying game.
<p><a href="https://play.google.com/store/apps/details?id=com.ziyadmansy.flappy_bird" target="_blank"><img alt="Google Play" src="https://img.shields.io/badge/Get%20it%20on%20google%20play-blue.svg?style=for-the-badge&logo=google-play" /></a></p>

### Soul Gym *(Native Android)*
Gym app for Soul Gym's members — schedules, workout guidance, and member updates in one simple app.
<p><a href="https://play.google.com/store/apps/details?id=com.soulgymegypt.soulgym" target="_blank"><img alt="Google Play" src="https://img.shields.io/badge/Get%20it%20on%20google%20play-blue.svg?style=for-the-badge&logo=google-play" /></a> <a href="https://apps.apple.com/bt/app/soul-gym/id1557887466" target="_blank"><img alt="App Store" src="https://img.shields.io/badge/Get%20it%20on%20app%20store-black.svg?style=for-the-badge&logo=app-store&logoColor=white" /></a></p>

### Totel — Hotel Room Sharing *(In Progress, Open Source)*
An open-source project sharing a clean, DDD-based architecture pattern. Lets US users post reserved hotel rooms so others can share the cost of an existing reservation.
<p><a href="https://github.com/ziyadmansy/totel-flutter-project" target="_blank"><img alt="Github" src="https://img.shields.io/badge/Github-View%20on%20github-lightgrey?style=for-the-badge&logo=github" /></a></p>

<hr>

<h2 align="left">🧩 Technical Assessments</h2>

Take-home architecture tasks completed for technical interviews — each built with clean, scalable architecture, Domain-Driven Design, and TDD.

| Company | Notes | Repo |
|---|---|---|
| Rubikal | Clean architecture, DDD, TDD | [GitHub](https://github.com/ziyadmansy/oivan-task-flutter) |
| Focal Agent | + BLoC / flutter_bloc state management | [GitHub](https://github.com/ziyadmansy/focal-agent-technical-task) |
| Inovola | Clean architecture, DDD, TDD | [GitHub](https://github.com/ziyadmansy/inovola-task-flutter) |

<hr>

<p align="center">
<img height="50%" width="auto" src="https://github-readme-stats.vercel.app/api?username=ziyadmansy&show_icons=true&count_private=true&theme=darcula&hide_border=true,contribs&bg_color=00000000"><img height="50%" width="auto" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ziyadmansy&layout=compact&hide_border=true&theme=darcula&bg_color=00000000&langs_count=6&hide=jupyter%20notebook,tex,css,php"><img src="https://github-readme-streak-stats.herokuapp.com?user=ziyadmansy&theme=darcula&hide_border=true&background=FFFFFF00">
<br>
<br>
</p>
