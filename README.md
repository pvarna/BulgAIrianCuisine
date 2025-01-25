# BulgAIrian Cuisine Ontology

## Overview
The **BulgAIrian Cuisine Ontology** is a comprehensive semantic representation of Bulgarian cuisine. It organizes traditional dishes, ingredients, cooking methods, textures, and regional origins, offering a structured approach to understanding and showcasing Bulgarian culinary heritage.

This ontology was developed as part of the "Knowledge Reasoning and Representation" course in the Faculty of Mathematics and Informatics at Sofia University. It supports applications like recipe recommendation systems, interactive cookbooks, and the promotion of Bulgarian culinary culture through semantic technologies.

## Features
- **Hierarchical Class Structure**: Organized into real-world objects (e.g., `Dish`, `Ingredient`) and abstract concepts (e.g., `ValuePartition` for properties like `Sweetness` and `Spiciness`).
- **Rich Semantic Relationships**: Includes detailed relationships such as `hasIngredient`, `hasCookingMethod`, and `hasRegion`.
- **Examples of Logical Inference**: Demonstrates classification of dishes (e.g., `HighCalorieDish`, `LeanDish`) based on their properties.
- **Support for Semantic Queries**: Facilitates knowledge extraction with queries, such as retrieving dishes by region or preparation time.

## Ontology Structure
### Main Classes:
- **Dish**: Represents traditional Bulgarian dishes. Examples: `Banitsa`, `Tarator`, `Kapama`.
- **Ingredient**: Represents food components. Examples: `DairyIngredient`, `VegetableIngredient`, `MeatIngredient`.
- **Region**: Represents Bulgarian regions contributing to culinary diversity. Examples: `RhodopeRegion`, `PirinRegion`, `ThracianRegion`.
- **CookingMethod**: Represents preparation techniques. Examples: `Baking`, `Boiling`, `Grilling`.
- **ValuePartition**: Abstract classes for properties like `Spiciness`, `Sweetness`, and `Texture`.

### Key Relationships:
- `hasIngredient`: Links dishes to their ingredients.
- `hasCookingMethod`: Defines the preparation method of a dish.
- `hasRegion`: Indicates the regional origin of a dish.
- `hasSpiciness`, `hasSweetness`, `hasTexture`: Describes sensory attributes of dishes and ingredients.

## Example Individuals
- **Banitsa**: A baked dish made with filo dough, eggs, butter, and cheese, characterized by its crunchy texture.
- **Shopska Salad**: A no-cook salad featuring cucumbers, tomatoes, peppers, and cheese, associated with the Pirin region.
- **Kapama**: A boiled dish from the Pirin region, featuring pork, chicken, rice, and sauerkraut.

## Files in This Repository
- **`visualisation_1MI3400571.json`**: The ontology in JSON format.
- **`bulgAIrian_cuisine.rdf`**: The ontology in RDF/XML format.
- **`visualisation_1MI3400571.svg`**: A visual diagram of the ontology structure.
- **`documentation_1MI3400571.pdf`**: Detailed project documentation, including design patterns, logical inferences, and future development ideas.

## Applications
- **Recipe Recommendation Systems**: Suggest dishes based on available ingredients or preferences.
- **Interactive Cookbooks**: Create digital guides with semantic search and filtering capabilities.
- **Cultural Promotion**: Highlight the uniqueness of Bulgarian cuisine in international contexts.

## Future Development
1. Expanding the ontology with additional dishes, ingredients, and regions.
2. Introducing new classes for categories like `Soup`, `Salad`, `MainDish`, and `Dessert`.
3. Adding a detailed hierarchy of spices and seasonings.
4. Enhancing the `ValuePartition` subclasses for more nuanced descriptions.

## Getting Started
### Requirements
To use the ontology, you will need:
- **Protégé** or similar OWL ontology editors for visualization and modification.
- A query engine for knowledge extraction.

### Usage
1. Clone this repository:
   ```bash
   git clone https://github.com/pvarna/BulgAIrianCuisine.git
   ```
2. Load the ontology files into your ontology editor or semantic web application.
3. Explore and adapt the ontology for your specific use case.

## Acknowledgments
This project was created by Petar Kolev (FN: 1MI3400571) as part of a Master's program in Artificial Intelligence. Inspiration and data were gathered from:
- Traditional Bulgarian recipes
- Wikipedia articles on Bulgarian cuisine
- Academic resources on ontology design

## License
This project is licensed under the MIT License. See the `LICENSE` file for details.
