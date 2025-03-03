# SQL Online Editor

**SQL Online Editor** aims to provide users with a seamless and user-friendly platform for executing SQL queries, displaying query results in a table, maintaining a query history log, and supporting the export of results in CSV formats. The application will also provide a list of themes to change the editor UI and available tables in the sidebar for easy reference.

### Live : [https://sql-editor-online.vercel.app/](https://sql-editor-online.vercel.app/)

### Project Overview

![Project Overview](./src/assets/screenshots/overview.png)

## Key Features 📌

- **SQL Query Execution**: The application will allow users to input custom SQL queries and execute them against the connected database.

- **Result Tabular Display**: The application will present query results in a tabular format with a smooth scroll. This ensures that large datasets are easily navigable, enhancing the user experience.

- **Query History**: The application will maintain a history log of all executed queries. Users can revisit previous queries, and re-run them as needed.

- **Export Data**: Users will have the option to download query results in CSV format.

- **List of Available Tables**: The application's sidebar will display a list of available tables in the connected database.

- **Change Editor Theme and Size**: The user can change the theme of the Editor by selecting the option from the dropdown and expanding or shrinking the editor size.

## Techstack used 🛠️

Following technologies and libraries are used for the development of this
project.

- [React](https://react.dev/)
- [React Ace](https://github.com/securingsincity/react-ace)
- [Chakra UI](https://chakra-ui.com/)
- [React Icons](https://react-icons.github.io/react-icons/)
- [React-json-to-csv](https://github.com/coston/react-json-to-csv)
- [Prettier](https://prettier.io/)

## Demo Screenshots

![Query History](./src/assets/screenshots/editor1.png)

![Available tables](./src/assets/screenshots/editor2.png)

![Changed Theme](./src/assets/screenshots/editor3.png)

## Performance

(Performance using [PageSpeed Insights](https://pagespeed.web.dev/))

![Pagespeed](./src/assets/screenshots/Performance1.png)

(Performance using Chrome Devtools LightHouse)

![Chrome Lighthouse](./src/assets/screenshots/Performance2.png)

### Optimisation

- Lazy loaded output display.
- No error logs to the console.
- Used Vercel for hosting.
