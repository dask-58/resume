# Usage

## Basic Commands

### Items
- Use `\resumeItem{}` for standard list items
- Example: `\resumeItem{Developed a web application using React}`

### Subheadings
- Use `\resumeSubheading{}{}{}{}` for main section entries
- Parameters: Title, Date, Subtitle, Location
- Example:
  ```latex
  \resumeSubheading
  {Company Name}{Jan 2020 - Present}
  {Job Title}{City, State}
  ```

### Sub-subheadings
- Use `\resumeSubSubheading{}{}` for additional details
- Parameters: Title, Date
- Example: `\resumeSubSubheading{Project Name}{June 2021}`

### Project Headings
- Use `\resumeProjectHeading{}{}` for project entries
- Parameters: Project Name, Technologies Used
- Example: `\resumeProjectHeading{Web Scraper}{Python, BeautifulSoup}`

## Sections and Lists

### Starting Lists
- `\resumeSubHeadingListStart` - Starts a list of subheadings
- `\resumeItemListStart` - Starts a list of items

### Ending Lists
- `\resumeSubHeadingListEnd` - Ends a list of subheadings
- `\resumeItemListEnd` - Ends a list of items

## Formatting

### Section Titles
- Use `\section{Section Name}` for main sections
- Example: `\section{Education}`

### URLs
- Use `\myUrl{}` for formatting URLs
- Example: `\myUrl{https://github.com/yourusername}`

## Tips
- Use `\vspace{-5pt}` to adjust vertical spacing between elements
- Customize colors using the `\color{}` command
- Modify margins and spacing in the preamble for overall layout adjustments

Remember to compile your LaTeX document to see the final result!
