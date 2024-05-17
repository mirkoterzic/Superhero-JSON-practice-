# Superhero-JSON-practice-

This HTML document serves as a practice example for utilizing JSON data to populate a webpage with superhero information. The document consists of HTML markup, JavaScript functions, and CSS styles.

## HTML Structure

- **Document Type Declaration**: Specifies the document type and language.
- **Head Section**: Contains metadata such as character encoding, page title, and links to external stylesheets.
- **Body Section**: Contains the main content of the webpage, including a header and a section for displaying superhero information.
  - **Header**: Displays the squad name and additional information such as hometown and formation year.
  - **Section**: Displays individual superhero profiles, including their name, secret identity, age, and superpowers.

## JavaScript Functionality

- **populateHeader(obj)**: Populates the header section with squad name, hometown, and formation year extracted from the provided JSON object.
- **populateHeroes(obj)**: Populates the section with individual superhero profiles extracted from the JSON object. Each profile includes the hero's name, secret identity, age, and a list of superpowers.
- **populate()**: Asynchronous function that fetches JSON data from an external source, processes it, and calls the above functions to populate the webpage.

## CSS Styling

- **General Styles**: Sets the font family for the entire document and centers the content.
- **Header Styles**: Styles the header section, including the squad name and additional information.
- **Section Styles**: Styles the individual superhero profiles displayed in the section.

## JSON Data

The provided JSON data represents a fictional superhero squad with three members. Each member has a name, age, secret identity, and a list of superpowers.



## Disclaimer

This project is intended for educational purposes and serves as a practice example for working with JSON data in web development. The superhero squad and its members are fictional and used solely for demonstration purposes.

## Live Preview

Superhero Dashboard page - [Live Preview](https://mirkoterzic.github.io/Superhero-JSON-practice-/)
