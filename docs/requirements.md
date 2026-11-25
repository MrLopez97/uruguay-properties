# Uruguay Properties - Software Requirements

Version: 1.0
Status: Draft

## 1. Project Overview

Uruguay Properties is a web application designed
to help users search, filter and explore real
estate properties in Uruguay.

The project focuses on frontend development,
responsive design and software quality assurance.

## 2. Project Scope

The application will include:

- Property catalog
- Property search
- Property filters
- Property details
- Favorite properties
- Contact form validation

The first version will use fictional property data.

Backend services, databases, user authentication
and real contact form submissions are out of scope.

## 3. Functional Requirements

| ID | Description | Priority |
|---|---|---|
| RF-001 | Display a property catalog | High |
| RF-002 | Search properties by title | High |
| RF-003 | Filter properties by department | High |
| RF-004 | Filter properties by price range | High |
| RF-005 | Filter properties by sale or rent | High |
| RF-006 | Display property details | High |
| RF-007 | Save favorite properties | Medium |
| RF-008 | Validate the contact form | Medium |
| RF-009 | Sort properties by price | Medium |

## 4. Non-Functional Requirements

| ID | Description |
|---|---|
| RNF-001 | Responsive design |
| RNF-002 | Cross-browser compatibility |
| RNF-003 | Web accessibility |
| RNF-004 | Performance optimization |
| RNF-005 | Maintainable code |
| RNF-006 | Secure HTTPS deployment |

## 5. Acceptance Criteria

### RF-001 - Property Catalog

- CA-001: The application displays available properties.
- CA-002: Each property displays a title, image,
  location, price and transaction type.
- CA-003: Each property includes a details link.
- CA-004: An empty catalog displays an informative message.

### RF-002 - Property Search

- CA-005: Search returns properties with matching titles.
- CA-006: Search is case-insensitive.
- CA-007: An empty search displays all properties
  when no other filters are active.
- CA-008: No matching results displays a message.
- CA-009: Leading and trailing spaces are ignored.

## 6. Technologies

- HTML5
- CSS3
- JavaScript ES6+
- JSON
- LocalStorage
- Git
- GitHub
- GitHub Pages
- Playwright
- GitHub Actions