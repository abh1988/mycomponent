# Advanced Multi-Condition Filter Table

This is an advanced table with multi-condition filtering capabilities, built using HTML, JavaScript (jQuery), DataTables, and Bootstrap. It allows users to filter data in the table based on multiple conditions with options to apply "AND" or "OR" logic between conditions, as well as the ability to apply advanced filter conditions such as "Equals", "Contains", "Greater than", and "Less than".

### Features:
- **Multi-Condition Filters**: Add multiple filter conditions using a modal interface.
- **Customizable Filters**: Filters can be applied to any column, with the ability to choose conditions (Equals, Contains, Greater Than, Less Than).
- **Responsive Table**: The table is fully responsive and displays data in a well-organized manner, adjusting for different screen sizes.
- **Reset Filters**: Clear all applied filters with a single button click.
- **Sorting**: The table supports both ascending and descending sorting by clicking the column headers.

### Technologies Used:
- **HTML**: For structure and content.
- **CSS**: For basic table styling and layout.
- **Bootstrap**: For styling, modal design, and responsive layout.
- **jQuery**: For handling DOM manipulations and events.
- **DataTables**: For creating a dynamic and responsive table with sorting and searching features.

### Installation:
1. Clone this repository:
    ```bash
    git clone https://github.com/your-username/your-repository-name.git
    ```

2. Open the `index.html` file in your browser to view the table and apply filters.

### Usage:
- **Add Filter**: Click the "Add Filter" button to open a modal where you can choose filter conditions for different columns.
- **Apply Filter**: After adding the filter conditions, click the "Apply Filters" button to filter the table data based on your conditions.
- **Clear Filters**: Click the "Clear Filters" button to reset all filters and show all the table data.
- **Sorting**: Click on column headers to sort the table data in ascending or descending order.

### Customizing Filters:
You can easily modify the table's columns and the available conditions in the filters by editing the HTML and JavaScript in the following sections:

- Modify the available columns for filtering in the `filter-column` `<select>` element.
- Add or modify filter conditions in the `filter-condition` `<select>` element.

### Example Data:
The table in this example contains sample data of names, ages, and job titles.

| Name     | Age | Job        |
|----------|-----|------------|
| Alice    | 30  | Developer  |
| Bob      | 25  | Designer   |
| Charlie  | 35  | Manager    |
| David    | 28  | Analyst    |

### License:
This project is open-source and available under the [MIT License](LICENSE).
