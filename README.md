## Base architecture

lib/
├── data/
│   ├── models/             # Data models for the app
│   ├── repositories/       # Repository implementation for data access
│   ├── services/           # External services integration such as payment and map services
│   └── sources/            # Implementation of data sources such as API and database
├── domain/
│   ├── entities/           # Entities that represent the business logic of the app
│   ├── repositories/       # Abstract classes for data access that define contracts for the repositories
│   └── providers/          # Main business logic
├── presentation/
│   ├── pages/              # UI pages/screens for the app
│   ├── widgets/            # Reusable widgets that are used across the app
│   ├── theme/              # Custom theme for the app
│   ├── utils/              # Helper/utility classes or functions
│   └── navigation.dart     # Navigation routes and logic
├── app.dart                # Main entry point of the app
├── main.dart               # Flutter application class and initialization
└── dependencies.dart       # Dependency Injection container configuration
