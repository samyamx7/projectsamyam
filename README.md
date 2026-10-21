# Guide to Comparing Domestic Franchises — 2025 Data

**Creator:** Samyam Poudel  
**Industry:** Korean coffee franchises  
**Brands:** MEGA MGC COFFEE (메가MGC커피), COMPOSE COFFEE (컴포즈커피), PAIK’S COFFEE (빽다방)  
**Comparison criterion:** Reported number of franchise locations at year-end 2025  
**Unit:** stores

## Project description
A responsive, bilingual (English and Korean) single-page guide comparing three coffee franchise brands. It includes brand introductions, the comparison criterion, a data table, four search queries and explanations, source links, and buttons to sort the reported numeric values in ascending or descending order. All HTML, CSS, and JavaScript are included in `index.html`; no external APIs are used.

## Data quality and limitations
The reported figures shown in the page are 3,969 for MEGA MGC COFFEE, 3,325 for COMPOSE COFFEE, and 1,819 for PAIK’S COFFEE. These values were reported in a secondary industry article, but have **not been independently confirmed against each brand's original 2025 franchise disclosure**. The webpage therefore labels them **Unverified**. Verify the original disclosures in the Korea Fair Trade Commission system before treating them as official or submitting a confirmed ranking. Publication date and data base year are not the same thing.

## Research sources
- Korea Fair Trade Commission — Franchise Disclosure System: https://franchise.ftc.go.kr/
- Leaders Fact industry article: https://www.leadersfact.co.kr/news/articleView.html?idxno=23623
- MEGA MGC COFFEE official website: https://www.mega-mgccoffee.com/
- COMPOSE COFFEE official website: https://composecoffee.com/
- PAIK’S COFFEE official website: https://paikdabang.com/

## Three specific project details
1. Selected three Korean coffee franchise brands from the same industry.
2. Used one comparison metric—reported year-end franchise store count—and labelled all unverified figures rather than presenting them as confirmed official data.
3. Added four search-query examples, English and Korean explanations, mobile-responsive layout, and sorting buttons that only sort when all rows contain numeric values.

## Tools used
- HTML, CSS, and JavaScript in one file
- GitHub for version control and hosting
- Korea Fair Trade Commission disclosure system and linked secondary/brand sources for research

## Deploy with Vercel
1. Import this GitHub repository into Vercel.
2. Choose **Other** as the framework preset if asked.
3. Leave the build command empty; the site is a static HTML page.
4. Deploy and open the generated URL to check the table, buttons, mobile layout, and source links.
