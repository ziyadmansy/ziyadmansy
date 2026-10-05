# Ziyad Mansy

**Senior Mobile Software Engineer · Flutter, iOS, Android** · Cairo, Egypt · Open to relocation

I build and ship production mobile apps for fintech, healthcare, transportation, HR and real-estate clients in the US, UK, Saudi Arabia and the UAE, with **200K+ downloads**. I led a 3-engineer team on a SAMA-licensed BNPL platform with **zero production security incidents**, and I currently build HIPAA-compliant fleet-operations apps handling **thousands of trips a day** in the US. I also research LLM-guided software testing and contribute to Google and JetBrains open-source libraries.

[Resume](https://drive.google.com/file/d/1BVTyt3yvdgfqH1I6h3tgGDZ3KOFlHoyc/view) · [LinkedIn](https://www.linkedin.com/in/ziyadmansy/) · [Email](mailto:ziyadmohammad37@gmail.com) · [Google Scholar](https://scholar.google.com/citations?user=Q9Q3LB8AAAAJ) · [Website](https://ziyadmansy.github.io) · [Stack Overflow](https://stackoverflow.com/users/14139092/ziyad-mansy)

---

## Now

- **Senior Mobile Software Engineer at Naveera Tech** (remote, US), building the Driver and Client apps of a fleet-operations platform.
- **Independent research** on LLM-guided fuzzing and differential testing: 3 sole-authored papers under review at ICST, AST and FORGE 2027.

## Selected work

| Product | What I did | Impact | Get it |
|---|---|---|---|
| **Naveera** · 2026 – now | Shipped a platform that had gone 9 months without a release **within 1 month of joining**. Designed an offline-first architecture for dispatch and trips. Built HIPAA-compliant routing, billing and live turn-by-turn navigation. | Thousands of trips a day across hundreds of US client organizations | [iOS](https://apps.apple.com/us/app/naveera-driver/id6769880111) · [Android](https://play.google.com/store/apps/details?id=tech.naveera.driver) |
| **MADFU** · Lead, 2023 – 2024 | **Led 3 Flutter engineers.** Rebuilt separate native Android and iOS apps as one Flutter app from scratch. Built the team's quality process: mandatory PR reviews, a shared component library and TDD. | 100K+ downloads · zero production security incidents across recurring external pentests (SSL pinning, encryption at rest, key handling) | [iOS](https://apps.apple.com/us/app/madfu-shop-today-pay-later/id1658723268) · [Android](https://play.google.com/store/apps/details?id=com.sa.app.madfuser) |
| **PropertyBox** · Focal Agent, 2024 – 2026 | Delivered AI photo enhancement, automated property descriptions and one-step social publishing. Built enterprise customizations for Reapit and Connells, plus EPC-compliance features. Shipped one Flutter codebase to Web, Android and iOS through Azure CI/CD. | Used by agencies across the UK, Europe and the UAE | [iOS](https://apps.apple.com/gb/app/propertybox/id1660237557) · [Android](https://play.google.com/store/apps/details?id=io.propertybox.propertybox2_app) |
| **Tahara** · 2022 | **Led a team of junior Flutter developers.** Built cycle tracking and a week-by-week pregnancy calendar for this women's-health app. | #2 in Health & Fitness on the Saudi App Store · 100K+ downloads · 4.6★ | [iOS](https://apps.apple.com/sa/app/tahara-%D8%B7%D9%87%D8%A7%D8%B1%D8%A9/id6446452995) · [Android](https://play.google.com/store/apps/details?id=com.tahara.tahara_app) |
| **Talmaro-ESS** · Founding engineer, 2021 | Built the HR app from scratch as the company's first mobile engineer: attendance, payroll, leave and approval workflows. | 10K+ downloads on iOS, Android and Huawei AppGallery | [iOS](https://apps.apple.com/us/app/talmaro-ess/id1484374387) · [Android](https://play.google.com/store/apps/details?id=com.onecliquesystems.one_click_app) · [AppGallery](https://appgallery.huawei.com/app/C109430081) |
| **Numa** | Built secure login, transaction tracking and budgeting features for a banking app serving freelancers. | 10K+ users · $300K+ in transactions | [iOS](https://apps.apple.com/gb/app/use-numa/id6444899716) · [Android](https://play.google.com/store/apps/details?id=com.cardlessBanki.app) |
| **GetN** | Built and launched the Client and Driver apps of a ride-hailing service. | Live on both stores | [iOS](https://apps.apple.com/eg/developer/getn-for-digital-content/id1659276865) · [Android](https://play.google.com/store/apps/developer?id=GetN) |

## Open source

- **[google/json_serializable](https://github.com/google/json_serializable.dart)** (18M+ downloads a month with built_value): reported, through differential testing, that int fields silently truncate (1.9 becomes 1) and saturate out-of-range values ([#1591](https://github.com/google/json_serializable.dart/issues/1591)). My documentation fix was merged ([#1592](https://github.com/google/json_serializable.dart/pull/1592)).
- **[google/built_value](https://github.com/google/built_value.dart)**: reported that a missing required list silently becomes empty ([#1404](https://github.com/google/built_value.dart/issues/1404)). The maintainer confirmed it was undocumented and documented it upstream ([dart-lang/build#5178](https://github.com/dart-lang/build/pull/5178)).
- **[Kotlin/kotlinx.serialization](https://github.com/Kotlin/kotlinx.serialization)**: reported, with a standalone reproducer, that strict JSON parsing accepts raw control characters the standard forbids ([#3276](https://github.com/Kotlin/kotlinx.serialization/issues/3276)).
- **[intercom_flutter](https://github.com/deepak786/intercom_flutter)** (200K+ monthly downloads): fixed an iOS startup crash by upgrading the native Intercom SDK, shipped in v9.0.4 ([#431](https://github.com/deepak786/intercom_flutter/pull/431)).

## Research

Three sole-authored papers on LLM-guided software testing, all under review. Code, data and preprints are public.

| Paper | Key result | Links |
|---|---|---|
| *Coverage-Free Fuzzing: LLM-Guided Refinement of Grammar-Based Test Generators* · FORGE 2027 | Raised valid test inputs for the cJSON parser (13K+ GitHub stars) from 58% to 97% without code instrumentation | [Preprint](https://doi.org/10.5281/zenodo.22556342) · [Code](https://github.com/ziyadmansy/agentic-grammar-fuzzing) |
| *Beyond Sanitizers: LLM-Guided Refinement for Differential JSON Deserialization Testing in Dart* · AST 2027 | Caught silent data errors in 5.7% of 43,336 checks across four Dart JSON libraries, leading to documentation updates in Google's json_serializable and built_value | [Preprint](https://doi.org/10.5281/zenodo.22555794) · [Code](https://github.com/ziyadmansy/agentic-fuzzing-dart-json) |
| *Where Does an LLM Fuzzer's Domain Knowledge Come From?* · ICST 2027 | In a pre-registered study of 8 JSON libraries in Dart and Kotlin (83,500 inputs), human-written domain knowledge raised inputs exposing library disagreements from 1.5% to 30.9% | [Preprint](https://doi.org/10.5281/zenodo.23002933) · [Code](https://github.com/ziyadmansy/knowledge-sources-fuzzing) |

## Tech

- **Languages:** Dart, Kotlin, Swift, Java, Python, JavaScript
- **Mobile:** Flutter, Android, iOS, Flutter Web, native platform integration, Riverpod, BLoC/Cubit, Provider, Firebase, REST APIs, payment gateways
- **Architecture:** Clean Architecture, SOLID, design patterns, offline-first systems
- **Testing and security:** unit, widget and integration testing, TDD, property-based testing, fuzzing, differential testing, penetration-test remediation, encryption at rest, SSL pinning, secure key storage
- **CI/CD:** Azure Pipelines, GitHub Actions, Bitbucket Pipelines, Codemagic
- **Compliance:** HIPAA, SAMA, UK EPC

## Independent apps and code samples

- **[5 apps on Google Play](https://play.google.com/store/apps/dev?id=6637516697625901674)** as sole developer, including [Piety of Hearts](https://play.google.com/store/apps/details?id=com.ziyadmansy.pietyofHearts) (Flutter, 9 languages, 1K+ downloads, 4.9★) and native Android apps in Java and Kotlin.
- **Client app:** [Soul Gym](https://play.google.com/store/apps/details?id=com.soulgymegypt.soulgym), a member app for a gym chain.
- **Architecture samples:** [Totel](https://github.com/ziyadmansy/totel-flutter-project) and [focal-agent-technical-task](https://github.com/ziyadmansy/focal-agent-technical-task), Flutter projects built with Clean Architecture, DDD and TDD.

## Education

**B.Sc. in Engineering, Computer Engineering and IT**, Modern Academy for Engineering and Technology, Cairo, 2022. Ranked 1st of ~200 in cohort.
