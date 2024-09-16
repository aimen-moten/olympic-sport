# Olympic Sport - Surfing 🏄‍♀️ 🏄‍♂️ 

This code sets up a Vue.js application for displaying Olympic sports. It involves creating multiple Vue components to structure the Olympic sports page.

### Initial Setup

- Initializes a new Vue project named `olympic-sports` inside a newly created folder called `initials-assignments`.

### Component Creation

- **`Sport.vue`**: Defines a component with a header displaying the name of a selected summer Olympic sport.
- **`SportDescription.vue`**: Defines a component with a header "Description:" followed by a paragraph containing the sport's description.
- **`SportRules.vue`**: Defines a component with a header "Rules:" followed by a paragraph detailing the sport's rules.
- **`SportHistory.vue`**: Defines a component with a header "Olympic History:" followed by a paragraph with the sport's history.
- **`SportPictogram.vue`**: Defines a component with a header "Pictogram:" and an image tag displaying the sport’s pictogram.

### Component Integration

- Integrates `SportDescription`, `SportRules`, `SportHistory`, and `SportPictogram` components into `Sport.vue` in that specific order under the header tag.
- Imports and uses the `Sport` component within the `<main>` block of `App.vue`.

### Final Adjustments

- Replaces the image in `App.vue` with a chosen Olympic photo.
- Renames the webpage title to "Olympic Sports".
- Adds CSS styling to customize the appearance of the webpage.
- Cleans up any unused Vue components and leftover styling.
