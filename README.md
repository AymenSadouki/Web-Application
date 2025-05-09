# Smartphone Recommendation Web Application

## Objective
Developed a dynamic PHP/JavaScript web application for smartphone recommendations using file-based JSON storage, implementing responsive design and client-server functionality as required by the 4222COMP coursework specifications.

## Core Features Implemented

### Frontend Components
- **Home Page**: Displayed smartphone summaries from `smartphones.json`
- **Product Pages**: Dynamic rendering using `smartphone.php`
- **Ranking System**: Sortable table with Bootstrap styling
- **User Reviews**: Form submission to `reviews.json`

### Backend Functionality
- **Data Management**:
  ```php
  // Load smartphone data
  $phones = json_decode(file_get_contents('data/smartphones.json'), true);
  ### Technical Implementation
 - **Frontend**:

Bootstrap 5 (Grid layout, components)

JavaScript (Form validation, dynamic content)

jQuery (DOM manipulation, AJAX)

- **Backend**:
PHP 8.2 (Data processing)

JSON (Data storage in 3 files)

Apache (UniServerZ deployment)
